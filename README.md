<div align="center">
  <br />
  <h1>Prepwise</h1>
  <h3 align="center">A job interview preparation platform powered by Vapi AI Voice agents</h3>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)  
2. ⚙️ [Tech Stack](#tech-stack)  
3. 🔋 [Features](#features)  
4. 🤸 [Quick Start](#quick-start)  
5. 🕸️ [Snippets](#snippets)  
6. 🔗 [Assets](#links)  
7. 🚀 [More](#more)  

---

## <a name="introduction">🤖 Introduction</a>

**Prepwise** is a platform designed to help job seekers practice and prepare for interviews.  
Built with **Next.js** for the frontend, **Firebase** for authentication & storage, and **Vapi AI** for real-time voice interviews, it provides an immersive experience to simulate real interview scenarios.  

Users can:  
- Take AI-powered mock interviews.  
- Get real-time feedback and transcripts.  
- Track performance in a personalized dashboard.  

---

## <a name="tech-stack">⚙️ Tech Stack</a>

- **Next.js** – Full-stack React framework  
- **Tailwind CSS** – Styling  
- **Firebase** – Authentication & Database  
- **Vapi AI** – Voice AI Agents  
- **shadcn/ui** – UI Components  
- **Google Gemini** – AI for evaluation & feedback  
- **Zod** – Data validation  

---

## <a name="features">🔋 Features</a>

👉 **Authentication** – Secure sign-up & login with Firebase  
👉 **Mock Interviews** – AI-driven interviews with voice interaction  
👉 **Feedback System** – Get structured feedback scored across multiple categories  
👉 **Transcripts** – View detailed logs of past interviews  
👉 **Dashboard** – Track and manage all your interview sessions  
👉 **Responsive UI** – Works smoothly on desktop and mobile  

---

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally:  

### Prerequisites
- [Git](https://git-scm.com/)  
- [Node.js](https://nodejs.org/)  
- [npm](https://www.npmjs.com/)  

### Clone & Install
```bash
git clone https://github.com/Ayp47098/Ai-based-Mock-interview.git
cd ai_mock_interviews-main
npm install



**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

Replace the placeholder values with your actual **[Firebase](https://firebase.google.com/)**, **[Vapi](https://vapi.ai/?utm_source=youtube&utm_medium=video&utm_campaign=jsmastery_recruitingpractice&utm_content=paid_partner&utm_term=recruitingpractice)** credentials.

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

