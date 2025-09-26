# SQL Data Analysis Portfolio
**Drug side effects analysis**

This project explores the side effects of pharmaceutical drugs using the “Drug Labels & Side Effects Dataset” from Kaggle. The dataset contains 1,400+ records with information about drug names, manufacturers, dosage forms, dosage amounts, and reported side effects.

The goal of this project is to analyze drug safety profiles, identify patterns in side effects, and showcase SQL and data analysis skills applied to a biologically relevant dataset.

**Dataset Description & Source** 

Name: Drug Labels & Side Effects Dataset | 1400+ Records

Source: [Kaggle Link](https://www.kaggle.com/datasets/pratyushpuri/drug-labels-and-side-effects-dataset)

This project uses the Drug Labels & Side Effects Dataset, which contains over 1,400 records of pharmaceutical drug information. The dataset was sourced from Kaggle and provides structured details on medications, their manufacturers, dosage forms and amounts, as well as associated side effects. Side effects are recorded as comma-separated values, making it possible to explore relationships between drugs and their reported adverse reactions.

| **Column Name** | **Description** |
| --- | --- |
| drug_name | Name of the pharmaceutical drug. |
| manufacturer | Company that produces the drug. |
| dosage_form | Form and amount of the drug (e.g., tablet, injection, mg dosage). |
| administration_route | Route of administration for the drug (e.g., oral, intravenous, topical). |
| side_effects | Reported side effects, listed as comma-separated values per drug entry. |
| side_effect_severity | Severity label of each reported side effect (e.g., mild, moderate, severe). |

**Project Objectives**
	•	Practice SQL fundamentals: filtering, grouping, aggregation, conditional logic.
	•	Explore drug safety patterns and severity distributions.
	•	Compare manufacturers and administration routes to identify risk patterns.
	•	Develop insights like severity-weighted scores and most common side effects.
	•	Showcase structured thinking and SQL proficiency in a portfolio-ready project.

**SQL Analysis Plan**

🟢 Core Beginner Queries
	•	Count drugs per manufacturer
	•	Most common administration routes
	•	Count side effects by severity

🟡 Intermediate Analysis
	•	Manufacturers with the highest percentage of severe side effects
	•	Severity distribution by administration route
	•	Drugs with the largest number of side effects

🔴 Advanced Insights
	•	Rank drugs by severity-weighted risk score (mild=1, moderate=2, severe=3)
	•	Rank manufacturers by average severity score
	•	Top 10 most frequently reported side effects

**Tools & Skills Used**
	•	SQL: SQLite 
	•	GitHub: Version control and portfolio hosting
	•	Data Analysis Concepts: Aggregation, grouping, filtering, conditional logic

**Future Work**
	•	Explore time trends in side effects if more data is available
	•	Implement Python or R for deeper statistical analysis
	•	Visualize severity distributions in dashboards or charts
