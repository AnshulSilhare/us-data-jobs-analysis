# 📊 US Data Analyst Job Market Analysis

<div align="center">

![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-2.0+-green?style=for-the-badge&logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

**Comprehensive Python analysis of 100,000+ US Data Analyst job postings**

*Identifying in-demand skills, salary trends, and career opportunities through data*

[View Analysis](#key-findings) • [Explore Code](notebooks/) • [Connect on LinkedIn](https://www.linkedin.com/in/anshul-silhare)

</div>

---

## 🎯 The Question

**What skills do Data Analyst employers ACTUALLY want in 2025?**

Everyone has opinions. I wanted data.

So I analyzed 100,000+ real job postings to find out.

---

## 🔍 Key Findings

### 📌 Finding #1: SQL Still Dominates

<div align="center">
<img src="images/02_skills_analysis/skills_likelihood_percentage.png" width="800" alt="Skills Demand Analysis">
</div>

**The Data:**
- **SQL**: 51% of Data Analyst jobs (Foundation skill)
- **Excel**: 41% of jobs (Still very relevant)
- **Tableau**: 28% of jobs (Visualization leader)
- **Python**: 27% of jobs (Growing rapidly)

**Key Insight:** SQL appears in nearly **2x more jobs** than Python. If you're learning one skill first, start with SQL.

---

### 📌 Finding #2: Degrees Are Optional

<div align="center">
<img src="images/01_market_overview/benefits_analysis.png" width="800" alt="Benefits and Requirements Analysis">
</div>

**72% of Data Analyst jobs don't explicitly require a formal degree.**

This validates the shift toward **skills-based hiring**. For students and career changers: **Skills > Credentials**.

**Additional Benefits Data:**
- 7.5% offer remote work
- 35.5% offer health insurance
- Degree requirement declining year-over-year

---

### 📌 Finding #3: The Optimal Skills Sweet Spot

<div align="center">
<img src="images/05_optimal_skills/optimal_skills_scatter.png" width="800" alt="Optimal Skills Analysis">
</div>

**Best ROI Skills (High Demand + High Salary):**

| Skill | Demand | Median Salary | Strategy |
|-------|--------|---------------|----------|
| **Python** | 33% | $98K | Highest salary premium |
| **Tableau** | 28% | $93K | Best visualization ROI |
| **SQL** | 60% | $91K | Widest demand |

**Learning Strategy:** SQL (foundation) → Python (salary boost) → Tableau (specialization)

---

### 📌 Finding #4: Salary Progression Path

<div align="center">
<img src="images/04_salary_analysis/salary_by_role.png" width="800" alt="Salary Distribution by Role">
</div>

**Clear Career Ladder:**
- Data Analyst: $85K median
- Senior Data Analyst: $110K median
- Data Scientist: $135K median
- Senior Data Scientist: $155K median

**Insight:** 45% salary increase from Analyst → Senior Analyst. Skills investment pays off.

---

## 🛠️ Technologies Used

<div align="center">

| Category | Tools |
|----------|-------|
| **Language** | Python 3.13 |
| **Data Analysis** | pandas, numpy |
| **Visualization** | matplotlib, seaborn |
| **Environment** | Jupyter Notebook |
| **Data Source** | Hugging Face Datasets |

</div>

---

## 📁 Project Structure

```
📦 us-data-jobs-analysis
│
├── 📂 notebooks/
│   ├── 1_EDA_Intro.ipynb              # Exploratory Data Analysis
│   ├── 2_Skills_Count.ipynb           # Skills demand analysis
│   ├── 3_Skills_Trend.ipynb           # Trending skills over time
│   ├── 4_Salary_Analysis.ipynb        # Salary by skill & role
│   └── 5_Optimal_Skills.ipynb         # High-demand + high-pay skills
│
├── 📂 images/
│   ├── 01_market_overview/            # Job market visualizations
│   ├── 02_skills_analysis/            # Skills demand charts
│   ├── 03_skills_trends/              # Monthly trend analysis
│   ├── 04_salary_analysis/            # Salary distribution charts
│   └── 05_optimal_skills/             # ROI skill analysis
│
├── 📄 requirements.txt                 # Python dependencies
└── 📄 README.md                        # This file
```

---

## 🚀 Quick Start

### Prerequisites
- Python 3.9+
- pip package manager

### Installation

**1. Clone the repository:**
```bash
git clone https://github.com/AnshulSilhare/us-data-jobs-analysis.git
cd us-data-jobs-analysis
```

**2. Install dependencies:**
```bash
pip install -r requirements.txt
```

**3. Launch Jupyter:**
```bash
jupyter notebook
```

**4. Open any notebook** in the `notebooks/` folder and run cells sequentially.

---

## 📊 Analysis Overview

### Notebook 1: Market Landscape
- Dataset exploration (100,000+ rows)
- US Data Analyst job filtering
- Remote work analysis (7.5% of jobs)
- Degree requirements (72% don't require)
- Top hiring companies (Robert Half, Insight Global)

### Notebook 2: Skills Demand
- Skill extraction from job postings
- Top 10 most requested skills
- Role comparison (Analyst vs Engineer vs Scientist)
- Demand percentages by skill

### Notebook 3: Skills Trends
- Month-over-month skill trends (2023)
- SQL dominance over time
- Power BI vs Tableau competition
- Emerging vs declining skills

### Notebook 4: Salary Analysis
- Salary distribution by role
- Impact of degree on salary (minimal)
- Highest-paying skills (Python: $98K)
- Salary by seniority level

### Notebook 5: Optimal Skills
- Demand vs salary scatter plot
- "Sweet spot" skill identification
- ROI analysis for learning
- Career path recommendations

---

## 💡 Key Learnings

### Technical Skills Gained:
✅ **pandas mastery**: `groupby()`, `explode()`, `merge()`, lambda functions  
✅ **Data cleaning**: Handling nested lists, missing values, datetime conversion  
✅ **Statistical analysis**: Medians, percentiles, distribution analysis  
✅ **Visualization**: Publication-quality charts with matplotlib & seaborn  

### Data Insights:
✅ **SQL > Python** for Data Analyst roles (2x more demand)  
✅ **Degrees becoming optional** (72% don't require)  
✅ **Python = highest salary premium** (+15% vs average)  
✅ **Tableau leads BI tools** (31% vs Power BI 18%)  

### Project Management:
✅ Breaking analysis into modular notebooks  
✅ Documenting findings as insights, not just numbers  
✅ Creating reproducible workflows  

---

## 🎓 About This Project

**Background:**
- My **first Python data analysis project**
- Completed as part of PGDM in Research & Business Analytics at WeSchool
- Built to make data-driven career decisions instead of guessing

**Timeline:**
- Learning Python basics: 1 week
- Building analysis: 1.5 weeks
- Total project time: ~2.5 weeks

**What I'd Do Differently:**
- Add interactive visualizations (Plotly/Dash)
- Include statistical significance testing
- Perform geographic salary analysis
- Build Streamlit dashboard
- Add time-series forecasting

---

## 📫 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/anshul-silhare)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/AnshulSilhare)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:your.email@example.com)

**Currently seeking Data Analyst / Business Analyst roles**

</div>

---

## 📈 Results Summary

<div align="center">

| Metric | Finding |
|--------|---------|
| **Top Skill** | SQL (51% of jobs) |
| **Highest Salary** | Python ($98K median) |
| **Best ROI** | Python (high pay + growing demand) |
| **Degree Requirement** | 72% don't require |
| **Remote Work** | 7.5% offer |
| **Career Growth** | 45% raise Analyst→Senior |

</div>

---

## 🙏 Acknowledgments

- **Dataset:** [Luke Barousse](https://www.lukebarousse.com/) for the comprehensive Data Jobs dataset
- **Inspiration:** Making data-driven career decisions
- **Community:** Python & Data Analytics community on LinkedIn

---

## 🔮 Future Enhancements

- [ ] Interactive Plotly visualizations
- [ ] Streamlit dashboard for exploration
- [ ] Geographic salary analysis (state-by-state)
- [ ] Company-specific insights (FAANG vs others)
- [ ] Skills co-occurrence analysis
- [ ] Time-series forecasting for skill demand
- [ ] Automated job scraping pipeline

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**⭐ If you found this analysis helpful, please star this repository!**

**Built with 🐍 Python | 📊 Data | 💡 Insights**

*Analysis by [Anshul Silhare](https://www.linkedin.com/in/anshul-silhare) | PGDM Student | WeSchool*

</div>
