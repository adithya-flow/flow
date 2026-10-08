# flow

My AI Engineer roadmap, learned in public. This repo holds the notes, notebooks and projects from every stage, written up cleanly so I can revise from them later.

**Target role:** AI Engineer (LLM / agent-focused), job-ready as a fresher.
**Approach:** mastery-based, not date-based. I don't move on from a stage until its mastery check passes.
**Rule for every project:** I write and understand every core piece myself. AI tools explain concepts; they don't generate the implementation.

---

## Progress

| # | Stage | Status |
|---|-------|--------|
| 1 | [Programming Foundations (Python, NumPy, pandas)](01-python-foundations/) | 🟡 In progress |
| 2 | [Mathematics for AI](02-math-for-ai/) | ⬜ Not started |
| 3 | [Data Analysis Foundations](03-data-analysis/) | ⬜ Not started |
| 4 | [Machine Learning Fundamentals](04-machine-learning/) | ⬜ Not started |
| 5 | [Deep Learning](05-deep-learning/) | ⬜ Not started |
| 6 | [LLM Engineering Core](06-llm-engineering/) | ⬜ Not started |
| 7 | [AI Agents & Tool Use](07-ai-agents/) | ⬜ Not started |
| 8 | [MLOps & Deployment](08-mlops-deployment/) | ⬜ Not started |
| 9 | [Software Engineering Practices](09-software-engineering/) | ⬜ Not started |
| 10 | [Specializations](10-specializations/) | ⬜ Not started |
| 11 | [System Design for AI](11-system-design/) | ⬜ Not started |

Legend: ✅ done · 🟡 in progress · ⬜ not started

### Stage 1 detail

- [x] 1.1 Python syntax & data structures (mastery check passed)
- [ ] 1.2 NumPy & pandas (content done, mastery check pending)

---

## Projects

| # | Project | Stage | Status |
|---|---------|-------|--------|
| 1 | Basic Data Analysis & Visualization | 3 | ⬜ |
| 2 | Predictive Modeling (classical ML) | 4 | ⬜ |
| 3 | Image Classifier or Text Model | 5 | ⬜ |
| 4 | RAG-Powered Q&A Application | 6 | ⬜ |
| 5 | Task-Oriented Agent | 7 | ⬜ |
| 6 | Deploy an End-to-End AI Service | 8 | ⬜ |
| ★ | Capstone: production-style RAG chatbot with an agentic tool-use layer, deployed and monitored | All | ⬜ |

---

## Repo structure

```
flow/
├── README.md
├── 01-python-foundations/
│   ├── README.md          # stage summary, what I learned, what tripped me up
│   └── *.ipynb            # one notebook per topic
├── 02-math-for-ai/
├── ...
├── projects/              # finished projects (or links to their own repos)
└── .gitignore
```

Each stage folder has its own `README.md` with a short summary, links to the notebooks, and the mastery-check result.

## Conventions

- Stage folders are numbered so they sort in learning order.
- Notebook names are lowercase with underscores, e.g. `02_control_flow.ipynb`.
- Notebooks are committed with heavy outputs cleared.
- Commits are small and descriptive, e.g. `add lists notebook`, `notes: closures`.

## Setup

```bash
git clone https://github.com/<your-username>/flow.git
cd flow
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install jupyter numpy pandas
jupyter notebook
```

Dependencies will be added per stage as the roadmap progresses.
