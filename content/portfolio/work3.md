+++
image = "img/portfolio/aging.jpg"
showonlyimage = false
date = "2016-11-05T19:44:32+05:30"
title = "The COVID-19 Pandemic and the Aging American Population: Data Exploration"
draft = false
weight = 2
+++

Maria Ambrosio, 
_Last run: 09-01-2021_

**Background**

In February 2020, the first case of the novel Coronavirus emerged in the U.S, and since then, it has taken the lives of Americans regardless of their race or age group. Older adults were significantly more affected by the SARS-CoV-2 for several reasons. The COVID-19 pandemic affected the three main domains for healthy aging, function, health status, and social inclusion. Due to prevention guidelines and high peak of infections, older Americans faced more barriers to maintaining a high level of mental and physical functioning and maintain an active engagement with life. The age group was also at higher risk for disease and disability due to age-related physiological changes such as decreased cardiac output and impaired gas exchange of the lungs (Drummond-Barbosa, 2020; Anderson et al., 2012).  

<!--more-->

**Objectives**

The primary objectives of this exploratory analysis are to (1)understand the impact of the COVID-19 pandemic in the American population 65 years and older, and (2) understand the challenges and prospects to support older adults in the U.S.

**Methods**

This analysis was developed by using descriptive statistics. The measures calculated were crude death rate, incidence rate, vaccination rate, and proportionate mortality. The policies evaluated were the COVID-19 vaccine policy and Medicaid Expansion. Data pre-processing and analysis were performed using SAS® and R programming language. 

>Data source 

* Centers for Disease Control and Prevention. (2021). Provisional COVID-19 Deaths by Sex and Age. Retrieved from https://www.cdc.gov/csels/dsepd/ss1978/lesson3/section3.html
  + (60,588 Observations, 15 Variables)
* Our World in Data. COVID-19-Data. (2021). Retrieved from covid-19-data/public/data at master · owid/covid-19-data · GitHub
  + (107,897 Observations, 60 Variables)
* United States Census Bureau. April. (2021). 2020 Census Apportionment Results, Table 2 Resident Population for the 50 States, the District of Columbia, and Puerto Rico: 2020 Census". Retrieved from https://www.census.gov/data/tables/2020/dec/2020-apportionment-data.html.
  + (51 Observations, 6 Variables)



**Results**

More than 600,000 Americans have died due to the infectious disease caused by the SARS-CoV-2 (New York Times, 2021). Individuals aged 65 and older represented 81% of those deaths. 

![US Death Rate Age Group][1]


Figure 1.Proportion of COVID-19 deaths among different age groups in the U.S.

The COVID-19 vaccine policy was fundamental in reducing the spread of the disease and the surge of new cases. In earlier summer, as vaccines became available and approximately more than half of the population was fully vaccinated, new cases declined dramatically. Nevertheless, as the more contagious Delta variant emerged incidence rate increased in July and August.  

> * Vaccination rate = number of individuals fully vaccinated recorded in a year /mid interval population * 100,000
> * Incidence rate = number of new cases recorded in a year /mid interval population * 100,000


![compare incidence and vaccination trends][2]

Figure 2.Comparison of COVID-19 incidence rate and rate of individuals fully vaccinated in the U.S.

<!--more-->

Illinois was the state with a higher COVID-19 death rate, 129 deaths per 100,000 people, while New York was the state that presented a lower death rate, 79 deaths per 100,000 people. The COVID-19 death rate in Georgia and Florida were 96 and 101 deaths per 100,000 people, respectively. The rate of deaths in California was 84 deaths per 100,000. On average, states without Medicaid Expansion presented a COVID-19 mortality rate 6.42% higher than states with expansion. 

> * Death Rate = number COVID-19 deaths recorded in a year / mid interval population * 100,000



![compare medicaid expansion and death rate among states][3]
Figure 3.Comparison of the COVID-19 death rate among the U.S states that approved Medicaid expansion policy and states that did not approve the policy.



<!--more-->


A similar evaluation was performed in the 52 states, and those without Medicaid Expansion presented a COVID-19 mortality rate 14% higher than states with expansion. 

> * Death Rate = number COVID-19 deaths recorded in a year / mid interval population * 100,000


![US Death Rate medicaid expansion states comparison][4]
Figure 4.Comparison of the COVID-19 death rate among the U.S states that approved Medicaid expansion policy and states that did not approve the policy.

