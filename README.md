# 🐦 Bird Species Observation Analysis

This project delivers a **comprehensive end-to-end data analysis** of bird species distribution across **forest and grassland habitats** using **Python** and **Power BI**. It uncovers insights into species diversity, habitat preferences, observer activity, and environmental influences such as temperature, humidity, and sky conditions.

---

## 📌 Project Objectives

* Study bird species distribution and diversity across habitats
* Identify habitat preferences and environmental factors influencing bird presence
* Determine peak observation times for fieldwork and eco-tourism
* Highlight dominant and rare species for targeted conservation efforts
* Recognize top observers to motivate accurate and consistent data collection
* Provide actionable insights for biodiversity conservation and eco-tourism planning

---

## 🛠️ Tools & Technologies Used

* **Python (Pandas, NumPy, Matplotlib, Seaborn, Missingno)** – Data cleaning, preprocessing, and exploratory data analysis
* **Power BI** – 3-page interactive dashboard with slicers, KPIs, and visual storytelling
* **Excel Data** – Forest and Grassland bird monitoring datasets across multiple administrative sites

---

## 🗃️ Data Workflow

### 1. Data Loading

* Combined **Forest** and **Grassland** Excel sheets into pandas DataFrames
* Explored structure, duplicates, and missing values
* Mapped **Admin Unit Codes** (e.g., ANTI, CATO, CHOH) to ecological sites

### 2. Data Preprocessing

* ✅ Dropped low-utility columns (e.g., `Sub_Unit_Code`)
* ✅ Imputed missing values (`Unknown`, `Undetermined`, or `Mode`)
* ✅ Cleaned and standardized time fields into `Observation_Hour`
* ✅ Converted categorical columns to efficient datatypes
* ✅ Removed duplicates to ensure integrity
* ✅ Saved cleaned dataset as `Bird_Monitoring_Clean_Merged_dataset.csv`

### 3. Exploratory Data Analysis (EDA)

* Habitat & sex distribution
* Top 10 observed bird species
* Distance distribution of sightings
* Observer activity & recognition
* Hourly & temporal observation trends
* Environmental influences (temperature, humidity, sky, wind)

---

## 📊 Dashboard Overview (Power BI)

The **3-page interactive dashboard** visualizes key biodiversity and observation insights:

### 📈 Page 1: Overview

* **KPIs**: Total Observations, Unique Species, Total Observers
* **Visuals**: Map of sites, Top 10 species, Observations by location type & time

### 🐦 Page 2: Species & Conservation

* **KPIs**: Unique Species, Identification Methods, Sex Distribution
* **Visuals**: Species diversity across habitats, ID method distribution, Top species by flyover

### 🌍 Page 3: Temporal & Environmental

* **KPIs**: Avg. Temperature, Avg. Humidity, Initial 3-Minute Observations
* **Visuals**: Observation trends by hour, sky condition, wind distribution, humidity vs distance

---

## 🔎 Key Insights

### 🌱 Habitat & Biodiversity

* Forests accounted for **55.6%** of observations; Grasslands **44.4%**
* Dominant species: **Northern Cardinal** & **Carolina Wren**
* Many species showed strong habitat preference (e.g., Red-eyed Vireo in forests)

### ⏰ Temporal Patterns

* Bird activity peaked between **6–7 AM**
* Grassland activity more consistent throughout the morning

### 👥 Observer Insights

* **Elizabeth Oswald** recorded the highest number of observations
* Observers contributed more in forests than in grasslands

### 🌦 Environmental Trends

* Most sightings occurred at \~**22°C**, high humidity, and partly cloudy skies
* Light breezes (1–3 mph) dominated wind conditions
* Sex was undetermined in **79%** of cases, suggesting training gaps

---

## ✅ Recommendations

* Improve **data quality** → reduce undetermined sex entries via better observer training
* Diversify **ID methods** (not only singing; add visualization and calls)
* Standardize **distance records** to avoid “Unknown” entries
* Conduct **fieldwork strategically** between **6–8 AM**
* Prioritize **forest habitats** but monitor underreported grasslands
* Recognize and support **top observers** for motivation
* Align eco-tourism activities with **favorable weather (\~22°C, partly cloudy, light breeze)**
---

