# 🧠 Expert Contributor Funnel Simulation – Growth Ops Practice Project

## ✨ Overview

This project simulates the core responsibilities of a **Growth Operations Lead** at a company like **Handshake AI**—where PhD-level experts are recruited, trained, and activated as contributors to improve large language models (LLMs).

Using a realistic, end-to-end funnel simulation with **Python, SQL-style logic, and Excel-style KPIs**, this project demonstrates how to:

- Track contributor progression through key funnel stages
- Identify drop-offs and performance gaps
- Analyze and visualize contributor quality and efficiency
- Propose data-driven improvements to training and activation workflows

---

## 🛠️ Tools Used

- **Python** (`pandas`, `numpy`, `matplotlib`, `seaborn`)
- **SQL-style queries** (via `pandas.query()` or SQLite)
- **Excel/Sheets-style metrics** (conversion %, drop-off, activation time)

---

## 🧩 Funnel Stages Simulated

| Stage               | Description                                                  |
|--------------------|--------------------------------------------------------------|
| Sourced             | PhD/SME signs up (via LinkedIn, referral, email, etc.)       |
| Qualified           | Candidate passes domain/education filters                    |
| Training Started    | Begins onboarding/training module                            |
| Training Completed  | Finishes training                                            |
| Passed Evaluation   | Scores well on mock/test annotation tasks                    |
| Activated           | Assigned to real-world client task (e.g., OpenAI)             |

---
## 🔍 Key Columns Explained
| Column                    | Description                                                     |
| ------------------------- | --------------------------------------------------------------- |
| `candidate_id`            | Unique identifier                                               |
| `source`                  | Where they came from (LinkedIn, Job Board, etc.)                |
| `domain`                  | Subject matter area (e.g., Biotech, Finance)                    |
| `qualified`               | Whether they passed initial filters                             |
| `training_started_date`   | When they began training (if at all)                            |
| `training_completed_date` | If they finished training                                       |
| `evaluation_score`        | Their simulated test task result (0–100)                        |
| `activated`               | Whether they were placed on a real client project               |
| `time_to_activate_days`   | Time from eval pass to activation (how fast they were deployed) |
