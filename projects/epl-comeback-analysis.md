# Premier League Comeback Analysis — Interactive Python Application
### Python · EDA · Data Visualization · GUI

---

## Overview
This project analyzes **25 seasons of Premier League match data (2000–2025)** to identify which teams are the most resilient — defined as overturning losing half-time positions.

It includes complete data cleaning, engineered metrics, exploratory analysis, visualizations, and a Tkinter-based GUI application for interactive team-level exploration.

---

## Data & Preparation

- **9,380 matches**, fully parsed and standardized  
- Match-level stats (goals, shots, cards, fouls, corners)  
- Cleaned date fields  
- Repaired dtypes and removed duplicates  
- Constructed derived metrics:
  - Half-Time Goal Difference (HT_GoalDiff)  
  - Full-Time Goal Difference (FT_GoalDiff)  
  - Comeback flag  
  - Attempt count per team  

---

## Analytical Methods

### **1. Comeback Logic**
A match is considered a comeback if:

- Team was *losing at half-time*, and  
- The team *did not lose at full-time* (draw or win)

### **2. Team-Level Metrics**
- Total comebacks  
- Number of times trailing at half-time (opportunities)  
- Comeback rate = comebacks / opportunities  
- “Big swings” (≥2-goal deficits overcome)

### **3. League Trends**
- Comebacks per season  
- Team clusters by adversity and efficiency  
- Tactical era patterns (e.g., pressing, defensive structure)

### **4. Visualizations**
- Bar charts of top comeback teams  
- Line plots of comeback trends over seasons  
- Bubble charts linking adversity vs recovery ability  
- Annotated team-level scatterplots

---

## Key Insights
- **1,324 total comebacks** across the dataset  
- Arsenal and Man United show excellent comeback rates  
- Some clubs trail frequently but rarely recover  
- Seasonal fluctuations align with tactical shifts across eras  
- Resilience is quantifiable and differs significantly across teams  

---

## GUI Application
Built with Tkinter:

- Dark-mode interface  
- Team dropdown selector  
- Instant display of:
  - Comebacks  
  - Times losing at HT  
  - Comeback rate  
- Trend plot button generating interactive charts  

The GUI transforms analysis into an accessible tool for fans, analysts, or casual exploration.

---

## What This Project Demonstrates
- Strong command of Python fundamentals  
- Ability to design custom analytical metrics  
- Clean EDA and visualization workflows  
- GUI design & user interaction logic  
- Domain reasoning in sports analytics  
- Transformation of raw data → metrics → insights → tool  

---

## Future Work
- Integrate expected goals (xG) data  
- Support manager-era comparisons  
- Add animation-based or web-based visualizations  
- Package GUI into a standalone executable  
