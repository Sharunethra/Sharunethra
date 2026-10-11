<div align="center">

<img src="assets/header.svg" alt="Sharu Nethra R — GitHub Banner" width="100%" />

# Sharu Nethra R

### **AI/ML Engineer | Full-Stack Developer | Trustworthy AI & FinTech Research**

<p align="center">
  <a href="https://github.com/Sharunethra"><img src="https://img.shields.io/badge/GitHub-Profile-FFCCE1?style=flat-square&logo=github&logoColor=2D3748&labelColor=F2F1ED" alt="GitHub Profile" /></a>
  <a href="https://www.linkedin.com/in/sharu-nethra-r-18a48b346/"><img src="https://img.shields.io/badge/LinkedIn-Connect-C6E2E7?style=flat-square&logo=linkedin&logoColor=2D3748&labelColor=F2F1ED" alt="LinkedIn Profile" /></a>
  <a href="mailto:sharunethra18@gmail.com"><img src="https://img.shields.io/badge/Email-Get_in_Touch-CDE5D9?style=flat-square&logo=gmail&logoColor=2D3748&labelColor=F2F1ED" alt="Email" /></a>
  <a href="https://github.com/Sharunethra?tab=repositories"><img src="https://img.shields.io/badge/Focus-AI_%26_Systems-F2EBCC?style=flat-square&logo=git&logoColor=2D3748&labelColor=F2F1ED" alt="Focus" /></a>
</p>

<img src="assets/divider.svg" alt="Pastel Divider" width="100%" />

</div>

## 🌿 About Me

Hello! I am a Computer Science undergraduate at **SRM Institute of Science and Technology, Kattankulathur**, pursuing an **Honours Track in Financial Technologies (FinTech)** with a cumulative CGPA of **9.24 / 10** (2024–2028).

My engineering focus centers on bridging **trustworthy machine learning** with resilient **full-stack and backend software architectures**:

- 🧠 **AI/ML & Local Retrieval Systems**: I build Retrieval-Augmented Generation (RAG) pipelines, semantic embeddings, and local language model workflows that prioritize data privacy, deterministic retrieval, and hallucination reduction.
- ⚙️ **Backend & Distributed Systems**: I design scalable relational database schemas, multi-tenant resource isolation mechanisms, strict authentication flows, and clean RESTful APIs.
- 💡 **FinTech & Impact-Driven Research**: I am deeply interested in trustworthy AI evaluation, financial inclusion architectures, and computational modeling for climate-related financial resilience.

I believe in measurable engineering: writing clean code, validating functionality with rigorous automated tests, and building software that solves concrete problems with high reliability.

<div align="center">
  <img src="assets/divider.svg" alt="Pastel Divider" width="100%" />
</div>

## 🚀 Featured Projects

