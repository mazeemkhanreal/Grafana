# Jobs & Salaries in Data Science
Basic visualization Dashboard built on Grafana.

This data was originally fetched from Kaggle.

[Kaggle Source](https://www.kaggle.com/datasets/hummaamqaasim/jobs-in-data)


## ABOUT THE DATASET
<ins>work_year:</ins> The year in which the data was recorded. This field indicates the temporal context of the data, important for understanding salary trends over time.

<ins>job_title:</ins> The specific title of the job role, like 'Data Scientist', 'Data Engineer', or 'Data Analyst'. This column is crucial for understanding the salary distribution across various specialized roles within the data field.

<ins>job_category:</ins> A classification of the job role into broader categories for easier analysis. This might include areas like 'Data Analysis', 'Machine Learning', 'Data Engineering', etc.

<ins>salary_currency:</ins> The currency in which the salary is paid, such as USD, EUR, etc. This is important for currency conversion and understanding the actual value of the salary in a global context.

<ins>salary:</ins> The annual gross salary of the role in the local currency. This raw salary figure is key for direct regional salary comparisons.

<ins>salary_in_usd:</ins> The annual gross salary converted to United States Dollars (USD). This uniform currency conversion aids in global salary comparisons and analyses.

<ins>employee_residence:</ins> The country of residence of the employee. This data point can be used to explore geographical salary differences and cost-of-living variations.

<ins>experience_level:</ins> Classifies the professional experience level of the employee. Common categories might include 'Entry-level', 'Mid-level', 'Senior', and 'Executive', providing insight into how experience influences salary in data-related roles.

<ins>employment_type:</ins> Specifies the type of employment, such as 'Full-time', 'Part-time', 'Contract', etc. This helps in analyzing how different employment arrangements affect salary structures.

<ins>work_setting:</ins> The work setting or environment, like 'Remote', 'In-person', or 'Hybrid'. This column reflects the impact of work settings on salary levels in the data industry.

<ins>company_location:</ins> The country where the company is located. It helps in analyzing how the location of the company affects salary structures.

<ins>company_size:</ins> The size of the employer company, often categorized into small (S), medium (M), and large (L) sizes. This allows for analysis of how company size influences salary.

## TRANSFORMATION OF DATASET INTO A DATABASE

This data was then dumped after refining into postgresql containarized database.
> [!NOTE]  
> Essential details for users who want to further touchbase on dockerization & Customization of POSTGRESQL IMAGE.


![image](https://github.com/mazeemkhanreal/Grafana/assets/75322899/93f1d8e4-cd10-4c50-9887-dabb3fa46de9)

## Grafana Visualization 

Following Grafana Panels were utilized with their detailed editing in creation of this dashboard:
* [Stat](https://grafana.com/docs/grafana/latest/panels-visualizations/visualizations/stat/)
* [Pie Chart](https://grafana.com/docs/grafana/latest/panels-visualizations/visualizations/pie-chart/)
* [Guage](https://grafana.com/docs/grafana/latest/panels-visualizations/visualizations/gauge/)
* [GeoMap](https://grafana.com/docs/grafana/latest/panels-visualizations/visualizations/geomap/)
* [BarChart](https://grafana.com/docs/grafana/latest/panels-visualizations/visualizations/bar-chart/)
* [Table](https://grafana.com/docs/grafana/latest/panels-visualizations/visualizations/table/)

Data visualization with grafana using all basic grafana plugins with standard column customizations:
![image](https://github.com/mazeemkhanreal/Grafana/assets/75322899/251444b8-a34a-46df-850c-2dbee401ba64)


Further, Breakdown of the data visualization panel wise.

![image](https://github.com/mazeemkhanreal/Grafana/assets/75322899/a34fbad8-79bc-4df0-a357-9e6d8803e07a)
Sample size of Salaries Country wise on Map visualization.


![image](https://github.com/mazeemkhanreal/Grafana/assets/75322899/39b0338f-1e0d-45bd-8e17-1c5a491e62c7)
Job Category wise highest Salary Distribution


![image](https://github.com/mazeemkhanreal/Grafana/assets/75322899/5d83a062-2711-4365-9e24-4a03278d7ba7)
Types of work setting wise highest Salary Distribution


![image](https://github.com/mazeemkhanreal/Grafana/assets/75322899/6e7f94fe-b41f-4a93-b74f-eb260d7adfd9)

Breakdown of total employees at each employee level


![image](https://github.com/mazeemkhanreal/Grafana/assets/75322899/78059853-92cd-48fd-b513-4ceb34639354)
Job Title wise Roles and Raw Table data of the dataset.


![image](https://github.com/mazeemkhanreal/Grafana/assets/75322899/b89a05da-726c-463d-a171-a999d0d033c0)
Country wise average salaries, featuring countries only having greater than 50 samples in this data set.


Furthermore ,Please refer to the JSON attached above to view detailed export file 

