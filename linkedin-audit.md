# LinkedIn Profile Audit and Rewrite: Archana Vankayalapati

Audited October 2026 against AI Engineer, GenAI Engineer, and ML Engineer postings at H-1B sponsors (Microsoft, Ford, R1 RCM, Cleveland Clinic and similar).

---

## 1. What the profile shows today

| Section | Current state |
|---|---|
| Headline | "AI Engineer" (2 words) |
| Location | "United States" |
| About | Empty |
| Experience | 3 job titles and dates, **no descriptions at all** |
| Top Skills | CSS, HTML5, HTML |
| Education | Not shown |
| Certifications | Claude Academy: Intro to MCP; Claude Academy: Building with the Claude API |

**Bottom line:** recruiters search LinkedIn by keywords, and right now your profile has almost none. Your RAG, agents, evaluation and fraud-model work is invisible. Recruiters who find you see "AI Engineer" plus HTML/CSS skills, which looks like a front-end developer. Everything that makes you a strong mid-level candidate is in your resume but not on LinkedIn.

---

## 2. Gaps

### A. Missing keywords

These terms come up again and again in current postings. Microsoft-ecosystem roles ask for end-to-end RAG pipelines, LangGraph agents, Azure OpenAI and evaluation of accuracy and hallucination rates. Ford's GenAI and ML Engineer roles ask for PyTorch, MLOps, Docker and Kubernetes. R1 RCM's AI Engineer II and Cleveland Clinic's AI roles ask for LLMs, agentic AI and healthcare unstructured data.

| Keyword | In your background? | On your LinkedIn now? |
|---|---|---|
| RAG / retrieval-augmented generation | Yes | No |
| LLM / large language models | Yes | No |
| AI agents / agentic AI | Yes (prior-auth agent) | No |
| LangGraph | Yes | No |
| Azure OpenAI | Yes | No |
| MCP (Model Context Protocol) | Yes (+ certification) | Certification only |
| LLM evaluation, LLM-as-judge, RAGAS | Yes | No |
| MLOps, MLflow | Yes | No |
| FastAPI, Kafka, Redis | Yes | No |
| Kubernetes (AKS), Azure | Yes | No |
| Fine-tuning, LoRA | Yes (Qwen2.5 project) | No |
| XGBoost, BERT, NLP, NER, FAISS, vector search | Yes | No |
| Elasticsearch, Scikit-learn, spaCy, GCP | Yes | No |
| Healthcare AI, clinical NLP, HIPAA, prior authorization | Yes | No |
| Fraud detection, KYC, OCR | Yes | No |
| Python | Surely yes | No |
| **PyTorch, Hugging Face, Docker** | **Not stated in your notes** | No |

> **Check this:** PyTorch, Hugging Face (Transformers/PEFT) and Docker show up in many of these postings. A LoRA fine-tune of Qwen2.5, BERT work and AKS deployments usually involve them, but they aren't in the background you gave me, so I left them out of the rewrites below. If you did use them, add them to your Skills section and to the bullets where they fit.

### B. Weak positioning

