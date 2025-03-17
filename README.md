<h1>Health & Safety Data Analysis</h1>h1>
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
Steps to Analyze Health & Safety Data Using Power BI
1. Import the Dataset
Open Power BI Desktop.
Click on Home > Get Data > Excel.
Select the Health & Safety.xlsx file and click Open.
Select the relevant sheet and click Load to import the data into Power BI.
2. Data Preparation
Once the data is loaded, you can see it in the Fields pane.
Click on Transform Data to open the Power Query Editor.
In the Power Query Editor, you can perform various data cleaning and transformation tasks such as:
Removing unnecessary columns.
Handling missing values.
Changing data types.
Filtering rows based on specific criteria.
3. Create Relationships (if needed)
If you have multiple tables and need to create relationships between them:

Go to the Model view.
Drag and drop fields to create relationships between tables.
4. Create Visualizations
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
5. Create Dashboards
Combine multiple visualizations into a single dashboard.
Use slicers to filter data dynamically.
Add titles, labels, and other formatting elements to make the dashboard more informative and visually appealing.
6. Publish and Share
Save your Power BI report.
Click on Publish to upload the report to the Power BI service.
Share the report with others by providing access through the Power BI service.
Example Visualizations
Here are some example visualizations you can create:

Incidents by Severity
!Incidents by Severity

Distribution of Incidents by Site
!Distribution of Incidents by Site

Most Frequent Injuries
!Most Frequent Injuries

Incidents Over Time
!Incidents Over Time
Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
If you have any questions or suggestions, please feel free to contact me at [your-email@example.com].