<table>
  <!-- PROJECT 1: LLAMA ASSISTANT -->
  <tr>
    <td width="100%" bgcolor="#FDFBF9" style="border: 2px solid #FFCCE1; border-radius: 12px; padding: 18px;">
      <div align="left">
        <a href="https://img.shields.io/badge/Featured-Project_01-FFCCE1?style=flat-square&labelColor=F2F1ED&color=FFCCE1"><img src="https://img.shields.io/badge/Featured-Project_01-FFCCE1?style=flat-square&labelColor=F2F1ED&color=FFCCE1" alt="Project 1" /></a>
        <a href="https://img.shields.io/badge/Live-Demo_Available-CDE5D9?style=flat-square&labelColor=F2F1ED&color=CDE5D9"><img src="https://img.shields.io/badge/Live-Demo_Available-CDE5D9?style=flat-square&labelColor=F2F1ED&color=CDE5D9" alt="Demo Available" /></a>
        <br />
        <h3 style="margin-top: 8px; margin-bottom: 6px; color: #1E293B;">
          🦙 <a href="https://github.com/Sharunethra/llama-assistant-rag" style="color: #1E293B; text-decoration: none;"><b>Llama Assistant — Local RAG-Based AI Document Assistant</b></a>
        </h3>
        <p style="color: #475569; font-size: 14px; line-height: 1.5; margin-bottom: 10px;">
          A full-stack, privacy-preserving document intelligence assistant that pairs localized Retrieval-Augmented Generation (RAG) with local language model inference to query personal documents without external API token leakage.
        </p>
        <p style="color: #334155; font-size: 13px; line-height: 1.5; margin-bottom: 8px;">
          <b>System Architecture &amp; Pipeline:</b>
        </p>
        <ul style="color: #475569; font-size: 13px; line-height: 1.5; margin-top: 0; margin-bottom: 12px;">
          <li><b>Document Ingestion &amp; Chunking:</b> Ingests multi-page PDF and TXT files, performing automated text extraction and deterministic chunking into 400-word passages with a 50-word sliding-window overlap to preserve syntactic boundaries.</li>
          <li><b>Dense Semantic Embeddings:</b> Encodes passages into 384-dimensional vector embeddings utilizing FastEmbed for lightweight, local vector transformation.</li>
          <li><b>Similarity Retrieval:</b> Computes cosine similarity over stored document vectors to isolate the top-four most relevant passages per user query.</li>
          <li><b>Document-Grounded Inference:</b> Feeds retrieved context into a locally executing Llama 3.2 3B model managed via Ollama, synthesizing precise, citation-grounded answers.</li>
          <li><b>Full-Stack Integration:</b> Token-authenticated Django REST Framework backend with PostgreSQL persistent multi-turn chat history, paired with a responsive React and Vite interface.</li>
        </ul>
        <p style="margin-bottom: 10px;">
          <a href="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
            <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /></a>
          <a href="https://img.shields.io/badge/Django_REST-092E20?style=flat-square&logo=django&logoColor=white">
            <img src="https://img.shields.io/badge/Django_REST-092E20?style=flat-square&logo=django&logoColor=white" alt="Django REST" /></a>
          <a href="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=2D3748">
            <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=2D3748" alt="React" /></a>
          <a href="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white">
            <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" /></a>
          <a href="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
            <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /></a>
          <a href="https://img.shields.io/badge/Ollama-Llama_3.2_3B-black?style=flat-square&logo=ollama&logoColor=white">
            <img src="https://img.shields.io/badge/Ollama-Llama_3.2_3B-black?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" /></a>
          <a href="https://img.shields.io/badge/Embeddings-FastEmbed_384d-CDE5D9?style=flat-square&labelColor=2D3748&color=CDE5D9">
            <img src="https://img.shields.io/badge/Embeddings-FastEmbed_384d-CDE5D9?style=flat-square&labelColor=2D3748&color=CDE5D9" alt="FastEmbed" /></a>
        </p>
        <p style="margin-bottom: 0;">
          🔗 <b>Repository:</b> <a href="https://github.com/Sharunethra/llama-assistant-rag">github.com/Sharunethra/llama-assistant-rag</a> &nbsp;|&nbsp;
          🌐 <b>Live Demo:</b> <a href="https://llama-assistant-rag-1.onrender.com/">llama-assistant-rag-1.onrender.com</a>
        </p>
      </div>
    </td>
  </tr>

  <!-- PROJECT 2: PROMANAGE -->
  <tr>
    <td width="100%" bgcolor="#FDFBF9" style="border: 2px solid #C6E2E7; border-radius: 12px; padding: 18px;">
      <div align="left">
        <a href="https://img.shields.io/badge/Featured-Project_02-C6E2E7?style=flat-square&labelColor=F2F1ED&color=C6E2E7"><img src="https://img.shields.io/badge/Featured-Project_02-C6E2E7?style=flat-square&labelColor=F2F1ED&color=C6E2E7" alt="Project 2" /></a>
        <a href="https://img.shields.io/badge/Tests-31%2F31_Passed-CDE5D9?style=flat-square&labelColor=F2F1ED&color=CDE5D9"><img src="https://img.shields.io/badge/Tests-31%2F31_Passed-CDE5D9?style=flat-square&labelColor=F2F1ED&color=CDE5D9" alt="Tests 31/31 Passed" /></a>
        <br />
        <h3 style="margin-top: 8px; margin-bottom: 6px; color: #1E293B;">
          📋 <a href="https://github.com/Sharunethra/project-management-system" style="color: #1E293B; text-decoration: none;"><b>ProManage — Unified Project Management System (Web + Mobile)</b></a>
        </h3>
        <p style="color: #475569; font-size: 14px; line-height: 1.5; margin-bottom: 10px;">
          A full-stack, multi-client project and task management system built upon a single unified REST backend and shared relational database, powering a responsive React web client alongside an Android mobile application.
        </p>
        <p style="color: #334155; font-size: 13px; line-height: 1.5; margin-bottom: 8px;">
          <b>Technical Architecture &amp; Implementation:</b>
        </p>
        <ul style="color: #475569; font-size: 13px; line-height: 1.5; margin-top: 0; margin-bottom: 12px;">
          <li><b>Unified REST Backend:</b> Engineered with Node.js, Express, and TypeScript, backed by Prisma ORM and PostgreSQL to serve both Web and mobile clients from a single authoritative source.</li>
          <li><b>Multi-Tenant Resource Ownership:</b> Enforces strict user isolation across all project and task CRUD operations, rejecting cross-tenant unauthorized reads, mutations, or deletions.</li>
          <li><b>Enterprise Security &amp; Auth:</b> Implements bcrypt password hashing (10 salt rounds), JWT authentication, strict Zod schema validation, and API rate limiting on authentication routes.</li>
          <li><b>Mobile Architecture &amp; Offline Resilience:</b> Cross-platform Android client built with React Native and Expo, utilizing Expo SecureStore for encrypted hardware-backed token persistence, graceful offline notifications, and session expiry recovery.</li>
          <li><b>Query Optimization &amp; Dashboards:</b> Database-backed pagination on list endpoints, multi-field search and status/priority filtering, and user-scoped real-time metric aggregates.</li>
          <li><b>Automated Test Suite:</b> Backed by <b>31/31 passing automated unit and integration tests</b> via Jest and Supertest, including end-to-end cross-platform synchronization verification (Tests A through F).</li>
        </ul>
        <p style="margin-bottom: 10px;">
          <a href="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white">
            <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" /></a>
          <a href="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
            <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /></a>
          <a href="https://img.shields.io/badge/Prisma_ORM-2D3748?style=flat-square&logo=prisma&logoColor=white">
            <img src="https://img.shields.io/badge/Prisma_ORM-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" /></a>
          <a href="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
            <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /></a>
          <a href="https://img.shields.io/badge/React_Vite-61DAFB?style=flat-square&logo=react&logoColor=2D3748">
            <img src="https://img.shields.io/badge/React_Vite-61DAFB?style=flat-square&logo=react&logoColor=2D3748" alt="React Vite" /></a>
          <a href="https://img.shields.io/badge/React_Native-Expo-000020?style=flat-square&logo=expo&logoColor=white">
            <img src="https://img.shields.io/badge/React_Native-Expo-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo" /></a>
          <a href="https://img.shields.io/badge/Jest_%26_Supertest-C21325?style=flat-square&logo=jest&logoColor=white">
            <img src="https://img.shields.io/badge/Jest_%26_Supertest-C21325?style=flat-square&logo=jest&logoColor=white" alt="Jest" /></a>
          <a href="https://img.shields.io/badge/Deploy_Ready-Render_%2F_Vercel_%2F_EAS-CDE5D9?style=flat-square&labelColor=2D3748&color=CDE5D9">
            <img src="https://img.shields.io/badge/Deploy_Ready-Render_%2F_Vercel_%2F_EAS-CDE5D9?style=flat-square&labelColor=2D3748&color=CDE5D9" alt="Deploy Configs" /></a>
        </ul>
        <p style="margin-bottom: 0;">
          🔗 <b>Repository:</b> <a href="https://github.com/Sharunethra/project-management-system">github.com/Sharunethra/project-management-system</a> &nbsp;|&nbsp;
          ⚙️ <i>Contains complete deployment configurations for Render, Vercel, and Expo EAS</i>
        </p>
      </div>
    </td>
  </tr>

  <!-- PROJECT 3: IMDB SENTIMENT CLASSIFICATION -->
  <tr>
    <td width="100%" bgcolor="#FDFBF9" style="border: 2px solid #CDE5D9; border-radius: 12px; padding: 14px 18px;">
      <div align="left">
        <a href="https://img.shields.io/badge/Featured-Project_03-CDE5D9?style=flat-square&labelColor=F2F1ED&color=CDE5D9"><img src="https://img.shields.io/badge/Featured-Project_03-CDE5D9?style=flat-square&labelColor=F2F1ED&color=CDE5D9" alt="Project 3" /></a>
        <a href="https://img.shields.io/badge/Accuracy-%3E85%25_Test-F2EBCC?style=flat-square&labelColor=F2F1ED&color=F2EBCC"><img src="https://img.shields.io/badge/Accuracy-%3E85%25_Test-F2EBCC?style=flat-square&labelColor=F2F1ED&color=F2EBCC" alt=">85% Accuracy" /></a>
        <br />
        <h3 style="margin-top: 8px; margin-bottom: 6px; color: #1E293B;">
          🎬 <a href="https://github.com/Sharunethra/TextClassificationWithTensorflow" style="color: #1E293B; text-decoration: none;"><b>IMDB Movie Review Sentiment Classification</b></a>
        </h3>
        <p style="color: #475569; font-size: 13px; line-height: 1.5; margin-bottom: 8px;">
          An NLP deep learning capstone project applying recurrent neural networks to classify large-scale movie reviews into positive and negative sentiment categories.
        </p>
        <ul style="color: #475569; font-size: 13px; line-height: 1.5; margin-top: 0; margin-bottom: 10px;">
          <li><b>Text Preprocessing Pipeline:</b> Performed text cleaning, HTML stripping, stopword handling, tokenization, vocabulary indexing, and sequence padding.</li>
          <li><b>Recurrent Architecture:</b> Built and trained an LSTM (Long Short-Term Memory) neural network using TensorFlow and Keras to capture sequential contextual dependencies.</li>
          <li><b>Evaluation:</b> Evaluated on the Kaggle IMDB dataset, achieving <b>&gt;85% classification accuracy</b> on unseen test data.</li>
        </ul>
        <p style="margin-bottom: 8px;">
          <a href="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
            <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /></a>
          <a href="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white">
            <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" /></a>
          <a href="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white">
            <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" alt="Keras" /></a>
          <a href="https://img.shields.io/badge/LSTM-Recurrent_NLP-CDE5D9?style=flat-square&labelColor=2D3748&color=CDE5D9">
            <img src="https://img.shields.io/badge/LSTM-Recurrent_NLP-CDE5D9?style=flat-square&labelColor=2D3748&color=CDE5D9" alt="LSTM" /></a>
          <a href="https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white">
            <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white" alt="Google Colab" /></a>
          <a href="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white">
            <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle" /></a>
        </p>
        <p style="margin-bottom: 0; font-size: 13px;">
          🔗 <b>Repository:</b> <a href="https://github.com/Sharunethra/TextClassificationWithTensorflow">github.com/Sharunethra/TextClassificationWithTensorflow</a>
        </p>
      </div>
    </td>
  </tr>
