<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0F6E56,50:0A4F8A,100:185FA5&height=200&text=Vishnu%20Surya%20Teja&fontSize=52&fontColor=FFFFFF&fontAlignY=42&desc=AI%2FML%20Engineer%20%C2%B7%20LLM%20Systems%20%C2%B7%20Agentic%20Pipelines&descSize=17&descAlignY=62&animation=fadeIn" width="100%" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1200&color=0F6E56&center=true&vCenter=true&random=false&width=720&lines=I+build+LLM+systems+that+work+in+production%2C+not+just+demos;The+model+is+the+least+important+variable+%E2%80%94+retrieval+is+everything;Agentic+AI+%7C+RAG+Pipelines+%7C+Full-Stack+AI+Integration;The+gap+between+research+and+production%3F+That%27s+home." alt="Typing SVG" />

<br/><br/>

<a href="https://linkedin.com/in/vishnu-surya-teja-veeraganti-1b172827a">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>&nbsp;
<a href="mailto:vishnusuryatejavst@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>&nbsp;
<a href="https://github.com/VishnuSuryaTejaa">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=VishnuSuryaTejaa&label=Profile+Views&color=0F6E56&style=flat-square" />
<img src="https://img.shields.io/github/followers/VishnuSuryaTejaa?label=Followers&style=flat-square&color=185FA5&labelColor=0D1117" />

<br/><br/>

<img src="https://img.shields.io/badge/Apps_Shipped-6%2B-0F6E56?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Search_Effort_Cut-70%25-185FA5?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/ML_Detection_Accuracy-87%25-0F6E56?style=for-the-badge&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Features_Engineered-22%2B-185FA5?style=for-the-badge&labelColor=0D1117" />

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%"/>

## 🧠 Who I Am

I'm an AI/ML Engineer who works at the gap between what foundation models can do in research and what actually holds up when deployed in the real world. I don't build demos. I build systems. Every project I ship goes from first principles through to production: LLM orchestration, retrieval architecture, full-stack integration, live deployment.

> **Current focus:** Vorkos — an agentic job aggregator where RAG scores listings against your actual resume profile, not keywords. Cut daily job-search effort by ~70%. The insight that made it work: the model was never the bottleneck. Retrieval was.

<details>
<summary><b>📖 My engineering beliefs (expand)</b></summary>
<br/>

- **The model is commodity. The surrounding system is the moat.** Retrieval strategy, chunking design, and what you compare against determine 80% of RAG quality. Liu et al. (2023) proved it in research. I proved it building Vorkos.
- **Debug retrieval before touching the LLM.** Most AI failures in production are retrieval failures wearing an LLM mask. The model sounds confident either way.
- **Build from first principles when no template applies.** Niche datasets don't exist? Build the pipeline. Standard features aren't enough? Engineer new ones. That's not heroics — that's the job.
- **Wrappers ship. Agents adapt.** An agent that can't influence its own execution path is a pipeline with better marketing.

</details>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%"/>

## ⚙️ What I Ship

