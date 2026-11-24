<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=240&section=header&text=Mohamed%20Hamdy&fontSize=62&fontColor=00F5FF&animation=fadeIn&fontAlignY=34&desc=AI%20%C2%B7%20Computer%20Vision%20%C2%B7%20RAG%20Engineer&descSize=20&descAlignY=56&descColor=B8B8FF" width="100%" alt="header"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=900&color=00F5FF&center=true&vCenter=true&width=760&lines=Teaching+machines+to+see+%F0%9F%91%81%EF%B8%8F;YOLOv11+%C2%B7+OCR+%C2%B7+Real-Time+Recognition;RAG+chatbots+grounded+in+real+data+%F0%9F%A4%96;Building+AI+that+makes+the+world+more+accessible+%E2%99%BF;Discipline+from+the+mat.+Precision+from+the+model.+%F0%9F%A5%8B" alt="Typing SVG" />
</a>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Mohamed-Hamdey&label=PROFILE+VIEWS&color=00F5FF&style=for-the-badge)
![Followers](https://img.shields.io/github/followers/Mohamed-Hamdey?label=FOLLOWERS&style=for-the-badge&logo=github&color=7B2FF7)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-hamdy-728757282/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamed.hamdey.hafez@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/)

</div>

---

<div align="center">

```text
 INPUT          HIDDEN          HIDDEN          OUTPUT

  (●)───┐        (●)───┐        (●)───┐
  (●)───┼──────→ (●)───┼──────→ (●)───┼──────→  [ PREDICTION ]
  (●)───┘        (●)───┘        (●)───┘
```

</div>

---

## 🧠 `> whoami`

```python
class MohamedHamdy:
    def __init__(self):
        self.role       = "AI / Computer Vision Engineer"
        self.education  = "B.Sc. Computer Science, Minia University (2026), GPA 3.6/4.0"
        self.focus      = ["Computer Vision", "NLP", "RAG Systems", "OCR"]
        self.based_in   = "Cairo, Egypt 🇪🇬"
        self.background = "National-level Kung Fu athlete (Egypt, 2021) 🥋"
        self.military   = "Exempted"
        self.mission    = "Ship AI that is accurate, real-time, and genuinely useful"
        self.open_to    = ["ML / CV / Applied AI roles", "Research internships", "Collaborations"]

    def forward(self, curiosity):
        return self.mission if curiosity > 0 else None

    def philosophy(self):
        return "Train hard. Measure everything. Never stop iterating."
```

I build **AI systems that work in the real world**: a YOLOv11 vehicle detector serving a university of 15,000+ people, a real-time sign-language-to-speech system, and a bilingual RAG chatbot grounded in live real-estate data. Before code, there was the mat: years of competitive Kung Fu taught me the discipline, patience, and resilience I now bring to every training run.

---

## ⭐ `> latest_build`

<table>
<tr>
<td valign="top">

### 🏙️ DarGlobal · Wasalt RAG Assistant
**Bilingual (EN / AR) retrieval-augmented chatbot over real-estate data**

A full pipeline built end to end by one person on a free-tier budget: scrape public data from **DarGlobal** and **Wasalt**, index it, and answer questions grounded in what was actually scraped.

- 🕷️ **Ingestion:** Playwright-based scraping of DarGlobal pages and Wasalt listings
- 🔎 **Retrieval:** plain-Python RAG pipeline (no LangChain / LlamaIndex)
- 🤖 **Generation:** free OpenRouter model behind a **FastAPI** backend
- 🌍 **Bilingual:** English and Arabic support
- 🐳 **Shipped:** containerised with **Docker** and deployed with a live demo
- 🎨 **UI:** custom chat interface designed to match the DarGlobal website's look and feel

[![Live Demo](https://img.shields.io/badge/LIVE_DEMO-00F5FF?style=for-the-badge&logo=render&logoColor=black)](https://darglobal-rag.onrender.com/)
[![Source Code](https://img.shields.io/badge/SOURCE_CODE-7B2FF7?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mohamed-Hamdey/darglobal-rag)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6467F2?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-FF1493?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

> ⏳ The demo runs on a free host, so the first load can take a moment to wake up.

</td>
</tr>
</table>

```mermaid
flowchart LR
    A[🕷️ Scrape<br/>DarGlobal + Wasalt] --> B[🧹 Clean &<br/>Chunk]
    B --> C[(🗂️ Index)]
    D[💬 User question<br/>EN / AR] --> E[🔎 Retrieve<br/>top matches]
    C --> E
    E --> F[🤖 LLM via<br/>OpenRouter]
    F --> G[✅ Grounded<br/>answer]
```

---

## 🚀 `> featured_projects`

<table>
<tr>
<td width="50%" valign="top">

### 🚌 UniMove
**Smart Transportation · Graduation Project**

AI module for Minia University's transportation system, serving **15,000+ students & staff**.

- 🎯 **YOLOv11** vehicle detection → **94% mAP**
- 🔢 **OCR pipeline** for mileage extraction → **98% accuracy**
- 🗂️ **5,000+** images annotated with CVAT & Roboflow

![YOLOv11](https://img.shields.io/badge/YOLOv11-00F5FF?style=flat-square&logoColor=black)
![OCR](https://img.shields.io/badge/OCR-8A2BE2?style=flat-square)
![Roboflow](https://img.shields.io/badge/Roboflow-6706CE?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
<td width="50%" valign="top">

### 🤟 SignVision
**Real-Time Sign Language → Speech**

Webcam-based gesture recognition that speaks for the user.

- ⚡ Real-time inference with **TensorFlow + OpenCV**
- 🎯 **96% accuracy** across **15 gestures**
- 🔊 Speech-synthesis APIs for instant audio output

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Accessibility](https://img.shields.io/badge/Accessibility-%E2%99%BF-2ea44f?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 👓 EchoLens
**Smart Glasses for the Hearing Impaired**

Assistive glasses that convert real-time environmental audio into **visual alerts**.

- 🎧 Python-based audio signal processing
- 👁️ Visual alerts for sounds around the user
- ♿ Built for accessibility and independence

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Audio DSP](https://img.shields.io/badge/Audio_DSP-FF4B4B?style=flat-square)

</td>
<td width="50%" valign="top">

### 🛡️ Barq Systems · Network Anomaly Detector
**Prototype ML model for network traffic**

Built during my network internship.

- 🌐 Analysed **10+ routing and switching protocols**
- 🧪 Python + scikit-learn anomaly detection

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
</table>

> 🔎 More on my [repositories page](https://github.com/Mohamed-Hamdey?tab=repositories).

---

## 🛠️ `> tech_stack`

<div align="center">

**🧠 AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLOv11](https://img.shields.io/badge/YOLOv11-00F5FF?style=for-the-badge&logoColor=black)
![NLP](https://img.shields.io/badge/NLP-8A2BE2?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-FF1493?style=for-the-badge)
![OCR](https://img.shields.io/badge/OCR-C71585?style=for-the-badge)

**💻 Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**🌐 Backend, Data & Cloud**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)

</div>

---

## 🧭 `> training_log`

```text
2021  🥋 National-level Kung Fu athlete (Egypt)
2023  🎓 Intro to AI & Applications, Zewail City of Science and Technology
2023  💼 IT Intern @ DP World, Sokhna: 20+ bugs fixed, error rates cut by 15%
2024  🌐 Network Intern @ Barq Systems: ML anomaly detector across 10+ protocols
2024  📊 Machine Learning for Data Analysis, NTI
2024  👨‍🏫 Software Instructor @ iSchool DEMI: 500+ students taught
2025  🧠 Deep Learning Specialization, DeepLearning.AI
2026  💬 NLP Specialization, DeepLearning.AI
2026  🎓 B.Sc. Computer Science, Minia University, GPA 3.6 / 4.0
2026  🏙️ Shipped a bilingual RAG chatbot over DarGlobal & Wasalt data
NOW   🚀 Building AI systems & looking for the next big challenge
```

---

## 🥋 `> mat_to_model`

| On the mat 🥋 | In the lab 🧠 |
|:---|:---|
| Thousands of repetitions to perfect one form | Thousands of epochs to perfect one model |
| Read your opponent in real time | Detect and recognize in real time |
| Fall seven times, stand up eight | Debug, retrain, ship |
| Respect the fundamentals | Master the math before the framework |

---

## 📊 `> metrics`

<div align="center">

<img height="170" src="https://github-readme-stats-salesp07.vercel.app/api?username=Mohamed-Hamdey&count_private=true&show_icons=true&theme=midnight-purple&rank_icon=github&border_radius=10&hide_border=true&title_color=00F5FF&icon_color=00F5FF" alt="stats"/>
<img height="170" src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=Mohamed-Hamdey&hide=HTML&langs_count=8&layout=compact&theme=midnight-purple&border_radius=10&hide_border=true&title_color=00F5FF&size_weight=0.5&count_weight=0.5" alt="top languages"/>

<br/>

<img src="https://github-readme-streak-stats-salesp07.vercel.app/?user=Mohamed-Hamdey&count_private=true&theme=midnight-purple&border_radius=10&hide_border=true&stroke=00F5FF&ring=7B2FF7&fire=00F5FF" alt="streak"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=Mohamed-Hamdey&theme=algolia&no-frame=true&row=1&column=7" alt="trophies"/>

</div>

---

## 🐍 `> contribution_grid`

<div align="center">

<!-- Needs the snake GitHub Action (snake.yml). Delete this block if you skip it. -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Mohamed-Hamdey/Mohamed-Hamdey/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mohamed-Hamdey/Mohamed-Hamdey/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Mohamed-Hamdey/Mohamed-Hamdey/output/github-snake.svg" />
</picture>

</div>

---

## 🎯 `> status: in_progress`

```diff
+ 🔭 Sharpening computer vision, RAG and real-time recognition systems
+ 📚 Deepening NLP after the DeepLearning.AI specialization
+ 🤝 Open to collaborations on assistive-tech and applied-AI projects
+ 💬 Ask me about: YOLO · OCR pipelines · RAG chatbots · teaching programming
+ ⚡ Fun fact: 500+ students taught, and a national stage fought on
```

---

<div align="center">

### 📫 `> connect.init()`

[![Email](https://img.shields.io/badge/mohamed.hamdey.hafez%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamed.hamdey.hafez@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-hamdy-728757282/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=130&section=footer&text=Thanks%20for%20stopping%20by&fontSize=20&fontColor=00F5FF&animation=fadeIn" width="100%" alt="footer"/>

</div>
