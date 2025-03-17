<h1>Health & Safety Data Analysis</h1>
<h3>Overview</h3>
<p>This repository contains a dataset of health and safety incidents, including details such as the date, number of incidents, near misses, lost hours, injuries, vehicle incidents, site, business unit, severity, and most frequent injury. The primary goal of this project is to analyze and visualize health and safety data to identify trends, improve safety measures, and reduce incidents.</p>

<h3>Dataset</h3>
<p1>The dataset Health & Safety.xlsx includes the following columns:</p1>
<ul>
<li>Date: Date of the incident.</li>
<li>Incidents: Number of incidents reported.</li>
<li>Near Miss: Number of near-miss incidents.</li>
<li>Lost Hours: Number of hours lost due to incidents.</li>
<li>Injuries: Number of injuries reported.</li>
<li>Vehicle Incidents: Number of vehicle-related incidents.</li>
<li>Site: Site where the incident occurred.</li>
<li>Business Unit: Business unit associated with the incident.</li>
<li>Severity: Severity level of the incident (e.g., Minor, Major, Critical).</li>
<li>Most Frequent Injury: Most frequent type of injury reported.</li>
</ul>

<h3>Steps to Analyze Health & Safety Data Using Power BI</h3>
<ol>
<li> Import the Dataset</li>
Open Power BI Desktop.
Click on Home > Get Data > Excel.
Select the Health & Safety.xlsx file and click Open.
Select the relevant sheet and click Load to import the data into Power BI.
<li>  Data Preparation</li>
Once the data is loaded, you can see it in the Fields pane.
Click on Transform Data to open the Power Query Editor.
In the Power Query Editor, you can perform various data cleaning and transformation tasks such as:
Removing unnecessary columns.
Handling missing values.
Changing data types.
Filtering rows based on specific criteria.
<li>  Create Relationships </li>
If you have multiple tables and need to create relationships between them:

Go to the Model view.

[image alt](https://github.com/Softechanalytics/-Health_Safety_Report/blob/44bb071289de3b70109caafea7633cf2e6b6cd21/Data%20model.png)
Drag and drop fields to create relationships between tables.
<li>  Create Visualizations</li>
Go to the Report view.
Use the Visualizations pane to create various charts and graphs. Here are some examples:
Incidents by Severity
Visualization Type: Bar Chart
Steps:
Select the Severity field.
Choose the Bar Chart visualization.
Add Incidents to the values.
Distribution of Incidents by Site
Visualization Type: Column Chart
Steps:
Select the Site field.
Choose the Column Chart visualization.
Add Incidents to the values.
Most Frequent Injuries
Visualization Type: Pie Chart
Steps:
Select the Most Frequent Injury field.
Choose the Pie Chart visualization.
Add Incidents to the values.
Incidents Over Time
Visualization Type: Line Chart
Steps:
Select the Date field.
Choose the Line Chart visualization.
Add Incidents to the values.
<li>  Create Dashboards</li>
Combine multiple visualizations into a single dashboard.
Use slicers to filter data dynamically.
Add titles, labels, and other formatting elements to make the dashboard more informative and visually appealing.
<li>  Publish and Share</li>
Save your Power BI report.
Click on Publish to upload the report to the Power BI service.
Share the report with others by providing access through the Power BI service.
</ol>
<b></b>Example Visualizations
Here are some example visualizations you can create: </b>


<h5> Minor Incident Report </h5>

![image alt](https://github.com/Softechanalytics/-Health_Safety_Report/blob/0a64e11faa508cb12b70a0f75f3f56d83f10d2cf/Minor.png)
<h5> Major Incident Report </h5>

![image alt](https://github.com/Softechanalytics/-Health_Safety_Report/blob/357d02f29826f733c9ae2839342d676e66d82190/Major.png)
<h5> Critical Incident Report </h5>

![image alt](https://github.com/Softechanalytics/-Health_Safety_Report/blob/6b3feb7e9d7400a5da5620f8fb3669098993091e/critical.png)

<h3>Contributing</h3>
Contributions are welcome! Please feel free to submit a Pull Request.

<h3>License</h3>
This project is licensed under the MIT License - see the LICENSE file for details.

<h3>Contact</h3>
If you have any questions or suggestions, please feel free to contact me at Chuks@softechanalytics.com
