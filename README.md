# sase-hack-2017

This repository is for storing cleaned datasets for use at SASE Hackathon 2017.

- [Further Topics](#topics-for-further-description--explanation)
- [Dataset Categories](#dataset-categories)
- [Datasets](#datasets)
	+ [Sleep-Related Datasets](#sleep-related-datasets)
	+ [Nutrition, Physical Activity, and Obesity](#nutrition-physical-activity-and-obesity)
	+ [Youth-Focus](#youth-focus)

## Topics for further description / explanation
```
* FIPS vs. County/ZIP.
* Geographic data munging/visualization gists in R/Python.
```

## Dataset Categories
```
Based on Army's Performance Triad:
1. Sleep
* Include data on sleep time, energy level.
2. Activity
* Include exercise, physical education, physical facility data.
3. Nutrition
* Include restaurant, fast food data.
* Include obesity data.
* Include diabetes, cholesterol, related ailment data.
``` 

## Datasets

***Missing Datasets***
```
* Adult physical facility data.
* College data.
* More detailed restaurant / fast food data per county/BIPS.
* Other related topics / factors.
```

### Sleep-Related Datasets
*CDC's National Health and Nutrition Examination Survey (2013-14)* - This data focuses on sleep disorders and includes a questionnaire on sleep habits and disorders.
* [Data Documentation](https://wwwn.cdc.gov/Nchs/Nhanes/2013-2014/SLQ_H.htm)
* [Data](https://wwwn.cdc.gov/Nchs/Nhanes/Search/DataPage.aspx?Component=Questionnaire&CycleBeginYear=2013)
```
Data is formatted in a SAS collection. Need method to move from XPT format to more universal format.
```
*Bureau of Labor Statistics's American Time Use Survey (2003-16)* - This data surveys down to BIPS and includes amount of time people spend doing activities. Data on over 10,000 households. Survey conducted annually.
* [Data Documentation](https://www.bls.gov/tus/)
* [Data](https://www.bls.gov/tus/#data)
```
Data may be different over the years. Will have to work to merge datasets.
```

### Nutrition, Physical Activity, and Obesity
*Behavioral Risk Factor Surveillance System (2011-2014)* - This dataset includes data on adult's diet, physical activity, and weight status from Behavioral Risk Factor Surveillance System.
* [Data Documentation](https://www.cdc.gov/brfss/data_documentation/index.htm)
* [Data](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-behavioral-risk-factor-surveillance-system)
```
Data is organized a bit weird in csv. May need to flatten. More current data may be available on CDC/BRFSS Webpage.
```

*Youth Risk Behavior Surveillance System (1993-2017)* - This dataset includes data on youth's diet, physical activity, drug, and behavior data. Data is provided every 2 years.
* [Data/Documentation](https://www.cdc.gov/healthyyouth/data/yrbs/data.htm)
```
Similar changes to above.
```

*Diabetes, Obesity, & Leisure-Time/Physical Inactivity Prevalence (2004-2013)* -
This dataset includes data from 2004-2013 for county-level diabetes, obesity, and leisure-time/physical inactivity prevalence.
* [Data/Documentation](https://www.cdc.gov/diabetes/data/countydata/countydataindicators.html)
```
All state data is listed in an odd fashion with merged rows.
```

*USDA Food Environment Atlas (v. years from 2000-2012)* -
This dataset includes a number of features regarding Food Environment, such as store/restaurant availability, SNAP Program, National School Lunch Program (NSLP), School Breakfast Program (SBP), Summer Food Service Program (SFSP), Child and Adult Care Food Program (CACFP), and the WIC Program. Also includes obesity and recreation/fitness facilities.
* [Data/Documentation](https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads/)
```
Multi-tab Excel format may be displeasing to some. May want to flatten.
```

### Youth-Focus
*National Survey of Children's Health (2003,2007,2011-12)* -
This dataset includes survey information for physical and emotional health of children ages 0-17. Special focus is made on the child's well-being, which includes family, home environment, school, and neighborhood. Completed over 95,000 child interviews.
* [Data/Documentation](https://www.cdc.gov/nchs/slaits/nsch.htm)
```
Data formatted in SAS. Need to move to more universal format.
```
*American College Health Association National College Health Assessment (2000-2015)* -
This dataset includes demographic and aggregated information on health of college students. Data is given in PDF or HTML format. Seek alternative.
* [Data](http://www.acha-ncha.org/pubs_rpts.html)
```
Data is in PDF form and appears to be an aggregate level.
```