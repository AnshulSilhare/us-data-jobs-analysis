# 📊 US Data & Business Analyst Job Market Analysis

![Python](https://img.shields.io/badge/Python-3.13-blue)
![pandas](https://img.shields.io/badge/pandas-2.0+-green)
![matplotlib](https://img.shields.io/badge/matplotlib-3.0+-orange)
![Status](https://img.shields.io/badge/Status-Complete-success)

> Comprehensive Python analysis of 100,000+ US Data & Business Analyst job postings to identify in-demand skills, salary trends, and market opportunities.

---

## 🎯 Project Overview

This project analyzes real-world job market data to answer critical questions for aspiring Data Analysts:

- **What skills are employers actually looking for?**
- **Which skills command the highest salaries?**
- **Is a formal degree still required?**
- **What are the trending skills in 2023?**
- **What's the optimal skill combination for career growth?**

**Key Finding:** 51% of Data Analyst jobs don't explicitly require a degree — skills matter more than credentials.

---

## 📈 Key Insights

### Top 5 Most Demanded Skills

![Top Skills](images/top_skills_demand.png)

1. **SQL** - 51% of postings (Foundation skill)
2. **Excel** - 41% of postings (Still relevant)
3. **Python** - 36% of postings (Growing fast)
4. **Tableau** - 31% of postings (Visualization leader)
5. **Power BI** - 18% of postings (Emerging)

### Salary Premium by Skill

![Salary Analysis](images/salary_by_skill.png)

- Jobs requiring **SQL**: +17% average salary
- Jobs requiring **Python**: +15% average salary
- Jobs requiring **Tableau**: +12% average salary

### Market Trends

- **51%** of jobs don't require a formal degree
- **13%** offer remote work
- **28%** offer health insurance
- Average salary: **$79,000**

---

## 🛠️ Tools & Technologies

**Programming:**
- Python 3.13
- Jupyter Notebook

**Libraries:**
- `pandas` - Data manipulation & analysis
- `matplotlib` - Static visualizations
- `seaborn` - Statistical data visualization
- `datasets` (Hugging Face) - Data source

**Data Source:**
- [Luke Barousse's Data Jobs Dataset](https://huggingface.co/datasets/lukebarousse/data_jobs)
- 100,000+ real job postings from 2023

---

## 📁 Project Structure
```
📦 us-data-jobs-analysis
├── 📂 notebooks/
│   ├── 1_EDA_Intro.ipynb           # Exploratory Data Analysis
│   ├── 2_Skills_Count.ipynb        # Skills demand analysis
│   ├── 3_Skills_Trend.ipynb        # Trending skills over time
│   ├── 4_Salary_Analysis.ipynb     # Salary by skill & role
│   └── 5_Optimal_Skills.ipynb      # High-demand + high-pay skills
├── 📂 images/                       # Chart screenshots
├── 📄 requirements.txt              # Python dependencies
├── 📄 .gitignore                    # Excluded files
└── 📄 README.md                     # This file
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- pip (Python package manager)

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/YOUR_USERNAME/us-data-jobs-analysis.git
cd us-data-jobs-analysis
```

2. **Install dependencies:**
```bash
pip install -r requirements.txt
```

3. **Launch Jupyter Notebook:**
```bash
jupyter notebook
```

4. **Open any notebook** in the `notebooks/` folder and run cells sequentially.

---

## 📊 Analysis Workflow

### 1. Exploratory Data Analysis (`1_EDA_Intro.ipynb`)
- Dataset overview & cleaning
- Remote work analysis
- Benefits analysis (degree requirements, health insurance)
- Top hiring companies

### 2. Skills Demand (`2_Skills_Count.ipynb`)
- Skill frequency by job role
- Top 10 most demanded skills
- Role-specific skill requirements

### 3. Skills Trends (`3_Skills_Trend.ipynb`)
- Month-over-month skill trends
- Growing vs declining skills
- Seasonal hiring patterns

### 4. Salary Analysis (`4_Salary_Analysis.ipynb`)
- Median salary by skill
- Salary distribution by role
- Premium for specific skill combinations

### 5. Optimal Skills (`5_Optimal_Skills.ipynb`)
- Skills with high demand + high salary
- Career growth recommendations
- Skill learning priority matrix

---

## 💡 Key Learnings

### Technical Learnings:
- Mastered **pandas** for data manipulation (groupby, merge, explode)
- Created publication-ready visualizations with **matplotlib** & **seaborn**
- Handled nested lists in datasets (skill extraction)
- Performed statistical analysis (percentiles, medians, trends)

### Business Learnings:
- **Skills-based hiring** is replacing degree requirements
- **SQL remains the #1 foundational skill** for data roles
- **Python + SQL combination** offers the highest salary premium
- **Remote work** is less common (13%) than expected for data roles

### Project Management:
- Structured analysis into modular notebooks
- Documented findings as insights, not just numbers
- Created reproducible analysis pipeline

---

## 🎓 About This Project

This is my **first Python data analysis project**, completed as part of my learning journey in transitioning to Data Analytics. 

**Background:**
- PGDM student specializing in Business Analytics & Operations
- Previously worked with SQL and Power BI
- This project marks my entry into Python for data analysis

**What I'd Do Differently:**
- Add interactive visualizations (Plotly)
- Include hypothesis testing (statistical significance)
- Create automated report generation
- Build a dashboard (Streamlit/Dash)

---

## 📫 Connect With Me

- **LinkedIn:** [Your LinkedIn URL]
- **Email:** your.email@example.com
- **Portfolio:** [Your portfolio website] *(optional)*

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Dataset:** [Luke Barousse](https://www.lukebarousse.com/) for the comprehensive data jobs dataset
- **Inspiration:** Exploring real-world data to make informed career decisions
- **Community:** Python & Data Analytics community on LinkedIn

---

## 📌 Future Enhancements

- [ ] Add interactive Plotly visualizations
- [ ] Create Streamlit dashboard for exploration
- [ ] Perform geographic salary analysis by state
- [ ] Add time-series forecasting for skill demand
- [ ] Include company-specific insights (FAANG vs others)

---

**⭐ If you found this analysis helpful, please star this repository!**
```

**Save/Commit this README**

---

### **STEP 5: Create requirements.txt**

**Click "Add file" → "Create new file"**

**Filename:** `requirements.txt`

**Content:**
```
pandas>=2.0.0
matplotlib>=3.7.0
seaborn>=0.12.0
datasets>=2.14.0
jupyter>=1.0.0
```

**Commit the file**

---

### **STEP 6: Final Touches**

**1. Add Topics to Repository**

- Go to your repository homepage
- Click ⚙️ (settings icon) next to "About" section on right
- Add topics (keywords for discovery):
  - `python`
  - `data-analysis`
  - `pandas`
  - `data-science`
  - `job-market`
  - `career-analysis`
  - `jupyter-notebook`
  - `data-visualization`

**2. Pin Repository to Your Profile**

- Go to your GitHub profile
- Click "Customize your pins"
- Select this repository
- It will appear at the top of your profile

---

## ✅ **YOUR FINAL REPOSITORY WILL LOOK LIKE:**

**Homepage Preview:**
```
📊 US Data & Business Analyst Job Market Analysis
[Badges: Python 3.13 | pandas 2.0+ | Status: Complete]

Comprehensive analysis of 100,000+ job postings

[Preview of top skills chart]

⭐ Star   🔱 Fork   📁 5 notebooks   📊 4 images
```

**What Makes This "Gold Level":**

✅ **Professional README** with badges, structure, clear sections  
✅ **Visual proof** (charts embedded in README)  
✅ **Clear documentation** (how to run, what you learned)  
✅ **Reproducible** (requirements.txt, installation steps)  
✅ **Organized structure** (folders, clear naming)  
✅ **Business value** (key insights upfront, not just code)  
✅ **Learning transparency** (what you'd improve)  
✅ **Professional touches** (license, acknowledgments, future work)  
✅ **SEO optimized** (topics, clear descriptions)  
✅ **Recruiter-friendly** (non-technical summary, clear findings)  

---

## 🎯 **WHAT TO DO RIGHT NOW (30-Minute Checklist)**

### **Tonight (Before Bed):**

**Phase 1: Repository Setup (10 mins)**
- [ ] Create GitHub repository with settings above
- [ ] Add MIT License
- [ ] Add Python .gitignore

**Phase 2: Upload Files (10 mins)**
- [ ] Upload all 5 notebooks to `notebooks/` folder
- [ ] Take 4 screenshots of your best charts
- [ ] Upload screenshots to `images/` folder

**Phase 3: Documentation (10 mins)**
- [ ] Replace README with my template above
- [ ] Add your LinkedIn URL to README
- [ ] Add your email to README
- [ ] Create requirements.txt file
- [ ] Add topics to repository

**Phase 4: Polish**
- [ ] Pin repository to your profile
- [ ] Make sure all images display in README
- [ ] Test that repository looks good on mobile

---

## 📱 **AFTER YOU FINISH, YOUR LINKEDIN FIRST COMMENT WILL BE:**
```
Full Python project on GitHub:
👉 github.com/YOUR_USERNAME/us-data-jobs-analysis

The repository includes:
✅ 5 Jupyter notebooks with complete analysis
✅ Visualizations of top skills & salary trends
✅ Fully documented code & methodology
✅ Reproducible with requirements.txt

Not perfect code. But production-ready code.

For anyone learning Python: Build in public. Ship messy. Improve later.

What helped YOU learn Python? Drop recommendations below.
