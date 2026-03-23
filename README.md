## 🧠 Human Cortical Organoid Electrophysiology & Movement Analysis

This repository contains Python notebooks and Excel datasets used to analyze cellular movement dynamics across different regions of human cortical organoids under various experimental conditions. 

# Experimental Background: 
- The goal of this research project is to determine the movement (cell count) and trajectory (velocity) can affect the cerebral cortex of the brain in healthy patients and determine if our findings has a significance in patients that have neurodegenerative disorders. Electrophysiology experiments were conducted using BEC ( Brain-on-electroaxis-chip) plates which were fabricated and tested on cortical organoids which were derived from iPSC(induced Pluroptient Stem Cells). All of the experiments were conducted at UCSC Genomics Institue under guidance of Professor Mircea Teodorescu and Professor David Hausseler. 

Across:

# Four Different Conditions:
   - Condition#1: Ventral Only(V)
   - Condition#2: Ventral-Dorsal-Ventral(vDv)
   - Condition#3: Dorsal Only(D)
   - Condition#4: Dorsal-Ventral-Dorsal(dVd)
# Young vs. old organoids 
   - comparison plots for the different figures with p-values across each of the different experimental conditions 
# Comparison Groups: 
- Young Organoid Ventral Comparisons(Average: Cell Count)
- Young Organoid Ventral Comparisons(Absolute Value: Velocity)
- Old Organoid Ventral Comparions(Avergae: Cell Count)
- Old Organoid Ventral Comparisons(Absolute Value: Velocity)
- Young Organoid Dorsal Comparisons(Average: Cell Count)
- Young Organoid Dorsal Comparisons(Absolute Value: Velocity)
- Old Organoids Dorsal Comparisons(Average: Cell Count)
- Old Organoids Dorsal Comparisons(Absolute Value: Velocity)
   - Ventral Comparisons:
       - Ventral Control(V)
       - Ventral-> Dorsal(vDv)
       - Ventral-> Dorsal(dVd)
       - Ventral-> Media(dVd)
   - Dorsal Comparisons:
        - Dorsal Control(D)
        - Dorsal-> Ventral(dVd)
        - Dorsal-> Ventral(vDv)
        - Dorsal-> Media(vDv)

# Repository Structure
- raw data(excel spreadsheets)
  - old organoids
  - young organoids
- python notebooks(data processing)
  - old organoids, young organoids
- final edits
  - final edits notebook
- requirments.txt
- README.md
📊 Data Description

The dataset includes:

Cell Count: Number of tracked cells per region
Velocity: Calculated as:
velocity = (y2 - y1) / (x2 - x1) 
where y-axis represents the cell count and x axis measures the time in hours 

# 🔬 Analysis Workflow
- Data Preprocessing
- Load Excel files
- Clean missing or inconsistent values
- Organize by region and condition
- Feature Extraction
- Compute velocity
- Aggregate cell counts
-  Statistical Analysis
-  - Compare groups across regions and conditions
   - Compute p-values (e.g., t-test, ANOVA)
# Data Visualization
- box plot generations across Ventral Comparison Group, Dorsal Comparison Groups, Old Vs. Young Organoid Data Comparisons
# Final Edits
- Clean up the box plot figures for consistency (font, color, shape, size, etc.)
📦 Requirements

Install dependencies with:

pip install -r requirements.txt
📄 requirements.txt

