# Covid19-Analyzer-Project

## Project Overview

The primary objective of this project is to analyze COVID-19 data from two reliable data sources to understand the spread, impact, and trends of the pandemic across various regions. This includes identifying key patterns, such as new_cases_per_million, new_death_cases_per_million, Obesity rates, median age, impact from Diabetes, testing rates etc.

## Repository Contents:
1. Project Code ipynb file - Covid19_Analyzer_Project.ipynb
2. CSV Dataset used - owid-covid-data.csv
3. html response saved to perform regular expression checks - response.txt
4. Images used

I worked on this project by refering to Derek Banas's github repository. Reference [here](https://github.com/derekbanas/Covid-19-Data-Analysis)

## Technologies Used

- Python
- Web Scraping
- Regular Expressions

## Pyhon & Web scraping Skills Acquired

- Use of Numpy & Pandas (data manipulation libraries)
- Use of Matplotlib and Plotly (visualization libraries)
- Use of Web scraping libraries like BeautifulSoup
- Regex with Python
- And much more 😅

## Key Concepts

- Moving Average
- Correlation does not imply causation


The project begins by asking the below questions to better understand the Global Pandemic Covid-19 and to harness the power of data analysis to answer the questions.

- How can we examine the progress of a country?
- Do lockdowns work?
- How Does Median Age Effect Death Rate?
- How Does Obesity Effect Death Rate?
- How Does Diabetes Prevalence Effect Death?
- Does More Testing Slow Deathrate?

## Please visit the actual ipynb file to checkout the Project Code along with explanation: 
- https://github.com/SandeepanBhattacharyya/Covid19-Analyzer-Project/blob/main/Covid19_Analyzer_Project.ipynb

## Project Conclusion

### 1. How can we examine the progress of a country?

MOVING AVERAGES !!!

<img src="https://github.com/SandeepanBhattacharyya/Covid19-Analyzer-Project/blob/main/movA.jpeg" class="center" style="width: 500px; height: 500px;">

- Moving averages are statistical tools used to smooth out fluctuations in data over a specified period, providing a clearer view of trends and patterns. In the context of COVID-19 data analysis, moving averages help to mitigate the impact of daily variations and anomalies, allowing for a more accurate assessment of trends in infection and mortality rates. 

- By calculating the average of data points over a rolling window, moving averages reveal underlying trends and help identify whether a country's death rate is increasing or decreasing relative to historical data. This approach facilitates more informed comparisons between countries and can guide public health responses by highlighting significant deviations from expected trends.

### 2. Do lockdowns work?

- We observe that Sweden, which implemented less restrictive lockdown measures, shows a higher rate of new COVID-19 cases compared to the moving average reference line.

- In contrast, Bolivia, which consistently enforced lockdowns, exhibits a declining rate of new cases, with the trend line falling below the moving average reference line.

### 3. How Does Median Age Effect Death Rate?

- Our analysis indicates that Serbia, which has a lower median age, reported a higher number of deaths per million compared to Japan, which has a higher median age.

- This observation does not necessarily imply that median age has no correlation with COVID-19 mortality rates. For instance, while comparing Japan and Bolivia, it is important to consider that numerous factors such as healthcare quality, infrastructure, and other variables may influence the mortality rates. Therefore, further investigation is required to understand the relationship between median age and COVID-19 deaths fully.

### 4. How Does Obesity Effect Death Rate?

- Our analysis reveals that countries with high obesity rates, such as the USA and Canada, exhibit higher death rates per million population. In contrast, countries like India and Japan, which have lower obesity rates, show lower death rates per million population.

### 5. How Does Diabetes Prevalence Effect Death?

- The curve for Ireland, a country with a low diabetes rate, indicates a flattening of the death rate. In contrast, the USA, which reports a higher death rate and a significant peak above the moving average line, continues to experience elevated mortality.

### 6. Does More Testing Slow Deathrate?

- We observe Denmark is performing better than Mexico. Denmark performed more testing, which has allowed them to quarantine/isolate more people which resulted in flattening the curve.

## Crearing a more flexible function to handle all Countries
- Harnessing the Power Of Plotly, to create a scatter plot to plot various combinations. It is also intercative in nature.
- `scatter_plot('2020-10-27', 'aged_70_older','total_deaths_per_million')`
<img src="https://github.com/SandeepanBhattacharyya/Covid19-Analyzer-Project/blob/main/newplot.png" class="center">

-`scatter_plot('2020-10-27', 'median_age','total_deaths_per_million')`
<img src="https://github.com/SandeepanBhattacharyya/Covid19-Analyzer-Project/blob/main/newplot (1).png" class="center">

-`scatter_plot('2020-10-27', 'diabetes_prevalence','total_deaths_per_million')`
<img src="https://github.com/SandeepanBhattacharyya/Covid19-Analyzer-Project/blob/main/newplot (2).png" class="center">

-`scatter_plot('2020-10-27', 'male_smokers','total_deaths_per_million')`
<img src="https://github.com/SandeepanBhattacharyya/Covid19-Analyzer-Project/blob/main/newplot (3).png" class="center">

Thank You. Once again, you can refer the explanation along with the Visulas in the Actual ipynb file: 
- https://github.com/SandeepanBhattacharyya/Covid19-Analyzer-Project/blob/main/Covid19_Analyzer_Project.ipynb

<img src="https://github.com/SandeepanBhattacharyya/Covid19-Analyzer-Project/blob/main/defeat_CV19.jpeg" class="center" style="width: 500px; height: 500px;">

## Actual Sites used for WebScraping:
- Link to the Actual Worldometers website is :https://www.worldometers.info/coronavirus
- Link to the Actual OurWorldInData Website is : https://ourworldindata.org/covid-cases


  

  
