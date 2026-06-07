<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&pause=1000&color=8B5CF6&center=true&vCenter=true&width=700&height=60&lines=AI%2FML+Developer;LLM+Agents+%26+RAG+Systems;Generative+AI+Engineer;Full-Stack+AI+Builder" alt="roles" />

# Lalit Yadav

**Undergraduate at IIT Roorkee** building end-to-end **LLM applications** — RAG pipelines, multi-agent systems, and the full-stack products around them. I care about making AI *reliable in production*, not just impressive in a demo.

<a href="https://www.linkedin.com/in/ydvlalit03/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:lalit@ph.iitr.ac.in"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/ydvlalit03"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<img src="https://komarev.com/ghpvc/?username=ydvlalit03&style=for-the-badge&color=8B5CF6&label=PROFILE+VIEWS" alt="views"/>

</div>

---

## 🧠 about_me.py

```python
from functools import wraps


def ships(stage: str):
    """Nothing leaves the bench until it's been through here."""
    def deco(fn):
        @wraps(fn)
        def wrapper(*args, **kwargs):
            return f"{fn(*args, **kwargs)} → {stage} ✅"
        return wrapper
    return deco


class LalitYadav:
    """AI engineer — makes LLMs reliable in prod, not just pretty in a demo."""

    def __init__(self) -> None:
        self.role   = "AI / ML Engineer"
        self.school = "IIT Roorkee · B.S + M.S (2022–2027)"
        self.focus  = ["RAG pipelines", "multi-agent systems", "full-stack LLM apps"]
        self.stack  = {
            "agents":   ["LangGraph", "LangChain", "Gemini", "Groq"],
            "backend":  ["FastAPI", "PostgreSQL", "Docker", "AWS"],
            "frontend": ["React", "Next.js", "TypeScript", "Tailwind"],
        }
        self._coffee = float("inf")  # ☕

    @property
    def currently_building(self) -> str:
        return "TravelOS — AI agents + CRM for travel agencies"

    @property
    def philosophy(self) -> str:
        return "eval over vibes · ground truth over guessing"

    @ships("production")
    def build(self, idea: str) -> str:
        return f"{idea} → tested"

    def __repr__(self) -> str:
        return "<Lalit: ship fast · eval faster · build things that actually work>"


me = LalitYadav()
print(me.build("a wild idea"))   # a wild idea → tested → production ✅
print(me)                        # <Lalit: ship fast · eval faster ...>
```

> 📫 reach me at **lalit@ph.iitr.ac.in**

---

## 💼 Experience

### 🟣 AI/ML Developer Intern — [Campayn](https://github.com/ydvlalit03) `(Remote · Apr 2026 – May 2026)`
- Shipped **dashboards, campaign workflows, auth systems and analytics platforms** straight from PRDs using Claude Code
- Integrated the **Instagram Graph API** with fallback scraping for real-time metrics (views, reach, saves, watch-time)
- Automated **Instagram/LinkedIn comment-to-DM flows**, webhook handling and API integrations — cutting manual ops effort

### 🟣 AI/ML Developer Intern — Leadfreak `(On-site · Dec 2025 – Mar 2026)`
- Engineered an **AI comment generator** using a **RAG pipeline over 2000+ high-engagement comments**, deployed end to end
- Built a **job-search platform** for career coaches with automated discovery, roadmap generation and pipeline management
- Delivered a **CRM, HRMS and salary estimator** for lead qualification, plus a company website that improved engagement

---

## 🛠️ Tech Stack

<div align="center">

**Languages & Machine Learning**

<img src="https://skillicons.dev/icons?i=python,cpp,typescript,pytorch,tensorflow,sklearn,opencv&theme=dark" />

**Generative AI & NLP**

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" />
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
<img src="https://img.shields.io/badge/Mistral_AI-FF7000?style=for-the-badge&logo=mistralai&logoColor=white" />
<img src="https://img.shields.io/badge/RAG-0EA5E9?style=for-the-badge" />
<img src="https://img.shields.io/badge/Multi--Agent_Systems-8B5CF6?style=for-the-badge" />
<img src="https://img.shields.io/badge/Sentence--BERT-EE4C2C?style=for-the-badge" />
<img src="https://img.shields.io/badge/Prompt_Engineering-10B981?style=for-the-badge" />

**Backend & Frontend**

<img src="https://skillicons.dev/icons?i=fastapi,react,nextjs,nodejs,tailwind,html,css&theme=dark" />

**Data, Vectors & Infra**

<img src="https://skillicons.dev/icons?i=postgres,sqlite,mongodb,docker,git,linux&theme=dark" />
<br/>
<img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white" />
<img src="https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge" />
<img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/NLTK-154F5B?style=for-the-badge" />

</div>

---

## 📌 Featured Projects

| 🚀 Project | What it does | Stack |
|-----------|--------------|-------|
| **[Go Issue Agent](https://github.com/ydvlalit03/go-issue-agent)** | Agentic AI that autonomously resolves GitHub issues in Go repos — localizes, fixes, validates against the Go toolchain, and drafts the PR | `LangGraph` `Ollama` `Go` |
| **[Geospatial Intelligence](https://github.com/ydvlalit03/Geospatial-Intel)** | Satellite-imagery analysis with U-Net segmentation + YOLOv8 detection and a LangGraph natural-language query agent | `PyTorch` `YOLOv8` `FastAPI` |
| **[Fantastic Jobs API](https://github.com/ydvlalit03/fantastic-jobs-api)** | Unified multi-tenant FastAPI backend: job search, resume→title generation, and salary estimation behind one API | `FastAPI` `Groq` `PostgreSQL` |
| **[Salary Estimator](https://github.com/ydvlalit03/salary-estimator)** | LangGraph agent that estimates salary from a LinkedIn profile via parallel web search + a ChromaDB knowledge base | `LangGraph` `Gemini` `ChromaDB` |
| **[LinkedIn Comment Generator](https://github.com/ydvlalit03/linkedin-comment-generator)** | Full-stack Next.js app that writes comments in *your* voice using a RAG pipeline + fast Groq inference | `Next.js` `Groq` `RAG` |
| **[Job Dhundo](https://github.com/ydvlalit03/My-Job-Searching-Partner)** | AI job-search platform for freshers — ATS resume scoring, job matching and a daily roadmap | `FastAPI` `Gemini` `LangGraph` |

---

## 📊 GitHub Statistics

<div align="center">

<img height="170" src="https://github-readme-streak-stats.herokuapp.com?user=ydvlalit03&hide_border=true&theme=tokyonight&background=0D1117&ring=8B5CF6&fire=8B5CF6&currStreakLabel=8B5CF6" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ydvlalit03&theme=react-dark&hide_border=true&bg_color=0D1117&color=8B5CF6&line=8B5CF6&point=c9d1d9&area=true&area_color=8B5CF6" width="98%"/>

</div>

---

## 🌱 Beyond Code

- 🏛️ **President, Student Affairs Council** — led the council, coordinating 6 of 7 General Secretaries across student affairs
- 🎭 **Dramatics Section** — led a 40+ member team at Inter-IIT Cultural Meets for two years
- 🏔️ **Deputy Secretary, Himalayan Explorers' Club** — ran finances and logistics for treks across the Himalayas

---

<div align="center">

### 🤝 Let's build something

<a href="https://www.linkedin.com/in/ydvlalit03/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:lalit@ph.iitr.ac.in"><img src="https://img.shields.io/badge/Reach_out-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<sub>⚡ ship fast · eval faster · build things that actually work</sub>

</div>
