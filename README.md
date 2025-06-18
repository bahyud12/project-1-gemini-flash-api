# project-1-gemini-flash-api

Project Introductions
Overview AI Tools 
Implementing Gemini AI Part. 1
Tools
PurposeGemini Code AssistTo help scaffold and auto-generate parts of the API logic
Gemini APIThe actual AI engine that processes user prompts
Node.js (Express)To build a RESTful API
Postman For testing the API
VS CodeOur code editor with Gemini Assist plugin (optional)


This project is a RESTful API built with ExpressJS that integrates with Google Gemini 1.5 Flash to generate text-based responses using various input types:●Plain text●Image files●Document files (e.g., PDF, TXT)●Audio files (e.g., MP3, WAV)It serves as a middleware between client requests (e.g., via Postman) and the Gemini AI API.


Preparation
Project SetupPreparation
$ mkdir gemini-flash-api
$ cd gemini-flash-api
$ npm init -y
$ npm install express dotenv @google/generative-ai multer

This setup prepares a Node.js project using Express and integrates the Gemini 1.5 Flash API through the @google/generative-ai package, enabling support for text, audio, image, or document input handling.

●express: Sets up the REST API.
●dotenv: Loads the Gemini API key securely from a .env file.
●@google/generative-ai: Connects to the Gemini API (including Flash 1.5).
●multer: Handles file uploads (image, audio, document inputs).

File Structure
gemini-flash-api
├── node_modules
├── uploads
├── .env
├── index.js
├── package-lock.json
└── package.json

TEST RUNNING
node index.js
