# Overview
This project analyzes the **data analyst job market in the United States** by exploring the relationship between **skills demand and salary trends**. It identifies the most in-demand skills, the highest-paying skills, and the optimal skills that balance both demand and compensation.

Through data visualization and analysis, the project highlights key insights into **career progression, market trends, and skill optimization strategies**, helping aspiring data analysts understand which skills to focus on to maximize job opportunities and earning potential.

# The Analysis
## 1.What are the most demanded skills for the top 3 most popular data roles?

view my notebook with detailed steps here:
[skill_demand.ipynb](project\skill_demand.ipynb)

### Rusults
visualizations of top skills of data nerds
![](project\output.png)

### Insights

* **Python dominates Data Science & Engineering**
  Highest demand in Data Scientist (72%) and Data Engineer (65%) roles.

* **SQL is the most universal skill**
  Appears consistently high across all roles, especially Data Engineer (68%) and Data Analyst (51%).

* **Role specialization is clear**

  * Data Scientists: strong focus on **Python + statistics tools (R, SAS)**
  * Data Analysts: emphasize **SQL + Excel + Tableau**
  * Data Engineers: focus on **SQL + cloud/big data tools (AWS, Azure, Spark)**

* **Excel is still highly relevant for Analysts**
  Second most demanded skill (41%) in Data Analyst roles.

* **Cloud & big data tools are exclusive to Engineering**
  AWS (43%), Azure (32%), Spark (32%) mainly appear in Data Engineer roles.

* **Visualization tools are mid-tier skills**
  Tableau demand is moderate (24–28%) across Data Scientist and Analyst roles.

* **R is niche but important for Data Science**
  Significant only in Data Scientist roles (44%), minimal elsewhere.

* **SAS has declining but present demand**
  Lower across all roles (19–24%), indicating reduced industry reliance.


## 2.How are in demand skills trending for data analysts?

view my notebook with detailed steps here:
[skill_trend.ipynb](project\skill_trend.ipynb)

### Results
![](project\output_2.png)
*bar graph visualizing the trending top skills for data analysts in the US in 2023.*

### Insights 

* **SQL remains the most in-demand skill all year**
  Consistently highest (~53–63%), with a slight decline toward the end.

* **Excel peaks in the Mid_year then fluctuates**
  Strong rise in July–August (~45%), followed by a drop and recovery in December.

* **Python trends upward toward year-end**
  After fluctuations, it increases noticeably in December (~33%).

* **Tableau stays relatively stable with a slight decline**
  Moves within ~29–35%, gradually decreasing toward year-end.

* **Power BI has the lowest but most stable demand**
  Remains around ~18–23% with minimal changes.

* **Mid-year (July–August) is the peak demand period**
  Several skills (Excel, Tableau, Python) reach higher levels during this time.

* **Overall decline in Q4**
  Most skills—especially SQL and Tableau—decrease toward the end of the year.

* **SQL is a core requirement**
  Large gap between SQL and other skills shows it is essential for Data Analyst roles.

## 3.How well do jobs and skills pay for data analysts?

view my notebook with detailed steps here:
[salary_analysis.ipynb](project\salary_analysis.ipynb)

### Results
![Salary distributions of data jobs in the US](project\output_3.png)
*Box blot visualizing the salary distributions for the top 6 data job titles*

### Insights

* **Senior roles earn significantly more**
  Senior Data Scientist and Senior Data Engineer have the highest salary ranges and medians.

* **Data Scientists earn more than Data Engineers (non-senior)**
  Median salaries for Data Scientists are slightly higher than Data Engineers.

* **Data Analysts have the lowest salaries**
  Both Data Analyst and Senior Data Analyst roles are at the lower end compared to other roles.

* **Wide salary variability in technical roles**
  Data Scientist and Data Engineer roles show large spreads, indicating diverse pay based on experience, company, or specialization.

* **High number of outliers at the top end**
  Many roles—especially Data Scientist and Data Engineer—have salaries reaching $300K–$600K.

* **Senior roles have more extreme high-end outliers**
  Indicates strong earning potential at top levels or in specialized positions.

* **Salary progression is clear across roles**
  Data Analyst → Data Scientist/Engineer → Senior roles shows a consistent upward trend.

* **Overlap exists between roles**
  Some high-paid Data Analysts can earn similarly to lower-paid Data Scientists or Engineers.

### Highest paid and most demanded skills for data analysts

### Results
![](project\output_4.png)
*Two separate bar graphs visualizing the highest paid skills and most in_demand skills for the data analysts in the US.*

### Insights

* **High-paying skills are not the most in-demand**
  Skills like *dplyr, Bitbucket, GitLab, Solidity* offer the highest salaries but are not widely requested.

* **Niche and specialized skills command premium salaries**
  Tools such as *Solidity (blockchain)* and *Hugging Face (AI)* significantly increase earning potential.

* **Core analyst tools dominate demand, not salary**
  *Python, SQL, Tableau, Excel* are the most requested but offer متوسط salaries compared to niche skills.

* **Python provides the best balance**
  It is both highly in-demand and offers relatively strong salaries.

* **Traditional tools have lower salary ceilings**
  *Excel, PowerPoint, Word* are widely used but associated with lower pay.

* **DevOps and engineering tools increase analyst value**
  Skills like *GitLab, Ansible, VMware* can boost salaries when combined with data analysis.

* **Backend and database tools pay more than BI tools**
  Tools such as *Cassandra* and *MXNet* offer higher salaries than *Tableau* or *Power BI*.

* **Key insight (career strategy)**
  Basic skills make you employable, but adding specialized or technical skills significantly increases your salary potential.



## 4.What is the most optimal skill to learn for data analysts?

view my notebook with detailed steps here:
[optimal_skills.ipynb](project\optimal_skills.ipynb)

### Results 
![](project\output_5.png)
*A scatter plot visualizing the most optimal skills(high paying & high demand) for data analysts in the US*

### Insights

* **Python offers the best overall value**
  High salary (~$98K) with strong demand (~35%) → best balance of pay and opportunities.

* **SQL is the most in-demand but not the highest paid**
  Highest demand (~58%) but moderate salary (~$91K).

* **Oracle stands out for high salary but low demand**
  One of the أعلى salaries (~$97K) but limited job share (~10%).

* **Tableau provides a strong balance among tools**
  Good demand (~31%) with solid salary (~$93K).

* **Excel is widely used but lower paying**
  High demand (~42%) but relatively lower salary (~$84K).

* **Basic tools have the lowest value**
  *Word* and *PowerPoint* show low demand and lowest salaries.

* **Programming skills outperform most tools**
  Skills like *Python, R, Go* generally offer higher salaries than analyst tools.

* **Databases provide stable mid-to-high value**
  *SQL Server* shows decent salary (~$92K) with lower demand (~9%).

* **Key insight (optimization)**
  The “optimal zone” lies in skills that balance demand and salary (Python, SQL, Tableau), not just one dimension.


# Tools I Used
 * python:
   * pandas library
   * matplotlip library
   * seaborn library
* jupyter notebooks
* cursor
* Git & Github

