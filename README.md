# healthcareanalysis
Tableau Project on Healthcare Analysis

### Tableau Public Link

This project has been uploaded to Tableau public and here is the link
https://public.tableau.com/views/CapstoneProject1_17167924483320/Healthcare?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

### Problem Statement

#### Dataset Information

The Sample - Superstore.xls excel sheet contains 3 tabs namely Orders, People and Returns. 

A) The Orders tab contains 9,994 rows and 21 columns namely 1) Row ID	2) Order ID	3) Order Date	4) Ship Date 5) Ship Mode	6) Customer ID	7) Customer Name	8) Segment	9) Country/Region	10) City	
11) State	12) Postal Code	13) Region	14) Product ID	15) Category	16) Sub-Category	17) Product Name	18) Sales	19) Quantity	20) Discount	21) Profit

B) The People tab contains 4 rows and 2 columns namely 1) Regional Manager	2) Region

C) The Returns tab contains 800 rows and 2 columns namely 1) Returned	2) Order ID

#### Instructions
Use Healthcare.xls data.
Note that you can use either Tableau Public or Desktop to find the answer.
If you are using Tableau Desktop, the Sample Superstore dataset should be present in the Saved Data sources and will also be present in your My Tableau Repository folder on your local machine.
Data should be an Extract and not a ‘Live’ connection.

#### Tableau Project Requirement
The workbook should have two dashboards.
The Workbook should have a Story consisting of several Story points based on the requirement.
Each worksheet/view/chart should meet the business requirement.
All worksheets should be hidden.
Workbook should be published to Tableau Public if possible.

#### Submission Guidelines
Copy-Paste the screenshots for every view in a word document and upload the document for verification.

#### Business Requirement
Connect to the CSV file Healthcare dataset, which includes the data regarding patients’ blood pressure, BMI, glucose, insulin, and diabetes for patients from the 20+ age group. Build 2 dashboards and then create a story using the 2 dashboards and a worksheet.

#### Dashboard 1 Requirements

Take any image regarding healthcare and drag it to the dashboard.
Using Text object, give it a meaningful name based on your data analysis of the file.

#### Dashboard 2 Requirements

##### View 1: Diabetic/Non-diabetic using Shapes
Use Shapes to show the distribution between diabetic/non-diabetic patients.
Using the “Outcome” field, write a calculated field by classifying 1 as Diabetic patients and 0 as Non-diabetic patients.
Show the percent distribution as shown in the expected view.
Use the color of your choice to differentiate Diabetic Vs. Non-diabetic patients.
Tooltip should display patient count.
You can use shapes of your choice or use the below one.
Format as per your choice.
Enable Action filters.

##### View 2: Patient summary by Blood Pressure category
Use any shape of your choice to show patient summary by blood pressure category.
Show the Patient count and BP category type on the labels.
Use the color of your choice to differentiate Diabetic Vs. Non-diabetic patients.
Format as per your choice.
Enable Action filters.

##### View 3: Create a Histogram to show Body Mass Index (BMI) by Age Groups.
Since we need to build a Histogram, using the Age field, let’s create bins using size 5.
In a Histogram, you will have bins 20, 25, 30, etc. So, the bin size 20 will include age groups between 20-24, and size 25 will include 25-29. So, to be clear let’s edit the aliases of the age groups as it might confuse the users. So, let’s use aliases as shown below or you can create a calculated field for the Age groups.
In case, there are missing values, hide them.
Display the average BMI value on top of each bar and round it to 2 decimals.
Use the average BMI to color the palette using shades of Red.

##### View 4: Single Bar showing percent distribution of patients by BMI type
Create a calculated field to classify Patients by BMI types.
[BMI]<18.5= 'Underweight'
[BMI]>=18.5 and [BMI]<25 ='Healthy Weight'
[BMI]>=25 and [BMI]<30 = 'Overweight'
[BMI]>=30 ='Obese'
Enable Action filters.

##### View 5: Bar Chart showing Patient break down by Blood Pressure and Diabetes
Create a calculated field to only highlight Diabetic patients with High and Low blood pressures.

