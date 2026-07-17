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

**3. Data Visualization - Charts**
| Chart Type | Analysis |
| --- | --- |
| **Histogram** | Distribution of publishing years |
| **Bar Chart** | Books per genre, Top 10 Authors of highest gross sales |
| **Scatter Plot** | Sale price vs units sold, Avg rating vs rating count |
| **Box Plot** | Rating count by genre, Units sold by author rating |
| **Pie Chart** | Language code distribution |
| **Line Chart** | Publishing year vs units sold trend |
| **Pivot Table** | Publisher vs Revenue analysis |


<img width="582" height="455" alt="Distibution of the Publishing Year" src="https://github.com/user-attachments/assets/4689fa67-2f06-401f-81aa-74d9bb48db28" />
<img width="389" height="411" alt="Distribution of languages" src="https://github.com/user-attachments/assets/c00631a7-f84a-4dba-acc6-39fad1de573a" />
<img width="571" height="528" alt="Number of books in each year" src="https://github.com/user-attachments/assets/46a257ab-f952-4bd8-bd4b-93b24a0701af" />
<img width="597" height="455" alt="Number of ratings for each genre" src="https://github.com/user-attachments/assets/2d19b843-0269-45e4-860c-8fa7e50c70c2" />
<img width="589" height="455" alt="Relationship between Author Rating   units sold" src="https://github.com/user-attachments/assets/78823287-ece9-43d9-8d30-03dadf73314c" />
<img width="616" height="455" alt="Relationship between Book average rating   Book ratings count" src="https://github.com/user-attachments/assets/28a21371-b347-47ed-aa84-ceeea42d1cd6" />
<img width="590" height="455" alt="Relationship between Sales Price and Unit Sold" src="https://github.com/user-attachments/assets/75e3784f-7dbf-488b-8270-e50935576e43" />
<img width="589" height="626" alt="Top 10 Authors of highest gross sales" src="https://github.com/user-attachments/assets/397e9e15-9722-471a-bee4-53a38401cf71" />
<img width="608" height="455" alt="Total units sold over the years" src="https://github.com/user-attachments/assets/128946f7-fd9b-4ac1-b908-d1b7442c052c" />












## Key Insights
1. Identified peak publishing years and sales trends over time using line chart
2. Determined top-performing publishers and authors by revenue using groupby + pivot
3. Found relationship between book pricing and units sold via scatter plot
4. Analyzed rating patterns across genres and authors using box plots
5. Mapped language distribution and market share with pie chart

## Skills Demonstrated
Data Cleaning, EDA, Statistical Analysis, Groupby, Pivot Tables, Data Visualization, Python Pandas, Matplotlib, Seaborn
