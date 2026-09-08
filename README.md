<h1 align="center">Mihai-Alexandru Andronescu</h1>
<p align="center">
  <b>Software Developer · AI, Data &amp; Full-Stack</b><br>
  Computer Science &amp; Economics (Economic Informatics) @ ASE Bucharest
</p>
<p align="center">
  I build end-to-end AI systems and web applications, and I ship them.<br>
  Currently targeting a Master's degree in Artificial Intelligence.
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/mihai-alexandru-andronescu-58792b33b/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:andronescumihai.alex13@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=andronescumihai&style=for-the-badge&color=0A66C2&label=Profile+Views" alt="Profile views" />
</p>

---

## About Me

I'm an **Economic Informatics (Cybernetics)** student at the **Bucharest University of Economic Studies (ASE)**, working at the intersection of software engineering, applied AI, and data.

I care about building complete projects, from multi-agent AI systems to deployed full-stack applications, and documenting them honestly, including their limitations. I'd rather ship one real, working product than list ten I haven't built.

I like owning a project from end to end: I come up with the idea, design the data model, handle the security, wire up the API integrations, and build the interface, all the way through to deployment. My background in Economic Informatics means I actually understand how the pieces fit together, not just how to make them run.

My next step is a **Master's in Artificial Intelligence**, with a focus on applied AI engineering that creates measurable value for businesses.

- 🎓 BSc Economic Informatics @ ASE Bucharest (academic merit scholar)
- 🧠 Focus: AI engineering, data pipelines, full-stack development
- 🚀 Building &amp; shipping: 4 projects currently deployed live on Vercel
- 🌍 Open to internships and junior developer / AI roles

---

## Featured Projects

### [AI Agentic Business Orchestrator](https://github.com/andronescumihai/AI-Agentic-Business-Orchestrator)
A multi-agent system that handles the everyday work of an appointments business: sorting incoming emails, booking appointments, and putting together basic financial reports. The agents are tied together by a LangGraph state machine.

Some of the design decisions I made:

- I built the agents so they can propose an action but never carry one out on their own. Before a booking is confirmed, my code validates the slot against the database, so nothing gets written on a guess.
- When an agent isn't confident, or its output comes back malformed, I route the request to a human instead of letting it act.
- I locked access down at the database level with **Postgres Row-Level Security**, so the owner, a doctor and a client each see only what's theirs.
- I connected it to a real Gmail inbox over OAuth2 and ran those messages through the same pipeline I designed for the rest.

<p>
  <img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" />
</p>

### [Global Market Sentiment Analyzer](https://github.com/andronescumihai/Global-Market-Sentiment-Analyzer) &nbsp;·&nbsp; 🟢 Live
A full-stack pipeline that aggregates news and social data to score market sentiment for financial assets, comparing several models on the same metrics. Deployed live on Vercel.

<p>
  <img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
</p>

### [Neural Automobile Market Forecaster](https://github.com/andronescumihai/Neural-Automobile-Market-Forecaster) &nbsp;·&nbsp; 🟢 Live
A deep-learning model (Keras MLP) that predicts used-car price and depreciation, trained on **~620,000 real listings** (R² ≈ **0.917** on price, MAE ≈ **$1,784**), with a live inference dashboard.

<p>
  <img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow%2FKeras-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
</p>

### [RealTime Object Detection Sentinel](https://github.com/andronescumihai/RealTime-Object-Detection-Sentinel) &nbsp;·&nbsp; 🟢 Live
A browser-based real-time computer vision app: a pre-trained CNN (COCO-SSD / MobileNetV2) runs fully client-side in TensorFlow.js on your webcam or an uploaded image, drawing bounding boxes with confidence scores. Includes a **Sentinel** watch-a-class alert mode, a live analytics dashboard, and a **privacy-first** design, no video ever leaves the device. Deployed live on Vercel.

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow.js-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
</p>

### [Smart User Behavior Recommender](https://github.com/andronescumihai/Smart-User-Behavior-Recommender) &nbsp;·&nbsp; 🟢 Live
A movie recommender that trains and compares **7 models** (collaborative filtering, matrix factorization, and more) on **1,000,000+ real MovieLens ratings**, evaluated on the same metrics.

<p>
  <img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
</p>

### Private &amp; Client Work

Not everything I build is public. Two projects I'm especially proud of:

- **Italian restaurant website** ([live](https://agatinogourmet.com)): a custom site with a product catalog backed by a database and smooth animations. I designed it, wired up the database, and built it to load fast and rank well on Google. The repository stays private because it holds a client's data.
- **Law study app** (built for a friend studying law): a personal tool for Romanian legislation. I built it to keep a database of the current laws that refreshes every week, generate practice tests, and explain any law or term in four different styles, so she can revise the way that suits her best. Private, since it's tailored to one person.

> My public repositories also include relational database systems (Oracle SQL / PL-SQL, Oracle APEX) and several Python data pipelines and web scrapers.

---

## Tech Stack

### Languages
<p align="left">
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### AI &amp; Data
<p align="left">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow.js-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
</p>

### Web &amp; Backend
<p align="left">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
</p>

### Databases &amp; Cloud
<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</p>

### Tools
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
</p>

---

## What I'm Working On

- 🧠 Just completed the **DeepLearning.AI TensorFlow Developer Professional Certificate**
- 🤖 Building more AI projects to deepen my deep-learning &amp; computer-vision portfolio
- 💼 Building websites, apps and automations for small businesses through my own freelance work
- 🎯 Preparing my application for a **Master's in Artificial Intelligence**

---

## Education &amp; Experience

- **BSc Economic Informatics (Cybernetics)**, ASE Bucharest · academic merit scholarship
- **UI/UX Internship**, Ideologiq (2026): user-persona analysis, GDPR compliance, front-end work
- **Oracle Tech Bootcamp**: Oracle APEX, SQL, relational data modeling, secure cloud architecture
- **Member**, Cybernetics Students' Union (SISC), ASE

---

## Certifications

- **DeepLearning.AI TensorFlow Developer Professional Certificate**
- **IBM Data Science Specialization**
- **Mathematics for Machine Learning**, Imperial College London
- **Python for Everybody**, University of Michigan
- **Google IT Professional Certificate**
- **AI for Everyone**, DeepLearning.AI
- **IBM AI Foundations for Business**
- *Planned:* **AWS certification**

---

## Highlights

<p align="center">
  <img src="https://img.shields.io/badge/Public_Repos-29-0A66C2?style=for-the-badge" alt="Repos" />
  <img src="https://img.shields.io/badge/Featured_AI_Projects-5-6C3FC6?style=for-the-badge" alt="AI Projects" />
  <img src="https://img.shields.io/badge/Live_on_Vercel-4-2E9E6B?style=for-the-badge" alt="Live" />
  <img src="https://img.shields.io/badge/Data_Points_Trained-1M%2B-F2B705?style=for-the-badge&logoColor=black" alt="Data" />
</p>

<p align="center">
  From multi-agent AI systems to deployed full-stack web apps, built and shipped end to end.
</p>

---

## What I'm Looking For

Junior **Software Developer / AI / Data** roles and internships where I can build real products, keep learning fast, and contribute from day one, whether on-site, hybrid, or remote.

**Beyond code:** eight years of judo (discipline over luck), and I produce music in my spare time.

<p align="center">
  <a href="https://www.linkedin.com/in/mihai-alexandru-andronescu-58792b33b/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:andronescumihai.alex13@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>
