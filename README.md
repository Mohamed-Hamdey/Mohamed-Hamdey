<div align="center">

<img src="assets/hero.svg" width="100%" alt="Mohamed Hamdy — I teach machines to see and to answer"/>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Mohamed-Hamdey&label=PROFILE+VIEWS&color=0F5132&style=for-the-badge)
![Followers](https://img.shields.io/github/followers/Mohamed-Hamdey?label=FOLLOWERS&style=for-the-badge&logo=github&color=B37800)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-hamdy-728757282/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamed.hamdey.hafez@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/)

</div>

<img src="assets/divider.svg" width="100%" alt=""/>

## 🧠 `> whoami`

<table>
<tr>
<td width="38%" valign="middle" align="center">

<a href="https://Mohamed-Hamdey.github.io/portfolio/">
  <img src="assets/asciify.gif" width="100%" alt="Portrait of Mohamed Hamdy rendered in ASCII"/>
</a>

</td>
<td width="62%" valign="top">

```python
class MohamedHamdy:
    def __init__(self):
        self.role      = "AI / Computer Vision Engineer"
        self.education = "B.Sc. CS, Minia University (2026), GPA 3.6/4.0"
        self.focus     = ["Computer Vision", "NLP", "RAG", "OCR"]
        self.based_in  = "Cairo, Egypt 🇪🇬"
        self.origin    = "National-level Kung Fu athlete (2021) 🥋"
        self.open_to   = ["ML / CV / Applied AI roles",
                          "Research internships", "Collaborations"]

    def forward(self, curiosity):
        return "ship it" if curiosity > 0 else None

    def philosophy(self):
        return "Train hard. Measure everything. Iterate."
```

</td>
</tr>
</table>

I build **AI systems that work in the real world**: a YOLOv11 vehicle detector serving a university of 15,000+ people, a real-time sign-language-to-speech system, and a bilingual RAG chatbot grounded in live real-estate data. Before code, there was the mat: years of competitive Kung Fu taught me the discipline, patience, and resilience I now bring to every training run.

<img src="assets/divider.svg" width="100%" alt=""/>

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

[![Live Demo](https://img.shields.io/badge/LIVE_DEMO-0F5132?style=for-the-badge&logo=render&logoColor=black)](https://darglobal-rag.onrender.com/)
[![Source Code](https://img.shields.io/badge/SOURCE_CODE-B37800?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mohamed-Hamdey/darglobal-rag)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6467F2?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-0E7C66?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

> ⏳ The demo runs on a free host, so the first load can take a moment to wake up.

</td>
</tr>
</table>

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#0b1620','primaryBorderColor':'#39FF88','primaryTextColor':'#C9F7E2','lineColor':'#FFB000','secondaryColor':'#0b1620','tertiaryColor':'#050a0f'}}}%%
flowchart LR
    A[🕷️ Scrape<br/>DarGlobal + Wasalt] --> B[🧹 Clean &<br/>Chunk]
    B --> C[(🗂️ Index)]
    D[💬 User question<br/>EN / AR] --> E[🔎 Retrieve<br/>top matches]
    C --> E
    E --> F[🤖 LLM via<br/>OpenRouter]
    F --> G[✅ Grounded<br/>answer]
```

<img src="assets/divider.svg" width="100%" alt=""/>

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

![YOLOv11](https://img.shields.io/badge/YOLOv11-0F5132?style=flat-square&logoColor=black)
![OCR](https://img.shields.io/badge/OCR-B37800?style=flat-square)
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

<img src="assets/divider.svg" width="100%" alt=""/>

## 🛠️ `> tech_stack`

<div align="center">

**🧠 AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLOv11](https://img.shields.io/badge/YOLOv11-0F5132?style=for-the-badge&logoColor=black)
![NLP](https://img.shields.io/badge/NLP-B37800?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-0E7C66?style=for-the-badge)
![OCR](https://img.shields.io/badge/OCR-C2410C?style=for-the-badge)

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

<img src="assets/divider.svg" width="100%" alt=""/>

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

<img src="assets/divider.svg" width="100%" alt=""/>

## 🥋 `> mat_to_model`

| On the mat 🥋 | In the lab 🧠 |
|:---|:---|
| Thousands of repetitions to perfect one form | Thousands of epochs to perfect one model |
| Read your opponent in real time | Detect and recognize in real time |
| Fall seven times, stand up eight | Debug, retrain, ship |
| Respect the fundamentals | Master the math before the framework |

<img src="assets/divider.svg" width="100%" alt=""/>

## 📊 `> metrics`

<div align="center">

<img height="170" src="https://github-readme-stats-salesp07.vercel.app/api?username=Mohamed-Hamdey&count_private=true&show_icons=true&bg_color=050a0f&text_color=C9F7E2&border_color=14352a&rank_icon=github&border_radius=10&title_color=39FF88&icon_color=39FF88" alt="stats"/>
<img height="170" src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=Mohamed-Hamdey&hide=HTML&langs_count=8&layout=compact&bg_color=050a0f&text_color=C9F7E2&border_color=14352a&border_radius=10&title_color=39FF88&size_weight=0.5&count_weight=0.5" alt="top languages"/>

<br/>

<img src="https://github-readme-streak-stats-salesp07.vercel.app/?user=Mohamed-Hamdey&count_private=true&background=050a0f&stroke=14352a&ring=FFB000&fire=39FF88&currStreakNum=C9F7E2&sideNums=C9F7E2&currStreakLabel=FFB000&sideLabels=39FF88&dates=6B8F83&border_radius=10" alt="streak"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=Mohamed-Hamdey&theme=matrix&no-frame=true&row=1&column=7" alt="trophies"/>

</div>

<img src="assets/divider.svg" width="100%" alt=""/>

## 🐍 `> contribution_grid`

<div align="center">

<!-- Needs the snake GitHub Action (snake.yml). Delete this block if you skip it. -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Mohamed-Hamdey/Mohamed-Hamdey/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mohamed-Hamdey/Mohamed-Hamdey/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Mohamed-Hamdey/Mohamed-Hamdey/output/github-snake.svg" />
</picture>

</div>

<img src="assets/divider.svg" width="100%" alt=""/>

## 🎯 `> status: in_progress`

```diff
+ 🔭 Sharpening computer vision, RAG and real-time recognition systems
+ 📚 Deepening NLP after the DeepLearning.AI specialization
+ 🤝 Open to collaborations on assistive-tech and applied-AI projects
+ 💬 Ask me about: YOLO · OCR pipelines · RAG chatbots · teaching programming
+ ⚡ Fun fact: 500+ students taught, and a national stage fought on
```

<img src="assets/divider.svg" width="100%" alt=""/>

<div align="center">

[![Email](https://img.shields.io/badge/mohamed.hamdey.hafez%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamed.hamdey.hafez@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-hamdy-728757282/)

<img src="assets/footer.svg" width="100%" alt="git commit -m let's build something that matters — open to ML, CV and Applied-AI roles"/>

</div>
