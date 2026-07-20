<h1 align="center">Janavee V</h1>
<h3 align="center">Full-Stack Developer building AI-powered and real-time systems</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/janavee-v-7809072b7/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:janavee2k6@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://leetcode.com/u/Janvi1/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
  <img src="https://komarev.com/ghpvc/?username=Janavee01&style=for-the-badge&color=blue" alt="profile views" />
</p>

<p align="center">
I like building things that actually run end to end — a computer vision pipeline that turns a 2D floor plan into a furnished 3D render, a legal advisor backed by hybrid retrieval over real statutes, a multiplayer game engine that stays in sync under 60ms. This page is a running log of that work.
</p>

---

## Projects

### AI Legal Advisor
A hybrid RAG system that answers questions over 37+ Indian Acts by combining semantic retrieval, BM25 keyword search, query expansion, and reranking. Comes with its own evaluation harness — Hit@1, Hit@3, Hit@5, and MRR — to catch retrieval failures before they become wrong answers.
`Python` `ChromaDB` `Sentence Transformers` `BM25` `FastAPI`
[Repository](https://github.com/Janavee01/Legal_Advisor)

### FloorPlan AI
A full computer vision pipeline that takes a 2D architectural floor plan and produces a photorealistic, furnished 3D render. Multi-pass OCR extracts room labels under any font or contrast, a custom Voronoi flood-fill (seeded from OCR positions) segments open-plan layouts without needing walls between rooms, and a ControlNet + Stable Diffusion stage renders the final scene from architectural line art.
`Python` `OpenCV` `PyTorch` `Tesseract` `ControlNet` `Stable Diffusion`
[Repository](https://github.com/Janavee01/floorplan)

### Real-Time Multiplayer Game
A 2D multiplayer fighting game built on a server-authoritative architecture with async, event-driven networking. Custom state-reconciliation logic cut desync incidents by 95%, and the WebSocket pipeline holds sync latency under 60ms even under load, with NGINX load balancing across game instances.
`Node.js` `Express` `Socket.IO` `NGINX` `JavaScript`

### Emovox — Emotion-Aware Storyteller
Turns written stories into emotionally expressive narration. Sentence-level emotion is scored with DistilRoBERTa, TinyLlama shapes the voice direction, and Parler-TTS handles expressive speech synthesis, with matching background music layered in automatically. Built with accessibility in mind — for creators, educators, and visually impaired readers.
`Next.js` `React` `NLP` `TinyLlama` `Parler-TTS`
[Repository](https://github.com/Janavee01/Emovox)

### NFT Rental Tickets
A decentralized access-control system where NFTs act as secure, time-limited keys to encrypted personal data vaults — no passwords, no centralized storage. Supports conditional access, automatic expiration, and multi-use NFTs that can be reused or transferred while access rules stay intact on-chain.
`Solidity` `Ethereum` `Web3.js` `React` `Tailwind CSS`
[Repository](https://github.com/Janavee01/NFT_rental_tickets)

### ICSD Club Website & Recruitment Portal
A monorepo of two Next.js applications built and shipped for a student technical club: a WebGL-driven informational site and a recruitment portal with client-side validated forms, serverless submissions to Google Sheets, and a modern UI built on shadcn/ui and Radix.
`Next.js` `TypeScript` `Tailwind CSS` `shadcn/ui` `Google Apps Script`
[Repository](https://github.com/Janavee01/club_website_and_recruitment_portal) · [Website](https://site-fu5n1mj73-janavee01s-projects.vercel.app/) · [Recruitment Portal](https://recruitmentportalicsd.vercel.app/)

### SkinSense
A responsive web app simulating an AI-powered skincare kiosk — real-time skin condition detection through a live webcam feed, with rule-based product recommendations and a smooth, guided UI.
`React` `Tailwind CSS` `OpenCV`
[Repository](https://github.com/Janavee01/SkinSense)

### AI Parental Control Extension
A Chrome extension for monitoring and restricting a child's browsing activity — tracks browsing and YouTube history, blocks content against updated blocklists, and surfaces everything on a responsive dashboard with real-time alerts.
`JavaScript` `Chrome Extensions API` `Tailwind CSS`

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)

**Backend & Real-Time**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

**AI, ML & Data**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

**Databases & Cloud**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

**Blockchain**

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![Web3.js](https://img.shields.io/badge/Web3.js-F16822?style=for-the-badge&logo=web3dotjs&logoColor=white)

**Tools & Platforms**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

---

## GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Janavee01&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Janavee01&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Janavee01&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph" width="100%"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Janavee01&theme=algolia&no-frame=true&column=7&margin-w=8" alt="Trophies"/>
</p>

<div align="center">

To turn your contribution graph into an actual snake game animation (the snake eats your contribution squares), add this repo to a workflow using the [Platane/snk](https://github.com/Platane/snk) GitHub Action — it generates an SVG you can embed right below your stats. Takes about five minutes to wire up and is one of the more memorable things a recruiter scrolling your profile will see.

</div>

---

<p align="center">
Open to full-time and internship roles where I can keep building systems like these — reach out at <b>janavee2k6@gmail.com</b>.
</p>
