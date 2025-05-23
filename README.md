📊 Data Engineering Portfolio by Erick Arias

Welcome to my data engineering project portfolio! 
This repository showcases a series of applied data projects focusing on ETL automation, natural language processing, predictive analytics, and simulation optimization using machine learning. Each project was selected to emphasize robust data pipelines, model optimization, and impactful visualization.

🔧 Project 1: Invoice Parser & Automated Oil Change Reminder
Description:
An end-to-end NLP and automation pipeline that extracts structured information from unstructured auto service invoices and uses it to trigger oil change reminders based on historical service patterns.

Highlights:

Optical Character Recognition (OCR) and pattern extraction from scanned PDFs.

Vehicle mileage parsing and service type classification via custom logic.

Triggered reminders using basic scheduling logic.

How to Use:

Clone the repository and install dependencies listed in requirements.txt.

Run the Jupyter Notebook Invoice Parser Automated Oil-Change-Reminder.ipynb.

Drop PDF invoices into the target folder and observe the extracted structured table.

Review parsed mileage and flagged reminder candidates at the end of the notebook.

Strengths:
This project demonstrates strong text parsing, data cleansing, and domain-specific logic building — key traits in practical data engineering workflows involving unstructured data.

📦 Project 2: Dropship Sales Profiler
Description:
A lightweight yet insightful analysis of sales trends across a simulated dropshipping dataset to identify product performance, geographic buying trends, and fulfillment anomalies.

Highlights:

Real-world simulation of SKU-level sales performance.

Time series segmentation and peak detection.

Groupby aggregation for product, customer, and region-level KPIs.

How to Use:

Open and run Dropship Project.ipynb.

Inspect breakdowns by city, top-selling categories, and high-volume customer segments.

Modify filtering cells to analyze subsets of the data interactively.

Strengths:
This project is a snapshot of practical sales ETL and customer trend analysis. It focuses on rapid prototyping with Pandas and Matplotlib to deliver insights that would be useful for decision-making dashboards.

📉 Project 3: Regression Model for Fusion Energy Simulations
Description:
A detailed scientific study evaluating inverse models for predicting fusion reactor conditions using RF deposition outputs. It uses Random Forest Regressors with hyperparameter tuning and k-fold validation to reverse-map plasma conditions from simulation results.

Highlights:

9-variable conditional regression using random forests.

Extensive model evaluation across k-folds and hyperparameter spaces.

Inclusion of auxiliary x-ray data and its correlation with improved model accuracy.

Error visualization by feature across best and worst-case predictions.

How to Use:

Read the project whitepaper: Evaluating_an_Optimized_Inversed_Data_Regression_Model_for_Weakness_and_Correlation_of_Input_Variables.pdf.

To replicate, adapt code from the described GitHub repo https://github.com/ariaserick25/Modeling-MSE.git (if public).

Focus on sections discussing n_estimators optimization and MSE breakdowns across input conditions.

Strengths:
Showcases high-level modeling, scientific rigor, and statistical evaluation. Demonstrates an engineer's ability to support simulation-based research with optimized and interpretable ML models.

📈 Project 4: Sales Performance Dashboard (Power BI)
Description:
An interactive Power BI dashboard that visualizes a company's sales KPIs including revenue trends, gross profit, service distribution, and customer segmentation.

Highlights:

Dynamic filters for time periods, regions, and service types.

KPI cards, clustered column charts, and decomposition trees.

Real-time analytics ready for business presentation.

How to Use:

Open Sales Performance Dashboard.pbix in Power BI Desktop.

Interact with slicers and visuals to uncover patterns in service types, sales volume, and profits.

Modify queries in Power Query Editor to link with refreshed data sources.

Strengths:
Demonstrates front-end BI skills for conveying analytical outputs to stakeholders. This dashboard ties back to the data pipelines engineered in earlier projects, completing the analytics lifecycle.

🛠 Tech Stack
Languages: Python, SQL

Tools: Jupyter Notebooks, Power BI, scikit-learn, pandas, matplotlib, ONNX

Skills Demonstrated: ETL automation, data parsing, model optimization, dashboard design, k-fold validation

📬 Contact
Erick Arias
Data Engineer & Applied Machine Learning Enthusiast
📧 ear...@mail.sfsu.edu
🌐 LinkedIn Profile
