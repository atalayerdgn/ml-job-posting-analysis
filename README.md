# Machine Learning Job Postings Analysis

## Overview
This project analyzes a dataset of machine learning job postings in the United States to uncover patterns and insights about the ML job market, including geographical distribution, required skills, experience levels, and company trends.

## Dataset
The dataset (`1000_ml_jobs_us.csv`) contains information about machine learning job postings with the following columns:

- `job_posted_date`: Date when the job was posted
- `company_address_locality`: City where the job is located
- `company_address_region`: State or region where the job is located
- `company_name`: Name of the company posting the job
- `company_website`: Company's website URL
- `company_description`: Description of the company
- `job_description_text`: Full text of the job posting
- `seniority_level`: Seniority level of the position (e.g., Entry-level, Mid-Senior level)
- `job_title`: Title of the job posting

## Analysis Components
The analysis covers several key aspects of the ML job market:

1. **Temporal Analysis**: How job postings are distributed over time
2. **Geographical Analysis**: Distribution of jobs by state and city
3. **Company Analysis**: Top companies posting ML jobs
4. **Job Title Analysis**: Common roles and terms in job titles
5. **Seniority Level Analysis**: Distribution of seniority levels
6. **Skills Analysis**: Most in-demand technical skills based on job descriptions

## How to Run
### Prerequisites
- Python 3.x
- Required libraries:
  ```
  pandas
  numpy
  matplotlib
  seaborn
  wordcloud (optional)
  ```

### Installation
1. Clone this repository
2. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   pip install wordcloud (optional)
   ```

### Running the Analysis
1. Open the Jupyter notebook:
   ```bash
   jupyter notebook ml_jobs_analysis.ipynb
   ```
2. Run all cells to perform the complete analysis

## Key Findings
- **Geographical Concentration**: ML jobs are primarily concentrated in tech hubs like California, New York, and Washington
- **Skills in Demand**: Python, Machine Learning, Deep Learning, and Cloud technologies are among the most requested skills
- **Company Distribution**: Top tech companies dominate the ML job market
- **Time Trends**: (Specific trends will be visible from the analysis)

## Data Cleaning
The analysis includes data cleaning steps to handle:
- Invalid date formats
- Missing values
- Data alignment issues
- State name normalization (e.g., "CA" to "California")

## Visualizations
The notebook generates several visualizations:
- Bar charts of job distribution by region
- Time series of job postings
- Company distribution charts
- Skill frequency analysis
- Word clouds of job titles and descriptions

## Future Work
Potential extensions to this analysis:
- Salary analysis (if data becomes available)
- Correlation between skills and seniority levels
- Industry-specific ML job trends
- Comparative analysis with other time periods or regions


## Acknowledgments
- The dataset was obtained from a collection of US-based ML job postings
- Analysis techniques were inspired by data science best practices