<br/>

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [Vorkos](https://github.com/VishnuSuryaTejaa/vorkos) — Agentic Job Aggregator

Built because manually searching, filtering, and matching job postings consumed hours daily. Full discovery-to-ranking pipeline that automates everything up to the apply step.

**Key insight:** Scoring against the actual resume profile (not a search query) is what made it work. The model understood *fit*, not just overlap.

<img src="https://img.shields.io/badge/RAG-ChromaDB-0F6E56?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Groq-API-F55036?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Tavily-Scraping-185FA5?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Flask-React-61DAFB?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&labelColor=0D1117" />

**📈 ~70% reduction in daily job-search effort**

</td>
<td width="50%" valign="top">

### 🔬 [Data Vacuum](https://github.com/VishnuSuryaTejaa/data-vacuum) — Custom Dataset Pipeline

Built to solve a real ML bottleneck: niche training datasets simply don't exist. Automated pipeline to collect and validate custom training data from scratch — no manual curation.

**Architecture:** Groq generates prompts → Tavily scrapes → NLP cleaning layer → ML relevance gate. Only high-quality, on-topic data enters.

<img src="https://img.shields.io/badge/Groq-Prompt_Gen-F55036?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/spaCy-NLTK-09A3D5?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Scikit--Learn-Relevance_Gate-F7931E?style=flat-square&labelColor=0D1117" />

**📈 End-to-end automated · Zero manual curation**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [Phishing Detector](https://github.com/VishnuSuryaTejaa/phishing-detector) — Dual-Vector Classifier

Two attack vectors, one system: URL-based phishing detector and email content classifier — built during a hackathon, deployed live via React frontend.

**22+ engineered features:** lexical patterns, domain age, redirect behaviour, special character ratios — structural signatures of malicious links, not blacklists.

<img src="https://img.shields.io/badge/Scikit--Learn-87%25_Acc-F7931E?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Flask-REST_API-000000?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/React-Frontend-61DAFB?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/NLP-22%2B_Features-185FA5?style=flat-square&labelColor=0D1117" />

**📈 87% accuracy · Real-time detection**

</td>
<td width="50%" valign="top">

### 💼 Production AI @ Mallurus Industry

10 months, fully remote. Shipped 6+ production web applications. Deployed a Groq-powered AI chatbot onto a live client site — converted a static page into an interactive experience with measurably better engagement.

Consistent delivery: UI/UX design through backend logic through AI integration through deployment.

<img src="https://img.shields.io/badge/6%2B-Apps_Shipped-0F6E56?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Groq-Chatbot_Deployed-F55036?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Nov_2024-Sep_2025-185FA5?style=flat-square&labelColor=0D1117" />

**📈 Faster load times · Improved visitor engagement**

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%"/>

## 🛠 Tech Stack

<div align="center">

<table>
<tr>
<td align="center" width="33%">

**🤖 AI · LLM · Agents**

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow" />

<br/><br/>

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
<br/>
<img src="https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square" />
<img src="https://img.shields.io/badge/Groq_API-F55036?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/RAG_Pipelines-0F6E56?style=flat-square" />
<img src="https://img.shields.io/badge/Prompt_Engineering-185FA5?style=flat-square" />

</td>
<td align="center" width="33%">

**🌐 Full-Stack · Infra**

<img src="https://skillicons.dev/icons?i=react,flask,docker,aws,git" />

<br/><br/>

<img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/AWS_S3-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/DVC-945DD6?style=flat-square&logo=dvc&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />

</td>
<td align="center" width="33%">

**🔬 Data · NLP · Security**

<img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square" />
<img src="https://img.shields.io/badge/NLTK-154F3C?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Gensim-0096D6?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/BeautifulSoup-3776AB?style=flat-square" />
<img src="https://img.shields.io/badge/Tavily-Scraping-0F6E56?style=flat-square" />
<br/><br/>
<img src="https://img.shields.io/badge/OWASP_Top_10-000?style=flat-square" />
<img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/Nmap-0E83CD?style=flat-square" />
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white" />

</td>
</tr>
</table>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%"/>

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=VishnuSuryaTejaa&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=0F6E56&icon_color=185FA5&text_color=FFFFFF" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=VishnuSuryaTejaa&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=0F6E56&text_color=FFFFFF" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=VishnuSuryaTejaa&theme=tokyonight&hide_border=true&background=0D1117&stroke=0F6E56&ring=0F6E56&fire=185FA5&currStreakLabel=FFFFFF&sideLabels=FFFFFF&dates=888888" width="68%" />

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%"/>

## 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=VishnuSuryaTejaa&theme=tokyo-night&bg_color=0D1117&color=0F6E56&line=185FA5&point=FFFFFF&area=true&hide_border=true" width="100%" />

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%"/>

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VishnuSuryaTejaa/VishnuSuryaTejaa/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/VishnuSuryaTejaa/VishnuSuryaTejaa/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/VishnuSuryaTejaa/VishnuSuryaTejaa/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%"/>

## 💼 Timeline

<br/>

<table>
<tr>
<td width="16%" align="center" valign="top"><br/><b>Nov 2024</b><br/>↕<br/><b>Sep 2025</b></td>
<td width="84%" valign="top">

#### 🏢 Full-Stack AI Developer · Mallurus Industry Pvt Ltd `Remote`
Shipped 6+ production web applications — SPAs, e-commerce platforms, AI-integrated experiences. Deployed a Groq-powered chatbot to a live client site. Delivered consistently end-to-end: UI/UX design through backend through AI integration through deployment.

`React` `Flask` `Groq API` `Docker` `AWS` `PostgreSQL`

</td>
</tr>
<tr><td colspan="2"><br/></td></tr>
<tr>
<td align="center" valign="top"><br/><b>Jan 2025</b><br/>↕<br/><b>Feb 2025</b></td>
<td valign="top">

#### 🔐 Cybersecurity Intern · The Red Users `Remote`
Penetration testing and vulnerability assessments using OWASP Top 10 standards. Automated threat-scanning workflows with Python scripts. Documented vulnerabilities with full reproduction steps and remediation paths.

`Burp Suite` `Nmap` `Wireshark` `Python` `OWASP Top 10`

</td>
</tr>
<tr><td colspan="2"><br/></td></tr>
<tr>
<td align="center" valign="top"><br/><b>2023</b><br/>↕<br/><b>2027</b></td>
<td valign="top">

#### 🎓 B.Tech Computing & Data Science (AIML) · SAI University, Chennai

`Machine Learning` `Deep Learning` `NLP` `Reinforcement Learning` `MLOps` `Data Structures & Algorithms` `Cryptography`

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%"/>

## 🤝 Let's Build Something Worth Deploying

<div align="center">

<br/>

I'm looking for a role where **uniqueness is an advantage, not a liability** — where I can build AI systems that actually ship, solve real problems, and hold up when it counts.

If you're working at the intersection of LLMs, agentic systems, or production ML — let's talk.

<br/>

<a href="mailto:vishnusuryatejavst@gmail.com">
  <img src="https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>&nbsp;
<a href="https://linkedin.com/in/vishnu-surya-teja-veeraganti-1b172827a">
  <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:185FA5,50:0A4F8A,100:0F6E56&height=130&section=footer&animation=fadeIn" width="100%" />

*"Build from first principles. Ship what works. Own the gap."*

</div>
