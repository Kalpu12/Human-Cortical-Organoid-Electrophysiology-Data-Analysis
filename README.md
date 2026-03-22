🧠 Human Cortical Organoid Electrophysiology & Movement Analysis

This repository contains Python notebooks and Excel datasets used to analyze cellular movement dynamics across different regions of human cortical organoids under various experimental conditions.

The project focuses on comparing:

Cell count
Velocity of movement

Across:

Different brain regions
Young vs. old organoids
Multiple experimental conditions
📁 Repository Structure
- data 
- excel spreadsheets respectively
-  notebooks
   -  old_organoid_analysis.ipynb
   -  young_organoid_analysis.ipynb
- requirements.txt
-  README.md
📊 Data Description

The dataset includes:

Cell Count: Number of tracked cells per region
Velocity: Calculated as:
velocity = (y2 - y1) / (x2 - x1)

Data is organized by:

Cortical region
Experimental condition
Organoid age (young vs. old)
🔬 Analysis Workflow
Data Preprocessing
Load Excel files
Clean missing or inconsistent values
Organize by region and condition
Feature Extraction
Compute velocity
Aggregate cell counts
Statistical Analysis
Compare groups across regions and conditions
Compute p-values (e.g., t-test, ANOVA)
Visualization
Box plots for:
Cell count distribution
Velocity differences
📦 Requirements

Install dependencies with:

pip install -r requirements.txt
📄 requirements.txt

