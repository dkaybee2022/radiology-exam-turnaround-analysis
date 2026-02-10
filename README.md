# Radiology Exam Turnaround Time Analysis (SQL)
## Business Question

### How long does it take radiologists to read exams, and how does performance vary across different modalities? This analysis helps identify efficiency patterns and potential areas for improvement in clinical operations.

## Dataset

Mock radiology operations data

## Contains:

- Exam start and end times

- Radiologist identifiers

- Exam modality

- Revenue per exam

## Approach

- Calculated exam duration in minutes using start and end timestamps.

- Used CTEs in SQL to create reusable metrics.

- Aggregated data to evaluate:

- Average exam duration per radiologist

- Average exam duration per modality

- Revenue per minute per radiologist

## Key Metrics & Insights

- Average Exam Duration by Radiologist:


- Average Exam Duration by Modality:


## Insights:

- Exam read times vary significantly by radiologist.

- Certain modalities consistently take longer to interpret.

- Revenue per minute highlights operational efficiency differences between radiologists.

## Skills Demonstrated

- SQL analytics: CTEs, aggregations, date/time calculations

- Data transformation and metric creation

- Business-focused insights and storytelling

- Presenting technical results visually

## Tools

- SQL (SQLite)

- Excel (for mock data creation)

### This project demonstrates how raw operational data can be transformed into actionable insights. It’s a simple but real-world example of data-driven decision making in healthcare operations.