</table>

<div align="center">
  <img src="assets/divider.svg" alt="Pastel Divider" width="100%" />
</div>

## 🛠️ Technology Stack

<table width="100%">
  <tr>
    <td width="30%" bgcolor="#FDFBF9" style="border: 1px solid #FFCCE1; padding: 12px; vertical-align: top;">
      <b>💻 Programming Languages</b>
    </td>
    <td width="70%" bgcolor="#FDFBF9" style="border: 1px solid #FFCCE1; padding: 12px;">
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL" />
    </td>
  </tr>
  <tr>
    <td width="30%" bgcolor="#FDFBF9" style="border: 1px solid #C6E2E7; padding: 12px; vertical-align: top;">
      <b>🤖 AI &amp; Machine Learning</b>
    </td>
    <td width="70%" bgcolor="#FDFBF9" style="border: 1px solid #C6E2E7; padding: 12px;">
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
      <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" alt="Keras" />
      <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="Scikit-Learn" />
      <img src="https://img.shields.io/badge/NLP-Deep_Learning-CDE5D9?style=flat-square&labelColor=2D3748&color=CDE5D9" alt="NLP" />
      <img src="https://img.shields.io/badge/Embeddings-FastEmbed-F2EBCC?style=flat-square&labelColor=2D3748&color=F2EBCC" alt="FastEmbed" />
      <img src="https://img.shields.io/badge/RAG-LLM_Applications-FFCCE1?style=flat-square&labelColor=2D3748&color=FFCCE1" alt="RAG" />
    </td>
  </tr>
  <tr>
    <td width="30%" bgcolor="#FDFBF9" style="border: 1px solid #CDE5D9; padding: 12px; vertical-align: top;">
      <b>🌐 Frontend Development</b>
    </td>
    <td width="70%" bgcolor="#FDFBF9" style="border: 1px solid #CDE5D9; padding: 12px;">
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
    </td>
  </tr>
  <tr>
    <td width="30%" bgcolor="#FDFBF9" style="border: 1px solid #F2EBCC; padding: 12px; vertical-align: top;">
      <b>⚙️ Backend Engineering</b>
    </td>
    <td width="70%" bgcolor="#FDFBF9" style="border: 1px solid #F2EBCC; padding: 12px;">
      <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django" />
      <img src="https://img.shields.io/badge/Django_REST-092E20?style=flat-square&logo=django&logoColor=white" alt="Django REST" />
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
      <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" alt="Express.js" />
      <img src="https://img.shields.io/badge/REST_APIs-Architecture-C6E2E7?style=flat-square&labelColor=2D3748&color=C6E2E7" alt="REST APIs" />
    </td>
  </tr>
  <tr>
    <td width="30%" bgcolor="#FDFBF9" style="border: 1px solid #F7DDE8; padding: 12px; vertical-align: top;">
      <b>🗄️ Databases &amp; Infrastructure</b>
    </td>
    <td width="70%" bgcolor="#FDFBF9" style="border: 1px solid #F7DDE8; padding: 12px;">
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
      <img src="https://img.shields.io/badge/pgvector-Vector_Search-CDE5D9?style=flat-square&labelColor=2D3748&color=CDE5D9" alt="pgvector" />
      <img src="https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white" alt="Neo4j" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
    </td>
  </tr>
  <tr>
    <td width="30%" bgcolor="#FDFBF9" style="border: 1px solid #FFCCE1; padding: 12px; vertical-align: top;">
      <b>🛠️ AI Tools &amp; Orchestration</b>
    </td>
    <td width="70%" bgcolor="#FDFBF9" style="border: 1px solid #FFCCE1; padding: 12px;">
      <img src="https://img.shields.io/badge/Ollama-Local_Inference-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
      <img src="https://img.shields.io/badge/LangGraph-Agent_Workflows-FFCCE1?style=flat-square&labelColor=2D3748&color=FFCCE1" alt="LangGraph" />
      <img src="https://img.shields.io/badge/LangSmith-Observability-C6E2E7?style=flat-square&labelColor=2D3748&color=C6E2E7" alt="LangSmith" />
    </td>
  </tr>
