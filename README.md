
![image](https://github.com/user-attachments/assets/53fedee9-4f05-4963-b415-7b943f1e7ae0)

# Aircraft Risk Analysis 

Author: [Tracy Gwehona](tracy.gwehona@student.moringaschool.com)

## Overview

The company is planning to enter into the aviation industry in order to diversify its assets, with the intention of purchasing and operating airplanes for commercial and private enterprises. This project analyzes aviation accident data sourced from Kaggle to identify airplanes with the lowest risk to the company.
A descriptive analysis of the data such as accident frequency, severity and other factors will highlight which aircrafts pose the least safety, financial and operational risks.
The company can use this analysis to decide which airplanes to purchase.

### Business Problem

The company may be able to minimize the risks of safety and financial liabilities associated with the operation of an aircraft by selecting the safest and most reliable models.
I aim to:
1. Identify low risk airplane models.
2. Evaluate the severity and frequency of accidents.
3. Assess factors that contribute to accidents.
4. Provide recommendations for selecting the best airplanes based on the data analysis results.

Doing so will help the company to make informed decisions on which airplanes to purchase.

### Data

In the `data` folder is a [dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) from the [National Transportation Safety Board](https://www.ntsb.gov/Pages/home.aspx) that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.  contains a detailed record of airplane accidents. Every accident has a unique ID and important details such as the date, location, airplane make and model, the severity of injuries, etc. The dataset also captures factors like weather conditions and the phase of flight.

## Methods
### Data Cleaning
Missing values and duplicated rows are handled. Also, columns irrelevant to the project are dropped. Formatting of columns and their contents for smooth analysis.

### Data Analysis
The aviation accident data is analysed by use of visualizations.
Sample visualizations include:

 a) Visualizations showing total fatal, serious, minor injuries and uninjured by model of aircraft
 
![Capture2](https://github.com/user-attachments/assets/796d80d5-fab5-4718-bad6-03cc6d3569b2)

 b) Visualizations showing total fatal, serious, minor injuries and uninjured by make of aircraft
 
![Capture](https://github.com/user-attachments/assets/7d46c77b-39b8-4e57-b5f9-95ae30c1f547)

## Conclusion

Accidents happen; they can be or can not be prevented. It is impractical to say that a certain aircraft will never be able to incur an accident. Make, model and other features of a plane may affect it but other measures should also be put in place by the company such as safety measures, etc.

Based on the analysis done:
- Model, make and type of engine affects the number of injuries/ unijured. 
- Number of engines in a plane is uncorrelated to the number of injuries/ uninjured.

## Recommendations

I would recommend the company to consider the following:
- Model of the aircraft: model 737. Even though it has the highest fatalities, it also has the highest number of uninjured. If more safety measures are put in place, the number of uninjured can surpass the injured.
- Make of the aircraft: Boeing. It shows to be the most safest due it is high number of uninjured and moderate numbers of injuries.
- Professionally built planes. Professionally built planes have proven to have more uninjured passengers as compared to amateur built ones.
- Type of engine: turbo tan engine since it had the most number of uninjured people.

If interested in a number of options, consider the following makes:
- Boeing 
- Mcdonnel 
- Douglas
- Piper
- Airbus

## Interactive Dashboard

The interactive dashboard is a collection of views that allows the viewer to change the views to understand different features in the data. Here is a link to my interactive dashboard [Tableau Dashboard](https://public.tableau.com/app/profile/tracy.gwehona/viz/AviationAccidentsNTSB1948-2022/AviationInjuriesDashboard)

