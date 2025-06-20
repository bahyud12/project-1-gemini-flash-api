# 🚀 project-1-gemini-flash-api

## 📌 Project Introduction

A RESTful API built with **ExpressJS** that integrates with **Google Gemini 1.5 Flash API** to generate intelligent, text-based responses based on different types of user inputs:

- 📝 Plain Text  
- 🖼️ Image Files  
- 📄 Document Files (PDF, TXT)  
- 🔊 Audio Files (MP3, WAV)

This API acts as a middleware between client requests (e.g., Postman or frontend) and the Gemini AI model.

---

## 🧰 Tools Used

| Tool                  | Purpose                                                       |
|-----------------------|---------------------------------------------------------------|
| **Gemini Code Assist**| Optional: helps scaffold code inside VS Code                  |
| **Gemini API**        | Core AI engine from Google for generating intelligent replies |
| **Node.js + Express** | Backend framework to create API endpoints                     |
| **Multer**            | Middleware for handling file uploads (image/audio/docs)       |
| **Postman**           | API testing tool                                              |
| **VS Code**           | Code editor (Gemini Assist plugin optional)                   |

---

## 🔧 Project Setup

Run the following commands to set up the project:

```bash
$ mkdir gemini-flash-api
$ cd gemini-flash-api
$ npm init -y
$ npm install express dotenv @google/generative-ai multer


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
