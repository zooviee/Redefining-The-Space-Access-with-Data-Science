# Redefining-The-Space-Access-with-Data-Science

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Dash](https://img.shields.io/badge/dash-008DE4?style=for-the-badge&logo=dash&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Microsoft PowerPoint](https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

_Offered by_ **IBM Data Science Professional Certificate** _on_ **Coursera** 

$9^{th}$ September $2023$


<img src="https://github.com/beatricemarrano/spacey/assets/93832250/bbf591d8-8f84-4b0f-954f-03037ff7235b" width="100" height="100">
<img src="https://github.com/beatricemarrano/spacey/assets/93832250/a7ac9be8-f535-4213-a438-647bec69a89f" width="100" height="100">



## Summary of project: 
In this project, we will take the role of a data scientist working for the new rocket company SpaceY. More in details, we will predict if the «Falcon 9» first stage will land successfully and consequently the price of each launch. In fact SpaceX advertises «Falcon 9» rocket launches on its website with a cost of 62 million dollars, while other providers cost upward of 165 million dollars. This big difference is due to the fact that SpaceX can reuse the first stage if it lands successfully.

<img width="413" alt="image" src="https://github.com/beatricemarrano/spacey/assets/93832250/d83fa0bd-cb15-4adc-b966-6c5d404b2b03">


## Summary of methodologies: 
To accomplish this we will gather data about SpaceX and create some visualization and dashboards for our team. Data will be gathered in 2 ways: with the SpaceX REST API call and with Web Scraping of some Wiki Tables.

## Summary of all results: 
The insights we found with this analysis is that the different launch sites have different success rates, and different maximum payload masses they carry; there are 4 main orbits that have a very high success rate (0.9-1.0), while all the others are around 0.6; only some orbtits’ success rate is linked to the Flight number; the success rate has kept increasing from 2013 to 2020. Furthermore, the application of the machine learning classification models, showed that the best model to predict if the first stage will land successfully is the decision tree classification model.

## Project questions:
* Will the first stage land successfully or not?
* What will then be the price of a launch?

## Documents overview:
In this repository there are 7 notebooks, 1 python file, 1 powerpoint presentation and 2 image folders. The analysis has been done by following the steps listed below:

**1. Data collection methodology:**
* Data Collection API.ipynb
* Data Collection Web Scraping.ipynb
* Data wrangling.ipynb

**2. Exploratory data analysis (EDA):**
*  EDA with Visualizations.ipynb 
*  EDA with SQL.ipynb
  
**3. Interactive visual analytics:**
* Interactive Maps using Folium: Interactive visualizations.ipynb and Folium_maps
* Building a data application in Python using Plotly Dash: dash_interactivity.py and Dash_images folder
  
**4. Predictive binary classification analysis:**
* Machine Learning Predictions.ipynb

**5. Project presentation:**
* Presentation_spacey.pdf

## Results: 
1. The exploratory data analysis gave us many information related to every feature and also on the inter features relationships. Among the main finding we have:
* There are 4 different launch sites
* For the VAFB SLC 4E there are no rockets lunched for payload mass higher than 10000
* There are 4 Orbits with a very high average success rate
* Only for some orbits the success appears to be related to the flight number
* Overall the success rate has always grown from 2013 to 2020. 

2. Interactive analysis: The interactive analysis showed geographical patterns linked to each launch site and their success rate in a visual and intuitive way.

3. Predictive analysis results: The classification analysis showed that the best model is the Decision Tree Classifier with a train accuracy of 88% and a test accuracy of 94%.
