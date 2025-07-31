## Project Overview
This project demonstrates the **Analyze and Activate** stages of the data journey by building an interactive business intelligence dashboard using **Looker Enterprise**. Developed as part of a Google Cloud Skills Boost lab, this dashboard provides key insights into loan health data for a fictitious financial institution, The Look Fintech.

## Business Need
The Treasury department at The Look Fintech required a user-friendly dashboard to monitor their loan portfolio. This dashboard was designed to answer four critical business questions:
1.  What is the total outstanding amount of all loans?
2.  What is the percentage of outstanding loans in each status category?
3.  What states have the highest number of outstanding loans?
4.  What customers own their homes outright and have current loans?

## Key Features of the Dashboard:
*   **Total Outstanding Loans:** A single-value visualization that dynamically changes color (red if over $3 Billion) to indicate the total outstanding balance.
*   **Percentage of Outstanding Loans by Status:** A pie chart illustrating the distribution of loans across different statuses (e.g., Current, Late, Charged Off).
*   **Top 10 States by Outstanding Loan Count:** A visualization (e.g., bar chart) showing geographical loan distribution and concentrations.
*   **Top 10 Customers by Highest Income (with specific criteria):** A table displaying details for high-income, home-owning customers with current loans.
*   **Cross-filtering:** Enabled interactivity allowing users to filter the entire dashboard by clicking on values in individual visualizations.
*   **Automated Refresh Rates:** Configured different refresh intervals for various tiles to ensure data freshness while optimizing performance.

## Technologies Used
*   **Looker Enterprise:** For data exploration, visualization, and dashboard creation.
*   **Google Cloud Platform:** Underlying infrastructure for the lab environment.
*   **Data Analysis & Visualization Principles**

### **Important Note on Live Access:**
The dashboard was built in a temporary, lab-provided Looker Enterprise instance (https://jmnkymxiamw35f46x3ecfasqtl7jfl4xx3bhstafrv3hwjjqhpna.us-central1-b.resources.bumper-boats-00.services.qwiklabs.com/dashboards/1).

### Dashboard Overview:
<img width="924" height="437" alt="Loan" src="https://github.com/user-attachments/assets/c7088021-8685-4b85-8e0c-67cabb651b34" />
