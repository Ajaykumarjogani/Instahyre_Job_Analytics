# Instahyre Job Market Analysis

This repository contains an in-depth analysis of job postings and employment opportunities on the website Instahyre.com, focusing on the mid-May 2023 timeframe. The analysis provides insights into the job market trends, industry distribution, company preferences, and more, based on data collected from over 650 job postings and information on more than 200 companies.

## Overview

Instahyre is a renowned professional opportunity and job listings platform that hosts a dynamic website for job postings from various companies. To perform this analysis, we utilized Python3 along with Selenium and BeautifulSoup4 libraries for web scraping. The scraped data was organized into a structured format using the pandas DataFrame. The dataset comprises critical information such as job ID, designation, company details, required skills, and founding year.

## Methodology

1. **Data Collection:** We employed web scraping techniques to collect job postings and company information from Instahyre's website. The data was fetched using JavaScript via Selenium, and then parsed using BeautifulSoup4.

2. **Data Cleaning:** Once the data was scraped, it underwent thorough cleaning processes using numpy and pandas libraries. This involved handling missing values, removing duplicates, and transforming data into a consistent format.

3. **Exploratory Analysis:** The cleaned data was divided into three main tables: Jobs, Companies, and Job Details. Primary keys were generated for Jobs and Companies to establish relationships between these tables.

4. **Data Insights:** Utilizing pandas, we conducted exploratory analysis to gain insights into the dataset. The tables were linked based on primary keys, enabling deeper understanding of relationships between job postings, companies, and job details.

5. **Export and Visualization:** The resulting tables were exported into comma-separated value files (CSV) for further analysis and visualization using tools like Microsoft Excel.

6. **Aggregations and Visualizations:** Aggregations were performed to analyze the job market across various parameters. These included job distribution across different cities, industries, company sizes, locations, and experience levels. The findings were translated into visualizations, which were consolidated into an Excel dashboard.

7. **Key Findings and Presentation:** A presentation was created to highlight crucial visualizations, metrics, and insights derived from the data. Key findings included a concentration of job openings in Bengaluru, dominance of the Information & Technology (IT) industry, and employment opportunities for younger and less experienced job seekers.

## Files

- `web_scraping.py`: Python script for web scraping using Selenium and BeautifulSoup4.
- `data_cleaning.ipynb`: Jupyter notebook containing the data cleaning process.
- `data_analysis.ipynb`: Jupyter notebook showcasing data exploration and insights.
- `data_visualization.xlsx`: Excel file with visualizations and the dashboard.
- `presentation.pdf`: Presentation summarizing the analysis results and key insights.

## Conclusion

The analysis of Instahyre's job postings provides valuable insights into the current job market. The data reveals the dominance of the IT industry and the strong influence of Bengaluru in terms of job opportunities. This repository encapsulates the entire process of data collection, cleaning, analysis, and visualization, shedding light on key trends that define the job landscape during mid-May 2023.