- **"AI Engineer" alone says nothing about level or focus.** It doesn't say GenAI, production or healthcare. You have 3+ years and real production systems, but nothing on the page shows it.
- **HTML/CSS as your top skills hurts you.** LinkedIn shows them on your profile card and uses them for matching, so they pull you toward the wrong jobs.
- **"United States" as your location hides you** from recruiters filtering for Cincinnati, Columbus, Ohio or Michigan. Set it to Cincinnati, OH and list remote plus your relocation cities under Open to Work (recruiters only).
- **No education.** An M.S. from the University of Cincinnati helps for H-1B (it counts toward the master's cap) and helps with Ohio employers. Add it.
- **No projects.** Your LoRA fine-tuning project shows you can go beyond calling APIs. Put it in the Projects section.

### C. Buried accomplishments

None of these numbers are on the profile: 72%→90% accuracy, recall@5 0.68→0.87, 100K+ documents, 400+ users, 18→11 min review time, 50K+ alerts/day, 25% fewer low-value alerts, 88% intent accuracy across 30+ intents, 40% less manual entry, 90% classification accuracy, invoice time cut in half, field accuracy 0.54→0.81. **This is the biggest single fix.** Numbers are what make a recruiter stop scrolling.

---

## 3. Rewrites

### Headline (150 characters)

```
AI/ML Engineer | GenAI, LLMs, RAG & AI Agents | LangGraph, Azure OpenAI, MCP | LLM Evaluation, MLOps, FastAPI, Kubernetes | Healthcare AI & Fintech ML
```

The first 40 or so characters show in search results, so the role names and "GenAI, LLMs, RAG" come first. If you confirm PyTorch, you can swap "MCP" for "PyTorch".

### About

> I build AI systems that people use every day. Right now that's a clinical RAG assistant used by 400+ people, where I raised answer accuracy from 72% to 90%.
>
> I'm an AI/ML engineer with 3+ years of experience, mostly in healthcare and banking. At MedTech Analytics I build GenAI tools on Azure OpenAI and LangGraph. The main one is a RAG assistant that searches 100K+ clinical documents. I improved its retrieval (recall@5 went from 0.68 to 0.87) and set up the testing that tells us whether a change actually helps: golden test sets, LLM-as-judge and RAGAS. I also built a prior-authorization agent that uses MCP tools to gather case information. It cut review time from 18 to 11 minutes.
>
> Before that I worked on classic ML at HDFC Bank. I built a fraud scoring model (XGBoost) that handles 50K+ alerts a day and cut low-value alerts by 25%, a BERT model that routes customer requests across 30+ intents, and an OCR + NER pipeline for KYC documents that cut manual data entry by 40%. At Infosys I built enterprise search, document classification and NER for invoice processing.
>
> On the side, I fine-tuned Qwen2.5 with LoRA for clinical note extraction and compared it to a frontier LLM. Field accuracy went from 0.54 to 0.81.
>
> What I work with: Python, LLMs, RAG, LangGraph, Azure OpenAI, MCP, LLM evaluation (RAGAS, LLM-as-judge), FastAPI, Kafka, Redis, Kubernetes (AKS), MLflow, XGBoost, BERT, FAISS, Elasticsearch, spaCy, Scikit-learn, Azure and GCP. I'm used to working with healthcare data under HIPAA.
>
> M.S. in Information Technology, University of Cincinnati.
>
> What I'm looking for: AI Engineer, GenAI/LLM Engineer or ML Engineer roles where I can ship and improve production AI systems. I'm based in Cincinnati, OH and open to fully remote roles in the US or relocating to Texas, Columbus or Michigan. I'm on STEM OPT and will need H-1B sponsorship.

*Why it works:* the first two lines (the part shown before "see more") say what you build, who uses it and a real result. The rest is plain sentences with the keywords worked in naturally. The ending says what you want and states sponsorship up front, so you don't waste time on recruiters who can't sponsor.

### Experience: top 3 bullets each

**MedTech Analytics, LLC: Gen AI Engineer** (Feb 2025–Present, Remote)
- Built and run a clinical RAG assistant on Azure OpenAI and LangGraph that searches 100K+ documents for 400+ users. Raised answer accuracy from 72% to 90% and retrieval recall@5 from 0.68 to 0.87.
- Built a prior-authorization AI agent that uses MCP tools to pull case information, cutting average review time from 18 to 11 minutes.
- Set up LLM evaluation with golden test sets, LLM-as-judge and RAGAS, and shipped the services on FastAPI, Kafka, Redis and Kubernetes (AKS), with MLflow tracking, in a HIPAA-regulated setting.

**HDFC Bank: Machine Learning Engineer** (Sep 2022–Jul 2023)
- Built an XGBoost fraud scoring model that scores 50K+ alerts a day and cut low-value alerts by 25%, so investigators spent more time on real fraud.
- Trained a BERT intent classifier that routes customer requests across 30+ intents with 88% accuracy, and added FAISS semantic search for faster lookups.
- Built a KYC document pipeline with OCR and NER that cut manual data entry by 40%.

**Infosys: Machine Learning Engineer** (Aug 2021–Sep 2022)
- Built a spaCy NER model to extract invoice fields, cutting invoice processing time in half.
- Built a Scikit-learn document classifier with 90% accuracy to sort incoming business documents.
- Built Elasticsearch enterprise search and served the models through Flask APIs on GCP.

---

## 4. Other quick fixes (about 15 minutes)

1. **Skills:** remove CSS, HTML5 and HTML. Pin these 3 as top skills: *Large Language Models (LLM)*, *Retrieval-Augmented Generation (RAG)*, *Machine Learning*. Then add: Generative AI, AI Agents, LangGraph, Azure OpenAI, LLM Evaluation, MLOps, Python, FastAPI, Kubernetes, MLflow, NLP, XGBoost, BERT, Elasticsearch (plus PyTorch, Hugging Face and Docker if true).
2. **Location:** change to Cincinnati, Ohio.
3. **Open to Work (recruiters only):** titles AI Engineer, Generative AI Engineer, Machine Learning Engineer, Applied AI Engineer, MLOps Engineer. Locations: Remote (US), Cincinnati, Columbus, Texas, Michigan.
4. **Education:** add M.S. Information Technology, University of Cincinnati (2024) and B.Tech ECE (2022).
5. **Projects:** add "LoRA Fine-Tuning Qwen2.5 for Clinical Note Extraction": *Fine-tuned Qwen2.5 with LoRA to pull structured fields from clinical notes and compared it with a frontier LLM. Field accuracy went from 0.54 to 0.81.* Link the GitHub repo (github.com/Archu9999) if it's public.
6. **Job title:** "Gen AI Engineer" is fine. If MedTech is OK with it, "Generative AI Engineer" matches more recruiter searches. Only change it if it stays accurate.
7. **Featured section:** pin the LoRA project repo and your two Claude Academy certifications.

---

Sources: [Microsoft-ecosystem AI Engineer (Azure AI Foundry, LangGraph)](https://leadecservices.keka.com/careers/jobdetails/61139) · [AI Engineer, RAG/agents/evaluation](https://insightglobal.com/jobs/find_a_job/job-482902) · [Ford AI Engineer](https://www.careers.ford.com/job/naucalpan-de-juarez/ai-engineer/48560/99235336688) · [Ford Generative AI Engineer](https://www.wearedevelopers.com/jobs/ext/6206953/generative-ai-engineer) · [R1 RCM AI Engineer II](https://builtincharlotte.com/job/us-ai-engineer-ii-r37/9044282) · [Cleveland Clinic AI](https://talentcommunity.clevelandclinic.org/job/21700942/cleveland-clinic-ai-cleveland-oh) · [Cleveland Clinic AI Software Engineer](https://www.ihiretechnology.com/jobs/view/523768709)
