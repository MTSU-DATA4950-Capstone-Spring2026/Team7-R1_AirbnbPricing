# [Project Name] - Team [X]

**DATA 4950 Data Science Capstone | Spring 2026**

**Team Members:** [List your names here]

---

## Project Overview

[Write 2-3 sentences describing your project. What problem are you solving? What data are you using?]

## Dataset

| Item | Description |
|------|-------------|
| **Source** | [Where did you get the data?] |
| **Size** | [How many rows and columns?] |
| **Target Variable** | [What are you predicting?] |
| **Task Type** | [Classification / Regression] |

## Repository Structure

```
├── README.md              ← You are here
├── LICENSE                ← MIT License
├── requirements.txt       ← Python packages needed
├── data/
│   ├── raw/              ← Original, unmodified data
│   └── processed/        ← Cleaned data for modeling
├── notebooks/
│   ├── 01_eda.ipynb                 ← Exploratory Data Analysis
│   ├── 02_data_preprocessing.ipynb  ← Data Cleaning & Preparation
│   ├── 03_feature_engineering.ipynb ← Feature Engineering & Pipelines
│   ├── 04_modeling.ipynb            ← Model Training & Selection
│   └── 05_evaluation.ipynb          ← Model Evaluation & Interpretation
├── reports/              ← Final reports and presentations
└── figures/              ← Saved plots and visualizations
```

## Setup Instructions

### 1. Clone the Repository
- Open **GitHub Desktop**
- Click **File → Clone Repository**
- Select your team's repository
- Choose local path and click **Clone**

### 2. Install Dependencies
- Open **Anaconda Prompt** (Windows) or **Terminal** (Mac)
- Navigate to your project folder
- Run: `pip install -r requirements.txt`

### 3. Run Notebooks
- Open **Anaconda Navigator**
- Launch **Jupyter Notebook**
- Navigate to the `notebooks/` folder

## Progress Tracker

| Deliverable | Due Date | Status |
|-------------|----------|--------|
| Project Charter & Data Acquisition Plan | End of Week 5 | ⬜ Not Started |
| Exploratory Analysis & Data Preparation Report | End of Week 9 | ⬜ Not Started |
| Peer Review 1 (Data Readiness Check) | Week 10 | ⬜ Not Started |
| Model Development & Evaluation Report | End of Week 12 | ⬜ Not Started |
| Peer Review 2 (Modeling Progress Check) | Week 13 | ⬜ Not Started |
| Final Presentation | Week 15 | ⬜ Not Started |
| Final Report & GitHub Repository | Week 15 + 5 days | ⬜ Not Started |

## Key Findings

*[Update this section as you discover insights from your analysis]*

1. Finding 1: ...
2. Finding 2: ...
3. Finding 3: ...

## Git Workflow for Team Collaboration

### Current Phase: EDA & Data Preparation

During the early stages of the project (EDA and data preparation), use this simple workflow:

**Before you start working:**
1. Open **GitHub Desktop**
2. Click **Fetch origin**
3. Click **Pull origin** (if available)

**After you make changes:**
1. Open **GitHub Desktop**
2. Review your changes in the left panel
3. Write a summary (e.g., "Add correlation analysis to EDA")
4. Click **Commit to main**
5. Click **Push origin**

> 💡 **Tip:** Communicate with your team! Let others know when you're working on a file to avoid conflicts.

---

### Future Phases: Feature Engineering & Modeling

As the project progresses to more complex development (feature engineering, modeling, evaluation), adopt a **feature branch workflow** to enable parallel development and code review:

**Creating a new branch:**
1. Open **GitHub Desktop**
2. Click **Current Branch** dropdown
3. Click **New Branch**
4. Name it descriptively (e.g., `feature/baseline-model`)
5. Click **Create Branch**

**Working on your branch:**
1. Make your changes in the project files
2. In GitHub Desktop, write a summary
3. Click **Commit to [your-branch-name]**
4. Click **Publish branch** (first time) or **Push origin**

**Creating a Pull Request:**
1. In GitHub Desktop, click **Create Pull Request**
2. This opens GitHub in your browser
3. Add a description of your changes
4. Request review from team members
5. After approval, click **Merge**

**Recommended branch names:**
- `feature/feature-engineering`
- `feature/baseline-model`
- `feature/hyperparameter-tuning`
- `fix/data-cleaning-bug`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Course:** DATA 4950 - Data Science Capstone  
**Instructor:** Yanfang Liu  
**Institution:** Middle Tennessee State University
