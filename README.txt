# 🔍 Chicago Crime Analysis (2001–2017)

This project provides a comprehensive analysis of crime trends, types, and hotspots across the city of Chicago using public crime data from 2001 to 2017. It explores long-term patterns, monthly seasonality, watch-based crime shifts, and district-level spatial insights to inform data-driven policing strategies.

---

## 📊 Project Objectives

- Analyze long-term crime and arrest trends.
- Identify seasonal and monthly variations in crime frequency.
- Examine crime distribution across police shifts (watches).
- Map spatial hotspots across districts and timeframes.
- Recommend actionable strategies for law enforcement and policy stakeholders.

---

## 🧠 Key Findings

- **📉 Decline in Crime & Arrests**: From 2001 to 2016, arrests dropped by 66%, mirroring a nearly 50% reduction in total reported crimes.
- **🌞 Seasonal Crime Peaks**: Summer months (especially July) consistently have higher crime rates, while winter months see declines.
- **🔝 Most Common Offenses**: 
  - Larceny/Theft
  - Simple Assault
  - Vandalism
- **🚔 District Hotspots**:
  - **District 8**: High crime in both 1st and 2nd Watches.
  - **District 11**: Consistently high crime, especially during the 3rd Watch.
  - **Districts 2 & 25**: Emerging hotspots during daytime hours.
- **⏰ Watch-Based Trends**:
  - **1st Watch (2 PM – 12 AM)**: Highest crime volume.
  - **2nd Watch (10 PM – 8 AM)**: Night crimes focused on assault and burglary.
  - **3rd Watch (6 AM – 4 PM)**: High daytime property-related crimes.

---

## 📍 Methodology

- **Data Cleaning & Preprocessing**: Used `pandas` and `numpy` to filter and restructure data.
- **Visualization**: Created bar charts, line plots, treemaps, and interactive maps using `matplotlib`, `seaborn`, `plotly`, and `folium`.
- **Custom Functions**: Built reusable functions to:
  - Analyze crime by police watch.
  - Visualize top crimes by district and shift.
  - Map geographic hotspots by time and category.

---

## ✅ Business Recommendations

1. **Dynamic Watch-Based Patrols**  
   Allocate resources differently by shift to match crime patterns in top districts like 8 and 11.

2. **Targeted Summer Enforcement**  
   Increase patrols and awareness campaigns during peak summer crime months (June–August).

3. **District-Level Resource Focus**  
   Prioritize Districts 8, 11, and 6 for crime prevention investments based on consistent high-volume offenses.

4. **Shift-Specific Crime Intervention**  
   Tailor patrol and prevention strategies to the most frequent offenses per watch (e.g., Larceny in 3rd Watch, Assault in 2nd Watch).

5. **Community-Driven Strategy Development**  
   Use visualized insights to engage local leaders and design community-specific safety programs.

---

## 🛠️ Tools & Technologies

- **Python**
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `folium`
- Jupyter Notebook
- Git/GitHub

---


