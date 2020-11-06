# Data Science Portfolio
Jeb Stewart\
(913) 742-1648\
jebstewart22@gmail.com

# [Project 1: Classification of Breast Cancer Cell Nucleii](https://github.com/JebStewart/BreastCancerTumorClassification)
**Objective:** Classify breast cancer cell nucleii samples as either benign or malignant

**Importance:** Benign and Malignant tumors are often treated using completely different methods. The treatments themselves can cause harm so using the incorrect treatment on a patient could not only be ineffective, but detrimental to the health of the patient.

**Outcome:** 
- Able to classify unseen data with an F1 Score of 0.974
- Explored the morphological changes of cancerous cell nucleii and their role in metastasis

![](/images/BCCresults.png)

**Skills Used:** Data Manipulation, Data Visualization, Classification with XGBoost, LightGB, and SVM 

# [Project 2: Robinhood Auto-Trader (WIP)](https://github.com/JebStewart/AlgoTrading)
**Objective:** Build a tool to predict short-term large moving stocks, and automate the buying and selling through Robinhood. 

**Importance** I used this as a higher stakes way to practice feature engineering, machine learning, and writing robust code. 

**Outcome (ongoing):** Model was trained on 100 most popular stocks on Robinhood from Jan 2019 to Jan 2020. In a simulated environment (using real values from the market) the auto-trader paper traded with $1000 dollars and managed to grow 300% in 9 months following the training time period. The auto-trader was then given access to my actual account with $118 and has grown to ~112% in roughly 4 weeks. I will update this every week.

![](/images/TestPredictorPlot.png)

**Skills Used:** Python, Statistics, Data Mining, Feature Engineering, Automation, API's, Web Scraping 

# Project 3: Predictive Maintenance Modeling
**Objective:** Using existing sensors on board product, approximate when failure will occur and request customer perform maintenance.  

**Importance:** Due to the high variation of environment products would operate in, time between failures varied wildly as customers did not know when to perform maintenance. The units regularly failed to meet warranty hour minimums as a result.

**Outcome:** 
- Able to predict failure within 10% of total life under lab conditions. 
- Acted as proof of concept for the application of the technology in our domain.
- Proved existing sensors would suffice for a retrofit software only solution (as hardware changes are significantly more expensive in aerospace)

**Skills Used:** Experiment Design, Data Collection, Mining, Cleaning, and Visualization, Time-Series Analysis and Regression

# Project 4: Data Collection and Parsing App
**Objective:** Create a tool for technicians to collect serial stream data from our products during experimentation, and parse the data into a .csv file for immediate analysis. I also included a basic dashboard in it to show non-fatal faults.

**Importance:** Sensor and processor state data is sent out constantly from the product, but was not stored or collected. This made diagnosing issues on the unit difficult as history logs alone would only capture snapshots of the product state when specific conditions were met. Oftentimes the unit would fail with hours of missing data between snapshots. 

**Outcome:** 
- I wrote a program that has been distributed to my associates and has been in constant use since creation
- In a few months the program has saved dozens of engineering hours in diagnosing unit failures during testing
- The program has reduced the amount of modifications that must be made to units for testing which has allowed more tests to be run on an individual unit
- The program has allowed for the capture of what the product "sees" and has allowed the team to isolate and fix discrepancies between the products perception and reality

![](/images/SerialLoggerScreenshot.png)

**Skills Used:** Python Programming with Kivy for UI, Data Collection, Data Cleaning, Automation, Git

Note: For project 3 and 4, the code is owned by Raytheon Technologies and includes proprietary information which is why it is not public on my GitHub.
