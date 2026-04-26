# 🚀 NxtBuild — AI-Powered Web App Builder

## 📌 Overview
NxtBuild is a full-stack AI-powered application that allows users to build complete web apps using simple natural language prompts. Users describe what they want, and the system generates a fully functional web application with live preview and editable code.

---

## ✨ Key Features

### 🔐 User Authentication
- Secure user registration and login  
- JWT-based authentication  
- Password hashing using bcrypt  

### 📁 Project Management
- Create new web app projects  
- View and manage existing projects  
- Rename and delete projects  

### 🤖 AI Code Generation
- Generate full HTML, CSS, and JavaScript apps  
- Powered by Gemini AI / LLM APIs  
- Converts plain English into working code  

### 💬 Chat Interface
- Interactive chat UI  
- Users can refine apps step-by-step  
- Continuous improvement using AI responses  

### 👀 Live Preview
- Real-time preview of generated apps  
- Rendered inside an iframe  
- Instant feedback on changes  

### 🧑‍💻 Code Editor
- View generated source code  
- Edit and customize directly  

### ⬇️ Code Download
- Download generated app as a standalone HTML file  
- Easy to deploy or share  

---

## 🛠️ Tech Stack
- Frontend: React.js  
- Backend: Node.js / Express.js  
- Database: MongoDB  
- Authentication: JWT, bcrypt  
- AI Integration: Gemini API / OpenAI API  

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
``bash
git clone https://github.com/vishnurnaik/nxtbuild.git
cd nxtbuild

2. Setup Backend
cd server
npm install
npm run dev
3. Setup Frontend
cd client
npm install
npm start
🔑 Environment Variables

Create a .env file inside the server folder:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
API_KEY=your_ai_api_key

📸 How It Works
User logs in or registers
Creates a new project
Enters app idea in chat (e.g., "Todo app with dark mode")
AI generates full web app code
App is previewed instantly
User can edit or download the code

🎯 Future Improvements
Add multi-page app generation
Deploy apps directly from platform
Add templates and themes
Collaboration features
