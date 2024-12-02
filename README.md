# Denver Airport Data Challenge - Hackathon Solution

This repository showcases the solution developed during a *Hackathon* organized by our department in collaboration with *Denver International Airport. Our project focused on cleaning, analyzing, and visualizing operational data to create insightful dashboards for both **clients (customer's perspective)* and *companies (internal perspective)*. The goal was to provide actionable insights and streamline decision-making processes.

---

## Project Overview

The challenge required us to process and integrate multiple datasets to design dashboards that addressed key operational challenges. Our final solution included *two interactive dashboards*:
1. *Customer Dashboard (Client's Perspective):*
   - Highlights customer-specific metrics such as enhancement progress and user stories.
2. *Internal Dashboard (Company's Perspective):*
   - Focuses on internal task tracking, completion states, and prioritization.

---

## Data Cleaning and Processing

We worked with two datasets:
1. *ADO_FeatureUserStorylist_V2.xlsx*  
   - Contains data on feature titles, user stories, states, and priorities.
2. *SN_enhancementlist_v2.xlsx*  
   - Includes enhancement numbers, customer names, and other attributes.

### Cleaning and Integration Steps:
- Removed duplicates and irrelevant data.
- Standardized column names for consistency.
- Combined the datasets into a single CSV file for streamlined analysis.

### Tools Used:
- *Python:* Libraries like Pandas and NumPy for cleaning and merging.
- *Excel:* Preprocessing and validation.

---

## Dashboards

### 1. Customer Dashboard (Client's Perspective)
![WhatsApp Image 2024-12-01 at 18 46 11_5ff5e8a6](https://github.com/user-attachments/assets/ce56e263-a10a-4592-84c5-2f7d2c04fd21)


Key Features:
- *Completion Tracking:* Visualizes the overall completion percentage for enhancements.
- *Customer-Specific Insights:* Displays enhancement metrics by customer.
- *Task States:* Highlights enhancement states such as Draft, Closed, and On Hold.

---

### 2. Internal Dashboard (Company's Perspective)
![WhatsApp Image 2024-12-01 at 18 41 58_93ebc4c4](https://github.com/user-attachments/assets/743eb739-5246-4400-97cb-ba0609e41960)


Key Features:
- *Task Assignments:* Tracks tasks assigned to internal team members.
- *State Analysis:* Shows task progress and current states.
- *Enhancement Overview:* Summarizes key enhancements and their priorities.

---

## Tools and Technologies

### Data Processing
- *Python:* Used for wrangling and merging datasets.
- *Excel:* For initial data cleaning and exploration.

### Visualization
- *Power BI:* Created interactive dashboards for actionable insights.
- *Power Query:* Enabled data transformations for visualization.

---

## Insights and Outcomes

- *Customer Perspective:*
  - Clients can monitor enhancement progress and track updates in real-time.
  - Simplifies understanding of feature titles and completion percentages.

- *Internal Perspective:*
  - Provides clarity on task prioritization and ownership.
  - Helps identify bottlenecks and improve operational workflows.

---

## How to Use

1. Open the Power BI report file (Hackathon.pbix) to view interactive dashboards.
2. Use available filters to explore insights by customer or task perspective.
3. Analyze the cleaned datasets for deeper insights.

---

## Challenges and Solutions

1. *Data Quality Issues:*
   - Addressed missing and inconsistent data using Python scripts.

2. *Merging Complex Data:*
   - Combined datasets seamlessly to enable unified visualization.

3. *Real-Time Insights:*
   - Designed dynamic dashboards with drill-down capabilities for in-depth analysis.

---

## Future Enhancements

- *Live Data Integration:* Connect dashboards to real-time APIs for updated insights.
- *Predictive Analytics:* Build machine learning models to forecast task delays or completions.
- *Enhanced Visualizations:* Add more metrics and trends for a comprehensive view.

---

## Files in this Repository

1. *Dashboards:*
   - Customer dashboard(Client's Perspective).png
   - Internal Dashboard(Company's Perspective).png

2. *Datasets:*
   - ADO_FeatureUserStorylist_V2.xlsx
   - SN_enhancementlist_v2.xlsx

3. *Power BI Report:*
   - Hackathon.pbix

---

## Acknowledgments

We thank *Denver International Airport* for providing the problem statement and datasets, and our department for organizing the hackathon. Collaborating on this project showcased the importance of teamwork and data-driven decision-making.

---

Feel free to explore the repository and reach out for contributions or queries!
