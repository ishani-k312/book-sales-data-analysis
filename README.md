## Project Description
This project analyzes book sales data to uncover trends in publishing, author performance, publisher revenue, and reader preferences. Using Python with Pandas and Matplotlib, I performed data cleaning, statistical analysis, and created 13 visualizations to extract actionable insights.

## Dataset
- <a href = "https://github.com/ishani-k312/book-sales-data-analysis/blob/main/Books_Data_Clean.csv">Data Set</a>



## Methodology
**1. Data Processing & Cleaning**
- Imported libraries and loaded dataset using Pandas
- Validated data structure and checked column headings
- Generated statistical summary using `describe()`
- Data cleaning: filtered `publish_year > 1900`, removed blanks and duplicates

**2. Exploratory Data Analysis** 
- Groupby operations: analyzed author ratings and publisher revenue
- Pivot table analysis: Publisher vs Revenue comparison
- Value counts: language code distribution

**3. Data Visualization - 13 Charts**
| Chart Type | Analysis |
| --- | --- |
| **Histogram** | Distribution of publishing years |
| **Bar Chart** | Books per genre, Top 10 Authors of highest gross sales |
| **Scatter Plot** | Sale price vs units sold, Avg rating vs rating count |
| **Box Plot** | Rating count by genre, Units sold by author rating |
| **Pie Chart** | Language code distribution |
| **Line Chart** | Publishing year vs units sold trend |
| **Pivot Table** | Publisher vs Revenue analysis |


<img width="608" height="455" alt="Total units sold over the years" src="https://github.com/user-attachments/assets/7855a230-17e7-423b-b0af-492f8da92bac" />




## Key Insights
1. Identified peak publishing years and sales trends over time using line chart
2. Determined top-performing publishers and authors by revenue using groupby + pivot
3. Found relationship between book pricing and units sold via scatter plot
4. Analyzed rating patterns across genres and authors using box plots
5. Mapped language distribution and market share with pie chart

## Skills Demonstrated
Data Cleaning, EDA, Statistical Analysis, Groupby, Pivot Tables, Data Visualization, Python Pandas, Matplotlib, Seaborn
