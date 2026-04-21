# Python Foundations for Health Professionals

**Python for clinicians, health informaticians, public-health researchers, and digital-health master's students — taught from zero.**

This repository is a complete block-teaching module: lecture notebooks, exercises, take-home assignments, and small datasets. It is designed for people who are **new to programming but bring domain knowledge from healthcare** — physicians, nurses, health informaticians, epidemiologists, public-health researchers, and master's students in Digital Health, Health Data Science, or Health Informatics.

**Instructor:** Dr. Jenny Delekta (physician, lecturer)
**Language of instruction:** English
**Scope:** 6 ECTS, Master's level
**Examination:** Practical assignment, 100%

---

## Who this is for

You will get the most out of this course if you can answer **yes** to at least one of the following:

- I work in healthcare (as a clinician, informatician, researcher, or public-health professional) and want to stop waving at data from the other side of the fence.
- I am a master's student in a health-data-related programme and need a solid Python foundation before moving on to advanced analytics.
- I have tried to learn Python on my own — maybe a MOOC, maybe a tutorial — but I never got the bridge from "I can read syntax" to "I can analyse my data".
- I think in clinical reasoning (anamnesis → anatomy → physiology → clinic → differential diagnosis) and want a teacher who thinks the same way.

You do **not** need prior programming experience. You do need a laptop, patience with a setup guide, and willingness to think out loud in a group.

---

## How to use this repository

1. Install Python, Git, and VSCode. A detailed walkthrough is in the course's welcome materials.
2. Clone this repository:
   ```bash
   git clone https://github.com/jendele/python-foundations-for-health-professionals.git
   cd python-foundations-for-health-professionals
   ```
3. Before every session, pull the latest version:
   ```bash
   git pull
   ```
4. Open the folder in VSCode. Each session has its own subfolder with lecture notes, exercises, and a homework notebook.

---

## Schedule

| Session | Date | Topic | Folder |
|---|---|---|---|
| 1 | Thu, 23 Apr 2026 | Python as a Tool — Setup & First Dialog | `session1/` |
| 2 | Fri, 24 Apr 2026 | Logic & Control Flow | `session2/` |
| — | 27 Apr – 5 May | Self-study week | `self_study/` |
| 3 | Wed, 6 May 2026 | Data Structures & Functions | `session3/` |
| 4 | Thu, 7 May 2026 | Files & Pandas | `session4/` |
| 5 | Fri, 8 May 2026 | Visualization, APIs, Clean Code | `session5/` |
| Exam | Tue, 12 May 2026 | Practical assignment | `exam/` |

All on-campus sessions run 09:00–12:45.

---

## Per-session structure

Each session folder contains:

- `README.md` — session goals, required pre-reading, homework deadline
- `lecture_notes.ipynb` — the notebook we build together in class
- `homework.ipynb` — take-home assignment
- `data/` — small datasets used in class (public data only)
- `solutions/` — released after the submission deadline

---

## Policies

### AI use

You are **allowed and encouraged** to use AI tools (ChatGPT, Claude, GitHub Copilot) as a learning companion. You are **not allowed** to submit code you cannot explain. For each homework, be ready to walk through your logic in 30 seconds. If you can't, it doesn't count — no matter who wrote it.

### Collaboration

Tandem pairs are set during Session 1. You may discuss, debug together, and explain to each other — but each person submits their own notebook. Identical submissions from two students count as one.

### Submissions

All homework is submitted via the course's official submission channel (announced in class), with a deadline at the start of the next session. Late submissions drop one notch on the rubric per 24 hours.

### Solutions

Reference solutions (`solutions/` folder) are published **only after** the submission deadline for each homework. This is deliberate: the learning is in the wrestling, not in the reading. Once you have submitted your own attempt, comparing it against the reference solution is where most of the deep learning happens — but only if you've already tried yourself first.

### Contact

- For content questions: the course discussion forum (first port of call — others benefit from your question).
- For personal matters: the email announced in the welcome materials (answers within 2 working days, not weekends).

---

## Prerequisites

Before Session 1, you must have:

- [ ] Python 3.11 or higher installed
- [ ] Git installed
- [ ] VSCode installed with **Python** and **Jupyter** extensions
- [ ] A GitHub account (free tier is fine)
- [ ] A Google account (for Colab access from Session 5 onwards)
- [ ] Passed the functional test: `python hello.py` prints `Hello, <your_name>!`

---

## Reuse and licensing

Course materials are released under **CC BY-NC-SA 4.0**: use, remix, teach with them — just give credit and don't sell them. Educators are warmly invited to adapt this for their own courses.

Dataset files in `data/` carry their own licenses — see the per-session README.

---

*Last updated: 18 April 2026*
