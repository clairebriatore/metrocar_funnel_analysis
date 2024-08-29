# Funnel Analysis Metrocar: Comprehensive Overview

## Objective:
The Funnel Analysis Mastery Project is designed to analyze and optimize the customer funnel of Metrocar, a ride-sharing app akin to Uber or Lyft. The primary goal is to identify areas within the customer journey that require improvement, enabling the company to enhance conversion rates, reduce drop-offs, and improve overall customer engagement. The analysis leverages SQL for data extraction and Pandas for in-depth data analysis and visualization.

## Project Overview:
Metrocar, like other ride-sharing platforms, has a multi-step customer journey from the initial user interaction to the completion of a ride. This project aims to dissect each stage of this journey using funnel analysis techniques to identify bottlenecks and areas for optimization. The insights derived from this analysis will inform actionable recommendations to enhance user experience and increase overall platform efficiency.

By applying a combination of SQL, Pandas, and advanced visualization techniques, the project will provide Metrocar with clear, data-driven recommendations to improve their ride-sharing service. 

## Data

The dataset used in this project is the [Metrocar Dataset](postgresql://Test:bQNxVzJL4g6u@ep-noisy-flower-846766-pooler.us-east-2.aws.neon.tech/Metrocar). The data includes customer information, transaction history, and riding behavior.

## Usage

To reproduce the analysis, run the Jupyter notebooks. Start Jupyter Notebook by accessing the file here:
[ metrocar_workbook.ipynb](https://github.com/clairebriatore/metrocar_funnel_analysis/blob/00461514ea8a5808b522054cd0002294894bf84a/metrocar_workbook.ipynb)

## Key Tasks of Analysis:

**Funnel Analysis:**
The central task is to conduct a comprehensive funnel analysis of Metrocar’s customer journey. This involves:

**Identifying points of user drop-off:**
Evaluating how different user segments (e.g., based on platform, age group) perform through the funnel.
Understanding the patterns of ride requests and their timing, which may reveal opportunities for implementing surge pricing.

**Data Collection and Preparation:**

SQL: Used for querying and extracting relevant data from the Metrocar database.
Pandas: Employed for cleaning, manipulating, and analyzing the data. This involves merging different tables, handling missing values, and preparing the data for visualization.
Visualization and Reporting: The project includes creating visual representations of the funnel analysis results.The use of tools like Plotly and Dash will enable the creation of interactive visualizations, allowing stakeholders to explore the data dynamically.

## Key Findings Summary

The funnel analysis of Metrocar revealed several key insights:

- Significant Drop-Offs: The largest user drop-offs occur between app download and signup (25%) and from ride acceptance to ride completion (49%). Simplifying the signup process and enhancing driver availability could help mitigate these losses.

- Platform Performance: iOS users show higher engagement, suggesting a need to prioritize budget allocation towards iOS platforms, particularly in the U.S., where higher income levels correlate with increased app revenue.

- Age Group Analysis: The primary user demographic is aged 35-44, with a significant 53% drop-off at the upper funnel stage, indicating the need for targeted strategies to improve retention.

- Surge Pricing Opportunities: Peak ride requests occur during weekday mornings and evenings, suggesting opportunities for surge pricing during these times to maximize revenue.

- Negative User Sentiment: Review analysis revealed overwhelmingly negative sentiments, particularly regarding driver professionalism and ride comfort, indicating a need for service quality improvements.

## Deliverables:

- Code Repository: Contains all SQL queries and Python scripts used for data extraction, analysis, and visualization.

- Visualizations: A collection of charts and graphs that illustrate the key findings of the funnel analysis

- Recommendations Report: A detailed report summarizing the insights gained from the funnel analysis. Actionable recommendations for improving user conversion rates, optimizing platform performance, and enhancing overall user engagement.

## Contact

For any questions or feedback, please contact:
- Name: Claire Briatore
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/claire-briatore/)


## Co-Authors

- [Lana Frenzel](https://github.com/lanafrenzel)
- [Prudensy Opit](https://github.com/prudensy)
- [Rama Al Homsi](https://github.com/rama-alhomsi)
