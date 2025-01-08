# Food Safety Insights: Analyzing Inspections in Chicago and Dallas | Alteryx, python (ydata profiling), Talend, MS Excel, MSSQL server, ER studio, Tableau, PowerBI

# Food Inspection Analysis: Chicago and Dallas  

This project provides an in-depth analysis of food inspection data from Chicago and Dallas. By exploring inspection trends, violation patterns, and other critical metrics, this project aims to enhance public health insights and improve food safety compliance.  

## Table of Contents  
1. [Project Overview](#project-overview)  
2. [Data Sources](#data-sources)  
3. [Technologies Used](#technologies-used)  
4. [Key Features and Visualizations](#key-features-and-visualizations)  
5. [Setup Instructions](#setup-instructions)  
6. [Insights and Conclusions](#insights-and-conclusions)  
7. [Future Work](#future-work)  

---

## Project Overview  
The project analyzes food inspection data from Chicago and Dallas to:  
- Identify patterns and trends in inspection outcomes.  
- Highlight high-risk establishments.  
- Provide actionable insights for public health authorities.  

## Data Sources  
- **Chicago Food Inspections Dataset**: Publicly available through the Chicago Open Data Portal.  
- **Dallas Food Inspections Dataset**: Extracted from the Dallas Open Data Portal.  

Both datasets include detailed information about inspection dates, types, outcomes, and violations.  

## Technologies Used  
- **Programming Language**: Python  
- **Libraries and Tools**:  
  - Pandas and NumPy for data preprocessing  
  - Matplotlib and Seaborn for visualizations  
  - Plotly for interactive dashboards  
  - Jupyter Notebook for prototyping  
  - SQLite for data storage and querying  

## Key Features and Visualizations  

### 1. Inspection Trends  
**Visualization:**  
A time-series plot displaying the number of inspections conducted monthly, highlighting trends over time.  

**Insights:**  
- Identify peaks and dips in inspection activities.  
- Analyze patterns related to seasons or public health campaigns.  

---

### 2. High-Risk Establishments  
**Visualization:**  
A heatmap showcasing geographical zones with the highest number of failed inspections.  

**Insights:**  
- Pinpoint areas requiring focused regulatory actions.  
- Assist authorities in prioritizing inspections.  

---

### 3. Violation Analysis  
**Visualization:**  
Bar charts and word clouds highlighting common violations reported during inspections.  

**Insights:**  
- Recognize frequently occurring violations.  
- Address recurring issues through training and enforcement.  

---

### 4. Outcome Comparison  
**Visualization:**  
Pie charts comparing inspection outcomes (Pass, Fail, etc.) between Chicago and Dallas.  

**Insights:**  
- Assess similarities and differences in compliance between cities.  

---

## Setup Instructions  

### 1. Clone the Repository  
```bash  
git clone https://github.com/dhirthacker7/Food_Inspections_Chicago_Dallas.git  
cd Food_Inspections_Chicago_Dallas  
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. juoyter notebook
```bash
jupyter notebook  
```

### 4. Access the Dataset
Download the datasets for Chicago and Dallas from their respective portals and place them in the data folder.

## Insights and Conclusions
#### Chicago has a higher percentage of violations related to sanitation, while Dallas sees more issues with food storage.
#### Certain neighborhoods in both cities consistently exhibit low compliance, indicating a need for targeted interventions.

## Future Work
#### Add predictive analytics to forecast inspection outcomes based on historical data.
#### Extend the project to include other major cities.
#### Automate the ETL pipeline for real-time data updates.
