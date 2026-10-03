<!--
  Mohammad Bilal · GitHub portfolio
  Burnt orange #D96B27 · GitHub dark #0D1117 / #161B22
  Upload profile-assets/ beside this file. No custom CSS or animated headings.
-->

<a id="top"></a>

<p align="center">
  <img src="./profile-assets/header.svg" width="100%" alt="Mohammad Bilal · AI/ML and Software Engineer, Doha, Qatar" />
</p>

<p align="center">
  <a href="#featured-work">Selected work</a> &nbsp; / &nbsp;
  <a href="#live-analytics">GitHub activity</a> &nbsp; / &nbsp;
  <a href="#stack">Toolkit</a> &nbsp; / &nbsp;
  <a href="#achievements">Achievements</a> &nbsp; / &nbsp;
  <a href="#connect">Contact</a>
</p>

I build **AI products with a complete software experience**: document assistants you can talk to, computer vision tools for accessible communication, and predictive dashboards that turn data into decisions.

I'm **Mohammad Bilal**, an **AI/ML and Software Engineer** based in **Doha, Qatar**, and a **Computer Science graduate from FAST NUCES**. My work connects models, APIs, databases, and interfaces.

[Portfolio](https://portfolio-beta-gilt-1emaymvhv5.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/mohammad-bilal-64489827b/) · [Email](mailto:bilalnadeema302003@gmail.com)

---

<a id="featured-work"></a>

## Selected work

<p align="center">
  <img src="./profile-assets/workbench.svg" width="100%" alt="Illustrated project overview: an open book for AI Book Assistant, an eye and blink waveform for the Morse detector, and a prediction gauge for customer churn" />
</p>

### AI Book Assistant

Upload PDFs and explore your books through **text and voice conversations**. A RAG-based reading assistant built around a full-stack interface.

**Built with:** Next.js · TypeScript · Vapi AI · Tailwind CSS

[Repository →](https://github.com/Bixal99/AIBookAssistant) &nbsp; [Live assistant →](https://ai-book-assistant-blush.vercel.app/)

<details>
<summary><b>See the document-to-conversation flow</b></summary>

```mermaid
%%{init: {"theme":"base","themeVariables":{"primaryColor":"#161B22","primaryTextColor":"#F0F6FC","primaryBorderColor":"#D96B27","lineColor":"#D96B27","edgeLabelBackground":"#0D1117","fontFamily":"Arial"},"flowchart":{"htmlLabels":false,"curve":"basis"}}}%%
flowchart LR
    PDF[/Uploaded PDF/] --> SEARCH[Retrieve relevant passages]
    SEARCH --> ANSWER[AI conversation]
    ANSWER --> TEXT([Text])
    ANSWER --> VOICE([Voice])
    class PDF,SEARCH,ANSWER panel
    class TEXT,VOICE result
    classDef panel fill:#161B22,stroke:#D96B27,color:#F0F6FC,stroke-width:1px
    classDef result fill:#D96B27,stroke:#D96B27,color:#0D1117,stroke-width:2px
    linkStyle default stroke:#D96B27,stroke-width:2px
```

</details>

### Eye Blink Morse Detector

A **hands-free communication tool** that translates intentional webcam-detected blinks into Morse code and text using facial landmarks and blink timing.

**Built with:** Python · OpenCV · MediaPipe Face Mesh · NumPy

[Repository →](https://github.com/Bixal99/EyeBlinkMorseDetector) &nbsp; [Live demo →](https://eye-blink-morse-detector-4l3hrfxqo-bixal99s-projects.vercel.app/)

<details>
<summary><b>See how a blink becomes a message</b></summary>

```mermaid
%%{init: {"theme":"base","themeVariables":{"primaryColor":"#161B22","primaryTextColor":"#F0F6FC","primaryBorderColor":"#D96B27","lineColor":"#D96B27","edgeLabelBackground":"#0D1117","fontFamily":"Arial"},"flowchart":{"htmlLabels":false,"curve":"basis"}}}%%
flowchart LR
    CAMERA[/Webcam/] --> FACE[Facial landmarks]
    FACE --> DURATION{Blink duration}
    DURATION -->|Short| DOT[Dot]
    DURATION -->|Long| DASH[Dash]
    DOT --> DECODE[Morse decoding]
    DASH --> DECODE
    DECODE --> MESSAGE([Text message])
    class CAMERA,FACE,DURATION,DOT,DASH,DECODE panel
    class MESSAGE result
    classDef panel fill:#161B22,stroke:#D96B27,color:#F0F6FC,stroke-width:1px
    classDef result fill:#D96B27,stroke:#D96B27,color:#0D1117,stroke-width:2px
    linkStyle default stroke:#D96B27,stroke-width:2px
```

</details>

### AI Customer Churn Prediction

An end-to-end telecom churn application combining **XGBoost predictions**, an interactive risk dashboard, and **Gemini-generated retention insights**.

**Built with:** Python · Streamlit · XGBoost · Plotly · Pandas · Gemini

[Repository →](https://github.com/Bixal99/Churn-Prediction) &nbsp; [Live dashboard →](https://churn-prediction-k3yjzaxx2mgel668arspbc.streamlit.app/)

<details>
<summary><b>See the predictive and generative workflow</b></summary>

```mermaid
%%{init: {"theme":"base","themeVariables":{"primaryColor":"#161B22","primaryTextColor":"#F0F6FC","primaryBorderColor":"#D96B27","lineColor":"#D96B27","edgeLabelBackground":"#0D1117","fontFamily":"Arial"},"flowchart":{"htmlLabels":false,"curve":"basis"}}}%%
flowchart LR
    DATA[(Customer features)] --> MODEL[XGBoost model]
    MODEL --> RISK[Churn probability]
    RISK --> DASHBOARD([Risk dashboard])
    RISK --> GEMINI[Gemini]
    GEMINI --> INSIGHTS([Retention insights])
    class DATA,MODEL,RISK,GEMINI panel
    class DASHBOARD,INSIGHTS result
    classDef panel fill:#161B22,stroke:#D96B27,color:#F0F6FC,stroke-width:1px
    classDef result fill:#D96B27,stroke:#D96B27,color:#0D1117,stroke-width:2px
    linkStyle default stroke:#D96B27,stroke-width:2px
```

</details>

### Other builds

- **[ResuMate](https://github.com/Bixal99/Resume-Builder)** · ATS-ready resume builder with neural parsing and AI bullet enhancement.
- **[Study Platform / Interview Help](https://github.com/Bixal99/Interview-Help)** · Student learning platform and software infrastructure. [Demo →](https://interview-help-eight.vercel.app/)
- **[Pentagram Image Diffusion](https://github.com/Bixal99/Pentagram-Image-Diffusion)** · Text-to-image generation from natural language prompts.
- **[Falcon](https://github.com/Bixal99/FALCON)** · Wholesale business books, inventory, customer accounts, and reporting for Doha shops.

<details>
<summary><b>Explore the full project collection</b></summary>

| Project | Repository | Live demo |
| :--- | :--- | :--- |
| Portfolio | [Source](https://github.com/Bixal99/Portfolio) | [Website](https://portfolio-beta-gilt-1emaymvhv5.vercel.app/) |
| RetroVerse | [Source](https://github.com/Bixal99/RetroVerse) | [Demo](https://retroverse-opal.vercel.app/) |
| Ghoomora | [Source](https://github.com/Bixal99/Ghoomora) | [Demo](https://ghoomora.vercel.app/) |
| Scrapper | [Source](https://github.com/Bixal99/Scrapper) | [Demo](https://helpscript.vercel.app/) |
| School Management System | [Source](https://github.com/Bixal99/School-Management-System) | - |
| HMS | [Source](https://github.com/Bixal99/HMS) | - |
| ODOO Guide | [Source](https://github.com/Bixal99/ODOO) | - |
| DailyLeet | [Source](https://github.com/Bixal99/DailyLeet) | - |

</details>

---

<a id="achievements"></a>

## GitHub achievements

<!-- All three earned achievements verified at https://github.com/Bixal99?tab=achievements. -->
<p align="center">
  <a href="https://github.com/Bixal99?achievement=pull-shark&amp;tab=achievements"><img src="https://github.githubassets.com/assets/pull-shark-default-498c279a747d.png" width="110" height="110" alt="Pull Shark achievement" /></a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/Bixal99?achievement=yolo&amp;tab=achievements"><img src="https://github.githubassets.com/assets/yolo-default-be0bbff04951.png" width="110" height="110" alt="YOLO achievement" /></a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/Bixal99?achievement=quickdraw&amp;tab=achievements"><img src="https://github.githubassets.com/assets/quickdraw-default-39c6aec8ff89.png" width="110" height="110" alt="Quickdraw achievement" /></a>
</p>

<p align="center"><b>Pull Shark &nbsp; · &nbsp; YOLO &nbsp; · &nbsp; Quickdraw</b><br/><sub><a href="https://github.com/Bixal99?tab=achievements">View on GitHub ·</a></sub></p>

---

<a id="live-analytics"></a>

## GitHub activity

<!-- Stats and streak are both 495 · 195 SVGs: identical width and aspect ratio. -->
<p align="center">
  <a href="https://github.com/Bixal99"><img width="48%" src="https://github-stats-extended.vercel.app/api?username=Bixal99&amp;show_icons=true&amp;card_width=495&amp;hide_border=false&amp;border_color=30363D&amp;border_radius=8&amp;bg_color=161B22&amp;title_color=D96B27&amp;icon_color=D96B27&amp;text_color=F0F6FC&amp;ring_color=D96B27&amp;include_all_commits=true&amp;disable_animations=true" alt="GitHub statistics for Mohammad Bilal" /></a>
  &nbsp;
  <a href="https://github.com/Bixal99"><img width="48%" src="https://streak-stats.demolab.com/?user=Bixal99&amp;card_width=495&amp;card_height=195&amp;hide_border=false&amp;border=30363D&amp;border_radius=8&amp;background=161B22&amp;ring=D96B27&amp;fire=D96B27&amp;currStreakNum=F0F6FC&amp;sideNums=F0F6FC&amp;currStreakLabel=D96B27&amp;sideLabels=F0F6FC&amp;dates=8B949E&amp;stroke=30363D&amp;timezone=Asia%2FQatar&amp;disable_animations=true" alt="Total contributions, current streak, and longest streak" /></a>
</p>

#### Contribution trends

<p align="center">
  <a href="https://github.com/Bixal99"><img width="96%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Bixal99&amp;name=Mohammad%20Bilal&amp;theme=github_dark&amp;title_color=D96B27&amp;text_color=F0F6FC&amp;bg_color=161B22&amp;border_color=30363D&amp;icon_color=D96B27&amp;chart_color=D96B27" alt="Annual contribution area chart on a dark background" /></a>
</p>

#### Contribution calendar

<!-- Native green palette; solid dark canvas and dark empty cells. -->
<!-- Service documentation: https://gh-heat.anishroy.com/ -->
<p align="center">
  <a href="https://github.com/Bixal99"><img width="96%" src="https://gh-heat.anishroy.com/api/Bixal99/svg?theme=green&amp;darkMode=true&amp;colors=161b22,0e4429,006d32,26a641,39d353&amp;bg=%230d1117&amp;transparent=false&amp;textColor=%238b949e&amp;borderColor=%2330363d&amp;borderWidth=0.5&amp;radius=2&amp;padding=22&amp;cellSize=13&amp;cellGap=3" alt="GitHub contribution heatmap: dark background, dark empty squares, and native green filled contribution squares" /></a>
</p>

<details>
<summary><b>View activity by hour · Qatar time, UTC+3</b></summary>

<p align="center">
  <a href="https://github.com/Bixal99"><img width="480" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Bixal99&amp;theme=github_dark&amp;utcOffset=3&amp;title_color=D96B27&amp;text_color=F0F6FC&amp;bg_color=161B22&amp;border_color=30363D&amp;icon_color=D96B27&amp;chart_color=D96B27" alt="Commit activity by hour, adjusted to Qatar time" /></a>
</p>

</details>

<p align="center"><sub>Live public GitHub data. Providers cache updates independently.</sub></p>

---

<a id="stack"></a>

## Toolkit

**AI and vision**  
LangChain · LangGraph · RAG · OpenCV · MediaPipe · OCR · XGBoost · OpenAI · Anthropic · Gemini · Ollama · Groq

**Product engineering**  
Python · JavaScript · TypeScript · Next.js · React · FastAPI · Flask · Node.js · Express · Pydantic · Better Auth

**Interfaces and data**  
Tailwind CSS · GSAP · Framer Motion · Zustand · Streamlit · Plotly · Pandas · NumPy · PostgreSQL · MongoDB · Supabase

**Delivery and tooling**  
Git · Docker · Linux · Vercel · GitLab CI/CD · Postman · Figma · Hugging Face · PyMuPDF · Selenium · Beautiful Soup

<details>
<summary><b>Foundations and applied expertise</b></summary>

**Foundations:** SQL · C · C++ · HTML5 · CSS3 · Algorithms · OOP · Networks · Software development lifecycle

- **Computer vision:** Facial landmarks, eye-blink detection, and accessible interfaces.
- **Machine learning:** Classification, regression, feature pipelines, and model evaluation.
- **Generative AI:** Retrieval, orchestration, prompting, and conversational applications.
- **Document intelligence:** PDF extraction, OCR, and scraping pipelines.
- **Analytics:** Interactive dashboards and visual data exploration.

</details>

---

## Experience, education, and recognition

**AI Engineer · Zennore**  
Pakistan · June 2025–Present

Deliver AI-powered product features through cross-functional collaboration, prompt engineering, and production workflows. Contribute from concept through release.

**BS Computer Science · FAST NUCES University**  
Pakistan · August 2022–June 2026

Computer Science graduate with a portfolio across AI, computer vision, full-stack development, and systems engineering, and 1+ year of professional AI engineering experience.

**Deloitte WorldClass certificates**

- **Critical Thinking** · completed September 8, 2026.
- **Effective Leadership** · completed September 10, 2026.

<details>
<summary><b>Further learning, coding profiles, and languages</b></summary>

**Certifications in progress:** AWS · Oracle · NPTEL · Cisco

**Coding profiles:** [LeetCode](https://leetcode.com/Bixal99) · [GeeksforGeeks](https://geeksforgeeks.org/user/Bixal99) · [HackerRank](https://hackerrank.com/Bixal99) · [CodeChef](https://codechef.com/users/Bixal99)

**Languages:** English (fluent) · Urdu (fluent) · Hindi (intermediate) · Arabic (beginner)

</details>

## Currently exploring

LangGraph orchestration, vector databases, and RAG with pgvector and Neon. Building AI infrastructure, LLM quality monitoring, and full-stack SaaS products; exploring CI/CD for AI systems and computer vision for accessibility.

---

<a id="connect"></a>

<p align="center">
  <a href="mailto:bilalnadeema302003@gmail.com"><img src="./profile-assets/footer.svg" width="100%" alt="Have a project in mind? Let's talk · AI/ML, computer vision, and full-stack development" /></a>
</p>

<p align="center">
  <a href="mailto:bilalnadeema302003@gmail.com">Email</a> &nbsp; / &nbsp;
  <a href="https://www.linkedin.com/in/mohammad-bilal-64489827b/">LinkedIn</a> &nbsp; / &nbsp;
  <a href="https://portfolio-beta-gilt-1emaymvhv5.vercel.app/">Portfolio</a> &nbsp; / &nbsp;
  <a href="https://github.com/Bixal99">GitHub</a>
</p>

<p align="center"><sub>Open to AI/ML roles, full-stack collaboration, freelance work, and contracts.</sub></p>
