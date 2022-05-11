# NYC 311 Calls Analysis
- Author(s): Alessandro Cuadros, Amanda Ma, Louise Jiang, Xinru Wang
- Date created: May 7, 2022
- Class: CIS 9440 (Baruch College - Zicklin School of Business)

## Project Objective 
Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Application

## Project Tools
The tools used to build this Data Warehouse were:
1. For data integration - Python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

# Kimball Lifecycle Project Stages

## Project Planning

### Motivation for project:
To get a detailed view at NYC's 311 calls. 

### Description of the issues or opportunities the project will address:
Allocation of resources is one of the primary issues that could be addressed by this study. For example, agencies who see higher traffic of open cases could benefit from acquiring more resources from their local government.

### Project Business or Organization Value:
(state value here)

# Data Sources:
1. [311 Service Requests from 2010 to Present](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9)
2. [NYC Community Districts](https://data.cityofnewyork.us/City-Government/Community-Districts/yfnk-k7r4)

# Business Requirements Definition

List of Data Warehouse KPI's:
1. Total Complaints per Borough
2. Number of Cases Handled by Agency
3. Top NYC Agencies
4. Average Noise Complaints per Week
5. Ratio of Closed and Open Cases per Agency

## Dimensional Model

This project's Dimensional Model consists of 2 Facts and 5 Dimensions

Use correct file path here to show picture of dimensional model...
![Alt text](/img/dimensional_model.JPG)

This project's Kimball Bus Matrix:

Use correct file path here to show picture of dimensional model...
![Alt text](/img/kimball_bus_matrix.JPG)

# Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Bar Chart for comparison of the five boroughs and the total calls made per borough
2. Bar Chart for comparison of the different agencies and the cases they each handled
3. Pie Chart for comparison of the top 3 NYC agencies and their allocation %
4. Line Chart for comparison of weekly number of noise complaints 
5. Two Bar Chart for comparison of closed versus open cases ratio

BI Application Wireframe design:

Use correct file path here to show picture of Wireframe design...
![Alt text](/img/wireframe_design.JPG)

Picture of final Dashboard:

Use correct file path here to show picture of Dashboard...
![Alt text](/img/Dashboard.JPG)

### Deployment

The project was deployed on Tableau Public:
[Map Dashboard](https://public.tableau.com/app/profile/alessandro.cuadros/viz/CommunityDistrictBreakdown/MapDashboard#1)
