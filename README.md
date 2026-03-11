[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/FdVrU54p)
#  Hospital Admission Records Analysis

## Team Members
- Rahaf Almanaseer
- Sara Ahmed
- Omar Khalid

> **Lab 1 starter repo** — Replace the heading above with your project title. Team member names are not part of the lab — they go in Section 2 of your completed README in the integration task.

---

## Project Overview

This project analyzes hospital admission records to understand patterns in patient admissions.  
The goal is to identify trends in hospital usage and common admission reasons.  
The results will help healthcare teams better understand patient flow.

---

## Data Sources

This project uses hospital admission data stored locally.

Data is not tracked in this repository. See the setup instructions below for how to obtain and place the data files before running any analysis.

Example data location:
data/raw/admissions.csv

```bash
python -m venv .venv

# Activate — choose the command for your OS:
# Mac / Linux:      source .venv/bin/activate
# Windows Git Bash: source .venv/Scripts/activate
# Windows CMD:      .venv\Scripts\activate.bat
# Windows PowerShell: .venv\Scripts\Activate.ps1

pip install -r requirements.txt
python test_environment.py    # should print "Environment OK"
```

---

## Contributing

- Branch naming: `setup/`, `feature/`, `fix/`
- Open a PR to `main` for all changes
- Commit messages: imperative mood, ≤ 50 characters

---

*Starter file for Lab 1 — lab-1-git-workflows | aispire-14005*
## Setup Instructions

Clone the repository:

git clone <repository-url>

Move into the project folder:

cd m1-l1-git-workflows-RahafAlmanaseer

Create virtual environment:

python -m venv .venv

Install requirements:

pip install -r requirements.txt