# UNLOCKING CURRENT OPPORTUNITIES IN BUSINESS ANALYTICS: MARKET TRENDS, INSIGHTS, AND AI APPLICATIONS

## Project Overview
This project aims to analyze current market trends, salary insights, and AI applications for Business Analyst roles across various industries. The objective is to provide actionable insights for individuals and companies in the business analytics domain by evaluating factors like job type, industry, location, experience, and salary variations.

---

## Objectives
1. Evaluate salary differences across industries for Business Analyst roles.
2. Analyze the relationship between salary, experience, industry, and job location.
3. Understand the impact of job type (Remote, Hybrid, Onsite) on salary.

---

## Workflow
The project followed a structured workflow consisting of six key steps:
1. **Define Objectives**
2. **Data Collection**
3. **Data Exploration**
4. **Data Visualization**
5. **Analysis**
6. **AI Applications**

---

## Data Source
The data was scraped from **BusinessAnalyst.com**, comprising job postings across industries, locations, and experience levels. The dataset includes:
- Job Title
- Industry
- Location (Remote, Hybrid, Onsite)
- Salary Range
- Experience Level
- Date of Posting

---

## Data Exploration
Data scraping and exploration involved the following:
- Scraped job listings from 35 pages of BusinessAnalyst.com.
- Parsed and cleaned salary data by calculating average salaries.
- Standardized location fields and handled missing or remote entries.
- Applied the Interquartile Range (IQR) method to remove outliers for accurate analysis.

---

## Key Visualizations & Insights
### 1. **Salary vs. Industry**
- Industries like Crypto, Automotive, and Tech offer the highest average salaries.
- Healthcare, Financial, and Consulting industries fall in the mid-range.

### 2. **Salary Trends by City (Top 10)**
- San Francisco, New York, and Boston offer the highest salary ranges.
- Cities like Jacksonville and Minneapolis fall on the lower end.

### 3. **Job Postings Trend by Month**
- Job postings peak mid-year, indicating hiring spikes around budget resets or business needs.

### 4. **Job Location vs. Salary**
- Hybrid roles offer the highest median salaries but show more variability.
- Onsite jobs have the lowest median salaries with narrow ranges.

### 5. **Salary vs. Experience**
- Individuals with 5-10 years of experience have the highest median salaries.
- The salary range widens with more experience.

---

## Healthcare Industry Analytics
### Salary Trends in Healthcare
- Early Peak: Around June 2024, there is a sharp rise in salaries, peaking at over $100,000 before gradually declining.
- Volatility: Salary trends demonstrate high volatility with frequent ups and downs, suggesting an unstable or rapidly changing compensation environment.

### Salary Distribution in Healthcare Roles (Remote vs. Onsite)
- **Remote Roles**: Employees with 3-5 years of experience dominate remote roles, while those with 0-3 years have a fair presence but tend to earn lower salaries. Few employees with 5-10 years of experience are represented in remote roles.
- **Onsite Roles**: Onsite jobs show a more balanced representation of all three experience levels. Employees with 3-5 years of experience earn higher salaries, while those with 0-3 years occupy the lower salary range. Very few onsite roles offer salaries above $100,000.

### Job Types Distribution in Healthcare
- **Remote Role Dominance**: Reflects the growing trend in the healthcare industry, where many administrative, analytical, and technical jobs have transitioned to remote work due to advancements in digital health and remote working infrastructure.
- **Hybrid Roles**: Significant presence indicating companies value a mix of in-office and remote work for team collaboration.
- **Relatively Low Onsite Roles**: Onsite roles make up only 9.4%, indicating less necessity for business analysts to be physically present compared to other industries.

---

## AI Applications
### **Web Scraping**
- Utilized to automate data extraction from websites.
- Enhanced by AI for cleaning, structuring, and adapting to website changes.

### **Data Visualization**
- AI-powered tools automate data analysis and highlight key patterns.
- Future trends include immersive visualization with VR/AR and real-time interactive dashboards.

---

## Tools & Technologies Used
- **Python**: For data scraping, cleaning, and analysis.
- **Pandas**: For data manipulation and exploration.
- **Matplotlib & Seaborn**: For visualizations.
- **BeautifulSoup & Requests**: For web scraping.
- **Jupyter Notebooks**: For code implementation and reporting.

---

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/hemanth379/Unlocking_Current_Opportunities_In_Business_Analytics.git
   ```
2. Navigate to the project directory:
   ```bash
   ccd Unlocking_Current_Opportunities_In_Business_Analytics
   ```
3. Run the Jupyter notebooks to explore data and visualizations:
   ```bash
   jupyter notebook
   ```

---

## How to Run the Project
1. **Web Scraping Code**: Execute the `webscraping_code.ipynb` to scrape job listings and save the data as a CSV file.
2. **Data Analysis Code**: Use the `data_visualization_code.ipynb` to perform data exploration and generate visualizations.

---

## Project Structure
```
|-- data
|   |-- business_analyst_jobs.csv
|-- notebooks
|   |-- webscraping_code.ipynb
|   |-- data_visualization_code.ipynb
|-- README.md
```

---

## Future Enhancements
1. **Expand the dataset** by scraping more job boards.
2. **Integrate machine learning models** to predict salary trends.
3. **Develop an interactive dashboard** for real-time insights.

---

## Contributors
- **Hemanth Varma Pericherla**
- **Vaishnavi Karingala**
- **Divyasri Yelubolu**
- **Sai Soumya Aloor**
- **Sri Charan Desetty**
- **Anantha Vyasa Kurudi**
- **Sanjana Paluru**
- **Vamshi Krishna Sai Myneni**

---

## Acknowledgements
- **Prof. Dr. Lan Wang** for guidance and support throughout the project.


