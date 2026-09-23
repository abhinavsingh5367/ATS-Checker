# ATS-Checker

An end-to-end, full-stack web application that leverages Artificial Intelligence to conduct mock job interviews, evaluate user responses in real-time, and generate detailed performance feedback reports.

Key Features :

>> User Authentication & Security: Complete registration, login, and logout flows backed by JWT (JSON Web Tokens), protected routes, and token blacklisting for enhanced security.
>> AI-Powered Interviewer: Dynamic interview sessions driven by an AI backend service tailored to simulate real-world technical and behavioral interview questions.
>> Resume & File Processing: Express middleware support for processing file uploads (such as candidate resumes or audio files).

>> Comprehensive Reports: Generates in-depth interview performance analysis, scoring, and feedback reports for candidate review.

>> Modular Frontend Architecture: Built with React and SCSS using a feature-based folder structure for scalable state management and clean component isolation.


 Tech Stack

Frontend
Framework: React.js (via Vite)
Routing: React Router DOM
State Management: React Context API (AuthContext, InterviewContext)
Styling: SCSS (Sass) with modular components
HTTP Client: Axios / Fetch API

Backend
Runtime Environment: Node.js
Framework: Express.js
Database: MongoDB / Mongoose ODM
Authentication: JWT (JSON Web Tokens) & Password Hashing
AI Integration: Custom AI Service (ai.service.js) for generating dynamic interview interactions
