# Analysis of Crime in Washington DC
Repository for analysis on Washington DC crime data analysis.


### Team Members: 

Irais Garcia, Omar Haddad, Lolita Dias , Nithin Sunil

### Understanding the trends and patterns in crime rates and to identify the most dangerous areas of D.C
Finding crime patterns and trends in DC by area to provide better information for law enforcement and civilians

## Questions:
1. Where is crime concentrated in D.C? 
2. When were crimes most likely to occur?
3. What were the most common crimes in D.C? 
4. Which type of crime is prominent in each area? 

## Datasets Used: 
 1. https://opendata.dc.gov/datasets/crime-incidents-in-2019?orderBy=REPORT_DAT
 2. https://edscape.dc.gov/page/neighborhood-factors-crime-and-safety
 3. https://www.arcgis.com/sharing/rest/content/items/fdacfbdda7654e06a161352247d3a2f0

## Breakdown of Tasks:

1. Get dataset from sources.
2. Cleaned data.
3. Breakdown and analyze the dataset.
4. Get crime rate for each street, ward, police service area (PSA), district, and neighborhood cluster.  
5. Find change in crime rates over time. 
7. Graph using matplotlib and plotly.
8. Make conclusions.


# Questions - Answered

#### 1. Where is crime concentrated in D.C? 

<img src="Images/density.png">
<img src="Images/crimes_district.png">
<img src="Images/crimes_ward.png">


* Central D.C had the most reported crime in our dataset
* Surprisingly, there was little correlation between crime reported in an area and homicides
* Very high correlation between gun violence and homicide

#### 2. When was crime most likely to take place?
<img src="Images/crimes_day.png">
<img src="Images/crimes_month.png">
<img src="Images/gun_crimes_month.png">
<img src="Images/hom_crimes_month.png">
<img src="Images/crimes_month.png">


* Crimes are more likely to take place during the weekends than weekdays
* Reported crimes peak in August, while homicides and gun crimes peak in January
* Crime is likely underreported in areas with high homicide rates

#### 3. What were the most common crimes?

<img src="/Images/type_crimes.png">
<img src="/Images/type_crimes_number.png" width= 800>

* The most common crimes were thefts. Thefts cumulatively made up 84.43% of all crimes in D.C 
* Homicides comprised only 0.34% of all crime
* Assault with a dangerous weapon was the most common violent crime
* Arsons were the least common crimes

#### 4. Trends in crime incidents over time

<img src="/Images/trend_homicide.png">
<img src="/Images/trend_assault.png">
<img src="/Images/trend_abuse.png">
<img src="/Images/trend_robbery.png">
<img src="/Images/trend_theft_other.png">
<img src="/Images/trend_arson.png">




* Almost all types of crimes experienced growth in the number of incidents over 2009-2019 
* This is likely due to increases in population growth over the period
* Arson incidents fell dramatically over the period to near zero incidents per year.

## Conclusions

Based on the data we have found: 
* There is no visible relationship between the crime and the median home cost, making it difficult to track neighborhood desirability based solely on property value changes. Despite gentrification in some areas such as  78702--with property values rising to over $200,000 in 2016--the amount of crime in that area remains roughly unchanged since 2016, with 629,616 crime reports filed in 2018.
* To avoid crime the best place to live would be away from Downtown Austin because the most crime concentration is in Downtown.
* While population and median home cost in Austin increased between 2011 and 2016 the crime rate decreased across most of the Austin zip codes.
* Population is not a good indicator of crime because many crimes are committed in commercial areas where not as many people live. 
* More investigation needed to determine what might affect the crime rate.

## Disclaimer 
This is not real safety & security advice, it is only based on the data and the results analyzed from the Austin crime data sample from 2011 - 2016.