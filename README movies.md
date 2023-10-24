# Creating Original Movies Project

This project was completed as the final Phase 2 assessment in the Flatiron School’s Data Science Bootcamp. 


## Overview

This project analyzes which types of movies generate the most revenue at the box office. Descriptive analysis of movie data sets collected from Box Office Mojo, IMBD, Rotten Tomatoes, The Movie DB, and The Numbers, will highlight specific movie characteristics that increase ROI such as, studio location, film rating (R, PG, etc), and movie genre. This analysis can be used by the company to decide in which location to build a studio and help the company's new movie studio operate with the lowest risk in their new business endeavor.


## Business Problem

Analyzing several movie datasets can provide valuable insights that can lead to concrete business recommendations in various aspects of the film industry. When considering characteristics of a successful movie, I analyzed the movie data to identify movies with the greatest return on investment. Based on this analysis, which is explained below, I can recommend       . Furthermore, below are three recommendations based on my analysis:

1. 
2. 
3. 

It's important to note that any business recommendations derived from data analysis should be accompanied by careful consideration of the specific context, legal and regulatory requirements, and limitations of the dataset. Additionally, these recommendations should be subject to ongoing evaluation and refinement based on updated data and emerging industry practices.


* **Jupyter Notebook**

The [Jupyter Notebook](https://github.com/cellister/2023-Flatiron-Data-Science-Bootcamp/blob/main/Phase%201/Phase%201%20Project/Phase%201%20Project%20Final%20Edits.ipynb) is the key deliverable and contains the details of my data strategy, methodology, data cleaning, visualizations, and actionable insights.

* **Presentation**

This 5-7 minute, non-technical [presentation](https://github.com/cellister/2023-Flatiron-Data-Science-Bootcamp/blob/main/Phase%201/Phase%201%20Project/Aircraft%20Investment%20Analysis%20Presentation.pdf) was made in [Canva](https://www.canva.com/design/DAFq9SLHAXA/iEdRqzE7akOfkr0au0UHvg/view?utm_content=DAFq9SLHAXA&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink) and gives an impactful and brief overview of the key insights and recommendations. 

* **Data**

The data used in this analysis can be found in the ‘Data’ folder. It was originally provided on the [Kaggle website](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses).

* **Visualizations**
Tableau graphs can be found on [Tableau Public](https://public.tableau.com/views/AmateurBuiltvsSurvivalPercentage/Sheet1?:language=en-US&:display_count=n&:origin=viz_share_link). for quick access please see the [Tableau Viz](https://github.com/cellister/2023-Flatiron-Data-Science-Bootcamp/tree/main/Phase%201/Phase%201%20Project/Tableau%20Viz) folder.


## Data Understanding 

The National Transportation Safety Board provides public data that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters. Each entry has a unique event ID associated with information such as the type of aircraft, date, fatalities, location, and many other factors.

Overview of dataset:

   **Source:** National Transportation Safety Board
 
   **About:** National and international civil aviation and selected incidents from 1962-2023
 
   **Design Variables used:** Total Fatal, Serious, Minor injuries, Total Uninjured, Make, Model, Engine Type, Amateur Built, Aircraft Damage
 
   **Operations Variable used:**  Event Date
 
   **Missing Values:** Rows missing complete data for make and model were dropped


## Key Findings

**Return on Investment:**
* Passenger survival percentage for each make and model set determines the 10 safest airplanes.


<img width="400" height="400" src="Images/10safest.png" alt="10safest">


Recommendations

**Studio Location**

* While experimental/amateur built aircrafts may show success, the survival rate for amateur built aircrafts involved in accidents is more than 15% lower than professional manufacturing.


<img width="400" height="400" src="Images/Amateurbuilt.png" alt="Amateurbuilt">


**Film Rating (R, PG, etc)**

* Several types of engines showed reliability. While electric, geared turbofan, and turbo shaft all had 100% survival rate, their survivors combined were 143 people. The turbo fan engine has a 98.78% survival rate and transported over 60K passengers suggesting further investigation is needed into the reported deaths to confirm that they were a direct result of the airplane accident. 


<img width="400" height="400" src="Images/Enginetype.png" alt="Enginetype">


**Movie Genre**

* Looking at the aircraft damage category, anything destroyed is a high-risk, substantial is medium- risk, and minor is low-risk.


<img width="400" height="400" src="Images/aircraftdamage.png" alt="aircraftdamage">


## Actionable Insights

1. 
2. 
3. 


## Author

Name: Erin Wasserman

GitHub: [Cellister](https://github.com/cellister)

Email address: cellister at gmail .com