## **Solution to Business Objective**
* **Prioritize habitat-specific strategies** — Focus more monitoring and conservation in forests, which currently have higher observation counts, while strengthening grassland biodiversity programs to balance efforts.
* **Enhance data collection quality** — Train observers to improve sex determination and accurately record observation distances to close current data gaps.
* **Leverage peak observation times** — Schedule eco-tourism activities and research during early morning hours (especially 6–7 a.m.) to maximize sightings.
* **Target conservation for rare species** — Create special monitoring programs for low-observation species to prevent population decline.
* **Empower top observers** — Recognize and incentivize leading contributors like Elizabeth Oswald to mentor others and improve team-wide performance.
* **Integrate environmental condition tracking** — Use insights on wind, sky, and disturbance levels to plan optimal birdwatching and research conditions.
* **Diversify observation coverage** — Increase monitoring in varied seasons and times to capture a more complete picture of bird diversity.
* **Promote eco-tourism marketing** — Highlight popular species and high-sighting times to attract birdwatching enthusiasts and boost tourism revenue.
* **Collaborate with conservation bodies** — Partner with wildlife NGOs, research institutions, and local communities to implement habitat-specific conservation measures.

---

## **Suggestions Regarding Business Objectives**:

Here are accurate and well-reasoned **business suggestions** derived from the bird diversity and distribution analysis across forest and grassland ecosystems:
####  **Wildlife Conservation**

* **Prioritize high-risk zones**: Direct conservation funding and protection efforts toward plots with high concentrations of **PIF Watchlist** and **Regional Stewardship** species (e.g., specific plots in PRWI and ROCR).
* **Create micro-habitats**: For rare or seldom-observed species identified in the dataset, develop micro-habitats tailored to their ecological preferences.

####  **Land Management & Habitat Restoration**

* **Use species-preference data**: Restoration plans should align with species that favor specific vegetation types (e.g., dense forest undergrowth vs. open grasslands).
* **Reduce human disturbance**: Implement buffer zones or limited-access areas in locations with high disturbance but low species count, to allow biodiversity recovery.

####  **Eco-Tourism Development**

* **Promote bird-watching hotspots**: Plots with consistently high species richness (biodiversity hotspots) should be branded as birding trails or eco-tourism destinations.
* **Seasonal event planning**: Use monthly and seasonal trends to schedule guided tours during peak bird activity (e.g., April–June), maximizing tourist experience.

####  **Sustainable Agriculture**

* **Enforce habitat-friendly practices**: In agricultural boundary areas, adopt no-spray zones and native vegetation buffers to reduce disturbance.
* **Monitor agro-impact zones**: Use disturbance analysis to regularly monitor agricultural impact on nearby bird populations and adapt practices accordingly.

####  **Policy and Governance Support**

* **Use evidence for conservation zoning**: Present spatial biodiversity heatmaps to policymakers to designate new or updated conservation zones.
* **Institutionalize long-term monitoring**: Advocate for systematic, repeated monitoring using standardized protocols, as repeat visits significantly increase species detection.

####  **Biodiversity Monitoring and Research**

* **Invest in continuous data collection**: The strong correlation between repeat visits and species count justifies funding long-term ecological monitoring programs.
* **Track climate-related changes**: Environmental influence analysis (temperature, wind, sky) can be integrated into climate resilience assessments for bird populations.

###  **Overall Strategic Direction**

* Integrate this ecosystem-level bird data into a **centralized biodiversity dashboard** for real-time decision-making.
* Encourage partnerships with **research institutions, tourism boards, and agriculture agencies** to co-develop region-specific conservation and development strategies.

---

## 📌 Conclusion

The Bird Species Observation Analysis project demonstrates how raw observational data can be transformed into **valuable biodiversity insights**. From species diversity to environmental dependencies, the findings inform conservation strategies, optimize eco-tourism activities, and highlight opportunities for better data collection practices. The **Power BI dashboard** enhances storytelling, making insights actionable for conservationists, researchers, and policymakers.

---
