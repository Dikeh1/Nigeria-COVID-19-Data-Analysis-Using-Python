# Nigeria COVID-19 Data Analysis using Python
![shutterstock_1697804203.jpg](attachment:e4da96ad-de66-4745-95d9-f11a61a4cae6.jpg)
## Overview
An infectious condition known as coronavirus disease (COVID-19) is brought on by a recently identified coronavirus. A person infected with the COVID-19 virus may develop mild to moderate respiratory infection and recover without the need for special care, while symptoms can occasionally be severe.  
Nigeria, a West-African country, has also been affected by the COVID-19 pandemic after recording its first case on 27th February 2020. Nigeria is a country with 37 states - Federal Capital Territory included- and a fast-growing economic environment with about 200 million citizens. COVID-19 has affected several country activities as the country steadily progressed from its first case to shutting down major airports, state-wide lockdown, curfews, and reviving its economy.
### **Data Collection**
The data source is divided into different parts, and these data will be combined to perform analysis and provide insights. Some of the data set was got from the [Github link](https://github.com/Ustacky-dev/Nigeria-COVID-19-Data-Analysis-Using-Python).

#### **1. The Nigeria Centre for Diseases Control (NCDC)**: 
The institution monitors the country’s COVID-19 situation, and releases data on metrics across all the 37 states in the country. From [NCDC](https://covid19.ncdc.gov.ng/) COVID-19 official website, performing a web extraction or web scraping, covid data was extracted.

#### **2. The Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE)**: 
The institute publishes daily data on confirmed, death and recovered cases across different countries. the daily data for Nigeria was extracted from their repositor.

#### **3. Nigeria Community Vulnerability Index data**
The vulnerability index was computed by considering several factors such as socio-economic status, population density, housing type, transportation, epidemiological, health system etc, these factors are known as themes. Each theme was broken into subthemes, and data was gathered from them to compute the overall vulnerability index score by weighing equally each theme. You can use the index data with datasets related to the pandemic such cases, deaths etc to determine relationships and correlations in your analysis.
#### **Note that:**
- The term “vulnerability” refers to the impact of the virus on a community after the virus arrives.
- It ranks from Very Low(0) to Very High(1+)


#### **4. Real Domestic Gross Product Data**
Data on the Real Domestic Gross Product(GDP) data for Nigeria was extracted. This aided us to determine the impact of COVID-19 on the economy. We can achieve this by comparing the Real GDP(Pre-COVID-19) with Real GDP(During COVID-19).

#### **5. State Budget Data**
States across the country reduced their initial budget due to the impact of COVID-19 on the economy. We will used the data provided to determine the impact of COVID-19 on the economy.
The project analyses the collected data to explore how the COVID pandemic affected Nigeria. 
- It was observed that Lagos had the highest confirmed COVID_19 cases. We then have the FCT and Rivers state also with high confirmed cases after Lagos state.
- Lagos state recorded the highest recovery and discharged cases accompanied by the FCT and Rivers state.
- There was a daily increase in the number of confirmed cases, hitting above 250,000 in 2022. From september 2022, the number of confirmed cases remained relatively the same all through to January 2023.
- A significant increase was recorded in recovered cases between May, 2020 to September, 2022 with more than 150,000 total recovered cases. There was a drop in recovered cases towards September, 2021. No recovered cases was recorded as seen in the global data analysed.
- Death cases due to COVID-19 was over 3000 as at January, 2022, with about 3155 death cases recorded on the 13th September, 2022. Death cases has remained relatively constant just after 13th September, 2022.
- Understanding the relationship between community vulnerability and confirmed cases of COVID-19 is important for developing effective public health interventions and policies to prevent the spread of the disease and protect vulnerable communities. Kaduna and kano had a significantly high vulnerability index with low rate of spread of the COVID virus while Lagos had a low overall community vulnerability index and a high number of confirmed cases, this may indicate that the disease is spreading rapidly despite the lower vulnerability of some communities. Appropriate public health intervention will be needed to check states like Kano and Kaduna to ensure proper testing is being carried out. There is a need to create and enforce policies to checkmate the rate of spread of the COVID virus in Lagos.
-  There were some direct correlation between the population density and the number of confirmed cases per state. It was also discovered that the number of confirmed COVID cases were not entirely dependent on the population density as some states with high population density were seen to have lower number of confirmed COVID cases. This could be as a result of the states observing good public health polices or there were not enough data got or testing done in that region
- The data shows that more death cases were recorded in states with low or insufficient health systems. States like Lagos and Edo with similar level of health system recorded high death rates compared to states like Delta and Kaduna.
- There was a drop in GDP in the third quarter of 2020. This indicates the negative effect the pandemic had on the economy.
- Due to the economic impact of the COVID-19 pandemic across the country, it was observed that all the states had their budgets revised. No state had the revised budget above the initial one. This goes to show how critical the pandemic affected lives across the country. 
![Dashboard 1.png](https://public.tableau.com/app/profile/chukwudike.ofodum/viz/NigeriaCOVIDData2/Dashboard1)
