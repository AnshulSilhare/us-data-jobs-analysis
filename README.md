# 📊 US Data Analyst Job Market Analysis

<div align="center">

![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

### *Comprehensive Python analysis of 100,000+ US Data Analyst job postings*

**What skills do employers actually want? | Which skills pay the most? | Is a degree still required?**

**I analyzed the data to find out.**

[📊 View Analysis](#-key-findings) • [💻 Explore Code](notebooks/) • [🤝 Connect on LinkedIn](https://www.linkedin.com/in/anshul-silhare)

</div>

---

## 🎯 Project Motivation

As a PGDM student in Research & Business Analytics at WeSchool, I faced a critical question:

**"What skills should I prioritize to maximize my career opportunities in Data Analytics?"**

Everyone had opinions. Tutorials said "learn Python." Forums said "master Tableau." Advisors said "get a degree first."

**I wanted data, not opinions.**

So I built my first end-to-end Python project to analyze 100,000+ real job postings and let the numbers decide.

**This repository documents what I found.**

---

## 🔍 Research Questions

1. **What are the most in-demand skills for Data Analysts?**
2. **How do skill requirements differ across Data Analyst, Engineer, and Scientist roles?**
3. **Is a formal degree still required in 2025?**
4. **Which skills command the highest salaries?**
5. **How are skill trends evolving over time?**
6. **What's the optimal skill combination for high demand + high pay?**
7. **Which companies are actively hiring Data Analysts?**
8. **How common is remote work for Data Analyst positions?**

---

## 📊 Dataset Overview

**Source:** [Hugging Face - Luke Barousse Data Jobs Dataset](https://huggingface.co/datasets/lukebarousse/data_jobs)

**Scale:**
- **Total Records:** 785,741 job postings
- **US Data Analyst Jobs:** 30,000+ postings
- **Time Period:** 2023 (full year)
- **Data Points:** Job titles, skills, salaries, locations, companies, benefits, requirements

**Data Processing:**
- Cleaned nested skill lists using `pandas.explode()`
- Converted date formats for time-series analysis
- Filtered by country (US) and role (Data Analyst)
- Handled missing values and outliers

---

## 📈 Key Findings

### 1️⃣ The Data Analyst Job Landscape

<div align="center">
<img src="images/01_market_overview/top_data_roles.png" width="850" alt="Top 5 Data Roles by Postings">
</div>

**Most Common Data Roles in the US:**
- **Data Engineer:** 230,000+ postings (highest demand)
- **Data Analyst:** 225,000+ postings (nearly equal demand)
- **Data Scientist:** 205,000+ postings
- **Business Analyst:** 48,000+ postings
- **Software Engineer:** 42,000+ postings

**Insight:** Data Analyst and Data Engineer roles dominate the market. If you're entering the field, these are the paths with the most opportunities.

---

### 2️⃣ Who's Hiring Data Analysts?

<div align="center">
<img src="images/01_market_overview/top_hiring_companies.png" width="850" alt="Top 10 Hiring Companies">
</div>

**Top 10 Companies Posting Data Analyst Jobs:**
1. **Robert Half** - 970+ postings
2. **Insight Global** - 810+ postings
3. **Dice** - 620+ postings
4. **UnitedHealth Group** - 510+ postings
5. **Get It Recruit** - 505+ postings

**Strategic Insight:** Recruitment agencies (Robert Half, Insight Global, Dice) dominate Data Analyst hiring. Consider working with these agencies for faster job placement, especially for entry-level roles.

---

### 3️⃣ SQL Dominates - Python Is Overrated (For Data Analysts)

<div align="center">
<img src="images/02_skills_analysis/skills_likelihood_percentage.png" width="850" alt="Skills Likelihood by Role">
</div>

**For Data Analyst Roles:**
- **SQL**: 51% of job postings
- **Excel**: 41% of postings
- **Tableau**: 28% of postings
- **Python**: 27% of postings
- **SAS**: 19% of postings

**For Data Engineer Roles:**
- **SQL**: 68% (even higher than Analysts)
- **Python**: 65% (critical for Engineers)
- **AWS**: 43%

**For Data Scientist Roles:**
- **Python**: 72% (essential)
- **SQL**: 51%
- **R**: 44%

**Critical Insight:** 

**SQL appears in 2x more Data Analyst jobs than Python.**

If you're entering Data Analytics (not Data Science or Engineering), **SQL is your foundation, not Python.** The internet overemphasizes Python because it's trendy, but the job market tells a different story.

**My Learning Strategy Based on This Data:**
1. **SQL first** (51% demand - foundation)
2. **Excel second** (41% demand - still essential)
3. **Tableau/Power BI third** (28% demand - visualization)
4. **Python fourth** (27% demand - salary booster)

---

### 4️⃣ Skills Differ Dramatically by Role

<div align="center">
<img src="images/02_skills_analysis/skills_count_by_role.png" width="850" alt="Top Skills Count by Role">
</div>

**Role-Specific Skill Patterns:**

**Data Analyst:**
- SQL (35,000 mentions)
- Excel (27,000 mentions)
- Tableau (20,000 mentions)
- Python (19,000 mentions)

**Data Engineer:**
- SQL (25,000 mentions)
- Python (24,000 mentions)
- AWS (13,000 mentions)
- Azure (10,000 mentions)
- Spark (10,000 mentions)

**Data Scientist:**
- Python (40,000 mentions - dominates)
- SQL (30,000 mentions)
- R (27,000 mentions)
- SAS (15,000 mentions)

**Career Path Insight:** 

Choose your role based on your skill preferences:
- **Love SQL + Excel + Dashboards?** → Data Analyst
- **Love Python + Cloud + Engineering?** → Data Engineer  
- **Love Python + Statistics + ML?** → Data Scientist

---

### 5️⃣ Degrees Are Becoming Optional (72% Don't Require)

<div align="center">
<img src="images/01_market_overview/benefits_analysis.png" width="850" alt="Benefits Analysis - Degree Requirements">
</div>

**Job Requirements & Benefits Breakdown:**

**Degree Requirement:**
- **72% of jobs DON'T explicitly require a formal degree**
- 28% require or prefer a degree

**Remote Work:**
- Only 7.5% offer remote work
- 92.5% require in-office or hybrid

**Health Insurance:**
- 35.5% offer health insurance
- 64.5% don't mention it

**The Shift to Skills-Based Hiring Is Real.**

For PGDM/MBA students like me: Don't rely on the degree alone. **Build the portfolio. Demonstrate the skills.** The credential opens doors, but skills get you hired.

**This finding changed my approach:** Instead of waiting to finish my degree before job hunting, I'm building projects NOW to show competence.

---

### 6️⃣ Remote Work Is Rare (Reality Check)

<div align="center">
<img src="images/01_market_overview/remote_work_percentage.png" width="850" alt="Remote Work Opportunities">
</div>

**Remote Work by Role:**
- **Business Analyst:** 8.3% offer remote
- **Data Analyst:** 7.5% offer remote

**Expectation vs Reality:**

Many people enter Data Analytics expecting remote flexibility. The data shows otherwise.

**Only 7.5% of Data Analyst jobs offer remote work.**

Most companies (92%+) still want you in the office, at least part-time. If remote work is non-negotiable for you, you're limiting yourself to <10% of opportunities.

**Personal Takeaway:** I'm optimizing for skills and salary, not remote work. Wider opportunities > location flexibility at this career stage.

---

### 7️⃣ Geographic Concentration - Where the Jobs Are

<div align="center">
<img src="images/01_market_overview/job_locations.png" width="850" alt="Job Locations for Data Analysts">
</div>

**Top 10 Locations for Data Analyst Jobs:**
1. **"Anywhere"** - 5,200+ jobs (remote-friendly postings)
2. **New York, NY** - 3,100+ jobs
3. **Atlanta, GA** - 2,600+ jobs
4. **Chicago, IL** - 2,400+ jobs
5. **Austin, TX** - 2,000+ jobs
6. **Dallas, TX** - 1,900+ jobs
7. **Washington, DC** - 1,600+ jobs

**Strategic Insight:** If you're willing to relocate, **New York, Atlanta, and Chicago** offer the most opportunities. If you want remote work, "Anywhere" postings are your best bet (though only 7.5% of total market).

---

### 8️⃣ Skills Are Evolving - Trends Over Time

<div align="center">
<img src="images/03_skills_trends/trending_skills_2023.png" width="850" alt="Trending Skills 2023">
</div>

**2023 Monthly Skill Trends:**

**Stable (Foundation Skills):**
- **SQL:** 55-60% consistently (rock-solid demand)
- **Excel:** 40-43% (slight decline but still essential)

**Growing (Emerging Skills):**
- **Python:** 31% → 35% (+13% growth)
- **Tableau:** Stable at 28-30%

**Rising (Fastest Growth):**
- **Power BI:** 18% → 22% (+22% growth rate)

**Key Insight:** 

While Python and Power BI are growing, **SQL hasn't budged from its dominant position.** It's not a legacy skill being replaced - it's the *permanent foundation* of data work.

**Implication for Learning:** Don't skip SQL to jump straight to Python. SQL isn't going anywhere.

---

### 9️⃣ The BI Tool Battle: Tableau vs Power BI

<div align="center">
<img src="images/03_skills_trends/powerbi_vs_tableau_trend.png" width="850" alt="Power BI vs Tableau Demand">
</div>

**Tableau vs Power BI - 2023 Trends:**

**Tableau:**
- Demand: 30-35% of jobs
- Status: Current market leader
- Growth: Stable

**Power BI:**
- Demand: 18-23% of jobs  
- Status: Fast-growing challenger
- Growth: +22% year-over-year

**Strategic Decision:**

**Tableau** has larger market share *now*. **Power BI** is growing *faster*.

**My Strategy:** Learn **Power BI first** (I already have access through university), then add Tableau. By the time I'm job hunting in 6 months, Power BI's share will be even larger.

If you have to pick one: **Power BI** for growth trajectory, **Tableau** for current opportunities.

**Best option:** Learn both (they're similar enough that mastering one makes learning the other quick).

---

### 🔟 Salary Distribution by Role (The Career Ladder)

<div align="center">
<img src="images/04_salary_analysis/salary_by_role.png" width="850" alt="Salary Distribution by Role">
</div>

**Median Salaries by Role & Seniority:**

| Role | Median Salary | 25th %ile | 75th %ile |
|------|---------------|-----------|-----------|
| **Senior Data Scientist** | $155,000 | $130K | $190K |
| **Senior Data Engineer** | $145,000 | $125K | $175K |
| **Data Scientist** | $135,000 | $110K | $165K |
| **Data Engineer** | $120,000 | $95K | $145K |
| **Senior Data Analyst** | $111,000 | $95K | $130K |
| **Data Analyst** | $85,000 | $70K | $105K |

**Career Progression Insight:**

**Junior → Senior Data Analyst = +30% salary ($85K → $111K)**

**Senior Data Analyst → Data Scientist = +22% salary ($111K → $135K)**

**Clear growth path exists.** Start as Analyst, grow to Senior Analyst, transition to Scientist/Engineer for $130K+ salaries.

**Time to Senior:** Typically 3-5 years with proven skills.

---

### 1️⃣1️⃣ Salary Impact: Degree vs No Degree

<div align="center">
<img src="images/04_salary_analysis/degree_vs_no_degree_salary.png" width="850" alt="Degree vs No Degree Salary">
</div>

**Salary Comparison:**

**Jobs Requiring Degree:**
- Median: $122,000
- Range: $90K - $150K

**Jobs NOT Requiring Degree:**
- Median: $110,000
- Range: $85K - $140K

**Difference: Only ~10%**

**The Surprising Truth:**

Jobs that don't require a degree pay *almost the same* as jobs that do require one. The salary gap is **much smaller than expected.**

**What matters more than the degree:**
- **Skills you can demonstrate** (GitHub, portfolio projects)
- **Years of experience**
- **Specific technical skills** (Python, SQL, cloud)

**For students:** Your degree gives you structure and credibility, but **skills get you paid.** Don't coast on the degree alone.

---

### 1️⃣2️⃣ Salary Progression by Seniority

<div align="center">
<img src="images/04_salary_analysis/salary_progression_seniority.png" width="850" alt="Salary Progression by Seniority">
</div>

**Clear Salary Ladder:**

**Junior Level:**
- Median: $115,000
- Range: $90K - $145K

**Mid-Level / Unspecified:**
- Median: $85,000  
- Range: $70K - $105K

**Senior Level:**
- Median: $135,000
- Range: $110K - $165K

**Return on Experience:**

**Mid → Senior = +59% salary increase**

**Each year of experience at the senior level is worth ~$10K-15K more.**

**Implication:** Don't job-hop too early. Invest 3-5 years building senior-level expertise before optimizing for title/salary. The jump from mid → senior is *massive*.

---

### 1️⃣3️⃣ Which Skills Pay the Most?

<div align="center">
<img src="images/04_salary_analysis/top_paying_skills.png" width="850" alt="Top 10 Highest Paid vs In-Demand Skills">
</div>

**Top 10 Highest-Paid Skills (Niche, Specialized):**
1. **dplyr** - $200K median (R data manipulation)
2. **bitbucket** - $189K (version control)
3. **gitlab** - $184K (DevOps)
4. **solidity** - $179K (blockchain)
5. **hugging face** - $175K (AI/ML)

**Top 10 Most In-Demand Skills (Broad, Foundational):**
1. **Python** - $98K median, 45,000 jobs
2. **Tableau** - $93K median, 40,000 jobs
3. **R** - $92K median, 38,000 jobs
4. **SQL Server** - $92K median, 35,000 jobs
5. **SQL** - $91K median, 60,000 jobs

**The Strategic Trade-off:**

**Niche skills** (dplyr, solidity, hugging face) pay $175K-200K but have **very few jobs** (<1,000 postings each).

**Core skills** (Python, SQL, Tableau) pay $91K-98K but have **massive demand** (30K-60K jobs each).

**Career Strategy Decision:**

**Early Career (Years 0-3):** Focus on **high-demand skills** (SQL, Python, Tableau). Get hired first, maximize opportunities.

**Mid Career (Years 3-7):** Add **niche specialization** (cloud, AI/ML, DevOps) on top of foundation. Boost salary.

**Senior Career (Years 7+):** Leverage **rare expertise** in niche + broad skills for $150K-200K+ roles.

**Don't learn rare skills first.** Build the foundation (SQL, Python), then specialize.

---

### 1️⃣4️⃣ The Optimal Skills Sweet Spot

<div align="center">
<img src="images/05_optimal_skills/optimal_skills_scatter.png" width="850" alt="Most Optimal Skills - Demand vs Salary">
</div>

**The Optimal Skills Quadrant (High Demand + High Salary):**

**Top-Right Quadrant (Best ROI):**
- **Python**: 33% demand, $98K salary (★ BEST overall)
- **Tableau**: 28% demand, $93K salary
- **SQL**: 60% demand, $91K salary (★ WIDEST opportunity)

**Why These 3 Skills Win:**

**SQL (60% demand, $91K):**
- Highest demand of ANY skill
- Foundation for all data work
- $91K median (above average)
- **Strategy:** Learn FIRST

**Python (33% demand, $98K):**
- Highest salary of common skills
- Growing 13% year-over-year  
- Versatile (analysis, ML, automation)
- **Strategy:** Learn SECOND

**Tableau (28% demand, $93K):**
- Leading visualization tool
- $93K median (above average)
- High demand in BI roles
- **Strategy:** Learn THIRD

**My Learning Roadmap Based on This Analysis:**
1. **SQL** (foundation, 60% demand) ✓ Already strong
2. **Python** (salary boost, 33% demand) ✓ This project
3. **Power BI/Tableau** (specialization, 28% demand) → Next 2 months

**Expected Outcome:** 
With SQL + Python + Tableau, I'm qualified for **60% of Data Analyst jobs** and positioned for **$93K-98K salary** at entry level.

---

### 1️⃣5️⃣ Operations & Supply Chain Analytics (Bonus Insight)

<div align="center">
<img src="images/02_skills_analysis/operations_skills.png" width="850" alt="Operations Analytics Skills">
</div>

**Top Skills for Operations & Supply Chain Analysts:**
1. **SQL** - 47.3%
2. **Python** - 46.1%
3. **Excel** - 34.8%
4. **R** - 30.0%
5. **Tableau** - 26.7%

**Interesting Finding:**

Operations Analytics roles value **Python almost as much as SQL** (47% vs 46%), unlike general Data Analyst roles where SQL dominates 2:1.

**Why:** Operations Analytics often involves:
- Optimization algorithms (Python)
- Predictive modeling (Python/R)
- Supply chain simulation (Python)

**Personal Relevance:** My PGDM specialization is Operations & Business Analytics. This data validates why I chose to learn Python early - it's more critical in Ops than general analytics.

---

## 🛠️ Technical Stack

<div align="center">

| **Category** | **Technologies** |
|--------------|------------------|
| **Language** | Python 3.13 |
| **Data Analysis** | pandas 2.0+, numpy 1.24+ |
| **Visualization** | matplotlib 3.7+, seaborn 0.12+ |
| **Environment** | Jupyter Notebook |
| **Data Source** | Hugging Face Datasets API |
| **Version Control** | Git, GitHub |

</div>

---

## 📁 Repository Structure

```
📦 us-data-jobs-analysis
│
├── 📂 notebooks/
│   ├── 1_EDA_Intro.ipynb              # Market overview & benefits analysis
│   ├── 2_Skills_Count.ipynb           # Skills demand frequency by role
│   ├── 3_Skills_Trend.ipynb           # Monthly skill trends (2023)
│   ├── 4_Salary_Analysis.ipynb        # Salary distribution & premiums
│   └── 5_Optimal_Skills.ipynb         # ROI analysis (demand vs salary)
│
├── 📂 images/
│   ├── 01_market_overview/            # Market landscape charts
│   │   ├── top_data_roles.png
│   │   ├── top_hiring_companies.png
│   │   ├── benefits_analysis.png
│   │   ├── remote_work_percentage.png
│   │   └── job_locations.png
│   │
│   ├── 02_skills_analysis/            # Skills demand analysis
│   │   ├── skills_count_by_role.png
│   │   ├── skills_likelihood_percentage.png
│   │   └── operations_skills.png
│   │
│   ├── 03_skills_trends/              # Time-series trends
│   │   ├── trending_skills_2023.png
│   │   └── powerbi_vs_tableau_trend.png
│   │
│   ├── 04_salary_analysis/            # Compensation insights
│   │   ├── salary_by_role.png
│   │   ├── degree_vs_no_degree_salary.png
│   │   ├── top_paying_skills.png
│   │   └── salary_progression_seniority.png
│   │
│   └── 05_optimal_skills/             # Strategic analysis
│       └── optimal_skills_scatter.png
│
├── 📄 requirements.txt                 # Python dependencies
├── 📄 .gitignore                       # Excluded files
├── 📄 LICENSE                          # MIT License
└── 📄 README.md                        # This file
```

---

## 🚀 Getting Started

### Prerequisites

- **Python 3.9+** installed ([Download here](https://www.python.org/downloads/))
- **pip** package manager (included with Python)
- **Jupyter Notebook** (or JupyterLab)

### Installation & Setup

**1. Clone this repository:**
```bash
git clone https://github.com/AnshulSilhare/us-data-jobs-analysis.git
cd us-data-jobs-analysis
```

**2. Create a virtual environment (recommended):**
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Mac/Linux
python3 -m venv venv
source venv/bin/activate
```

**3. Install dependencies:**
```bash
pip install -r requirements.txt
```

**4. Launch Jupyter Notebook:**
```bash
jupyter notebook
```

**5. Open any notebook in `notebooks/` folder and run cells sequentially.**

---

## 📊 Analysis Methodology

### Notebook 1: Exploratory Data Analysis

**File:** `1_EDA_Intro.ipynb`

**Objectives:**
- Load and explore the dataset (785K+ total jobs)
- Filter to US Data Analyst positions (30K+ jobs)
- Analyze job benefits (remote work, health insurance, degree requirements)
- Identify top hiring companies and geographic distribution

**Key Techniques:**
- `pandas.read_csv()` with Hugging Face datasets
- Boolean filtering for US jobs: `df[df['country'] == 'US']`
- Value counts for categorical analysis
- Pie charts for benefit distribution

**Outputs:**
- 5 visualizations (companies, locations, benefits, remote work, roles)
- Summary statistics on job market landscape

---

### Notebook 2: Skills Demand Analysis

**File:** `2_Skills_Count.ipynb`

**Objectives:**
- Extract skills from nested lists in job postings
- Calculate skill frequency by role (Analyst vs Engineer vs Scientist)
- Determine skill likelihood percentages
- Compare skill requirements across roles

**Key Techniques:**
- `df.explode('job_skills')` to unnest skill lists
- `groupby()` + `size()` for skill counts
- Percentage calculations: `(skill_count / total_jobs) * 100`
- Multi-panel bar charts for role comparison

**Outputs:**
- 3 visualizations (skills by role, likelihood percentages, operations focus)
- Top 10 most demanded skills per role

---

### Notebook 3: Skills Trend Analysis

**File:** `3_Skills_Trend.ipynb`

**Objectives:**
- Analyze month-over-month skill demand trends (2023)
- Track SQL vs Python vs Excel evolution
- Compare Power BI vs Tableau growth rates
- Identify emerging vs declining skills

**Key Techniques:**
- `pd.to_datetime()` for date conversion
- `df.groupby(['month', 'skill']).size()` for time-series aggregation
- Line plots with multiple series
- Growth rate calculations

**Outputs:**
- 2 visualizations (trending skills, BI tool comparison)
- Monthly trend data for top 5 skills

---

### Notebook 4: Salary Analysis

**File:** `4_Salary_Analysis.ipynb`

**Objectives:**
- Analyze salary distribution by role and seniority
- Compare salaries: degree required vs no degree
- Identify highest-paying skills
- Map salary progression paths

**Key Techniques:**
- Box plots for distribution visualization
- Median calculations with `df.groupby().median()`
- Outlier detection using IQR method
- Dual-axis bar charts (salary vs demand)

**Outputs:**
- 4 visualizations (salary by role, degree impact, top skills, progression)
- Salary ranges (25th, 50th, 75th percentiles) by role

---

### Notebook 5: Optimal Skills Strategy

**File:** `5_Optimal_Skills.ipynb`

**Objectives:**
- Create demand vs salary scatter plot
- Identify "sweet spot" skills (high demand + high pay)
- Calculate ROI for learning each skill
- Provide career path recommendations

**Key Techniques:**
- Scatter plots with bubble sizes (skill importance)
- Quadrant analysis (demand vs salary axes)
- Color coding by skill category
- Labeling for top skills

**Outputs:**
- 1 comprehensive visualization (optimal skills quadrant)
- Strategic skill learning recommendations

---

## 💡 What I Learned

### Technical Skills Acquired

**Python & pandas Mastery:**
- ✅ `groupby()` for aggregation
- ✅ `explode()` for nested list handling
- ✅ `merge()` for joining datasets
- ✅ Lambda functions for custom transformations
- ✅ `apply()` for row-wise operations

**Data Cleaning:**
- ✅ Handling missing values (`dropna()`, `fillna()`)
- ✅ Date/time conversion (`pd.to_datetime()`)
- ✅ String parsing (`str.split()`, `ast.literal_eval()`)
- ✅ Outlier detection (IQR method)

**Statistical Analysis:**
- ✅ Median, mean, percentile calculations
- ✅ Distribution analysis (box plots, histograms)
- ✅ Trend analysis (time-series)
- ✅ Comparative statistics (role vs role)

**Data Visualization:**
- ✅ matplotlib fundamentals (figure, axes, subplots)
- ✅ seaborn for statistical plots
- ✅ Multi-panel visualizations (3+ charts)
- ✅ Color schemes and professional styling
- ✅ Annotations and labels for clarity

---

### Data Insights Gained

**Market Dynamics:**
- ✅ **SQL > Python** for Data Analyst roles (2:1 ratio)
- ✅ **Degrees becoming optional** (72% don't require)
- ✅ **Remote work is rare** (only 7.5% of jobs)
- ✅ **Recruitment agencies dominate hiring** (Robert Half, Insight Global)

**Skill Strategy:**
- ✅ **Foundation first** (SQL, Excel) before specialization (Python, Tableau)
- ✅ **Power BI growing faster** than Tableau (22% YoY growth)
- ✅ **Niche skills pay more** but have fewer opportunities
- ✅ **Core skills** (SQL, Python, Tableau) offer best ROI

**Salary Patterns:**
- ✅ **Junior → Senior = +30-45% salary jump**
- ✅ **Degree impact is minimal** (~10% salary difference)
- ✅ **Python adds 15% salary premium** vs average
- ✅ **Clear career ladder** exists (Analyst → Senior → Scientist)

---

### Project Management Lessons

**Planning:**
- ✅ **Start with questions, not tools** - I rewrote my analysis 3 times because I was solving the wrong problem initially
- ✅ **Modular structure** - Breaking analysis into 5 notebooks made debugging easier
- ✅ **Version control** - Git saved me when I accidentally overwrote a notebook

**Execution:**
- ✅ **Iterate fast** - First visualizations were ugly; refined over 3-4 iterations
- ✅ **Document as you go** - Markdown cells in notebooks made README writing easy
- ✅ **Reproducibility matters** - requirements.txt ensures anyone can run this

**Communication:**
- ✅ **Insights > numbers** - "SQL appears in 2x more jobs than Python" is better than "SQL: 51%, Python: 27%"
- ✅ **Visualizations tell stories** - Charts make patterns obvious that tables hide
- ✅ **Know your audience** - Recruiters care about ROI; students care about learning path

---

## 🎓 About This Project

### Background

**Who I Am:**
- PGDM student in Research & Business Analytics at WeSchool
- Career goal: Data Analyst / Business Analyst roles
- Previously worked with: SQL, Power BI, Excel
- **This is my first end-to-end Python data analysis project**

**Why I Built This:**

I was overwhelmed by conflicting advice on what to learn:
- Online tutorials: "Python is the only skill that matters"
- LinkedIn influencers: "Master Tableau or you're obsolete"
- University professors: "Get the degree, then worry about skills"

**I needed data, not opinions.**

So I spent 2.5 weeks building this analysis to make *data-driven* career decisions instead of guessing.

**The result:** A clear skill learning roadmap backed by 100,000+ job postings.

---

### Timeline

**Week 1: Learning Python Basics**
- Completed Python fundamentals (variables, loops, functions)
- Learned pandas basics (DataFrames, indexing, filtering)
- Watched YouTube tutorials on matplotlib

**Week 2-3: Building the Analysis**
- Day 1-2: Data exploration and cleaning
- Day 3-5: Skills analysis (notebooks 2-3)
- Day 6-8: Salary analysis (notebook 4)
- Day 9-10: Optimal skills strategy (notebook 5)
- Day 11-12: Visualization refinement
- Day 13-14: Documentation and GitHub setup

**Total Time:** ~2.5 weeks (60-70 hours)

---

### What I'd Do Differently Next Time

**Technical Improvements:**
- [ ] **Add interactive visualizations** with Plotly/Dash for better exploration
- [ ] **Statistical significance testing** (Are differences between skills meaningful?)
- [ ] **Geographic analysis** (Salary variations by state/city)
- [ ] **Time-series forecasting** (Predict future skill demand)
- [ ] **Correlation analysis** (Which skills appear together in job postings?)

**Tooling Enhancements:**
- [ ] **Build Streamlit dashboard** for non-technical users to explore
- [ ] **Automated data pipeline** to refresh analysis monthly
- [ ] **A/B testing framework** for visualization effectiveness
- [ ] **Unit tests** for data processing functions

**Scope Expansions:**
- [ ] **Company-specific analysis** (FAANG vs startups vs enterprise)
- [ ] **Industry breakdown** (Finance vs Tech vs Healthcare)
- [ ] **Certification impact** (Do AWS/Azure certs boost salary?)
- [ ] **Job description NLP** (Extract soft skills, not just tech skills)

---

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anshul-silhare)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnshulSilhare)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anshulsilhare@gmail.com)

</div>

**I'm actively seeking Data Analyst / Business Analyst roles.**

If you're hiring, know someone who is, or want to discuss data analytics career paths, **let's connect!**

**Looking for:**
- Entry-level Data Analyst positions
- Business Analyst roles (operations focus)
- Analytics internships or project collaborations

**Location:** Open to opportunities in Mumbai, Bangalore, Pune, or remote

---

## 📈 Project Impact

**Repository Stats:**
- ⭐ Star this repo if you found it helpful!
- 🍴 Fork it to build your own analysis
- 📣 Share it with others learning data analytics

**What This Project Demonstrates:**

For recruiters and hiring managers, this repository shows:
- ✅ **Python proficiency** (pandas, matplotlib, seaborn)
- ✅ **Statistical analysis** (distributions, trends, correlations)
- ✅ **Data visualization** (15 publication-quality charts)
- ✅ **Project management** (structured, documented, reproducible)
- ✅ **Business thinking** (ROI analysis, career strategy)
- ✅ **Communication skills** (insights, not just numbers)

**This isn't just a tutorial I followed. This is original research I designed, executed, and documented from scratch.**

---

## 🙏 Acknowledgments

**Data Source:**
- [Luke Barousse](https://www.lukebarousse.com/) for creating and sharing the comprehensive Data Jobs dataset on Hugging Face

**Inspiration:**
- The need to make data-driven career decisions instead of relying on anecdotal advice

**Learning Resources:**
- [pandas documentation](https://pandas.pydata.org/docs/)
- [matplotlib tutorials](https://matplotlib.org/stable/tutorials/index.html)
- [Python Data Science Handbook by Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/)

**Community:**
- Python & Data Analytics community on LinkedIn for motivation and feedback

**Mentors:**
- WeSchool faculty for guidance on research methodology
- Online forums (Stack Overflow, Reddit r/datascience) for troubleshooting

---

## 🔮 Future Roadmap

**Phase 2: Enhanced Analysis (Next 1-2 months)**
- [ ] Add interactive Plotly visualizations
- [ ] Perform statistical significance testing
- [ ] Include geographic salary analysis (state-by-state)
- [ ] Build skills co-occurrence network graph

**Phase 3: Production Dashboard (Next 3-4 months)**
- [ ] Create Streamlit/Dash web application
- [ ] Automated monthly data refresh pipeline
- [ ] User filters (by role, location, salary range)
- [ ] Export functionality (PDF reports)

**Phase 4: Advanced Analytics (Future)**
- [ ] Machine learning model: Predict salary based on skills
- [ ] NLP analysis: Extract soft skills from job descriptions
- [ ] Time-series forecasting: Predict 2025-2026 skill demand
- [ ] Certification impact analysis (AWS, Azure, Google Cloud)

**Phase 5: Community Contribution (Ongoing)**
- [ ] Create video tutorial series on YouTube
- [ ] Write blog posts on career strategy insights
- [ ] Open source the analysis framework for others to use
- [ ] Collaborate with other students on similar projects

---

## 📜 License

This project is licensed under the **MIT License**.

You are free to:
- ✅ Use this code for personal or commercial projects
- ✅ Modify and adapt the analysis
- ✅ Share and distribute

**Attribution appreciated but not required.**

See the [LICENSE](LICENSE) file for full details.

---

## 🎯 Summary: Key Takeaways

If you only remember 5 things from this analysis:

**1. SQL > Python for Data Analysts**
- SQL: 51% of jobs | Python: 27% of jobs
- Learn SQL first, Python second

**2. Degrees Are Becoming Optional**
- 72% of jobs don't require formal degrees
- Skills matter more than credentials

**3. The Optimal Skill Combo**
- SQL (foundation) + Python (salary) + Tableau (specialization)
- This combination qualifies you for 60%+ of Data Analyst jobs

**4. Remote Work Is Rare**
- Only 7.5% of Data Analyst jobs offer remote work
- Optimize for skills/salary, not location flexibility (early career)

**5. Clear Salary Progression Exists**
- Data Analyst: $85K → Senior: $111K → Scientist: $135K
- 30-45% salary jumps with proven skills

---

<div align="center">

## ⭐ Support This Project

**If this analysis helped you make better career decisions:**

[![Star this repo](https://img.shields.io/github/stars/AnshulSilhare/us-data-jobs-analysis?style=social)](https://github.com/AnshulSilhare/us-data-jobs-analysis)
[![Follow me](https://img.shields.io/github/followers/AnshulSilhare?style=social)](https://github.com/AnshulSilhare)

**Share it with others learning Data Analytics!**

---

**Built with 🐍 Python | 📊 Data | 💡 Insights**

*Analysis by [Anshul Silhare](https://www.linkedin.com/in/anshul-silhare)*  
*PGDM Student | Research & Business Analytics | WeSchool*  
*March 2026*

---

**📧 Questions? Feedback? Job opportunities?**  
**Reach out on [LinkedIn](https://www.linkedin.com/in/anshul-silhare) or [Email](mailto:anshulsilhare@gmail.com)**

</div>
