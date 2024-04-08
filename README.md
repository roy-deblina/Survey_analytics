# Survey_analytics
#Objective:

The primary objective of this project is to analyse survey data to uncover key insights regarding professionals in the data field. By examining various facets such as demographics, career trajectories, salary trends, preferred programming languages, and job satisfaction, the project seeks to provide valuable perspectives on the state of the data industry.

#Power BI File Transformation:

Removed unnecessary columns such as from "browser" to "referrer" as it is empty.

Cleaned the "Title" column by categorising all titles except the primary one into "Others." For that splitted the "Title" column by delimiter (,) and  the leftmost delimiter chosen to separate the titles. Go to "Split Column" > "Custom" and use "," as the delimiter, as it's followed by a parenthesis in the titles.

Duplicated the "Current Yearly Salary" column and splitted both columns by digit to non-digit. Now, we have simplified occupation titles, and the extra column will be removed.

To remove any "+ value" after 225, a custom column was created for average salary calculation: (Lower Range + Higher Range) / 2. Changed the data type of both salary columns to whole numbers. Arranged the average salary column beside the original salary column.

#Visualisation

Text Box and Card:

Added a text box with a title of the project ‘Data Professional Survey Background” and background colour.
Create a card for unique IDs, counting the number of unique IDs to count the number of survey takers.
Create a card for visualising the average age of survey.

Stacked Bar Chart:

Added a stacked bar chart to understand the average salary by different job titles.
Included average salary and job title in x and y axis respectively.
Converted the data type of average salary from text to decimal numbers and in the bar customisation changed the colour of each bar to make a colourful visualisation.

Stacked Column Chart:

Added a Stacked Column chart to understand the Unique ID by favourite Programming Language.
Included Favourite Programming Language and count of Unique ID in x and y axis respectively and in the data label, job title is added to understand the visual by different job titles and legend set in top centre of the chart.



Gauge:

Two gauges added to understand the average of happiness of current position with salary and minimum and maximum values of each value also added to visualise the range and to understand happiness with work/life balance and here aso minimum and maximum values of each value also added to visualise the range.

Donut Chart:

Donut chart added to understand the percentage of male and female average salary. For that Average of average salary added to values and male/female is added to the legends.

Tree Map:

Tree Map created to understand the country of survey takers. For that country of living added to the category and count of country of living added to the values and category labels set on to understand each part well.


#Insights

The analysis of the survey data reveals several noteworthy insights. Firstly, the total count of survey participants amounts to 630, indicating a substantial dataset for analysis.

Secondly, the average age of survey participants ranges from 29 to 30 years, suggesting a relatively young demographic engaging in the surveys.

Interestingly, female participants slightly outnumber male participants in survey participation, indicating a balanced representation across genders.

Moreover, the United States emerges as the primary contributor to the survey dataset, with a significant presence of professionals from this region compared to other countries. Conversely, Canada has the fewest contributors, suggesting variations in participation rates across different regions.

In terms of professions, Data Scientists command the highest average salary, reflecting the demand and value associated with their skill set in the industry.

The survey data also highlights Python as the most favoured programming language among professionals, underscoring its widespread adoption and versatility in various domains.

Furthermore, Data Analysts constitute the largest group among survey takers, indicating a significant interest and representation from this professional category.

Lastly, the overall happiness with salary scores 4.76 out of 10, while happiness with work/life balance scores 5.74 out of 10, suggesting areas for potential improvement in both salary satisfaction and work-life balance among professionals surveyed.

In conclusion, these insights provide valuable information about the demographics, preferences, and sentiments of professionals surveyed, offering opportunities for organisations and stakeholders to tailor strategies and initiatives to better meet the needs and expectations of the workforce.
