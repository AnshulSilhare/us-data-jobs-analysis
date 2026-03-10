# 📊 US Data Analyst Job Market Analysis

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-2.0+-green?logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Complete-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

> **First Python project:** Analyzing 100,000+ real US Data Analyst job postings to uncover what skills employers actually want, which skills pay the most, and whether a degree still matters in 2025.

---

## 🎯 Project Motivation

As a PGDM student transitioning into Data Analytics, I wanted to answer a critical question:

**"What skills should I learn to maximize my career opportunities?"**

Instead of guessing or following random advice, I built this Python analysis to let the data decide.

---

## 🔍 Key Questions Answered

1. **What are the most in-demand skills for Data Analysts?**
2. **Do I really need a degree to get hired?**
3. **Which skills command the highest salaries?**
4. **Is Python more important than SQL?** (Spoiler: No)
5. **What's the optimal skill combination for high pay + high demand?**

---

## 📈 Top Findings

### 1️⃣ SQL Still Dominates (Despite the Hype Around Python)

![Skills Demand](images/02_skills_analysis/skills_likelihood_percentage.png)

**For Data Analysts:**
- **SQL**: 51% of job postings
- **Excel**: 41% of postings  
- **Tableau**: 28% of postings
- **Python**: 27% of postings

**Key Insight:** SQL appears in nearly TWICE as many Data Analyst jobs as Python. If you're learning one skill first, make it SQL.

---

### 2️⃣ Degree Requirements Are Disappearing

![Benefits Analysis](images/01_market_overview/benefits_analysis.png)

**72% of Data Analyst jobs don't explicitly require a formal degree.**

This validates the shift toward skills-based hiring. For students and career changers: **Skills > Credentials**.

---

### 3️⃣ The Most Optimal Skills (High Demand + High Pay)

![Optimal Skills](images/05_optimal_skills/optimal_skills_scatter.png)

**Best ROI Skills:**
- **Python**: 33% demand, $98K median salary
- **Tableau**: 28% demand, $93K median salary
- **SQL**: 60% demand, $91K median salary

**SQL** has the highest demand. **Python** has the highest salary. **Learn both.**

---

### 4️⃣ Salary Insights

![Salary Distribution](images/04_salary_analysis/salary_by_role.png)

**Median Salaries by Role:**
- Senior Data Scientist: $155K
- Data Scientist: $135K
- Senior Data Analyst: $111K
- **Data Analyst: $85K**

**Salary Premium by Skill:**
- Python: +15% average salary
- SQL: +12% average salary
- Cloud skills (AWS/Azure): +18% average salary

---

### 5️⃣ Remote Work Reality Check

![Remote Work](images/01_market_overview/remote_work_percentage.png)

Only **7.5% of Data Analyst jobs** offer remote work.

Lower than expected. Most companies still want you in the office.

---

## 🛠️ Tech Stack

**Programming:**
- Python 3.13
- Jupyter Notebook

**Data Analysis:**
- `pandas` - Data manipulation & transformation
- `numpy` - Numerical operations

**Visualization:**
- `matplotlib` - Static charts
- `seaborn` - Statistical visualizations