</table>

<div align="center">
  <img src="assets/divider.svg" alt="Pastel Divider" width="100%" />
</div>

## 💼 Experience

### 🔹 **Web Developer** — Studique (The Momentum)
*Remote &nbsp;|&nbsp; March 2026 – September 2026*
- Contributed to a live student academic platform serving over 12K+ visitors and 50K+ platform page views.
- Updated syllabus structures and refined the CGPA calculation modules tailored for SRMIST student workflows.
- Maintained academic course material and verified calculation precision across seven or more core student-focused features.

### 🔹 **AI Intern** — Techjays
*Coimbatore, Tamil Nadu &nbsp;|&nbsp; July 2026 – August 2026*
- Engineered a full-stack, local RAG-based AI document assistant powered by Llama 3.2 3B.
- Built backend services in Python and Django REST Framework with PostgreSQL, integrating FastEmbed and Ollama for vector transformations and local language model queries.
- Implemented document ingestion pipelines, overlapping chunking algorithms, dense vector search, and grounded conversational Q&A interfaced through React and Vite.

### 🔹 **AI/ML Intern** — Pirai Infotech Pvt. Ltd.
*Pollachi, Tamil Nadu &nbsp;|&nbsp; June 2026*
- Developed end-to-end machine learning workflows using Python, NumPy, Pandas, Scikit-learn, and TensorFlow.
- Conducted data cleaning, feature extraction, exploratory data analysis (EDA), model training, and comparative evaluation metrics.

