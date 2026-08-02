<h1 align="center">Hi, I'm Manoj Kumar 👋</h1>

<p align="center">
  <b>AI Engineer</b> &nbsp;·&nbsp; I build agentic systems that ship &nbsp;·&nbsp; Bangalore, India
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/manojkumar21k/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://medium.com/@manojkotary"><img src="https://img.shields.io/badge/Medium-12100E?style=flat&logo=medium&logoColor=white" alt="Medium"/></a>
  <a href="https://huggingface.co/Manoj21k"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black" alt="Hugging Face"/></a>
  <a href="mailto:manojkotary@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=Manoj21k&style=flat&color=blue" alt="Profile views"/>
</p>

---

### About

I'm an AI Engineer at **[The Math Company (MathCo)](https://themathcompany.com/)**, where I build production GenAI systems and multi-agent applications — designing LLM-powered agents, evaluating and observing them, and shipping the surrounding APIs and UIs.

- 🤖 Deep in **agentic AI architectures** — multi-agent orchestration, tool-use, MCP, and evaluation
- 🔬 Care a lot about the unglamorous parts: **evals, observability, and reliability** of LLM systems
- ✍️ I write about AI engineering on [Medium](https://medium.com/@manojkotary)
- 📫 Reach me at **manojkotary@gmail.com**

---

### 🔭 Building now

- **[agentic-code-review](https://github.com/Manoj21k/agentic-code-review)** — a multi-agent code review plugin for Claude Code: parallel specialized reviewers (bugs, security, git history, test coverage), confidence scoring, and inline GitHub PR comments
- **[kisan-mitra-voice-agent](https://github.com/Manoj21k/kisan-mitra-voice-agent)** — a multilingual voice assistant for Indian farmers, end-to-end on the Sarvam AI stack (STT → tool-calling LLM → TTS) with an MCP server and eval harness
- **[loop-engineering](https://github.com/Manoj21k/loop-engineering)** — notes and code on making agents *reliable*: getting there takes more than a good model — it takes a carefully designed harness of loops

---

### 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Manoj21k/agentic-code-review">🔎 Agentic Code Review</a></h4>
      <p>A Claude Code plugin that reviews pull requests with a fleet of parallel specialized agents — bug hunting, security, CLAUDE.md compliance, git history, and test coverage. Findings are confidence-scored to filter noise, then reported in the terminal or as inline GitHub PR comments.</p>
      <p><sub><b>Stack:</b> Claude Code · Multi-agent · GitHub API · JavaScript</sub></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Manoj21k/kisan-mitra-voice-agent">🌾 Kisan Mitra — Voice Agent for Farmers</a></h4>
      <p>A multilingual voice assistant for Indian farmers, built end-to-end on Sarvam AI: Saaras STT, Sarvam-30B with tool-calling, and Bulbul TTS. Ships with an MCP server for agricultural tools and an eval harness to keep answers grounded.</p>
      <p><sub><b>Stack:</b> Python · Sarvam AI · MCP · Evals</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Manoj21k/multimodal-deep-researcher">🔍 Multimodal Deep Research Agent</a></h4>
      <p>Multi-agent framework that turns an open-ended research query into a professionally formatted PDF report with embedded data visualizations. 5 specialized agents (Researcher, Planner, Drafter, Coder, Critic), iterative web search across 30+ sources, and an actor–critic loop for chart generation.</p>
      <p><sub><b>Stack:</b> Python · LangGraph · Tavily · Plotly · Streamlit</sub></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Manoj21k/multi-agent-financial-assistant">💰 Multi-Agent Financial Assistant</a></h4>
      <p>Modular multi-agent system for personalized financial guidance. A coordinator routes queries through Triage → Clarification → Advisor → Optimizer agents, each with explainable steps so users see <i>why</i> they got a recommendation.</p>
      <p><sub><b>Stack:</b> Python · LangGraph · OpenAI · FastAPI</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Manoj21k/loop-engineering">🔁 Loop Engineering</a></h4>
      <p>Agents are useful — getting them to work reliably is the hard part. This repo collects patterns and working code for the harness around the model: retry loops, verification loops, actor–critic loops, and the plumbing that turns a demo into a system.</p>
      <p><sub><b>Stack:</b> Python · Agent harness patterns</sub></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Manoj21k/LangGraph_101">📚 LangGraph 101</a></h4>
      <p>A hands-on guide to LangGraph covering sequential, parallel, conditional, and iterative workflows — plus a full-stack chatbot app. The repo I wish I had when I started building agentic systems.</p>
      <p><sub><b>Stack:</b> Python · LangGraph · LangChain</sub></p>
    </td>
  </tr>
</table>

<p><sub><b>More projects:</b>
<a href="https://github.com/Manoj21k/groq-chatbot">groq-chatbot</a> (LLM app with Langfuse observability) ·
<a href="https://github.com/Manoj21k/gpt-oss-streamlit-chat">gpt-oss-local-chat</a> (GPT-OSS on your own hardware via Ollama) ·
<a href="https://github.com/Manoj21k/Collection-of-Practical-AI-Tools">practical-ai-tools</a> (curated AI tools by use case) ·
<a href="https://github.com/Manoj21k/prompting-guides">prompting-guides</a> (prompt engineering guides from major AI labs)
</sub></p>

---

### ✍️ Latest writing

<!-- BLOG-POST-LIST:START -->
- [Stop Asking One LLM to Review Your Code. Here’s the 7-Agent Pipeline That Actually Works](https://ai.plainenglish.io/stop-asking-one-llm-to-review-your-code-heres-the-7-agent-pipeline-that-actually-works-08e795df7669?source=rss-b20a1db53442------2)
- [Google Shrunk LLM Memory by 6× With Zero Accuracy Loss. Here’s How TurboQuant Works.](https://ai.plainenglish.io/google-shrunk-llm-memory-by-6-with-zero-accuracy-loss-heres-how-turboquant-works-8a1233ff56b1?source=rss-b20a1db53442------2)
- [Choosing the Right Chunking Strategy: What Nobody Tells You](https://ai.plainenglish.io/choosing-the-right-chunking-strategy-what-nobody-tells-you-8829e2cb99f8?source=rss-b20a1db53442------2)
- [The Evolution of Intelligence: From Traditional AI to the Dawn of Agentic Systems](https://ai.plainenglish.io/the-evolution-of-intelligence-from-traditional-ai-to-the-dawn-of-agentic-systems-1df5d5a80227?source=rss-b20a1db53442------2)
<!-- BLOG-POST-LIST:END -->

<p><sub>More on <a href="https://medium.com/@manojkotary">Medium →</a></sub></p>

---

### 🛠️ Tech Stack

**LLMs & GenAI Platforms**
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat&logo=anthropic&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=flat)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat&logo=groq&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)

**Agentic Frameworks & Protocols**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google%20ADK-4285F4?style=flat)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-000000?style=flat)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat&logo=claude&logoColor=white)

**Observability, Evals & MLOps**
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat)
![Phoenix](https://img.shields.io/badge/Arize%20Phoenix-7C3AED?style=flat)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Dynatrace](https://img.shields.io/badge/Dynatrace-1496FF?style=flat&logo=dynatrace&logoColor=white)

**Cloud & Infra**
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex%20AI-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat&logo=firebase&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D4?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

**Databases — Vector · Graph · SQL**
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat)
![Chroma](https://img.shields.io/badge/Chroma-FC521F?style=flat)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

**ML / DL / NLP**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

**Languages, Backend & Serving**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**BI & Visualization**
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat)

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.zohan.tech/api?username=Manoj21k&show_icons=true&count_private=true&theme=tokyonight&hide_border=true&include_all_commits=true" height="160" alt="Manoj's GitHub stats"/>
  <img src="https://github-readme-stats.zohan.tech/api/top-langs/?username=Manoj21k&layout=compact&langs_count=8&theme=tokyonight&hide_border=true" height="160" alt="Top languages"/>
</p>

---

<p align="center"><sub>If you're building agentic systems and want to trade notes — my inbox is always open.</sub></p>
