# 🎙️ AI Interview Preparation Assistant  

[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)  
[![Vapi.ai](https://img.shields.io/badge/Vapi.ai-Voice%20AI-blue?style=for-the-badge)](https://vapi.ai/)  
[![Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://deepmind.google/technologies/gemini/)  
[![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)  

An **AI-powered mock interview platform** that helps candidates practice interviews in real time.  
This app uses **[Vapi.ai](https://vapi.ai/)** for **voice-based conversation** and **Google Gemini** to generate **dynamic, role-specific interview questions**.  

---

## 🚀 Features  

- 🎤 **Voice-based Interviewing** – Talk to an AI interviewer powered by Vapi.ai.  
- 🤖 **Smart Question Generation** – Gemini generates questions based on role, experience, and tech stack.  
- 🧠 **Adaptive Flow** – Questions get progressively harder based on answers.  
- 📊 **Interview Feedback (Planned)** – Insights and suggestions for improvement.  
- 🌐 **Built with Next.js** – Fast, scalable, and deployable on Vercel.  

---

## 🛠️ Tech Stack  

- **Frontend**: [Next.js](https://nextjs.org/) + TypeScript  
- **Voice AI**: [Vapi.ai](https://vapi.ai/)  
- **LLM**: Google **Gemini**  
- **Deployment**: [Vercel](https://vercel.com/)  

---

## ⚡ Getting Started  

First, clone the repository:  

```
git clone https://github.com/your-username/ai-interview-assistant.git
cd ai-interview-assistant
```

Install dependencies:  

```
npm install
# or
yarn install
# or
pnpm install
```

Run the development server:  

```
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.  

---

## 🔑 Environment Variables  

Create a `.env.local` file in the root directory and add your keys:  

```
VAPI_API_KEY=your_vapi_key_here
GEMINI_API_KEY=your_gemini_key_here
```

---

## 📦 Deployment  

Easiest way: Deploy on **Vercel**.  

```
vercel
```

Docs: [Next.js Deployment](https://nextjs.org/docs/app/building-your-application/deploying)  

---

## 📌 Roadmap  

- ✅ Basic voice interview flow  
- ✅ AI-generated role-specific questions  
- ⏳ Automated scoring & feedback  
- ⏳ Custom interview scenarios  

---