### 🔹 **Django & MySQL Intern** — MBT
*Hosur, Tamil Nadu &nbsp;|&nbsp; December 2025*
- Contributed to backend application development using Django and MySQL relational databases.
- Implemented data validation logic and database persistence schemas to support operational workflows.
- Built interactive dashboard visualization components for administrative monitoring.

<div align="center">
  <img src="assets/divider.svg" alt="Pastel Divider" width="100%" />
</div>

## 🎓 Education

- **SRM Institute of Science and Technology, Kattankulathur**
  - **B.Tech in Computer Science and Engineering**
  - **Honours Track:** Financial Technologies (FinTech)
  - **CGPA:** **9.24 / 10** &nbsp;|&nbsp; *2024 – 2028*
- **CS Academy, Coimbatore**
  - Class XII, CBSE — **87.6%** &nbsp;|&nbsp; *2024*
- **Srinivasa Public School, Udumalpet**
  - Class X, CBSE — **94.2%** &nbsp;|&nbsp; *2022*

<div align="center">
  <img src="assets/divider.svg" alt="Pastel Divider" width="100%" />
</div>

## 🔬 Research Interests

- **Trustworthy AI & System Evaluation:** Investigating hallucination mitigation, safety guardrails, and deterministic evaluation protocols for large language models.
- **Retrieval-Augmented Generation (RAG):** Contextual chunking methods, dense/hybrid vector index design, and low-latency on-device inference pipelines.
- **Financial Inclusion & FinTech Architectures:** Designing resilient, accessible transaction mechanisms and risk-scoring workflows for underserved economic communities.
- **Climate-Related Financial Resilience:** Computational modeling to quantify environmental and climate risk vectors on consumer finance, credit risk, and institutional resilience.
- **Responsible AI in Practical Software:** Implementing privacy-by-design, cryptographic token security, and strict data isolation across distributed systems.

