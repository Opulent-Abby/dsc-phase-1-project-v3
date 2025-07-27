# Aviation-Database-Phase-1-
# Aviation Safety Risk Analysis

##  Overview

This project analyzes civil aviation accident data from the National Transportation Safety Board (NTSB) between 1962 and 2023. The objective is to provide actionable insights that guide safe investment decisions as a company expands into the aviation sector. Through data cleaning, analysis, and interactive visualization, this project identifies patterns in accident severity across different aircraft makes, engine types, and flight purposes.

---

## Business Understanding

**Stakeholder**:  
Head of the company’s new Aviation Division

**Business Objective**:  
To identify the safest aircraft for purchase and operation by evaluating historical accident data. The analysis focuses on determining which aircraft types, engine configurations, and flight purposes are associated with higher or lower safety risks.

**Key Business Questions**:
- Which aircraft manufacturers are most commonly associated with fatal accidents?
- Are certain types of flight operations (e.g., personal vs. commercial) more dangerous?
- Do specific engine types correlate with higher accident severity?

---

## Data Understanding & Analysis

### Data Source
- **Provider**: National Transportation Safety Board (NTSB)
- **Dataset**: Civil Aviation Accidents and Incidents (1962–2023)
- **Access**: Provided via course materials

### Data Description
The dataset includes fields such as:
- `Aircraft Make`
- `Engine Type`
- `Purpose of Flight`
- `Injury Severity`
- `Event Date`
- `Location`, among others

After initial inspection, the dataset was cleaned to remove null values in critical fields and grouped logically to support analysis of fatality patterns.

---

## Key Visualizations

These visualizations were created using Tableau to support both exploratory analysis and business decision-making:

1. **Top 10 Aircraft Makes by Fatal Accidents**  
    Identifies the aircraft makes with the highest frequency of fatal incidents.

2. **Fatality Rate by Flight Purpose**  
   Displays the percentage of incidents by injury severity across flight types (e.g., personal, commercial, business).

3. **Injury Severity Distribution by Engine Type**  
   Shows which engine types are associated with more or less severe outcomes.

## Interactive Dashboard
Explore my dashboard for more visual information.
https://public.tableau.com/app/profile/abigael.musyoka/viz/AnalysingAircraftsGuideforSaferInvestmentDecisions-OpulentAbby/AviationSafetyRiskDashboardAnalyzingaircraftmakepurposeandenginetypetoguidesaferinvestmentdecisions_?publish=yes


## Conclusion

### Summary of Findings

1. **Aircraft make** is a significant factor in accident fatality counts — certain manufacturers appear disproportionately in fatal incidents.
2. **Personal-use flights** have notably higher fatality rates compared to commercial and business flights.
3. **Reciprocating/single-engine aircraft** show a higher frequency of fatal or serious injuries compared to turbofan or multi-engine configurations.

### Recommendations

- Prioritize investment in aircraft with strong safety records and low fatal incident history.
- Focus operations on commercial or business flight categories to reduce risk exposure.
- Favor multi-engine or turbofan aircraft over single-engine designs where possible.



## Repository Structure
├── README.md # This project overview
├── aviation_clean.csv # Cleaned dataset used for Tableau
├── aviation_notebook_final.ipynb # Final Jupyter Notebook with analysis
├── presentation.pdf # Business-facing slide deck
├── .gitignore # Files to ignore in version control


---

## Version Control & Collaboration

This repository includes a clean commit history showing the progression from data cleaning to visualization and dashboard development.

- ✅ Clear and descriptive commit messages
- 📅 Regular updates throughout the project timeline
- 👥 Prepared for individual or group collaboration



## .gitignore

A `.gitignore` file is included at the root to prevent unnecessary files from being pushed, such as:
- System files (e.g., `.DS_Store`)
- Environment files
- Large raw data files

The base file was adapted from GitHub’s recommended [Python .gitignore](https://github.com/github/gitignore/blob/main/Python.gitignore).

---

##  Author

**Created by**: ABIGAEL NZIVU MUSYOKA  
**Connect**: [Your LinkedIn Profile](https://linkedin.com/in/your-profile)  
**Dashboard**: [View Tableau Public Dashboard]https://public.tableau.com/app/profile/abigael.musyoka/viz/AnalysingAircraftsGuideforSaferInvestmentDecisions-OpulentAbby/AviationSafetyRiskDashboardAnalyzingaircraftmakepurposeandenginetypetoguidesaferinvestmentdecisions_?publish=yes

---





