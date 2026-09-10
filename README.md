## Project Title:
Real Time Air Quality Index Dataset: Monitoring and Forecasting Pollution Trends Across Cities
https://raw.githubusercontent.com/Archana-3009/https-www.data.gov.in-catalog-real-time-air-quality-index/refs/heads/main/3b01bcb8-0b14-4abf-b6f2-c1bfd384ba69.csv

Numpy Tutorial

## Description
This Project analyses the Assessment of Air Quality: Provide a standardized measure of pollutants (like PM2.5, PM10, NO₂, SO₂, CO, O₃) to understand how clean or polluted the air is.

Identify Trends: Track changes in air quality across cities

Enable Decision-Making: Help policymakers, city planners, and environmental agencies design interventions (e.g., traffic restrictions, industrial regulations).

Raise Awareness: Inform the public about safe vs. hazardous air conditions, often through AQI categories (Good, Moderate, Unhealthy, Hazardous).

Predictive Analysis: forecast pollution levels.

The project includes:

*  Data Cleaning & Preprocessing
*  Exploratory Data Analysis (EDA)
*  Statistical Analysis
* Data Visualization
* Interactive Power BI Dashboard
* End-to-End Automation Workflow using Python + Google Sheets + Power BI
## Dataset

| Details   | Value              |
|-----------|--------------------|
| Dataset   | Air Quality Index  |
| Source    | Data.govt.in       |
| Records   | 3514 Rows                |
| Features  | 11 Columns         |
| File Type | CSV                |


### This drive contains:
  ✅ Raw Dataset
  ✅ Cleaned Dataset
 	✅ Google Colab Note
 	✅ Python Code
 	✅ Project Report
 	✅ Power BI Dashboard Files