##### View 6: Build a HEAT MAP showing several health factors by Age group

#### Story Requirements
Story Name: Healthcare
Story Title: Healthcare Summary Report
Story description: Add one if you wish to
Story size:  Custom Size (best choice)
Story Layout: Navigator style should be set to Numbers
Story Point 1: Should contain Dashboard 1
Story Point 2: Should contain Dashboard 2
Story Point 3: Should contain Heat Map Worksheet

### Purpose of Solving this problem

Analyzing patient healthcare data such as blood pressure, BMI, glucose levels, insulin, and diabetes for patients aged 20+ using Tableau can serve numerous critical purposes in healthcare management, prevention, and policy formulation. Tableau's data visualization capabilities help uncover insights that can improve patient outcomes and resource allocation. Here are some key purposes:

#### 1. Monitoring Patient Health Trends
Chronic Disease Trends: Identify the prevalence of diabetes, hypertension, and obesity in the 20+ age group.
Risk Factors: Analyze correlations between BMI, glucose, insulin levels, and the likelihood of developing chronic conditions.
Population Health Metrics: Understand the average health parameters of the population to benchmark against health standards.

#### 2. Early Disease Detection and Prevention
High-Risk Groups: Detect individuals or subgroups with abnormal blood pressure, glucose, or insulin levels to target preventive measures.
Warning Signs: Visualize trends that indicate worsening conditions, such as rising BMI or increasing glucose levels over time.
Screening Effectiveness: Evaluate how well screening programs are identifying at-risk patients.

#### 3. Tailoring Patient Care Plans
Personalized Interventions: Segment patients based on their health metrics to recommend tailored lifestyle changes, diets, or treatments.
Treatment Outcomes: Assess how interventions (e.g., insulin therapy or weight management programs) impact specific metrics like glucose or BMI.

#### 4. Resource Allocation and Planning
Healthcare Demand: Predict resource needs, such as insulin supplies or hypertension management programs, based on patient data trends.
Facility Utilization: Identify regions or populations with higher healthcare needs to allocate resources effectively.
Program Prioritization: Focus on age groups or demographics with the most critical health challenges.

#### 5. Understanding Demographic Variations
Age-Specific Trends: Explore how health metrics differ within subgroups (e.g., patients in their 20s vs. 40s).
Gender Differences: Examine how conditions like diabetes or hypertension vary between males and females.
Regional Insights: Identify geographic hotspots for specific conditions to target interventions.

#### 6. Public Health Policy Development
Preventive Campaigns: Use insights to design campaigns addressing obesity, diabetes, or hypertension.
Health Equity: Identify disparities in health metrics across socioeconomic or ethnic groups.
Community Health Goals: Set measurable objectives based on analyzed trends.

#### 7. Enhancing Clinical Research
Hypothesis Generation: Identify patterns or anomalies that warrant further investigation in clinical studies.
Drug Efficacy: Analyze data to evaluate the effectiveness of medications or lifestyle interventions in managing blood pressure, glucose, and insulin.

#### 8. Improving Patient Engagement
Visual Health Dashboards: Create interactive dashboards that patients can view to understand their health metrics and progress.
Education: Help patients see how changes in lifestyle affect metrics like BMI or glucose levels.

#### Why Tableau for This Analysis?

Interactive Dashboards: Enable healthcare professionals to drill down into specific patient groups or metrics.
Cross-Filtering: Correlate metrics like glucose and insulin to uncover complex health relationships.
Data Integration: Combine data from multiple sources (e.g., lab results, patient history) for comprehensive insights.
Custom Alerts: Highlight patients or metrics outside normal ranges.
Geospatial Analysis: Map health trends by region to visualize geographic disparities.

#### Outcome
Analyzing patient healthcare data in Tableau can lead to better chronic disease management, informed healthcare policies, efficient resource allocation, and improved individual and population health outcomes. It ensures healthcare providers and policymakers can act proactively rather than reactively, improving overall quality of care.









