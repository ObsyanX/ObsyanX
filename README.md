![Banner](Banner.svg)

<svg width="1200" height="260" viewBox="0 0 1200 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      /* ===============================
         🌑 DARK THEME (Default)
         =============================== */
      :root {
        --bg: #000000;
        --surface: #0D0D0D;
        --text: #FFFFFF;
        --accent: #FFBF00;
        --border: #333333;
        --edition-gold: #D18605;
        --edition-purple: #8226D9;
        --edition-blue: #0073E6;
        --edition-green: #1B9865;
      }

      /* ===============================
         ☀️ LIGHT THEME
         =============================== */
      @media (prefers-color-scheme: light) {
        :root {
          --bg: #F9F7F2;
          --surface: #EBE9E4;
          --text: #20242B;
          --accent: #F9A006;
          --border: #D1CFCA;
          --edition-gold: #D18605;
          --edition-purple: #8226D9;
          --edition-blue: #0073E6;
          --edition-green: #1B9865;
        }
      }

      text {
        font-family: Inter, Segoe UI, system-ui, sans-serif;
      }
    </style>

    <!-- Accent gradient -->
    <linearGradient id="accentGradient" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="var(--edition-gold)"/>
      <stop offset="50%" stop-color="var(--accent)"/>
      <stop offset="100%" stop-color="var(--edition-purple)"/>
    </linearGradient>

    <!-- Soft glow -->
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1200" height="260" fill="var(--bg)" />

  <!-- Card surface -->
  <rect x="40" y="30" width="1120" height="180"
        rx="18"
        fill="var(--surface)"
        stroke="var(--border)"
        stroke-width="1"/>

  <!-- Accent line -->
  <rect x="40" y="190" width="1120" height="3"
        fill="url(#accentGradient)"
        filter="url(#glow)"/>

  <!-- Name -->
  <text x="80" y="105"
        font-size="46"
        font-weight="700"
        fill="var(--text)">
    Sayan Dutta
  </text>

  <!-- Role -->
  <text x="80" y="145"
        font-size="22"
        fill="var(--edition-green)">
    AI Engineer • Deep Learning • Full-Stack Developer
  </text>

  <!-- Tagline -->
  <text x="80" y="175"
        font-size="16"
        fill="var(--edition-blue)">
    Designing intelligent systems with clarity, ethics, and impact
  </text>
</svg>



<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&pause=1000&color=00FFD1&center=true&vCenter=true&width=850&lines=AI+%7C+Deep+Learning+%7C+Full-Stack;Building+Intelligent+Systems+for+the+Real+World;Code+with+Purpose.+Design+with+Intent." />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ObsyanX&label=Profile+Views&color=00FFD1&style=flat" />
</p>

---

## 👨‍🚀 About Me

I’m a **final-year Computer Science student** focused on building **intelligent, scalable, and human-centric systems** at the intersection of **AI, Web, and real-world impact**.

- 🚀 **Domain**: AI • Web • Real-World Systems  
- 🧠 **Primary Focus**: Deep Learning for Healthcare  
- 🔬 **Currently Exploring**:
  - Generative AI & Large Language Models  
  - Quantum Machine Learning  
  - Neural & Human-Computer Interfaces  

> *“I don’t just build software — I design systems that think, adapt, and matter.”*

---

## 🛠️ Core Technology Stack

**Frontend**
- React • Vite • Tailwind CSS • Three.js  

**Backend & AI**
- Node.js • FastAPI  
- TensorFlow • PyTorch  

**Databases**
- MongoDB • Neo4j • Supabase  

**DevOps**
- Docker • GitHub Actions • Kubernetes  

---

## 💎 Featured Projects

### 🧠 NeuroScan — Parkinson’s Disease Diagnosis
**AI-powered neurological screening system**

- CNN-LSTM hybrid models for early detection  
- Multimodal analysis: gait + voice biomarkers  
- Adaptive learning using clinician feedback  

**Tech**: TensorFlow • Librosa • Streamlit  
🔗 https://github.com/ObsyanX/Parkinsons-Diagnosis-AI

---

### 🌍 Aether — Smart Air Quality Intelligence Platform
**Predictive environmental health ecosystem**

- Pollution forecasting & exposure modeling  
- Clean-route optimization for urban mobility  
- AR-based pollution hotspot visualization  

**Tech**: XGBoost • GeoSpark • React • IoT  
🔗 https://github.com/ObsyanX/air-quality-index-analysis

---

### ⚙️ QuantumScraper — Intelligent RFQ Analytics Engine
**Autonomous commerce intelligence system**

- Self-healing web extraction pipelines  
- NLP-based RFQ trend prediction  
- Dynamic throttling & proxy rotation  

**Tech**: Selenium • Scrapy • NLP  
🔗 https://github.com/ObsyanX/alibaba_web_scraping

---

### 🌌 Nebula — Immersive 3D Portfolio
**Experimental interactive developer portfolio**

- 3D & VR-ready experience  
- Voice-controlled navigation  
- Real-time interactive components  

**Tech**: React-Three-Fiber • GSAP • EmailJS  
🔗 https://github.com/ObsyanX/Portfolio_Latest1_25-07-25

---

## 🧪 Research & Experimental Work

- 🧠 **Currently studying**: Quantum Machine Learning frameworks  
- 🧬 **Experimenting with**: Neural Radiance Fields (NeRF)  
- 🔐 **Research interest**: Blockchain-based AI model verification  

---

## 📊 GitHub Activity Snapshot

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ObsyanX&show_icons=true&theme=react&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ObsyanX&layout=compact&theme=react&hide_border=true)

---

## 🌐 Connect With Me

[![Email](https://img.shields.io/badge/Email-00FFD1?style=for-the-badge&logo=gmail&logoColor=black)](mailto:duttasayan947595@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/duttasayan835)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)](https://github.com/ObsyanX)

---

## ✨ Philosophy

> *“The most elegant systems are built when engineering discipline meets ethical intent.”*

---

## 🚀 Open to

- Research collaborations  
- AI / ML internships & roles  
- High-impact open-source work  

**Let’s build something meaningful.**

---
