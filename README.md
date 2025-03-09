# 📚 Optimizing Emergency Room Wait Times in Ontario's Healthcare System

## 📌 Project Overview
Emergency rooms (ER) in Ontario face long wait times, often exceeding 8 hours, double the global standard. The most significant delays occur during the initial assessment, where patients first interact with healthcare professionals. Traditional solutions, such as hiring more staff or expanding facilities, are limited by budget constraints and staff shortages.

This project aims to analyze ER wait times, explore the impact of AI-driven triage tools, and suggest technology-based solutions to reduce delays. Through statistical analysis and hypothesis testing, we assess how AI can optimize patient flow and resource allocation.

### **Team Members (Group-7)**:
- **Dheeraj Kuldeep Choudhary** - 9014533      
- **Harika Ravi** - 9032698
- **Nasr Alani** - 9039537
- **Paljeet Singh Sambhi** - 8918495
- **Priyanka Chitikela** - 8909667

## Installation Instructions

### Prerequisites
- Python 3.8 or higher
- Pandas
- numpy
- matplotlib
- seaborn
- scipy

## **Dataset Details**
We synthesized an ER wait times dataset for Ontario based on real-world statistics, including total visits, CTAS levels, and wait time distributions. The dataset includes Date of visit, CTAS levels, wait times (sampled from normal distributions using real median and 90th percentile values), hospital names, days of the week, and Season. CTAS proportions were assigned realistically, and wait times were adjusted to prevent negative values. Randomized dates and hospital assignments ensured diversity. 

The dataset used in this analysis is **`er_wait_times_ontario_updated.csv`**, containing:
- **Patient Visit Information**: Date, hospital, region
- **CTAS Levels**: Triage priority levels (I-III, IV-V, Admitted cases)
- **Wait Times**: Measured in hours before treatment
- **Additional Factors**: Day of the week, hospital capacity

## **Execution Steps**



## **Interpreting Results**
- **If p-value < 0.05**, reject the null hypothesis (significant difference exists).
- **T-Test Results:** Determines if wait times differ between **CTAS I-III and CTAS IV-V**.
- **ANOVA Results:** Determines if wait times significantly vary **across all CTAS levels**.
  

## **GitHub Repository**
Find the full project and dataset on GitHub:
[GitHub Repository Link](https://github.com/your-username/ER_Wait_Time_Analysis)

---
**Authors:** *Group7*


## Notes
- Ensure datasets are correctly loaded before running analyses.
- Modify the test parameters as per dataset requirements.
