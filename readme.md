# CA-Projects-template-submission-repo
.

## Summary
| Code      | Name        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
| LP1 | Indian Start-up analysis |  [Best article of the world](https://medium.com/p/e8c38173088f/edit) | [Best app of the world](https://app.powerbi.com/groups/me/reports/3ab3ea7b-1da3-433e-a575-5c0d7f4f9fe7/ReportSection?redirectedFromSignup=1) |

## Project Description
...India's economy has been growing rapidly, and this growth has been fueled in part by a thriving startup ecosystem. In the last ten years, a significant number of highly successful startups, known as "unicorns," have emerged in India, and these startups have had a global impact. Although startups are typically small businesses, they can have a significant impact on the economy by creating jobs, which can lead to lower unemployment rates and a healthier economy overall. In addition, startups can help drive innovation and competition, which can further contribute to economic growth and vitality.
As a data scientist, I recently conducted research on the Indian startup ecosystem to better understand which industries were more likely to receive the most funding. I used data collected from startups in India that received funding between 2018 and 2021. To facilitate a more informed decision, I analyzed and visualized the data using Python.
However, I encountered some difficulties during the data cleaning process as there were inconsistencies in the dataset for each year. Despite these challenges, I found that technological companies were more likely to receive funding.
To begin the data analysis process in Python, it's important to import the necessary libraries. I imported commonly used libraries for data analysis and visualization, including Pandas, NumPy, Matplotlib, and Seaborn.
Taking a look at the datasets across the years, certain columns were common in all the datasets and were deemed relevant in the analysis. In importing the datasets, specific columns were imported. These included: Company Name, Industry, Round/Series, Amount & Location. To ensure consistency, some columns were renamed to match the columns in the dataset of subsequent years. Industry was renamed 'Sector' and Round/Series was renamed 'Stage'. The unique values for these columns were also analyzed and I realized that there were inconsistencies .
The 2018 dataset, a few of the amounts were in Rupees and the rest in dollars. The data type was changed to string and the rupees were converted to dollars using the average exchange rate in 2018.
Similar cleaning was done for the 2018, 2019,2020 and 2021. After the data cleaning process, clean data from all the years were concatenated and merged into 1 dataframe with 2854 rows and 10 columns in total.
Further univartiate and multivariate analysis was done to ascertain the distribution of data within the columns. these analysis were plotted using bargraph, box plot, histogram.
the business questions were then answred

## Setup
...(https://medium.com/p/e8c38173088f/edit)

## App Execution
...https://app.powerbi.com/groups/me/reports/3ab3ea7b-1da3-433e-a575-5c0d7f4f9fe7/ReportSection?redirectedFromSignup=1

## Author
Ama Chinbuah

