# InstahyreJobAnalytics

An analysis of job postings and employment opportunities on the website Instahyre.com.

The professional opportunity and job listings company Instahyre's main job portal was studied to analyse the job market during mid-May, 2023. 

Instahyre posts jobs from companies on a dyanmic website using JavaScript. To scrape the data from Instahyre, the Python3 libraries Selenium and BeautifulSoup4 were used. The data was scraped and collected in a list that was converted into a pandas DataFrame. 
It comprised more than 650 job postings and information on more than 200 companies. 

Data cleaning and exploratory analysis were done using numpy and pandas. The data was segregated into three tables: Jobs, Companies and Job Details. Primary keys were generated for Jobs and Companies. Amongst the data points collected were: job ID, designation, company name, the number of employees in the company, the HR of the company, the skills required for the job and the year of the company's founding.

After the tables were created, further analysis was done on pandas to understand and gain insight into the data collected. The tables were linked to one another based on the primary keys generated. These tables were then exported into comma separated value files. These files were then used to perform more analysis and data visualisation on Microsoft Excel.

Aggregations were generated to understand the job market. The number of jobs for different cities were measured, jobs were segregated by industry, company size, location and experience level. The findings were then visualised into an excel dashboard, and a presentation was created to highlight key visualisations, metrics and insights from the data.

In conclusion, the data showed a heavy bias towards the city of Bengaluru, which had the highest number of job openings overall, and the industry of Information & Technology (IT) was by far the biggest employer with more than 50% of jobs being software/technology or data analytics based. Other insights were also discovered. Overall, the IT Industry has a massive economic effect on the public and offers the most employment opportunities to younger, more inexperienced job seekers.
