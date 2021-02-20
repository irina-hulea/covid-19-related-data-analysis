# COVID-19 Vaccination Progress Data Analysis

## Project motivation

The vaccination campaign started around three months ago already and with so many information in the media, it may be difficult to get the big picture.

This data analysis is focused on summarizing how the Covid-19 vaccination is going around the world. More accurately, it is focused on answering the following questions 

* How many types of vaccine are used? Where a specific vaccine is used in the world?
* Where are vaccinated more people per day? Is the number of daily vaccinations going up?
* In which country/region the vaccination programme is more advanced? When will we have 25% of the population vaccinated?

## Technologies used

- the data analysis is done in a Jupyter Notebook with Python 3
- libraries needed for the notebook to run successfully together with the version I used:
    - ``` pandas==1.2.0 ```
    - ``` numpy==1.16.5 ```
    - ``` matplotlib==3.1.3 ```
    - ``` plotly==4.14.3 ```
    - ``` fbprophet==0.5 ```
        - note that in order to be able to properly visualize the plotly plots, you should run the notebook yourself after installing the packages above or check [my Kaggle notebook](https://www.kaggle.com/irinahulea/covid-19-vaccination-progress-around-the-world) on the same subject

## File Description

- **covid-19-vaccination-progress-around-the-world.ipynb** 
    - Jupyter Notebook containing the data analysis
- **country_vaccinations.csv** 
    - Our World in data COVID-19 World Vaccination Progress
    - file downloaded from Kaggle, you can find it [here](https://www.kaggle.com/gpreda/covid-world-vaccination-progress) (this data is collected daily from [Our World in Data](https://github.com/owid/covid-19-data) GitHub repository for Covid-19)
- **continents2.csv**
    - country iso and region/continent information
    - file downloaded from Kaggle, you can find it [here](https://www.kaggle.com/andradaolteanu/country-mapping-iso-continent-region)
    
## Results

The main findings from this data analysis cand be found on [my blog post](https://irinahulea.medium.com/how-is-the-vaccination-campaign-against-covid-19-going-10abf0935af4) on Medium