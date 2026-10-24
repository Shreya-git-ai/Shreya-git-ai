<h1 align="center">Shreya Chaturvedi</h1>

<p align="center">
  CS (AI &amp; ML) undergraduate at RNSIT, Bengaluru<br>
  Building Python backends and applied-AI projects, and sharpening DSA alongside them.
</p>

<p align="center">
  <a href="#featured-projects">Projects</a> ·
  <a href="#toolkit">Toolkit</a> ·
  <a href="#problem-solving">Problem solving</a> ·
  <a href="#connect">Connect</a>
</p>

---

## About

I'm a B.E. Computer Science (AI & ML) student at RNS Institute of Technology, Bengaluru, looking for software engineering and AI/ML internships.
I enjoy projects where the interesting part is the pipeline: how data flows through a system, how results get scored, and how the system explains its output.
Right now I'm building RAG-style backends in Python and working through DSA in C++.

## Featured projects

### [Recruiter Brain](https://github.com/Shreya-git-ai/Recruiter_Brain)
Ranks candidates against a job description by meaning rather than keyword overlap, so keyword-stuffed profiles don't win by default.

- Pipeline: hard-requirement filters → profile-quality and honeypot heuristics → embedding similarity (`all-MiniLM-L6-v2`, cosine) → career-fit and hiring-signal scoring → a short written rationale per candidate
- Design choice: candidate embeddings are precomputed once and cached, so ranking runs CPU-only with no API calls
- Includes a Streamlit interface, a `tests/` folder, and a submission validator
- **Stack:** Python, sentence-transformers, scikit-learn, pandas, Streamlit

🔗 [Live demo](https://recruiterbrain-u5hmq6tp5jnpafboh3ke5x.streamlit.app/)

### [PrepMate](https://github.com/Shreya-git-ai/PrepMate) · in progress
A RAG-based study assistant that turns PDFs into a searchable knowledge base for interview prep.

- Working: PDF ingestion → page-level chunks → Sentence-Transformer embeddings → ChromaDB
- Next: retrieval, LLM-grounded answers, topic classification and mastery tracking
- **Stack:** Python, ChromaDB, sentence-transformers, FastAPI/Alembic scaffolding, TypeScript frontend

 [KALPA ML](https://github.com/Shreya-git-ai/Kalpa-ml) · team project
ML layer for a hyper-local business advisory platform: a demand-prediction model and a feasibility classifier, built on Census, ASUSE and village-amenity data.

- Evaluated with a geographic holdout (whole unseen districts) and a leakage audit, not a random split
- Honest finding: with leakage-prone features removed, the demand model has limited signal against a proxy target, and the README says so
- **Stack:** Python, scikit-learn
-->

<!-- Keep only if the TrustFlow repo is public and its README supports each line:
### [TrustFlow](https://github.com/Shreya-git-ai/TrustFlow) · hackathon project
Milestone-based payment platform built for the PayPal AI hackathon as a team. My part: the AI assessment agent, a FastAPI endpoint with idempotency handling and a pytest suite.
-->

## Toolkit

| | |
|---|---|
| **Languages** | Python (primary) · TypeScript (project frontends) |
| **Backend & data** | FastAPI · SQLAlchemy · PostgreSQL · Alembic · Streamlit |
| **AI / ML** | sentence-transformers · scikit-learn · pandas · ChromaDB (RAG) · LLM APIs |
| **Tools** | Git · GitHub |
| **Learning** | DSA and problem solving in C++ |

## Problem solving

[LeetCode profile](https://leetcode.com/u/Shreya_Chaturvedi1803/)

## Currently

- Strengthening DSA and problem solving in C++
- Taking PrepMate from ingestion to retrieval and mastery tracking
- Preparing to contribute to open source, with GSoC in mind. Merged contributions will be listed here as they happen.

## Connect

[GitHub](https://github.com/Shreya-git-ai) · [LinkedIn](https://www.linkedin.com/in/shreya-chaturvedi-64020a359)
