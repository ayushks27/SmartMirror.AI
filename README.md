🧠 AI Mock Interview App
An intelligent web app that simulates real-time mock interview sessions using Google's Gemini AI, with Clerk authentication, hosted on Firebase, and styled beautifully using Tailwind CSS. Built with React + TypeScript for a responsive, maintainable front-end experience.

🔍 About the Project
This project helps users prepare for job interviews by generating realistic AI-driven questions and evaluating responses in a structured, interactive format. Users can log in securely using Clerk, select interview topics or difficulty levels, and receive instant AI feedback powered by Gemini.

Whether you're practicing for behavioral interviews, technical rounds, or system design, this app delivers a smart and engaging experience.

🚀 Tech Stack
Category	Tech Used
Frontend	React.js, TypeScript, Tailwind CSS
Authentication	Clerk
Hosting	Firebase Hosting
Backend / API	Gemini API (via Google AI)
State & Logic	React Hooks, Context API (optional)

⚙️ Installation
1. Clone the repository:
git clone https://github.com/your-username/ai-mock-interview-app.git
cd ai-mock-interview-app
2. Install dependencies:
npm install
3. Set up environment variables:
Create a .env file in the root directory:
env
VITE_CLERK_PUBLISHABLE_KEY=your-clerk-key
VITE_GEMINI_API_KEY=your-gemini-api-key
💡 Important: Do not expose secret Gemini keys in the frontend. Use Firebase Functions to keep it secure in production.

4. Start the development server:
npm run dev

🌐 Deployment
This app is deployed via Firebase Hosting. To deploy:
npm run build
firebase deploy
You must run firebase login and firebase init once before deploying.

📸 Screenshots (optional)
Add interface images or screen flows here.

🙌 Contributions
Feel free to fork this repo and submit pull requests. Feedback and improvements are always welcome!


