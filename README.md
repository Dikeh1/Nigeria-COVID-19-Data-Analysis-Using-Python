# Nigeria COVID-19 Data Analysis using Python
![covid](https://github.com/user-attachments/assets/a40871c4-7f33-4f08-bde7-6bfaf9c6ae5b)
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

### KEY FINDINGS
- It was observed that Lagos State had the highest number of confirmed COVID-19 cases. Following closely were the Federal Capital Territory (FCT) and Rivers State.
- Lagos State also recorded the highest number of recovered and discharged cases, followed by the FCT and Rivers State.
- There was a daily increase in confirmed cases, surpassing 250,000 in 2022. From September 2022 to January 2023, the number of confirmed cases remained relatively stable.
- A significant increase in recovered cases was recorded between May 2020 and September 2022, with over 150,000 total recovered cases. However, there was a decline in recovered cases around September 2021. No recovered cases were recorded, as seen in the global data analyzed.
- As of January 2022, over 3,000 COVID-19-related deaths had occurred. On September 13, 2022, the death toll reached approximately 3,155. Since then, the number of deaths has remained relatively constant.
- Understanding the relationship between community vulnerability and confirmed COVID-19 cases is crucial for developing effective public health interventions and policies to prevent the spread of the disease and protect vulnerable communities. Kaduna and Kano, with significantly high vulnerability indices, had low rates of COVID-19 spread. Conversely, Lagos, with a low overall community vulnerability index, had a high number of confirmed cases, suggesting rapid disease spread despite lower vulnerability. Appropriate public health interventions are needed to ensure adequate testing in states like Kano and Kaduna. Additionally, policies to curb the spread of COVID-19 in Lagos should be implemented and enforced.
-  A correlation was observed between population density and the number of confirmed cases per state. However, it was also discovered that the number of confirmed cases was not solely dependent on population density, as some densely populated states had lower case numbers. This could be due to effective public health policies or insufficient data and testing in those regions.
- The data indicates that more deaths were recorded in states with low or insufficient health systems. States like Lagos and Edo, with similar healthcare systems, had high death rates compared to states like Delta and Kaduna.
- The GDP declined in the third quarter of 2020, highlighting the pandemic's negative impact on the economy.
- Due to the economic impact of the COVID-19 pandemic, all states revised their budgets downward. This demonstrates the significant impact of the pandemic on the nation's economy and livelihoods.
-  ![Dashboard 1](https://github.com/user-attachments/assets/23776529-8fed-48c6-a1a0-9309376727ec)
