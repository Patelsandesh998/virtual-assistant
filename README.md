🧠 Voice Assistant with Gemini AI
A smart, voice-controlled assistant built using React, Google Gemini API, and the Web Speech API. This assistant listens to voice commands, speaks back responses, and can open apps or search platforms like Google, YouTube, Instagram, etc.


🔧 Features
🎤 Voice recognition (via Web Speech API)

🗣️ Speech synthesis (Text-to-Speech)

🧠 AI integration via Gemini API

🔍 Command-based actions (search Google, play on YouTube, etc.)

📱 Responsive layout with hamburger menu

🧑 User customization and login/logout

📜 History view of past commands

🚀 Live Demo
(Add your deployed link here if available)

📁 Folder Structure
bash
Copy
Edit
src/
├── assets/            # GIFs and images
├── context/           # User context
├── components/        # React components
├── pages/             # Home and other pages
├── App.js             # Main app entry
└── index.js           # React DOM render
🛠️ Installation & Setup
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install dependencies

bash
Copy
Edit
npm install
Set up environment variables

Create a .env file and add:

env
Copy
Edit
REACT_APP_SERVER_URL=http://localhost:5000
Start the app

bash
Copy
Edit
npm start
🧠 Tech Stack
React – Frontend UI

React Router – Navigation

Web Speech API – Voice recognition + speech synthesis

Axios – API communication

Google Gemini API – Natural language understanding

Tailwind CSS – Styling

📌 Commands Supported
"Search [something] on Google"

"Open Instagram / Facebook"

"Play [song name] on YouTube"

"What's the weather?"

"Open calculator"

...and more via the Gemini integration!

🔐 Authentication
Login and logout functionality

Uses cookies (via withCredentials) for session handling

📦 Available Scripts
bash
Copy
Edit
npm start      # Start development server
npm run build  # Build for production
