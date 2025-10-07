# HEALTH-CONSEQUENCES-OF-MICROPLASTICS-AND-NANOPLASTICS-IN-FOOD-USING-MACHINE-LEARNING

📌 Project Overview
This notebook aims to:

Explore and analyze chemical data related to microplastics.
Understand their chemical classes, hazard levels, and industrial usage.
Identify potential links between chemicals and health outcomes.
Present insights visually using Python data analysis tools.

📁 Dataset Summary

File: Microplastic (1) (1).xlsx
Notebook: Microplastic1.ipynb
Sheets Included:

Sheet Name	Description
B.1. Chemicals list	Details of each chemical (class, CAS number, SMILES, InChI, source, hazard rating, etc.)
B.1. Chemical list key	Descriptive reference key for chemical identifiers
B.2. Health outcomes list	Health effects potentially linked to chemical exposure
B.3. Countries list	Countries involved in research or reporting related to microplastics

Sample Data Features:

Chemical class – e.g., Bisphenols, Phthalates, Flame retardants
CAS number – Chemical identification code
Smiles / InChI – Structural formulas
Hazard rating – Toxicity level or data availability
Sector of use – Industries using each chemical (construction, automotive, etc.)

🔧 Libraries Used
python  
pandas, numpy, matplotlib, seaborn, openpyxl  

🔍 Data Analysis Highlights
🟡 Chemical Composition Overview

Dataset includes hundreds of chemicals categorized into multiple classes like:
Bisphenols
Phthalates
Brominated Flame Retardants
Perfluorinated Compounds (PFCs)

Each class contains data about usage purpose, hazard potential, and source references.

🔵 Hazard Rating & Production Volume

Around 35–40% of listed chemicals have a “high hazard rating.”

Production volumes vary widely — some exceeding 1,000,000 tons per year, indicating mass-scale use despite potential risks.

A few chemicals have “No data available” for hazard or volume, showing significant data gaps in environmental research.

🟣 Sector of Use Distribution

Common industries identified:
Building & Construction
Electrical and Electronics
Automotive
Consumer Products

The Building & Construction sector accounts for the highest concentration of chemicals.

🔴 Health Outcomes

Health outcomes listed in the dataset are linked to:
Endocrine disruption
Reproductive toxicity
Carcinogenicity
Neurotoxicity

Some chemical classes like Bisphenols and Phthalates appear repeatedly across multiple health categories.

🟢 Data Visualization Highlights

**Count plots** display frequency of chemicals by class.
**Bar charts** show the number of “high hazard” chemicals by sector.
**Pie charts** represent the share of found vs. not found chemicals in the ECHA database.

⚙️ Data Preprocessing Steps

Removed empty rows and columns.
Standardized chemical names and CAS numbers.
Mapped categorical values like “found/not found” to numerical form for visualization.
Filtered data to focus on chemicals with available hazard ratings and production data.
Aggregated statistics by chemical class and sector for pattern identification.

🧠 Insights & Results
Insight	Observation
High Hazard Compounds	Over one-third of the chemicals analyzed are classified as high hazard.
Industrial Overlap	Most chemicals are used across multiple industries, indicating widespread risk.
Data Gaps	Several chemicals lack hazard or production data, making risk assessment incomplete.
Bisphenols’ Risk	Bisphenol-based compounds show consistently high production and hazard levels.
Global Concern	Data spans multiple countries, confirming microplastic contamination is a global issue.

📌 Conclusion

The dataset reveals that a significant number of high-volume chemicals used in industrial sectors pose potential health and environmental hazards.
Bisphenols and Phthalates emerge as key chemical groups linked to high toxicity.
The analysis demonstrates the need for stricter monitoring, public transparency, and international collaboration to regulate microplastic-related chemicals.
Future work could involve machine learning classification to predict hazard ratings based on chemical features.



Would you like me to add a short Results Visualization Section (with example chart titles and interpretations) and a requirements.txt file based on your notebook imports? It’ll make your GitHub repo look more complete and professional.
