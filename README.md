# 📊 Data Engineering Portfolio by Erick Arias

Welcome to my data engineering project portfolio! This repository showcases a series of applied data projects focusing on ETL automation, natural language processing, predictive analytics, and simulation optimization using machine learning. Each project was selected to emphasize robust data pipelines, model optimization, and impactful visualization.

---

## 🔧 Project 1: Invoice Parser & Automated Oil Change Reminder

**Description:**  
An end-to-end NLP and automation pipeline that extracts structured information from unstructured auto service invoices and uses it to trigger oil change reminders based on historical service patterns.

**Highlights:**
- Optical Character Recognition (OCR) and pattern extraction from scanned PDFs.
- Vehicle mileage parsing and service type classification via custom logic.
- Triggered reminders using basic scheduling logic.

**How to Use:**
1. Clone the repository and install dependencies listed in `requirements.txt`.
2. Run the Jupyter Notebook `Invoice Parser Automated Oil-Change-Reminder.ipynb`.
3. Drop PDF invoices into the target folder and observe the extracted structured table.
4. Review parsed mileage and flagged reminder candidates at the end of the notebook.

---

## 📦 Project 2: Dropship Sales Profiler

**Description:**  
A lightweight yet insightful analysis of sales trends across a simulated dropshipping dataset to identify product performance, geographic buying trends, and fulfillment anomalies.

**Highlights:**
- Real-world simulation of SKU-level sales performance.
- Time series segmentation and peak detection.
- Groupby aggregation for product, customer, and region-level KPIs.

**How to Use:**
1. Open and run `Dropship Project.ipynb`.
2. Inspect breakdowns by city, top-selling categories, and high-volume customer segments.
3. Modify filtering cells to analyze subsets of the data interactively.

---

## 📉 Project 3: Regression Model for Fusion Energy Simulations

**Description:**  
A detailed scientific study evaluating inverse models for predicting fusion reactor conditions using RF deposition outputs. It uses Random Forest Regressors with hyperparameter tuning and k-fold validation to reverse-map plasma conditions from simulation results.

**Highlights:**
- 9-variable conditional regression using random forests.
- Extensive model evaluation across k-folds and hyperparameter spaces.
- Inclusion of auxiliary x-ray data and its correlation with improved model accuracy.
- Error visualization by feature across best and worst-case predictions.

**How to Use:**
1. Read the project whitepaper: `Evaluating_an_Optimized_Inversed_Data_Regression_Model_for_Weakness_and_Correlation_of_Input_Variables.pdf`.
2. To replicate, adapt code from the described GitHub repo `https://github.com/ariaserick25/Modeling-MSE.git` (if public).
3. Focus on sections discussing `n_estimators` optimization and MSE breakdowns across input conditions.

---

## 📈 Project 4: Sales Performance Dashboard (Power BI)

**Description:**  
An interactive Power BI dashboard that visualizes a company's sales KPIs including revenue trends, gross profit, service distribution, and customer segmentation.

**How to Use:**
1. Open `Sales Performance Dashboard.pbix` in Power BI Desktop.
2. Interact with slicers and visuals to uncover patterns in service types, sales volume, and profits.
3. Modify queries in Power Query Editor to link with refreshed data sources.

---

## 🛠 Tech Stack

- **Languages:** Python, SQL
- **Tools:** Jupyter Notebooks, Power BI, scikit-learn, pandas, matplotlib, ONNX
- **Skills Demonstrated:** ETL automation, data parsing, model optimization, dashboard design, k-fold validation

---

## 📬 Contact

**Erick Arias**  
Data Engineer & Applied Machine Learning Enthusiast  
📧 ear...@mail.sfsu.edu  
🌐 [LinkedIn Profile](https://linkedin.com/in/your-link-here)