<!--more-->

Two other mortality rate measures were used to investigate if states that approved Medicaid Expansion policy presented lower COVID-19 deaths due to higher deaths associated with other diseases. However, the data revealed that states without Medicaid Expansion presented a COVID-19 proportionate mortality rate 11% higher than states with expansion.

> * Proportionate Mortality= number of deaths recorded in a year  / Total deaths recorded in same year* 100

![US proportionate Death Rate][5]
Figure 5.Comparison of the proportionate mortality rate among the U.S states that approved Medicaid expansion policy and states that did not approve the policy.

<!--more-->


![US Death Rate Age Group][6]
Figure 6.Comparison of the crude death rate among the U.S states that approved Medicaid expansion policy and states that did not approve the policy.

States without Medicaid Expansion presented a crude death rate 13.7% higher than states with expansion. Therefore, regardless of approving Medicaid Expansion or not, the same trend is observed among states. Death rates among older adults are extremely higher compared to other age groups. The COVID-19 pandemic only came to uncover and exacerbate an important problem within the American Health System. Even though Medicare provides medical coverage to Americans aged 65 and older, it does not yield custodial care (Feder, Komisar & Niefeld, 2000). High costs of long-term care (LTC) force older adults to rely on unpaid family caregivers (Dodge, 2018). The disease also negatively impacted the nursing home industry. Nursing homes occupancy rates decreased by approximately 14% from the first quarter of 2020 to the first quarter of 2021 (Barone, 2021). 

Further research is needed to analyze if exists a causal relationship between Medicaid Expansion and the state's capability to manage the COVID-19 crisis. The results from this study could inform the development of a government-run program to provide long-term care coverage to the population 65 years and older and inform policies to help regulate and grow the long-term care insurance market. Additionally, is it is important to investigate strategies that could inform the alignment of medical care and social care services to better serve older adults in the U.S.



                            References

1. The New York Times. (2021). Coronavirus in the U.S.: Latest Map and Case Count. Retrieved from https://www.nytimes.com/interactive/2021/us/covid-cases.html
2. Drummond-Barbosa, D. (2020). Physiology and aging: New understanding of organs that affect the physiology of aging. Innovation in Aging, 4(Supplement_1), 739–740. https://doi.org/10.1093/geroni/igaa057.2641 Retrieved from https://academic.oup.com/innovateage/article/4/Supplement_1/739/6038565
3. Anderson, L. A., Goodman, R. A., Holtzman, D., Posner, S. F., & Northridge, M. E. (2012). Aging in the United states: Opportunities and challenges for public health. American Journal of Public Health, 102(3), 393–395. https://doi.org/10.2105/ajph.2011.300617 
Retrieved from https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3487684/
4. Feder, J., Komisar, H. L., & Niefeld, M. (2000). Long-Term care in The United states: An overview. Health Affairs, 19(3), 40–56. https://doi.org/10.1377/hlthaff.19.3.40. Retrieved from
https://www.healthaffairs.org/doi/full/10.1377/hlthaff.19.3.40?casa_token=LdKnqdeICuQAAAAA%3AXFr-Te1HzgbNrbC2cO_L9IOBpoQ9QtoUCjABIoTGdiSaHzaaeL-q9VNr_DKKaw-U22JeNwFuA-o
5. Barone, E. (2021). COVID-19 Exposed the Faults in America’s Elder Care System. This Is Our Best Shot to Fix Them. Retrieved from https://time.com/6071582/elder-care-after-covid-19/
6. Dodge, J. (2018). The No-Brainer Case for Universal Long-Term Care. Retrieved from The No-Brainer Case for Universal Long-Term Care – People's Policy Project (peoplespolicyproject.org)

NB: This analysis was presented at the Georgia Health Policy Center on 08/12/2021.

>Access the full code to create this analysis here: http://covid19-dataexploration.mtcambrosio.com/?fbclid=IwAR2yxt4Vhvim3wjvtnaciPdzgqXRNLcvXPqdO7h_waHT5JPAWXn4hVJXP68

###### Copyright © 2021 Maria Ambrosio 

[1]: /img/deathage.png


[2]: /img/vaccine.png

[3]: /img/statedeathrate.png

[4]: /img/avgcovidmedicaid.png

[5]: /img/propormedicaid.png

[6]: /img/crudedeath.png
