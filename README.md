![](Screenshots/crime-tape.jpg)

# Do stricter state gun laws have a positive correlation on US mass shootings? 
By Chris Baeurle

## Overview
Gun violence has become normalized in our US society. The latest data from the US Centers for Disease Control and Prevention (CDC) shows a total of 45,222 people died from gun-related injuries of all causes during 2020. More than 19,000 of the deaths were homicides. Reports from the Gun Violence Archieve, along with Mother Jones present the dismal fact that mass shootings have been ever increasing. Meanwhile the US continues to be at odds over gun rights and regulation. That begs the question, do gun laws in place have an effect on preventing mass shootings? 

I set out to find if there is indeed a correlation.

## Data Process
* Problem statement and decision tree planning
* BigQuery to scrape certain data from internet, pull others <br/>
* Creating standardized scoring metric in for state laws and incorporating into data 
* Python - Data Cleaning, Data Analyses (regression, including predictive regression modeling), visualizations (radar, scatter, distribution)
* Dashboard visualization for overall results presentation <br/>

## Data Analysis and Presentation

[Python](https://github.com/ChrisBaeurle/Gun-Violence-vs-State-Laws/blob/main/US%20Gun%20Violence.ipynb)<br/>
<img src="https://github.com/ChrisBaeurle/Gun-Violence-vs-State-Laws/blob/main/Screenshots/Screenshot_1.png" width="200" />

[Tableau](https://public.tableau.com/app/profile/chris.b6153/viz/USMassShootings_16751150296610/GVAkilled-state)<br/>
<img src="https://github.com/ChrisBaeurle/Gun-Violence-vs-State-Laws/blob/main/Screenshots/Screenshot_Tab.png" width="200" />

## About the dataset
* everytownreasearch - organization committed to reducing gun violence, datasets tracked
* Mother Jones - news site collecting data on mass shooting and applying more detailed metrics/info from data obtained through researching news articles
* Gun violence archive - online database committed to tracking all gun violence accounts in the US
* Gun laws in the US (wiki) - excel power query extract of each state's laws from Wikipedia; comprehensive database of all states backed up with citations
* NST-EST2022 - state by state population data from the US Census Bureau.

## Tech Stack
* Excel (BigQuery for web scraping), Powerpoint
* Python (pandas, seaborn, matplotlib, plotly, scikit-learn)
* Tableau
