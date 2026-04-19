🤖 IntervAI – AI-Powered Interview Preparation Platform

IntervAI is an AI-driven, intelligent interview preparation platform that helps students and developers practice, analyze, and improve their interview skills through personalized feedback and real-time evaluation.

🚀 Features
👤 User Side

🎯 Topic-based mock interviews (Frontend, Backend, HR)

📄 Resume-based question generation

🤖 AI-powered answer evaluation

📊 Performance insights & scoring

📈 Personalized improvement suggestions

🔄 Continuous practice & feedback loop

🧠 Adaptive question flow based on responses

🌐 Clean and interactive UI

🧱 Tech Stack
Layer	Technology
Frontend	React.js, HTML, CSS, JavaScript
Backend	Node.js, Express.js
AI	Python, Flask
AI API	Gemini API
Data Handling	REST APIs, JSON
Version Control	Git, GitHub

📂 Project Structure
intervai/
│
├── frontend/
│   ├── src/
│   ├── components/
│   └── App.js
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── controllers/
│   └── ai/
│
└── .gitignore

⚙️ How to Run Locally
Frontend
cd frontend
npm install
npm start
Backend
cd backend
npm install
node server.js
AI Service
cd backend/ai
python app.py
🎯 Hackathon Vision

IntervAI aims to transform traditional interview preparation by integrating AI-based evaluation, enabling users to practice smarter, receive real-time insights, and continuously improve their performance.

👨‍💻 Author

Sunil Kumawat
Sattar kureshi
Punyadeep singh


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
