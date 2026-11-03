<!-- Profile README for github.com/riyazbiju/riyazbiju
     TODO before publishing: replace every "REPO_LINK" with the real repo URL. -->

<div align="center">

<img src="assets/banner.svg" width="100%" alt="Riya Biju, Agentic AI and ML Engineer, Munich"/>


![Status](https://img.shields.io/badge/Available-Dec%202026-2EA44F?style=flat-square)
![Roles](https://img.shields.io/badge/Open%20to-Full--time%20AI%20Engineer%20roles-1E90FF?style=flat-square)
![Location](https://img.shields.io/badge/Based%20in-Germany%20%C2%B7%20Open%20to%20Europe-lightgrey?style=flat-square)

[![Portfolio](https://img.shields.io/badge/Portfolio-riyazbiju.github.io-0B3D91?style=for-the-badge&logo=googlechrome&logoColor=white)](https://riyazbiju.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-riya--biju-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/riya-biju)
[![Email](https://img.shields.io/badge/Email-bijuriya18@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bijuriya18@gmail.com)

</div>

---

## ▶️ Watch my 24-second intro

<div align="center">

<a href="assets/intro.mp4"><img src="assets/intro.gif" width="720" alt="Animated intro: who I am, what I build, results, flagship projects CAIRA and SKYBRIEF"/></a>

<sub>Click the video to open the full-quality MP4.</sub>

</div>

---

## 🧭 Quick read

<table>
<tr>
<td width="33%" valign="top">

### 📍 Now
Building AI at **BMW Group, Munich**. Multi-agent systems on a Neo4j knowledge graph for quality investigations. My Master Thesis is there too, on knowledge graphs and link prediction.

</td>
<td width="33%" valign="top">

### 🛠️ I do
Agents, GraphRAG, local LLMs and the full stack around them: data pipelines, APIs and the interface people actually use.

</td>
<td width="33%" valign="top">

### 🎯 Looking for
Full-time **AI Engineer** roles in Germany and across Europe. Available from **Dec 2026**.

</td>
</tr>
</table>

---

## 🛤️ My path

```mermaid
flowchart LR
    A["2023<br/>ML Intern<br/>Acmegrade / IIT Mumbai"] --> B["2024<br/>AI Associate<br/>Angloverse"]
    B --> C["2025<br/>Student Assistant<br/>Center for AI & Robotics"]
    C --> D["2026<br/>AI Engineer<br/>BMW Group"]
```

<details>
<summary><b>What I did at each step</b></summary>

<br>

| Role | What I did |
|:--|:--|
| **BMW Group** · 2026 → now | Built a multi-agent system on a Neo4j knowledge graph that finds root causes for quality issues |
| **Center for AI & Robotics** · 2025–26 | Built CAIRA, a local RAG assistant that answers in German and English |
| **Angloverse** · 2024–25 | Built the NLP pipeline behind an IELTS training platform, and grew international enrollment by 75% |
| **Acmegrade / IIT Mumbai** · 2023–24 | Built ML models and Power BI dashboards |

</details>

---

## 📊 Proof, in numbers

<table>
<tr>
<td align="center" width="20%"><h3>1.5B → 1.6M</h3><sub>records narrowed for real-time use at BMW</sub></td>
<td align="center" width="20%"><h3>~1 day → minutes</h3><sub>to assign a root cause</sub></td>
<td align="center" width="20%"><h3>−60%</h3><sub>CAIRA response time</sub></td>
<td align="center" width="20%"><h3>&gt;50%</h3><sub>lower SKYBRIEF prediction error</sub></td>
<td align="center" width="20%"><h3>3× smaller</h3><sub>edge model, accuracy 94.6% → 96.7%</sub></td>
</tr>
</table>

---

## 🚀 Flagship projects, side by side

<table>
<tr>
<td width="50%" valign="top">

### 🎙️ CAIRA
**A local voice and text assistant for university students**

Runs fully on local NVIDIA servers. Answers in German and English over 70+ documents.

• Sub-second retrieval, 60% faster responses<br>
• Query expansion for vague, multi-part questions<br>
• Session memory across a whole conversation

`FastAPI` `Gradio` `FAISS` `multilingual-e5-small` `Qwen2.5`

🔗 [Repo](REPO_LINK)

</td>
<td width="50%" valign="top">

### ✈️ SKYBRIEF
**Weather briefings for pilots**

A Latent ODE model that forecasts temperature, wind and visibility across location, altitude and time. I led a team of three and built the full stack.

• Error cut by more than half against two standard methods<br>
• 60–67% better on a real flight route<br>
• 231 airports in Canada, data up to 38,000 ft

`PyTorch` `Latent ODE` `Python` `React`

🔗 [Repo](REPO_LINK)

</td>
</tr>
</table>

<details>
<summary><b>🔍 See how each one works</b></summary>

<br>

**CAIRA**

```mermaid
flowchart LR
    A["Voice or text question<br/>German / English"] --> B["Query expansion"]
    B --> C["FAISS semantic search<br/>70+ documents"]
    C --> D["Local Qwen2.5<br/>1.5B to 7B"]
    D --> E["Answer"]
```

**SKYBRIEF**

```mermaid
flowchart LR
    A["Airport weather<br/>231 airports, Canada"] --> C["Latent ODE model"]
    B["Atmospheric data<br/>up to 38,000 ft"] --> C
    C --> D["Continuous forecast<br/>location, altitude, time"]
    D --> E["React briefing app<br/>for pilots"]
```

</details>

---

## 🧩 More things I've built

<details>
<summary><b>Show all 5 projects</b></summary>

<br>

| Project | What I built | Stack |
|:--|:--|:--|
| **[Edge AI PPE Detection](REPO_LINK)** | Pruned a MobileNet by ~69% (8.63 MB → 2.77 MB). Accuracy went up, and speed on a Raspberry Pi stayed the same. | `PyTorch` `MobileNet` `Raspberry Pi` |
| **[Explainable Pneumonia Detection](REPO_LINK)** | ResNet-18 on chest X-rays, with Grad-CAM and LIME to show where the model looks. | `PyTorch` `Grad-CAM` `LIME` |
| **[SignEase](REPO_LINK)** | Real-time sign language translation for inclusive meetings. Published in IJRAR (2024). | `CNN-LSTM` `MediaPipe` |
| **[β-VAE on CelebA](REPO_LINK)** | Face generation model that separates traits like head pose into adjustable controls. | `PyTorch` `VAE` |
| **[Prakrithi-Identifier](REPO_LINK)** | Ayurvedic constitution prediction, extended to skin disease detection with a camera. | `scikit-learn` `Computer Vision` |

</details>

---

## 🧰 Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=py,pytorch,fastapi,docker,aws,react,ts,neo4j,git,github&perline=10" alt="Tech stack icons"/>

</div>

<table>
<tr>
<td valign="top" width="50%">

**🤖 Agents and LLMs**<br>
LangChain · LangGraph · GraphRAG · Qwen · Llama · tool and skill interfaces

**🔎 Retrieval**<br>
FAISS · vector databases · semantic search · multi-hop reasoning

**🕸️ Graphs**<br>
Neo4j · Cypher · graph projections · TransE · ComplEx · R-GCN

</td>
<td valign="top" width="50%">

**⚙️ Backend and data**<br>
FastAPI · REST APIs · SQL · Oracle · Palantir Foundry · Docker · CI/CD

**📊 Dashboards**<br>
Power BI

**🌍 Languages**<br>
English (C1) · German (B1) · Malayalam · Tamil · Hindi

</td>
</tr>
</table>

---

## 🏆 Recognition

- 🥇 Finalist, **Medha V** Global AI Data Viz Hackathon (BMW Techworks India)
- 📄 **IJRAR 2024**, two papers: Ayurveda + AI survey (IIT Palakkad innovation finalist) and SignEase
- 🥈 **2nd Best Paper**, National Conference on Emerging Frontiers of Medicine and Technology
- 🎓 **Best Outgoing Student Award**, Holy Grace Academy of Engineering (2024)

---

## 📈 GitHub activity

<div align="center">

[![Riya's GitHub stats](https://github-readme-stats.vercel.app/api?username=riyazbiju&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117)](https://github.com/riyazbiju)
[![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=riyazbiju&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117)](https://github.com/riyazbiju?tab=repositories)

</div>

---

## 💬 Let's talk

<table>
<tr>
<td width="50%" valign="top">

**Ask me about**<br>
• Multi-agent systems and GraphRAG<br>
• Running LLMs locally<br>
• Getting AI into real workflows

</td>
<td width="50%" valign="top">

**Happy to collaborate on**<br>
• Agent tooling<br>
• Knowledge graphs<br>
• AI for healthcare and accessibility

</td>
</tr>
</table>

<div align="center">

[![Say hello](https://img.shields.io/badge/Say%20hello-bijuriya18%40gmail.com-1E90FF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bijuriya18@gmail.com?subject=Hello%20Riya)
[![Connect on LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/riya-biju)
[![Open the portfolio](https://img.shields.io/badge/See%20more-Portfolio-0B3D91?style=for-the-badge&logo=googlechrome&logoColor=white)](https://riyazbiju.github.io)

> 🤖🤝👤 Still deciding whether to trust AI or humans, so I build AI that shows its work.


</div>
