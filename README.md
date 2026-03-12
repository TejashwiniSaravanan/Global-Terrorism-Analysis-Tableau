# 🌍 Horrors of Global Terrorism (1970-2017): A Visual Data Study

## 📝 Project Overview 

This project analyzes the Global Terrorism Database (GTD) to identify patterns, trends, and regional hotspots of terrorist activity over nearly five decades. By visualizing this complex data, the project aims to provide a logical, data-driven understanding of global security challenges to help inform strategic counter-terrorism efforts

 🔗 **Interactive Dashboard:** [View Live on Tableau Public](https://public.tableau.com/app/profile/tejashwini.saravanan/viz/TheGlobalTerrorsim/TheGlobalTerrorism)


## 🎯 Objective

  * To analyze the distribution and categories of terrorism acts worldwide.
  * To determine the most prevalent and lethal weapon types used.
  * To identify regions with the highest concentration of successful attacks to assist in strategic resource allocation

## 📊 The Dataset

* Cleaned Dataset for Analysis: [Download from Google Drive](https://docs.google.com/spreadsheets/d/1Na_GEc0VDvpfdwCib3QEfCGgah1m6cZo/edit?usp=sharing&ouid=101474871000924766896&rtpof=true&sd=true)
* Original Raw Source: [Kaggle - Global Terrorism Database (GTD)](https://www.kaggle.com/datasets/START-UMD/gtd)

## 🛠️ Data Preparation & Optimization

* To ensure the data was ready for high-impact visualization, I performed the following changes in Microsoft Excel: 
  *  Dimensionality Reduction: Narrowed the original 135 variables down to the most critical columns (e.g., Attack Type, Weapon Type, Region, and Casualty counts) to improve dashboard performance.
  *  Data Cleaning: Addressed missing values and standardized regional naming conventions to ensure accurate geospatial mapping across South Asia, Europe, and the USA.
  *  Metric Calculation: Created calculated fields for "Successful Attacks" and "Kill Success Rates" to identify patterns among the 181,691 recorded cases

☁️ **Note on Data Access:** Because the database contains over 181,000 records, the file size exceeds GitHub’s 100 MB upload limit. The Cleaned Dataset is hosted securely on Google Drive. This allows reviewers to inspect the exact data used to generate the metrics without compromising the repository's speed.


## 💡 Key Insights

* Regional Impact: South Asia represents the most volatile region, with 147.58K total attacks, significantly higher than Western Europe (56.22K) or North America (14.11K).
* Lethality Patterns: While explosives are the most frequently deployed weapon (92,426 incidents), firearms have caused a nearly equal number of fatalities (~174K each), indicating a significantly higher death-per-incident rate for firearms.
* Success Rates: Iraq has faced the highest volume of successful attacks, totaling 21.36K incidents.
* Total Human Cost: The study tracks a total of 411,868 lives lost and 523,870 individuals wounded within the study period

## 🧠 Project Reflections

* What Went Well: Successfully raised awareness and provided a comprehensive overview of 47 years of data.
* Lessons Learned: Future iterations would benefit from more recent data (post-2017) and simplified visuals for a broader audience

## 📂 Repository Navigation
This repository is organized to provide a clear path from raw data to visual insights:

* Documentation/: Contains the full Project Report and Visual Poster (PDFs) detailing the analysis of 181,691 records.
* The Global Terrorism.twbx: The original Tableau Packaged Workbook for technical review of the dashboard.
* Data Access: Since the dataset exceeds 100 MB, the cleaned Excel file is hosted on Google Drive (see link above).
* README.md: This main landing page providing the project's objective, methodology, and key insights like the 411,868 total human cost.

## 👤 Author
Tejashwini Saravanan
[LinkedIn](https://www.linkedin.com/in/tejashwinisaravanan/)
