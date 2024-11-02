# DunderMifflin-Sales-Analysis
## Project Overview
Dunder Mifflin is a provider of essential office supplies for businesses, organizations, and individuals. This project aims to use Business Intelligence in Power BI to identify and analyze sales challenges, offering decision-makers actionable insights for business improvement.

Link to dataset on Github: [here](https://github.com/tdmitch/DunderMifflin/tree/master).

<p align="center">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/youtube%20logo.png" alt="Youtube logo">
</p>

**Course**: Business Intelligence

**Institution**: University of Economics Ho Chi Minh City (UEH) - School of Technology and Design

## Project Objective
The main objective of this project is to analyze:
- Business performance
- Human resource management effectiveness
- Transportation activities
- Supply chain and warehouse management efficiency
- Customer loyalty

## Methodology
### 1. ETL Process:
**Extract**: We used SQL to merge text files from the Dunder Mifflin dataset on GitHub.

**Transform**:

We used Power Query Editor for data cleaning and preprocessing, followed by Python to visualize the distribution of each column:
- Removed unnecessary tables and ambiguous columns, such as the Regions table, EmployeeRegions table, and People table.
- Handled missing values in certain fields by replacing them with appropriate default values or means.

**Load**: The transformed data was loaded into Power BI for further analysis and visualization.
  
### 2. Data Modeling:
Created dimension and fact tables to store structured information about:
- Time (e.g., year, month)
- Regions and countries
- YouTuber categories and awards
- Types of YouTubers (e.g., Entertainment, Music, People & Blogs)
- Video views and rankings

<p align="center">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/BI_Youtube_Data%20Modeling.png" alt="Youtube Data Modeling">
</p>  

Implemented transformations to align the data structure with Power BI's analytical capabilities.

### 3. Analysis:
We conducted the following analyses:
- Overview of Business Performance

<p align="center">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/Dashboard%20and%20Reports/Youtube_Dashboard%20overview.png" alt="Youtube Dashboard overview">
</p> 
  
- Yearly and Monthly Performance: Tracked the performance trends of channels over time, identifying seasonal patterns and yearly growth.

<p align="center">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/Dashboard%20and%20Reports/Youtube_Year%20report.png" alt="Youtube Year report">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/Dashboard%20and%20Reports/Youtube_Month%20report.png" alt="Youtube Month report">  
</p> 

- Regional and Country-based Analysis: Explored how geographical factors influence channel performance, with the U.S. and India leading in YouTuber presence.

<p align="center">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/Dashboard%20and%20Reports/Youtube_Region%20report.png" alt="Youtube Region report">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/Dashboard%20and%20Reports/Youtube_Country%20report.png" alt="Youtube Country report">  
</p> 

- Category and Subcategory Performance: Investigated performance differences across categories such as Entertainment, Music, and People & Blogs, with Entertainment channels having the highest number of top performers.

<p align="center">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/Dashboard%20and%20Reports/Youtube_Category%20report.png" alt="Youtube Category report">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/Dashboard%20and%20Reports/Youtube_SubCategory%20report.png" alt="Youtube SubCategory report">  
</p> 
  
- YouTuber Types and Awards: Analyzed how YouTube Creator Awards (e.g., Silver, Gold, Diamond Play Buttons) correlate with subscriber counts and views.

<p align="center">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/Dashboard%20and%20Reports/Youtube_TypeofYoutuber%20report.png" alt="Youtube TypeofYoutuber report">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/Dashboard%20and%20Reports/Youtube_YoutubeCreatorAwards%20report.png" alt="Youtube YoutubeCreatorAwards report">  
</p> 

Link to Full Dashboard and Reports: [here](https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/Dashboard%20and%20Reports/BI_Youtube_Dashboard_Reports.pdf)


## Key Insights
- **Growth Trends**: YouTube channels have shown consistent growth over the years, but subscriber trends have plateaued for top-performing channels in recent years, likely due to increased competition and changing viewer preferences.
- **Regional Insights**: The majority of top YouTube creators come from India and the United States, with channels in these regions showing the highest engagement and subscription rates.
- **Content Categories**: Categories like Entertainment and Music dominate in terms of both channel count and viewership, while niche categories like Nonprofits & Activism and Autos & Vehicles have much smaller representation.
- **Influence of Video Length and Frequency**: Channels with higher upload frequency and longer video content tend to have better subscriber growth and viewer engagement.
- **Impact of YouTube Creator Awards**: Channels with YouTube Creator Awards tend to exhibit higher engagement metrics, indicating the importance of community recognition.

## Tools and Technologies
- **Python**: Used for data preprocessing and cleaning, including handling missing data and transforming raw data into usable formats.
- **Power BI**: Utilized for data visualization, modeling, and performing detailed analysis. Dashboards were created to present insights clearly and effectively.
- **Excel**: Employed during the initial stages for exploratory data analysis (EDA) and descriptive statistics.

## Challenges
- **Data Quality Issues**: Handling missing and inconsistent data was a significant part of the data preprocessing stage, requiring a robust approach to ensure clean, usable data.
- **Complexity of Analysis**: Given the large variety of categories and countries, segmentation and categorization required careful planning to ensure meaningful insights could be drawn.

## Conclusion and Recommendations
This project provided actionable insights into YouTube channel performance, highlighting critical factors such as upload frequency, content type, and regional trends that affect channel success. Content creators are encouraged to:
- Increase video upload frequency and maintain high-quality content to boost subscriber growth.
- Tailor content based on regional preferences and viewer habits.
- Focus on achieving YouTube Creator Awards to increase community engagement and channel visibility.