<div align="center">
  <img src="assets/divider.svg" alt="Pastel Divider" width="100%" />
</div>

## 📜 Certifications

- **Oracle Certified Professional: Java SE 17 Developer** — *Oracle (Issued July 2026)*
- **NPTEL: Programming in Java** — *Elite Grade*
- **NPTEL: Fundamentals of Object-Oriented Programming** — *Elite Grade*

<div align="center">
  <img src="assets/divider.svg" alt="Pastel Divider" width="100%" />
</div>

## 🏆 Achievements

- **1st Place — E-SUMMIT ’26 Ideathon**
  - E-Cell, Indian Institute of Information Technology, Design and Manufacturing (IIITDM), Kancheepuram

<div align="center">
  <img src="assets/divider.svg" alt="Pastel Divider" width="100%" />
</div>

## 📊 GitHub Statistics

<div align="center">
  <table border="0" cellspacing="0" cellpadding="0">
    <tr>
      <td align="center" valign="middle">
        <a href="https://github.com/Sharunethra">
          <img src="https://github-readme-stats.vercel.app/api?username=Sharunethra&show_icons=true&title_color=2D3748&text_color=4A5568&icon_color=FFCCE1&bg_color=F2F1ED&border_color=FFCCE1" alt="Sharunethra's GitHub Stats" />
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://github.com/Sharunethra">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sharunethra&layout=compact&title_color=2D3748&text_color=4A5568&bg_color=F2F1ED&border_color=C6E2E7" alt="Top Languages" />
        </a>
      </td>
    </tr>
  </table>
</div>

<div align="center">
  <img src="assets/divider.svg" alt="Pastel Divider" width="100%" />
</div>

## 📬 Contact & Collaboration

I am always interested in discussing technical research, trustworthy AI, backend system architecture, and impactful engineering opportunities. Feel free to connect:

- 🐙 **GitHub:** [@Sharunethra](https://github.com/Sharunethra)
- 💼 **LinkedIn:** [sharu-nethra-r-18a48b346](https://www.linkedin.com/in/sharu-nethra-r-18a48b346/)
- ✉️ **Email:** [sharunethra18@gmail.com](mailto:sharunethra18@gmail.com)

---

<div align="center">
  <p style="color: #64748B; font-size: 12px;">
    Crafted with care using a custom pastel aesthetic • © 2026 Sharu Nethra R
  </p>
</div>
