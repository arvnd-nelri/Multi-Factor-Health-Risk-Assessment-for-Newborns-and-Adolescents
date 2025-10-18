# Multi-Factor Health Risk Assessment for Newborns

## Project Description
We are building a **Health Risk Index** for newborns and infants using real-world health data from San Francisco. The goal is to go beyond reporting statistics and create a system that can **predict, classify, and explain health risks** based on multiple factors such as race, insurance type, geography, and medical history.

The project combines three machine learning approaches:

- **Clustering** – to find hidden groups of infants with similar risk profiles.  
- **Regression** – to calculate the risk index for newborns.  
- **Classification** – to assign risk levels (low, medium, high) for easier interpretation.  

Our dataset includes **83,000+ birth records, hospital visits, and screenings**, providing a strong foundation for analysis. The final output will include risk scores, visual insights, and predictive models that can help healthcare providers, policymakers, and communities better understand and address disparities in infant health.

---

## Team

**Sai Annessha Veluri**  
Graduate Student in Data Science, specialized in data cleaning, preprocessing, and statistical modeling. Passionate about health data and analytics (Data Lead).  
[LinkedIn](https://www.linkedin.com/in/sai-annessha-veluri-05515b227) | [GitHub](https://github.com/Annessha18)

**Sai Aravind Nelluri**  
Masters in Data Science student, interests lie in applying AI techniques to improve early detection of health risks. Focused on machine learning and predictions (Modeling Lead).  
[LinkedIn](https://www.linkedin.com/in/sai-aravind-nelluri) | [GitHub](https://github.com/arvnd-nelri)

**Vishvapavani Bhupathi**  
Data Science graduate student, specialized in transforming complex data into clear and impactful visualizations. Interested in storytelling with data (Visualization Lead).  
[LinkedIn](https://www.linkedin.com/in/vishvapavani-bhupathi-bb8a1b227/) | [GitHub](https://github.com/vishvap-bhupathi)

---

## Milestone 1: Project Proposal – Outcomes
For Milestone 1, our team defined the project scope by planning to build a health risk assessment for newborns using San Francisco health data. We highlighted the research significance by addressing disparities in infant health outcomes across race, insurance type, and geography, and identified key stakeholders including families, healthcare providers, hospitals, policymakers, and communities.  

We reviewed existing machine learning solutions and noted gaps in regression and clustering approaches. Our project blueprint outlines the use of clustering, regression, and classification to create actionable risk categories. Additionally, we proposed **10 research questions** to guide our analysis and successfully set up the project website along with the GitHub repository.

---

## Milestone 2: Data Acquisition, Preprocessing, and Visualization – Outcomes
For Milestone 2, our focus was on acquiring, cleaning, and preparing the dataset for analysis. The dataset, titled **“Maternal, Child, and Adolescent Health Needs Assessment (2023–2024)”**, was obtained from the [Data.gov public health portal](https://www.data.gov/) ensuring open and ethical access. The raw dataset contained over 83,000 records covering demographics, health outcomes, and socioeconomic factors.

Key steps in data preprocessing included:

- **Standardizing categorical variables** (e.g., merging duplicates like “ALL” and “All”, “Female” and “FEMALE”).  
- **Addressing missing values** across 26 features using imputation and logical replacements.  
- **Filtering irrelevant or incomplete records** for consistency across years and health metrics.  
- **Generating derived metrics** such as `Rate_SF_pop` for more meaningful comparisons.  

Post-cleaning, data quality and completeness were validated, achieving **0 missing values across all features**.  

Initial visual exploration using Python (**Matplotlib** and **Seaborn**) helped identify trends by sex, insurance type, and year, revealing early insights into infant health disparities.  

This milestone established a **clean, structured, and analysis-ready dataset**, forming the foundation for modeling and clustering in the next phase.
