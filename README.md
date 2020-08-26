# Jeb Stewart Portfolio
Data Science Portfolio

# Project 1: Classification of Breast Cancer Cell Nucleii
**Objective:** Classify breast cancer cell nucleii samples as either benign or malignant

**Importance:** Benign and Malignant tumors are often treated using completely different methods. The treatments themselves can cause harm so using the incorrect treatment on a patient could not only be ineffective, but detrimental to the health of the patient.

**Outcome:** 
- Able to classify unseen data with an F1 Score of 0.974
- Explored the morphological changes of cancerous cell nucleii and their role in metastasis

**Skills Used:** Data Manipulation, Data Visualization, Classification with XGBoost, LightGB, and SVM 

# Project 2: Predictive Maintenance Modeling
**Objective:** Using existing sensors on board product, approximate when failure will occur and request customer perform maintenance.  

**Importance:** Due to the high variation of environment products would operate in, MTBF varied wildly as customers did not know when to perform maintenance. The units regularly failed to meet warranty hour minimums as a result.

**Outcome:** 
- Able to predict failure within 10% of total life under lab conditions. 
- Acted as proof of concept for the application of the technology in our domain.
- Proved existing sensors would suffice for a retrofit software only solution (as hardware changes are significantly more expensive)

**Skills Used:** Experiment Design, Data Collection, Mining, Cleaning, and Visualization, Time-Series Analysis and Regression

# Project 3: Data Collection and Parsing App
**Objective:** Create a tool for technicians to collect serial stream data from our products during experimentation, and parse the data into a .csv file for immediate analysis.

**Importance:** Sensor and processor state data is sent out constantly from the product, but was not stored or collected. This made diagnosing issues on the unit difficult as history logs alone would only capture snapshots of the product state when specific conditions were met. Oftentimes the unit would fail with hours of missing data between snapshots. 

**Outcome:** 
- I wrote a program that has been distributed to my associates and has been in constant use since creation
- In a few months the program has saved dozens of engineering hours in diagnosing unit failures during testing
- The program has reduced the amount of modifications that must be made to units for testing which has allowed more tests to be run on an individual unit
- The program has allowed for the capture of what the product "sees" and has allowed the team to isolate and fix discrepancies between the products perception and reality

**Skills Used:** Python Programming with Kivy for UI, Data Collection, Data Cleaning, Automation, Git

Note: For project 2 and 3, the code is owned by Collins Aerospace and includes proprietary information which is why it is not public on my GitHub.
