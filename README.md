# FairScan 🔍
### Know what your AI really decides.

FairScan is an AI ethics auditing platform that tests machine learning 
models for bias, explains their decisions, and issues compliance 
certificates for regulators, developers, and businesses.

---

## 🎯 Problem Statement
70% of AI systems show measurable bias. Hiring algorithms reject 
qualified candidates. Loan algorithms discriminate against protected 
groups. FairScan solves this.

---

## ✨ Features
- **Bias Detection** — Tests across 5 fairness dimensions
- **Explainability** — SHAP/LIME for individual decisions  
- **Proxy Detection** — Finds hidden discrimination via correlated features
- **Remediation** — Actionable fix suggestions with before/after simulation
- **Compliance Reports** — PDF certificates for RBI, SEBI, EU AI Act

---

## 🏗️ Tech Stack
| Layer | Technology |
|---|---|
| Frontend | React + Tailwind CSS |
| Backend | Python + FastAPI |
| Bias Detection | IBM AIF360 + Fairlearn |
| Explainability | SHAP + LIME |
| Database | PostgreSQL |
| Reports | ReportLab |

---

## 👥 Team
| Member | Role |
|---|---|
| [Ishwari Ugale] | Team Lead + Integration |
| [Ishwari Ugale] | ML Core Engineer |
| [Apurva Chaudhari] | Backend Engineer |
| [Samrudhi Take] | Frontend Engineer |
| [Aditi Deshmukh] | Reports + Presentation |

---

## 🚀 Getting Started

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

---

## 📊 JEDI Score
FairScan rates every AI model on a 0-100 ethics score:
- 🟢 80-100 — Certified, safe to deploy
- 🟡 50-79 — Issues found, remediation required  
- 🔴 0-49  — High risk, do not deploy

---

## 🎯 SDGs Addressed
- SDG 16 — Peace, Justice & Strong Institutions
- SDG 8  — Decent Work & Economic Growth
- SDG 10 — Reduced Inequalities

---

*Built for JEDI Code Compliance Hackathon*
