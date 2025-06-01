# Employability: Data Science Project Plan  

## 1. Problem Statement  
The audience for this project is data analysts job seekers. Here, we define some key questions we aim to answer through this project.

### Job Market & Hiring Trends
- How has the demand for data analysts changed over time?
- What industries are posting the most jobs for data analysts?
- Which cities or states hire the most data analysts?
- Are startups, mid-sized firms, or large corporations hiring more analysts?
- Which companies post the highest number of data analyst job listings?
- Where are employers posting job listings—LinkedIn, Indeed, Upwork, or others?

### Skills, Experience, and Qualifications
- What are the most frequently mentioned technical and soft skills in job postings for data analysts?
- How do employers describe the required years of experience, and how do they define "entry-level" vs. "senior" roles?
- How do educational requirements vary? Is a degree in data science necessary, or do companies prioritize certifications and practical experience?
- What data tools (Excel, SQL, Python, Power BI) are in high demand?
- What keywords appear most frequently in data analyst job descriptions?

### Salary and Work Culture
- What is the salary range for data analysts across different industries and locations?
- How do salaries differ for remote vs. in-office positions?
- Is there a correlation between years of experience and salary?
- What percentage of data analyst jobs offer remote work options?
- What benefits (healthcare, stock options, flexible schedules) are commonly listed?
- Do certain industries provide better perks than others?

### Emerging Trends and Future Insights
- Has the rise of AI and automation impacted job descriptions?
- Are internships and junior roles increasing or decreasing in job postings?
- Are companies mentioning ChatGPT, AutoML, or other AI tools in job postings?

## 2. Data Collection  
- **Data Source:** Kaggle dataset (`gsearch_jobs.csv`)  
- **Collection Method:** Scraping job postings via Google search  
- **Data Format:** CSV file with 27 attributes  

## 3. Data Preprocessing & Cleaning  
- Handle missing values (imputation or deletion)  
- Standardize salary formats and currency conversion  
- Extract useful keywords from job descriptions using NLP  

## 4. Exploratory Data Analysis (EDA)  
- Visualize job postings distribution per location  
- Analyze top required skills using word clouds  
- Identify salary trends across industries  

## 5. Feature Engineering  
- Create skill-based ranking for job requirements  
- Extract numeric features from job descriptions (e.g., number of required years of experience)  
- Convert categorical variables into usable formats  

## 6. Model Selection & Training  
- **Machine Learning Task:** Salary prediction & skill clustering  
- **Algorithms Considered:**  
  - Linear Regression (for salary estimation)  
  - K-Means Clustering (for skill grouping)  
  - Random Forest (for job role classification)  
- **Training Process:** Splitting dataset into training and test sets  

## 7. Evaluation Metrics  
- Root Mean Squared Error (RMSE) for salary predictions  
- Accuracy for classification models  
- Silhouette score for clustering  

## 8. Deployment & Visualization  
- Interactive dashboard with job market insights (using Streamlit)  
- API integration for real-time job posting updates  

## 9. Project Timeline  
| Phase                 | Tasks                                   | Estimated Timeframe |
|----------------------|----------------------------------|------------------|
| Data Collection     | Scraping, sourcing, formatting  | 2 weeks |
| Data Cleaning      | Handling missing values, preprocessing | 2 weeks |
| Exploratory Analysis | Visualizations, correlation analysis | 3 weeks |
| Feature Engineering | Creating relevant features | 2 weeks |
| Model Training      | Experimenting with ML algorithms | 3 weeks |
| Evaluation         | Model tuning and validation | 2 weeks |
| Deployment        | Building dashboard/API | 3 weeks |

## 10. Future Enhancements  
- Expand to international job postings  
- Introduce deep learning techniques  
- Automate salary estimation based on text descriptions  
