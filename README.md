# 🚀 GitHub Portfolio Analyzer

[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat&logo=next.js)](https://nextjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=flat&logo=tailwind-css)](https://tailwindcss.com/)
[![Gemini AI](https://img.shields.io/badge/AI-Gemini_2.0_Flash-4285F4?style=flat&logo=google)](https://deepmind.google/technologies/gemini/)
[![Vercel](https://img.shields.io/badge/Deployment-Vercel-000000?style=flat&logo=vercel)](https://vercel.com/)

> **🔴 Live Demo:** [https://github-portfolio-analyzer.vercel.app](https://github-portfolio-analyzer.vercel.app)
>
> **🎥 Video Demo:** [Watch the 30s Walkthrough Here](PASTE_YOUR_YOUTUBE_LINK_HERE)

---

## 💡 The Problem
Recruiters spend less than **6 seconds** on a resume. When they click your GitHub link, they are looking for **engineering signals**, not just "green squares."

Most student profiles suffer from **"Tutorial Bloat"**—To-Do lists, Weather Apps, and Clones that don't show real skill. Existing tools give everyone a "Participation Trophy" score (90/100) just for having a README.

## 🚀 The Solution: A "Ruthless" AI Recruiter
**GitHub Portfolio Analyzer** is a **Cynical Senior Engineer AI**. It doesn't just count commits; it judges **Code Quality, Architecture, and Consistency**.

It uses **Gemini 2.0 Flash** to perform a deep audit of your top repositories and assigns a "Hireability Score" based on:
1.  **Technical Depth:** Distinguishes between a "Hello World" and a Distributed System.
2.  **Documentation:** Penalizes READMEs that lack architecture diagrams or trade-offs.
3.  **Consistency:** Flags "Ghost Profiles" (inactive for >3 months).

---

## ✨ Key Features (The "Secret Sauce")
* **🧠 Context-Aware Scoring:**
    * **Student Cap:** Simple CRUD apps are capped at 65/100.
    * **Founder Immunity:** "Founders" and "DevRel" profiles are judged on impact, avoiding the "Tutorial Penalty."
* **📉 The "One-Hit Wonder" Detector:** Detects if a user has only one good repo (Hackathon project) and 10 bad ones, adjusting the score accordingly.
* **⚡ Instant Analysis:** Uses Next.js Server Actions and Caching to deliver results in <3 seconds.
* **🎨 Cyberpunk Dashboard:** A "Dark Mode First" UI designed for developers, featuring glassmorphism and data visualization.

---

## 🛠️ Tech Stack
* **Framework:** [Next.js 15](https://nextjs.org/) (App Router)
* **Styling:** Tailwind CSS + Shadcn UI + Framer Motion
* **AI Engine:** Google Gemini 2.0 Flash (via OpenRouter)
* **Data:** GitHub REST API (Octokit)
* **Deployment:** Vercel

---

## 🚀 Getting Started Locally

### Prerequisites
* Node.js 18+
* GitHub Token (Classic)
* Gemini/OpenAI API Key

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/Pranjal685/Github-Portfolio-Analyzer.git
    cd Github-Portfolio-Analyzer
    ```

2.  **Install Dependencies**
    ```bash
    npm install
    ```

3.  **Set up Environment Variables**
    Create a `.env.local` file in the root:
    ```env
    GITHUB_TOKEN=ghp_your_github_token_here
    GEMINI_API_KEY=your_ai_api_key_here
    ```

4.  **Run the Development Server**
    ```bash
    npm run dev
    ```
    Open [http://localhost:3000](http://localhost:3000) to see the app.

---

## 📄 License
MIT License © 2026
