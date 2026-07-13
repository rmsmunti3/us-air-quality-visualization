# Air Quality & Ozone Analysis Across the United States (2020)

A comprehensive data visualization project developed as part of the **CCDS302 - Data Visualization** course at the **University of Jeddah**. 

This repository showcases how we transformed raw outdoor air quality monitoring data into a highly intuitive, interactive Power BI dashboard to analyze ozone levels and Air Quality Index (AQI) patterns across the US during the year 2020.

---

## Project Structure & Objectives
The goal of this project was to leverage advanced visualization techniques to answer critical environmental questions:
1. **Correlation:** Is there a relationship between average ozone concentration and maximum AQI levels?
2. **Geographical Distribution:** How is air pollution distributed spatially across the United States?
3. **Hotspots Identification:** Which US counties registered the highest average AQI?
4. **Temporal Patterns:** How did ozone pollution fluctuate month-by-month throughout 2020?
5. **Data Density:** Which states contributed the most records to our monitoring network?

---

## 🖥️ Interactive Power BI Dashboard
Here is the final layout of the interactive dashboard designed to monitor and analyze US ozone pollution levels[cite: 4]:

![DataVisualization Dashboard](DataVisualization%20Dashboard.jpeg)

---

## Technical Architecture & Dataset
* **Dataset:** 2020 US Environmental Protection Agency (EPA) outdoor monitoring station records, capturing daily ozone concentrations, AQI values, state/county identifiers, and temporal metrics.
* **Tool Used:** Power BI Desktop (Power Query for final transformations, Native Interactive Visuals, Map Integration).

---

## Detailed Visualization & Analytical Insights

### 1. Scatter Plot: Ozone vs. AQI Correlation
* **Visual Choice:** Scatter Plot with a Linear Trend Line.
* **Key Finding:** A clear positive correlation is visible. Higher average arithmetic mean values of ozone concentration directly map to higher Maximum AQI levels. The trend line validates that ozone levels are a key driver of overall air quality degradation.

### 2. Map Visual: Geographical Distribution of AQI
* **Visual Choice:** Filled/Bubble Geographic Map Layer.
* **Key Finding:** While air quality monitors cover almost every US state, a massive density of high-AQI observations is centered around industrial zones and heavily populated metropolitan areas.

### 3. Horizontal Bar Chart: Top 10 Heavily Polluted Counties
* **Visual Choice:** Horizontal Bar Chart sorted by Average AQI (Descending).
* **Key Finding:** **San Bernardino County** recorded the highest average AQI, with the remaining top 9 counties consistently maintaining average AQIs above 50, indicating moderate-risk air quality environments.

### 4. Area Chart: Monthly Trends of Average Ozone in 2020
* **Visual Choice:** Line/Area Chart.
* **Key Finding:** Ozone levels followed a clear seasonal curve—steadily rising during the first half of the year, peaking sharply during the warm summer months of **May and June**, and gradually declining toward late autumn and winter.

### 5. Donut Chart: Record Distribution Across Top 5 States
* **Visual Choice:** Donut Chart with Percentage Data Labels.
* **Key Finding:** The monitoring network records are heavily skewed. **California** holds the largest share of records in the dataset (**42.71%**), followed by Texas (**18.3%**) and Florida (**14.71%**), highlighting where US air monitoring efforts are most concentrated.


---

## Team Members
* **Rimas Almuntashiri**
* **Layan Almunammis**
* **Layan Alshaikhi** 
