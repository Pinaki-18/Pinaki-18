<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=160&section=header&text=FITjob&fontSize=52&fontColor=fff&animation=twinkling&fontAlignY=36&desc=AI%20Resume%20Analyzer%20%7C%20Know%20Your%20Chances%20Before%20You%20Apply&descAlignY=58&descSize=15" width="100%"/>

</div>

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_LLaMA_3.3_70B-FF6B35?style=for-the-badge)

</div>

---

## 🎯 What is FITjob?

**FITjob** is an AI-powered platform that helps IT professionals maximize their interview chances by analyzing how well their resume matches a job description — *before they apply.*

> Everyone in IT faces the same problem — not getting interview calls. People waste time applying to jobs where their resume doesn't match the requirements at all. **FITjob fixes that.**

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 📊 **ATS Match Score** | Know exactly how well your resume matches the JD (0–100%) |
| 🔍 **Keyword Suggester** | AI finds missing keywords to boost your ATS ranking |
| 💼 **Live Job Search** | Real matching jobs from 50+ portals instantly |
| 📄 **PDF Upload** | Drag & drop resume upload with instant parsing |
| 💡 **AI Suggestions** | Strengths, gaps & improvement recommendations |
| 📱 **Responsive UI** | Works seamlessly on all devices |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React.js + Vite |
| **Backend** | Node.js + Express |
| **AI** | Groq AI (Llama 3.3 70B) |
| **PDF Parsing** | pdf-parse |
| **Job Search** | JSearch API (RapidAPI) |

---

## 🚀 Run Locally

### Prerequisites
- Node.js v18+
- Groq API Key → [console.groq.com](https://console.groq.com) *(free)*
- RapidAPI Key → [rapidapi.com](https://rapidapi.com) *(free)*

### Backend Setup

```bash
cd server
npm install
```

Create a `.env` file in `/server`:

```env
GROQ_API_KEY=your_groq_key
RAPID_API_KEY=your_rapidapi_key
PORT=5000
```

```bash
node server.js
```

### Frontend Setup

```bash
cd client
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) 🎉

---

## 👨‍💻 Built By

**Pinaki Mishra** — [GitHub](https://github.com/Pinaki-18)

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
