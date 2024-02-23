# From Messy Data to Insights: My Product Catalog Creation Process

Introduction

I began with a dataset containing orders, the backbone of my analysis. To enrich this dataset, I integrated information from products .csv and customer .txt files into the worksheet.
Separated them into their own “Raw Data” worksheets and copied and started working on them in a different worksheet, to maintain the Raw Data, in case of need. 

Section 1: Cleaning the Data

Detecting duplicates is crucial for maintaining data integrity. I reviewed product IDs and customer IDs, eliminating 1210 and 231 duplicates respectively. Standardizing customer names by concatenating first and last names into a "Full Name" column streamlined the dataset for further analysis.

Recognizing inconsistencies in customer state abbreviations, I rectified this by trimming excess spaces and standardizing entries. Similarly, I streamlined customer addresses to display street, city, and zip code in a uniform format.


Section 2: A Touch of Analysis

Calculating the average price of products sold and identifying expensive products relative to this average provided valuable insights into pricing strategies and customer preferences. Additionally, sorting orders by delivery priority and payment method provided a detailed insight into operational efficiency and revenue streams.

Section 3: Enriching the Data

Augmenting the orders dataset with product names and categories using VLOOKUP enhanced the granularity of analysis, facilitating deeper insights into product performance and market segmentation.

Section 4: Unleashing the Power of Pivot Tables and Charts

Pivot tables served as the cornerstone for exploratory data analysis, allowing me to slice, dice, and summarize data effortlessly. Complementing these tables with visually appealing charts brought key findings to life, making complex insights accessible.

Conclusion

In the realm of data analysis, every step, from data wrangling to visualization, contributes to the creation of a compelling narrative. Through meticulous attention to detail and strategic analytical enhancements, I transformed disparate data points into a cohesive project showcasing the power of data-driven decision-making.
