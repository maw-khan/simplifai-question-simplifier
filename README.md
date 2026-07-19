ClarifAI – AI-Powered Question Simplifier
Overview
ClarifAI is an AI-powered educational web application designed to help students better understand difficult study questions before attempting to solve them.
Many students struggle not because they lack knowledge, but because they have difficulty understanding what a question is actually asking. ClarifAI addresses this problem by using Generative AI to simplify complex academic questions into clear, easy-to-understand language while providing a concise explanation, highlighting the key concepts involved, and offering a helpful hint to guide the student's thinking.
Instead of immediately providing the complete solution, the application encourages conceptual understanding and independent learning.
Live Demo
Application URL
👉 clarifai.ai.studio
GitHub Repository
Source Code
👉 YOUR_GITHUB_REPOSITORY_URL
Problem Statement
Students frequently encounter questions in assignments, quizzes, textbooks, and examinations that contain difficult wording, technical terminology, or complex sentence structures.
This often leads to confusion before they even begin solving the problem.
Rather than immediately searching for complete solutions online, students first need help understanding what the question actually means.
ClarifAI solves this problem by transforming difficult questions into simple language while preserving their original meaning.
Solution
ClarifAI uses Google's Gemini AI model to analyze a student's question and generate four educational outputs:
A simplified version of the question
A concise explanation of what the question is asking
The most important concepts involved
A helpful hint that guides the student without revealing the complete answer
This approach promotes learning and comprehension instead of answer memorization.
Target Users
ClarifAI is designed for:
School students
College students
University students
Self-learners
Anyone who wants to better understand academic questions before solving them
Features
The application includes the following features:
AI-powered question simplification
Converts difficult questions into simple language
Provides a concise explanation of the question
Identifies the key concepts involved
Generates one helpful learning hint
Clean and modern mobile-friendly interface
Simple navigation using a bottom navigation bar
Copy Response functionality
Simplify Another option for new questions
Fast AI response generation
Responsive design suitable for different screen sizes
Application Workflow
Open the application.
Navigate to the Simplify screen.
Paste or type a study question.
Press Simplify Question.
The application sends the request to Gemini AI.
The AI processes the question.
The application displays:
Simplified Question
Explanation
Key Concepts
Helpful Hint
The user can copy the response or simplify another question.
AI Feature
The core functionality of ClarifAI is powered by Google's Gemini AI model.
Instead of generating complete answers, the model is instructed to act as an educational assistant whose purpose is to improve understanding.
For every submitted question, the AI generates four structured outputs:
Simplified Question
Explanation
Key Concepts
Helpful Hint
This ensures responses remain concise, educational, and focused on comprehension.
AI System Prompt
The following system instruction is used to guide the AI:
You are an educational assistant.
Your task is NOT to solve the student's question directly.
Given a study question, return ONLY the following four sections:
1. Simplified Question
Rewrite the question in simple, easy-to-understand language.
Keep it under 25 words.
2. Explanation
Briefly explain what the question is asking.
Maximum 50 words.
3. Key Concepts
List exactly 3–4 short bullet points.
4. Helpful Hint
Provide one short hint that helps the student think about the solution.
Do not reveal the final answer.
Rules:
Be concise.
Do not answer the question directly.
Keep the entire response under approximately 150 words.
Return only the required output format.
Technologies Used
Design
Google Stitch
Development
Google AI Studio
AI Model
Google Gemini
Programming
AI-assisted (Vibe Coding)
Version Control
Git
GitHub
Deployment
Vercel
Application Screens
The application consists of four primary screens:
Home
Introduces the application and explains its purpose.
Simplify Question
Allows the user to enter a study question and submit it for AI processing.
Results
Displays:
Simplified Question
Explanation
Key Concepts
Helpful Hint
It also includes options to copy the generated response or simplify another question.
About
Provides information about the application, developer, and project details.
Screenshots
Home Screen
(Insert screenshot here)
Example:
screenshots/home.png
Simplify Screen
(Insert screenshot here)
Example:
screenshots/simplify.png
Results Screen
(Insert screenshot here)
Example:
screenshots/results.png
About Screen
(Insert screenshot here)
Example:
screenshots/about.png
Project Structure
ClarifAI
│
├── src/
├── components/
├── pages/
├── assets/
├── public/
├── README.md
└── package.json
(Project structure may vary depending on the exported project.)
How to Run the Project
**Prerequisites:**  Node.js
1.  dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
Future Improvements
Potential enhancements include:
Multi-language support
Voice input
Save previous questions
Dark mode
Study history
PDF question extraction
Image-to-text question recognition
Personalized learning suggestions
Learning Outcomes
This project demonstrates:
AI-powered application development
Prompt engineering
User-centered design
Mobile-first interface design
AI-assisted software development
GitHub version control
Web application deployment
Developer
Muhammad Ali Waris Khan
Final Project for the AI Application Development Course
License
This project was developed for educational purposes as part of an AI application development course.
Acknowledgements
Special thanks to:
Google Stitch for interface design
Google AI Studio for AI-assisted application development
Google Gemini for powering the intelligent question simplification feature
AI Studio for source code hosting
AI Studio for application deployment



