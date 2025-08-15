AirPure Innovations: A Data-Driven Market Fit Analysis
📊 Project Overview
This repository contains a comprehensive market fit analysis for AirPure Innovations, a startup entering India's $507.5M air purifier market. The project develops a data-driven, go-to-market strategy by analysing real-time AQI patterns, public health data, consumer search trends, and the competitive landscape to identify critical business opportunities.

🎯 Key Findings
Market Size: The market is valued at USD 507.5M and is projected to grow at a 14.06% CAGR.

Critical Markets: The analysis identifies 4 high-priority cities in the Indo-Gangetic Plain as the prime targets for market entry.

Health Impact: Severe air pollution leads to an average 5.3-year reduction in life expectancy, creating a strong, health-driven consumer demand.

Market Opportunity: A significant opportunity exists for a product with superior VOC filtration and smart features, targeting the mid-range price segment.

📈 Dashboard Highlights
An interactive, four-page Power BI dashboard was created to provide executive-level insights.

Market Metrics: High-level analysis of market size, growth rate, and health impact.

Geographic Analysis: An interactive map with a dynamic City Risk Score to identify priority markets.

Seasonal & Demand Analysis: A heatmap of seasonal pollution trends and a correlation analysis proving that pollution spikes drive consumer demand.

Competitive Landscape: A feature-gap matrix and strategic recommendations for product positioning and R&D.

<img width="1391" height="781" alt="Screenshot 2025-08-15 154749" src="https://github.com/user-attachments/assets/195ff468-ebba-4982-93ab-d7064f7e4824" />


🛠️ Methodology
The project followed a structured, four-phase analytical process:

Data Extraction & Transformation (ETL): Raw CSV datasets (AQI, Health, Population, Vehicle Data) were ingested into a Jupyter Notebook. Using Pandas, the data was cleaned, transformed, and structured into a star schema with fact and dimension tables.

Data Modelling: The cleaned tables were loaded into Power BI, where relationships were established to create a robust and efficient data model, optimised for analysis.

DAX & Analysis: A comprehensive suite of advanced DAX measures was developed to perform the analysis, calculating key metrics like the Enhanced City Risk Score, AQI YoY Growth, and Market Opportunity Matrix.

Dashboard & Visualisation: The final insights were presented in a four-page interactive Power BI dashboard designed to tell a clear story, from identifying the problem to presenting the final strategic solution.

💻 Tech Stack
Analysis: Python (Pandas, NumPy)

Visualisation: Power BI, Matplotlib

Data Sourcing: Web Scraping (BeautifulSoup), Google Trends API, Public Datasets

🚀 How to View This Project
View the Dashboard: The interactive Power BI dashboard can be found in the /powerbi folder.

Explore the Analysis: The Jupyter Notebooks detailing the data cleaning, transformation, and exploratory data analysis process are in the /notebooks folder.

📋 Business Impact & Strategic Recommendations
Market Entry: Focus on Delhi-NCR and other Tier-1 cities in the Indo-Gangetic Plain for the initial launch.

Timing: Launch in Q3 to build awareness just ahead of the peak winter pollution season (Q4), which is the primary buying period.

Product: Engineer a product with superior VOC filtration and smart features to fill identified gaps in the competitive landscape.

Marketing: Leverage the powerful health-impact data (e.g., "5.3 years of life lost") to create a sense of urgency and position the product as a health essential.
