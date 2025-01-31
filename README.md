
---

# 💊 Drug Poisonings Data Analysis Dashboard

![my screenshot](https://github.com/prof2022/Drug-poisoning-data-analysis/blob/Master/assets/Screenshot%20(38).png)

## 📖 Overview

The **Drug Poisonings Data Analysis Dashboard** is a comprehensive and interactive tool that visualizes statistics on drug poisoning fatalities from **1999 to 2015**. It provides detailed insights into deaths categorized by age groups, trends over time, and demographic factors such as sex. This dashboard is designed for health analysts, policymakers, businesses, and researchers to understand the patterns and trends of drug-related deaths, enabling them to devise data-driven strategies for prevention and awareness.

---

## ✨ Key Features

### 📊 **Core Metrics**
- **Age-Based Analysis**:
  - Total deaths for specific age groups (e.g., 75+ years: **2,544 deaths**, under 15 years: **536 deaths**).
- **Overall Fatalities**:
  - Highlights the total deaths from drug poisonings (e.g., **136,216 deaths** in the dataset).
- **Trend Analysis**:
  - Line chart showing yearly increases in deaths from **1999 to 2015**.

### 📆 **Yearly Selector**
- A dynamic **year slider** enables users to explore data for specific years (e.g., the snapshot shows data for **2006**).
- Displays age group distribution and fatalities for the selected year.

### 📊 **Bar Chart: Top Age Groups**
- Visualizes deaths by age groups for the selected year.
- Provides a clear ranking of age groups most affected by drug poisoning fatalities (e.g., **45-54 years** had the highest deaths in **2006**, with **41k deaths**).

### 🥧 **Demographic Breakdown**
- **Sex-Based Analysis**:
  - A pie chart displays the percentage and total deaths by gender (e.g., **36.4% female** and **63.6% male** in **2006**).
- Gender-specific insights help identify key trends and disparities.

---

## 🛠️ Technologies Used

| Technology        | Purpose                                        |
|--------------------|-----------------------------------------------|
| **Python Dash**    | For creating the interactive dashboard.       |
| **Plotly**         | For designing dynamic and customizable charts.|
| **Pandas**         | For processing and analyzing large datasets.  |
| **CSS & HTML**     | For styling and responsive design.            |

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/prof2022/drug-poisonings-dashboard.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application locally:
   ```bash
   python app.py
   ```

4. Open your browser and access:
   ```
   http://127.0.0.1:8050
   ```

---

## 📸 Project Analysis 

![my screenshot](https://github.com/prof2022/Drug-poisoning-data-analysis/blob/Master/assets/Screenshot%20(38).png)


This snapshot highlights:
1. **Deaths by Age**:
   - The **45-54 years** age group has the highest fatalities (41k deaths) in **2006**.
   - Significant disparities exist between younger and older populations.
2. **Yearly Trend**:
   - Steady increase in drug-related deaths, with a peak at **190k deaths in 2015**.
3. **Gender Breakdown**:
   - Males constitute **63.6%** of deaths, whereas females account for **36.4%** in **2006**.

---

## 🌟 Impact of the Project

- **Health Policy Insights**:
  Helps policymakers identify vulnerable age groups and demographics to target interventions.
- **Research-Driven Solutions**:
  Enables health analysts to explore trends and derive actionable conclusions.
- **Public Awareness**:
  Raises awareness about the increasing fatalities due to drug poisoning over the years.

---

## 🔍 Recommendations for Business Actions

Businesses in healthcare, pharmaceuticals, and public health sectors can utilize these insights to take impactful actions:

1. **Pharmaceutical Companies**:
   - Analyze age groups and demographics most affected to design safer medication protocols.
   - Develop targeted marketing campaigns promoting safer drug use and overdose prevention.

2. **Health Insurance Providers**:
   - Offer tailored insurance plans addressing high-risk age groups and demographics.
   - Implement preventative healthcare measures for the 45-54 years age group, the most affected.

3. **Rehabilitation Centers**:
   - Focus resources on regions with the highest fatalities and vulnerable demographics.
   - Develop age-specific rehabilitation programs and advertise them to at-risk groups.

4. **Public Health Campaigns**:
   - Launch awareness campaigns focusing on the dangers of drug poisoning, targeting the most affected age groups (e.g., 45-54 years).
   - Use gender-specific messaging, addressing behavioral trends observed in males (63.6% of deaths in 2006).

5. **Technology and Analytics Firms**:
   - Develop AI-based tools to predict high-risk populations and locations.
   - Partner with healthcare providers to deploy solutions for early intervention.

---

## 🔍 Recommendations for Future Enhancements

1. **Include Predictive Analytics**:
   Add models to forecast future trends in drug poisoning fatalities.
2. **Expand Dataset**:
   Incorporate newer data (post-2015) for up-to-date insights.
3. **Regional Breakdown**:
   Introduce a geographic view to analyze fatalities by region or state.
4. **Interactive Comparison**:
   Allow comparisons between years, age groups, or demographics.

---

## 📈 Future Enhancements

- **Real-Time Integration**:
  Link with live data sources to update the dashboard dynamically.
- **Alert System**:
  Provide automatic alerts for significant spikes in fatalities.
- **Custom Reports**:
  Enable users to export data visualizations and summaries for presentations.
