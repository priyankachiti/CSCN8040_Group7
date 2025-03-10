# Optimizing Emergency Room Wait Times in Ontario's Healthcare System

## Project Overview
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
Ensure you have Python installed (recommended: Python 3.7+). Install the required dependencies using the following commands:

- `pip install matplotlib`
- `pip install pandas`
- `pip install numpy`
- `pip install scipy`
- `pip install seaborn`
  

## **Dataset Details**
We synthesized an ER wait times dataset for Ontario based on real-world statistics, including total visits, CTAS levels, and wait time distributions. The dataset includes Date of visit, CTAS levels, wait times (sampled from normal distributions using real median and 90th percentile values), hospital names, days of the week, and Season. CTAS proportions were assigned realistically, and wait times were adjusted to prevent negative values. Randomized dates and hospital assignments ensured diversity. 

The dataset used in this analysis is **`er_wait_times_ontario_updated.csv`**, containing:
- **Patient Visit Information**: Date, hospital, region
- **CTAS Levels**: Triage priority levels (I-III, IV-V, Admitted cases)
- **Wait Times**: Measured in hours before treatment
- **Additional Factors**: Day of the week, hospital capacity

## **Execution Steps**
1. **Open Jupyter Notebook**
   - Run the following command in your terminal to start Jupyter Notebook:
     ```
     jupyter notebook
     ```
   - Open the `EDA_Statastical_Test.ipynb` file.

2. **Perform Exploratory Data Analysis (EDA)**
   - The notebook includes data visualization using `matplotlib` and `seaborn`.
   - Run the respective cells to generate visual insights such as histograms, box plots, and correlation heatmaps.

3. **Conduct Statistical Tests**
   - The notebook applies statistical tests such as:
     - **t-test** for comparing means
     - **ANOVA** for multiple group comparisons
     - **Chi-square test** for categorical data
   - Run the respective code cells to compute and interpret statistical values.

4. **Evaluate Hypothesis**
   - The notebook assesses hypotheses based on statistical test results.
   - Look for `p-value` calculations and conclusions regarding accepting or rejecting the null hypothesis.


## **Interpreting Results**
Statistical tests confirmed significant differences in wait times:  
  - **ANOVA results** showed that CTAS levels significantly impact ER wait durations.  
  - **T-Test results** confirmed CTAS I–III patients wait significantly longer than CTAS IV–V patients.  
  - **Chi-Square test** indicated a strong relationship between patient acuity and wait time categories (Short, Medium, Long). 


## 📌 Acknowledgments  
We extend our gratitude to:  
- **Professor David Espinosa Carrillo** for guidance and support.  
- **Conestoga College** for providing resources to conduct this research.  
- **Our research team (Group-7)** for collaborative efforts in data analysis and AI integration.
