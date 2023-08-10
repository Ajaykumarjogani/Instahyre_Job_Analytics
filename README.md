# Instahyre Job Market Analysis

<p align="center">
  <img src="https://github.com/divyechopra/Instahyre-Job-Analytics/assets/122443219/4d12f489-95e8-48a9-a6fc-4fabdc60c6cd" alt="WhatsApp Video 2023-07-24 at 10 15 43 AM">
</p>

## Project Description

This repository presents an extensive analysis of job postings and employment opportunities on Instahyre.com during. 
The analysis offers insights into job market trends, including industry distribution, geographical preferences, and company tendencies. 
The project is based on data collected from over 650 job postings and details of more than 200 companies.

![Viz_5](https://github.com/harshahari8/Instahyre_Job_Analytics/assets/133602303/8c328f24-1282-4a9b-a822-fcbcc2e8811b)


## Problem Aimed to Solve

The project addresses the need for understanding the dynamic job market landscape by utilizing data-driven analysis. By exploring trends and patterns within job postings, the project aims to provide valuable insights that can aid job seekers, companies, and policy makers in making informed decisions.

## Data Description
- **Dashboard & Tables**: Contains an Excel file for analysis and insights visualization. Additionally, this file also contains the structured tables generated through web scraping job data and establishing primary keys. The tables capture key details such as job attributes, company information, and more, all organized for systematic exploration.

- **Jupyter Notebook Files**: The collection of Jupyter notebook files within the repository reflects the various stages of the analysis process. The web scraping process is documented in one of the notebooks, providing transparency into data collection techniques using tools like Beautiful Soup and Selenium. Furthermore, an initial exploratory data analysis (EDA) is presented using the power of numpy and pandas, highlighting trends, patterns, and data cleansing processes.

- **Presentation**: The repository features a PowerPoint presentation file containing insights and visualizations derived from the analysis. This presentation distills the key findings and trends discovered during the project, offering an easily accessible overview for stakeholders seeking to grasp the project's impact at a glance

## Scraping and Preprocessing

Data collection involved web scraping using Python, leveraging the Selenium and BeautifulSoup4 libraries. These tools facilitated the extraction of job postings and company data from Instahyre's dynamic website. Subsequent preprocessing procedures addressed missing data, ensured data consistency, and eliminated duplicates. The structured data was then organized into a pandas DataFrame.

#### Using Selenium to automate the Chrome Browser:

![Webscraping_1](https://github.com/harshahari8/Instahyre_Job_Analytics/assets/133602303/224f5cc2-2d88-456e-9fb1-b9824e282781)

#### Using Selenium and BeautifulSoup to extract the data using HTML Classes:

![Webscraping_2](https://github.com/harshahari8/Instahyre_Job_Analytics/assets/133602303/09721e73-77ba-4f5b-9c9f-8f8dd807a64e)

## Exploratory Data Analysis

The exploratory data analysis phase encompassed the segmentation of data into distinct tables: Jobs, Companies, and Job Details. Relationships between these tables were established using primary keys. Utilizing pandas, the analysis delved into these relationships, yielding insights into job postings, companies, and associated attributes.

#### Initial aggregations on the data collected:
![EDA_1](https://github.com/harshahari8/Instahyre_Job_Analytics/assets/133602303/f8513b7c-2c41-4050-a69c-d16837023f24)

#### Generating primary keys and creating three linked tables:
![EDA_2](https://github.com/harshahari8/Instahyre_Job_Analytics/assets/133602303/d6c2b512-eb7c-4496-b89f-40272193b38c)


## Visualizations

Visualizations played a pivotal role in communicating analysis findings. Aggregations provided insights into various job market aspects, including city-wise job distribution, industry segments, company sizes, locations, and experience level preferences. These visualizations were consolidated into an Excel dashboard, enhancing the presentation of key insights.

#### A visualization to show the spread of roles in major cities based on years of experience required:
![Viz_3](https://github.com/harshahari8/Instahyre_Job_Analytics/assets/133602303/e57de352-d5dc-4af8-a906-b34a68e48cf4)

#### A dashboard summarizing key insights:
![Viz_1](https://github.com/harshahari8/Instahyre_Job_Analytics/assets/133602303/63e35d86-4028-455d-9268-b1cf1d88176e)


## Learning, Limitations and Challenges Faced

In the pursuit of completing this project, several learning opportunities and challenges were encountered:

- **Learning New Tools:** We acquired proficiency in utilizing tools such as Beautiful Soup and Selenium for web scraping. These skills enabled us to extract and analyze job market data from Instahyre's platform effectively.

- **Data Quality and Biases:** It's important to acknowledge that the accuracy of our analysis is inherently tied to the quality of the scraped data. The presence of biases within the collected data could impact the insights drawn from our analysis.

- **Web Scraping Constraints:** The constraints posed by web scraping, including limitations imposed by the website's structure and the information collected by the company, influenced the scope of data that we were able to collect and analyze.

- **Data Volume Impact:** While the insights we present here are valuable, it's essential to recognize that a larger dataset would likely yield more accurate and comprehensive results. A more extensive dataset would provide a broader perspective on industry trends.

Despite these challenges, this project serves as a testament to our commitment to continuous learning and the extraction of insights from complex datasets. The outcomes of this analysis hold potential not only for our immediate findings but also for guiding recruiters and job seekers in navigating the intricate landscape of employment opportunities.