# Drive Link
[Link Text] (https://colab.research.google.com/drive/15iUkMUCfYkf4yqDC_s7rAU3JnTFHjAQA?usp=drive_link)

🎯 Objectives
•	Analyze major Pollutants.
•	Major Pollutant category
•	Health hazards caused by Pollutants.
•	Analyse the pollutant distribution across states & Cities.
•	Pollutant registered in Pollutant stations.
________________________________________
🛠 Tools & Technologies
| Tools & Technologies | Usage / Purpose |
|----------------------|-----------------|
| Python               | Programming & data analysis |
| Pandas               | Data manipulation & cleaning |
| KNN                  | Machine learning (imputation/classification) |
| Matplotlib           | Visualization & plotting |
| Seaborn              | Statistical visualizations |
| Google Colab         | Cloud-based coding environment |
| Power BI             | Interactive dashboards & reporting |
| Google Sheets        | Data entry & lightweight analysis |
| GitHub               | Version control & project sharing |
________________________________________
🧹 Data Preprocessing
•	Performed Exploratory Data Analysis (EDA)
•	Checked missing values
•	Verified duplicate records
•	Converted date columns
•	Removed Time column
•	Handled missing values

<img width="580" height="455" alt="image" src="https://github.com/user-attachments/assets/b7e2bc92-cca6-4244-b49f-10b07954309f" />

## Interpretation of your above chart

* Most pollutant averages fall in the lower ranges below 50.

* The KDE curve highlights the overall trend, showing a right-skewed distribution.

* Occasional extreme spikes Values above 200 - indicate severe pollution events.

* This suggests that while air quality is often acceptable, dangerous peaks do occur.

<img width="704" height="470" alt="image" src="https://github.com/user-attachments/assets/bb428175-bc04-4a68-acbd-6b76b6272c58" />

## Interpretation of your above chart* Frequency of pollutant categories (Low, Moderate, High, Very High).
## 📌 Pollutant Category Analysis

- **Feature Used:** `Pollutant_Category`
- **Low Category (~3000 records):** Majority of data → air quality is generally safe.
- **Moderate Category (~400 records):** Present but less frequent → occasional concern.
- **High Category (rare):** Severe pollution events, uncommon but important.
- **Very High Category (rare):** Extreme pollution, critical but infrequent.
- **Interpretation:** Most areas are safe, but rare extreme pollution events highlight the need for continuous monitoring.



<img width="695" height="409" alt="image" src="https://github.com/user-attachments/assets/a8695f0b-ee08-4d97-94d0-31ba36cec159" />

## Interpretation of your above chart
## 📊 Boxplot Analysis of Pollutant Averages

* **Spread and variability of pollutant averages.  
* **Feature used:** `pollutant_avg`.

### ✅ Interpretation
- The **median lies around 20**, showing the central tendency of pollution levels.  
- The **interquartile range (IQR)** highlights typical pollution levels between ~8 and ~37.  
- **Outliers above 200** represent extreme pollution spikes.  
- This confirms **variability in


<img width="850" height="525" alt="image" src="https://github.com/user-attachments/assets/3102e56b-0c40-4b81-99b7-8829e71d4212" />

## Interpretation of the above chart
## 📊 Comparison of Pollutant Groups

**What it shows:** Comparison of pollutant groups (Particulate Matter, Gaseous Pollutants, Other) with category breakdown.  
**Features used:** `Pollutant_Group`, `pollutant_avg`, `Pollutant_Category`.

### ✅ Interpretation
- **Particulate Matter:** Contributes significantly to pollution, often falling in Moderate/High ranges.  
- **Gaseous Pollutants:** Show strong averages, typically linked to traffic and industrial emissions.  
- **Other Pollutants:** Occasionally spike, adding toxic hazards.  
- **Policy Insight:** This chart helps policymakers prioritize interventions such as dust control, emission filters, and fuel standards




<img width="603" height="559" alt="image" src="https://github.com/user-attachments/assets/c31caf6b-b5da-4e53-a250-4e38d92ff018" />

## 🥧 Distribution of Pollutant Groups

**What it shows:** The pie chart illustrates the share of pollutant groups (Particulate Matter, Gaseous Pollutants, Other) in the dataset.  
**Features used:** `Pollutant_Group`, `pollutant_avg`, `Pollutant_Category`.

### ✅ Interpretation
- **Gaseous Pollutants (42.9%)** → Largest slice, indicating traffic emissions, industrial gases, and fuel combustion are dominant contributors to poor air quality.  
- **Particulate Matter (28.6%)** → Significant share, highlighting dust, construction, and crop burning as major sources.  
- **Other Pollutants (28.6%)** → Smaller but equal share, including NH₃, Pb, Benzene, which represent toxic hazards affecting neurological health.  
- **Insight:** Extreme pollution events are uncommon, but the presence of toxic pollutants makes continuous monitoring critical.  
- **Policy Relevance:** This visualization helps policymakers prioritize interventions such as dust control, emission filters, and stricter fuel standards.

### 📌 Why It’s Meaningful
This chart **summarizes the overall composition of pollution types in one glance**, making it easy for policymakers and the public to understand which pollutants are most problematic.


<img width="757" height="511" alt="image" src="https://github.com/user-attachments/assets/3ba8d59a-457b-4d04-ae8f-8106269a036c" />
## 📊 Key Insight: Influence of Maximum Spikes

- **What it shows:** Average pollution is heavily influenced by maximum spikes.  
- **Feature used:** `pollutant_avg` compared with `pollutant_max`.  

### ✅ Interpretation
- **Reliability of averages:** Since averages are skewed by extreme values, they may not fully represent day-to-day pollution.  
- **Pollutant behavior:** Monitoring maximum spikes helps reveal how sudden events (traffic surges, industrial emissions) drive overall air quality.  
- **Evidence:** Outliers prove that extreme values dominate averages, making them critical for analysis.  
- **Policy implication:** Continuous monitoring of **maximum pollutant levels** is essential for protecting public health and guiding interventions.



<img width="580" height="486" alt="image" src="https://github.com/user-attachments/assets/bf284161-6647-4f7a-ba30-e4e8052b2228" />

## 🩺 Relationship Between Pollution Categories and Health Hazards

**Features used:** `Pollutant_Category`, `Health_Hazard`

### ✅ Interpretation
- **Low Pollution:** Mostly linked to **respiratory hazards** (asthma, bronchitis, reduced lung function).  
- **Moderate Pollution:** Increasing presence of **respiratory + cardiovascular risks**, showing early impact of gaseous pollutants.  
- **High / Very High Pollution:** More associated with **cardiovascular and toxic hazards**, including neurological effects from heavy




<img width="997" height="651" alt="image" src="https://github.com/user-attachments/assets/143bb342-d969-4d95-acc2-e4fac10c911f" />
## 🌍 State-wise Average Pollutant Levels

**What it shows:** Comparison of average pollutant levels across all states, highlighting air quality differences.

### ✅ Interpretation
- **Taller bars = Higher average pollution** → Greater exposure risks for residents.  
- **Delhi, Punjab, Haryana, Bihar** → Show higher averages, indicating **poor air quality**.  
- **Sikkim, Mizoram, Uttarakhand** → Show lower averages, indicating **cleaner air**.  
- **Left side (shorter, darker bars)** → States with the cleanest air.  
- **Right side (taller, brighter bars)** → States with the highest average pollution.  
- **Viridis color palette** → Smooth gradient that visually distinguishes states while keeping focus on pollutant intensity.  
- **Policy Insight:** This ordered view makes it easy to identify **priority states for intervention** and compare relative air quality across the country.  
- **Overall Finding:** Pollution is **not evenly distributed** — some states consistently face worse air quality, making them priority areas for environmental and health interventions.



<img width="1005" height="525" alt="image" src="https://github.com/user-attachments/assets/5afa86a6-9659-49ac-8888-60893d315ad6" />

## 🏙️ Top 10 Cities – Pollutant Average

**What it shows:** A bar chart of the 10 cities with the highest average pollutant levels, broken down by pollutant type (PM2.5, PM10, NO₂, SO₂, CO, O₃, NH₃).  
**Features used:** `city`, `Pollutant_Name`, `pollutant_avg`.

### ✅ Interpretation
- **Samastipur (~210, dominated by PM2.5):** Severe particulate matter pollution.  
- **Leh:** Dominated by PM10 → dust and construction sources.  
- **Ambala:** Dominated by NO₂ → vehicular emissions.  
- **Ballabgarh:** Dominated by CO → industrial and traffic sources.  
- **Pali, Gorakhpur:** Also appear among the top polluted cities.  
- **Overall Insight:** While all these cities face poor air quality, the **pollutant mix differs city by city**.  

### 📌 Policy Relevance
- **Ambala:** Stricter vehicle checks.  
- **Leh:** Dust control measures.  
- **Ballabgarh:** Industrial emission regulation.  
- **Samastipur:** Focus on reducing PM2.5 (crop burning, fuel combustion).  

This chart highlights **priority cities for intervention** and shows how **different pollutants dominate in different regions**, guiding targeted environmental policies.


<img width="1005" height="633" alt="image" src="https://github.com/user-attachments/assets/223806d1-08e6-4780-83f3-2a7dfa308211" />

## 🏙️ Top 20 Cities – Health Hazard Distribution

**What it shows:** The chart highlights the top 20 cities with the highest pollutant ranges, associated with health hazards.  
**Features used:** `city`, `Pollutant_Range`, `Health_Hazard`.

### ✅ Interpretation
- **Respiratory issues dominate** across these cities → pollutants like PM2.5 and PM10 are the primary drivers of health risks.  
- **Cardiac and Neurological hazards** appear less frequently → either less strongly linked to pollution or less prevalent in the top polluted cities.  
- **Overall Insight:** Air pollution in the most affected cities is strongly correlated with **respiratory health problems**, making them the most critical concern for public health interventions.  
- **Policy Relevance:** This chart strengthens the case for **targeted respiratory health programs**, stricter particulate matter controls, and public awareness campaigns.

## PowerBI Dashboard

<img width="940" height="554" alt="image" src="https://github.com/user-attachments/assets/e205a51a-3e5f-4743-8b80-7070c5df80ec" />


<img width="940" height="532" alt="image" src="https://github.com/user-attachments/assets/a2a18d94-4040-41f8-962e-d78fd405cee9" />

📌 Key Findings – AQI Analysis
• Processed 3514 AQI records across multiple cities.
• Analyzed 11 dataset features (pollutants, AQI, categories, locations).
• Created 13 Python visualizations (line charts, bar charts, scatterplots, heatmaps, boxplots, maps).
• Built 2 Interactive Power BI Dashboards (city-level monitoring & pollutant impact).
• Developed an automated workflow for AQI cleaning, categorization, and reporting.
• PM2.5 emerged as the strongest driver of AQI, showing severe particulate matter pollution.
• Majority of records fell under the **Low category (~3000)**, but ~400 records showed **Moderate pollution**.
• High and Very High categories were rare, but critical → extreme pollution spikes.
• Cities like **Delhi, Punjab, Haryana, Bihar** showed consistently higher averages → poor air quality.
• Cities like **Sikkim, Mizoram, Uttarakhand** showed lower averages → cleaner air.
• Respiratory hazards dominated health risks, strongly linked to PM2.5 and PM10.
• Cardiac and toxic hazards appeared in High/Very High categories → less frequent but severe.
• Geographic hotspot analysis identified priority states and cities for intervention.
• Policy insight: Different pollutants dominate in different regions (e.g., dust in Leh, NO₂ in Ambala, CO in Ballabgarh).
• Overall, AQI analysis confirms variability in air quality, with **respiratory health risks as the most critical concern**.


## Authors

## Archana S

## Skills
* Python
* SQL
*	Power BI
* Excel

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aec