**Data Source:**
- [Hugging Face: Luke Barousse Data Jobs Dataset](https://huggingface.co/datasets/lukebarousse/data_jobs)
- 100,000+ real job postings from 2023

---

## 📁 Project Structure
```
📦 us-data-analyst-job-market-python
│
├── 📂 notebooks/
│   ├── 1_EDA_Intro.ipynb              # Market overview & benefits
│   ├── 2_Skills_Count.ipynb           # Skills demand by role
│   ├── 3_Skills_Trend.ipynb           # Trending skills over time
│   ├── 4_Salary_Analysis.ipynb        # Salary insights
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
├── 📄 .gitignore                       # Excluded files
├── 📄 LICENSE                          # MIT License
└── 📄 README.md                        # This file
```

---

## 🚀 How to Run This Project

### Prerequisites
- Python 3.9 or higher
- pip package manager

### Installation

**1. Clone the repository:**
```bash
git clone https://github.com/YOUR_USERNAME/us-data-analyst-job-market-python.git
cd us-data-analyst-job-market-python
```

**2. Install dependencies:**
```bash
pip install -r requirements.txt
```

**3. Launch Jupyter Notebook:**
```bash
jupyter notebook
```

**4. Open any notebook in the `notebooks/` folder and run cells sequentially.**

---

## 📊 Analysis Breakdown

### Notebook 1: Market Overview (`1_EDA_Intro.ipynb`)
- Dataset exploration (785,741 total rows)
- Filtering to US Data Analyst jobs (30,000+ postings)
- Remote work analysis
- Degree requirement trends
- Top hiring companies
- Geographic distribution

### Notebook 2: Skills Demand (`2_Skills_Count.ipynb`)
- Extracting skills from nested lists
- Calculating skill frequency by role
- Comparing Data Analyst vs Engineer vs Scientist
- Top 10 most requested skills
- Skills likelihood percentages

### Notebook 3: Skills Trends (`3_Skills_Trend.ipynb`)
- Month-over-month skill trends (2023)
- SQL dominance over time
- Power BI vs Tableau competition
- Emerging vs declining skills

### Notebook 4: Salary Analysis (`4_Salary_Analysis.ipynb`)
- Salary distribution by role
- Impact of degree requirements on salary
- Highest-paying skills
- Salary progression by seniority
- Outlier analysis

### Notebook 5: Optimal Skills (`5_Optimal_Skills.ipynb`)
- Creating demand vs salary scatter plot
- Identifying "sweet spot" skills
- ROI analysis (Return on Investment for learning)
- Career path recommendations

---

## 💡 What I Learned

### Technical Skills:
- **pandas mastery**: `groupby()`, `explode()`, `merge()`, lambda functions
- **Data cleaning**: Handling nested lists, missing values, datetime conversion
- **Statistical analysis**: Medians, percentiles, distribution analysis
- **Visualization**: Creating publication-quality charts with matplotlib & seaborn

### Data Analysis Insights:
- **Ask the right question first**: I rewrote my analysis 3 times because I was solving the wrong problem
- **Data doesn't lie**: My assumptions about Python > SQL were completely wrong
- **Context matters**: "51% don't require a degree" doesn't mean degrees are useless—it means skills are equally important

### Project Management:
- Breaking large analysis into modular notebooks
- Documenting findings as insights, not just numbers
- Creating reproducible analysis workflows

---

## 🎓 About This Project

**Background:**
- This is my **first Python data analysis project**
- PGDM student (Operations & Business Analytics specialization)
- Previously worked with SQL and Power BI
- Built this project to learn Python while answering real career questions

**Timeline:**
- Learning Python basics: 1 week
- Building analysis: 1.5 weeks
- Total project time: ~2.5 weeks

**What I'd Do Differently Next Time:**
- Add interactive visualizations with Plotly
- Perform statistical significance testing
- Include geographic salary analysis by US state
- Build a Streamlit dashboard for exploration
- Add automated reporting

---

## 📫 Let's Connect

- **LinkedIn:** [Your LinkedIn Profile]
- **Email:** your.email@example.com
- **Portfolio:** [Optional - your website]

**I'm actively seeking Data Analyst / Business Analyst roles.** If you're hiring or know someone who is, let's talk!

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Dataset:** [Luke Barousse](https://www.lukebarousse.com/) for the comprehensive job postings dataset
- **Inspiration:** Making data-driven career decisions instead of guessing
- **Community:** Python & Data Analytics community on LinkedIn for motivation

---

## 🔮 Future Enhancements

- [ ] Add interactive Plotly visualizations
- [ ] Create Streamlit dashboard for non-technical users
- [ ] Perform geographic salary analysis (state-by-state)
- [ ] Add company-specific insights (FAANG vs startup vs enterprise)
- [ ] Include skills co-occurrence analysis (which skills appear together?)
- [ ] Time-series forecasting for future skill demand

---

## ⭐ If This Helped You

If you found this analysis useful for your career planning:
- **Star this repository** ⭐
- **Share it** with others learning data analytics
- **Connect with me** on LinkedIn

Let's build in public and help each other grow! 🚀

---

**Note:** This project uses publicly available job posting data for educational analysis. No proprietary or confidential company information is included.
```

**Save this README** (Commit changes)

---

### **STEP 5: Create requirements.txt**

**Add file → Create new file**

**Filename:** `requirements.txt`

**Content:**
```
pandas>=2.0.0
numpy>=1.24.0
matplotlib>=3.7.0
seaborn>=0.12.0
datasets>=2.14.0
jupyter>=1.0.0
```

**Commit**

---

### **STEP 6: Add Topics (SEO)**

1. Go to repository homepage
2. Click ⚙️ next to "About"
3. Add these topics:
```
python
data-analysis
pandas
jupyter-notebook
data-science
job-market
career-planning
data-analyst
seaborn
matplotlib
first-project
portfolio-project
```

---

### **STEP 7: Pin to Profile**

1. Go to your GitHub profile
2. Click "Customize your pins"
3. Select this repository
4. Move it to top-left position

---

## ✅ **YOUR GITHUB IS NOW GOLD-LEVEL**

**What makes it professional:**

✅ Clean README with badges
✅ Clear project structure
✅ Professional visuals embedded
✅ Reproducible (requirements.txt)
✅ Well-organized folders
✅ Business insights, not just code
✅ Learning transparency
✅ Future roadmap
✅ Contact information
✅ Proper licensing
✅ SEO optimized (topics)

---

## 📱 **NOW: YOUR LINKEDIN POST (Thursday 8:30 AM)**

**Use: OPTION 2 (Market Research Angle)** 

**Attach: Image `2-2.png` (Skills Likelihood)**

**The Post:**
```
Analyzed 100,000+ US Data Analyst job postings.

Found something surprising.

SQL appears in 51% of jobs.
Python? Only 27%.

Here's what else the data revealed:

---

THE QUESTION:

Everyone says "learn Python" or "master Tableau."

But what do Data Analyst jobs ACTUALLY require?

I built my first Python project to find out.

---

THE APPROACH:

**Dataset:** 100k+ real job postings (Hugging Face)

**Tools:** Python (pandas, matplotlib, seaborn)

**Analysis:**
→ Skills demand frequency  
→ Salary by skill
→ Degree requirements
→ Remote work trends
→ Optimal skills (high demand + high pay)

5 Jupyter notebooks. First time coding in Python.

---

THE FINDINGS:

**Top 5 Skills for Data Analysts:**

1. **SQL** (51%) - Still the foundation
2. **Excel** (41%) - Not dead yet
3. **Tableau** (28%) - Visualization king
4. **Python** (27%) - Growing fast
5. **SAS** (19%) - Niche but stable

**Key Insights:**

→ **Skills > Degrees**  
72% of jobs don't explicitly require formal education.
The shift to skills-based hiring is real.

→ **SQL Pays Premium**  
Jobs requiring SQL: Average $91K
Jobs without SQL: Average $78K
+16% salary boost.

→ **Remote Work: 7.5%**  
Lower than expected.
Most Data Analyst roles still want you in office.

→ **Python = Salary Premium**  
When Python is listed, median salary jumps to $98K.
High demand + high pay = worth learning.

---

THE SURPRISE:

I started this project thinking Python was "the" skill.

It's not.

SQL appears in MORE postings than Python.

If you're choosing what to learn first:
→ Start with SQL
→ Add Python second
→ Then Tableau/Power BI

Data-driven career planning > guessing.

---

WHY THIS MATTERS:

I'm a PGDM student targeting Data Analyst roles.

This analysis helped me prioritize:
→ SQL (already strong) ✓
→ Python (learning now) ✓  
→ Tableau (next on list)

Instead of learning "everything," I'm learning what employers actually want.

---

Full Python analysis on GitHub (link in comments).

What skill surprised YOU as being in-demand for data roles?

#DataAnalytics #Python #JobMarket #DataAnalyst #CareerResearch #SQL #BuildingInPublic #PGDM #FirstProject #DataScience
```

---

## 💬 **FIRST COMMENT (Post Within 2 Minutes):**
```
Full Python project on GitHub:
👉 github.com/YOUR_USERNAME/us-data-analyst-job-market-python

The repository includes:
✅ 5 Jupyter notebooks with complete analysis
✅ 15 professional visualizations  
✅ Skills demand, salary, and trend analysis
✅ Fully documented code & methodology
✅ Reproducible with requirements.txt

This was my first Python project - code isn't perfect, but insights are solid.

For anyone learning Python: Build something real. You'll learn more in 2 weeks than in 2 months of tutorials.

What helped YOU learn Python? Drop recommendations below 👇
