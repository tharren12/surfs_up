# Surf Shop Analysis

## Overview of Project

The intent of this project was to study temperature trends before opening a surf shop in Oahu. There was two months of the year that were utilized for the study - June and December. The patterns in these two months was studied in order to determine if the surf and ice cream shop business is sustainable year-round.

## Resources

* Software: Python 3.6.8, Jupyter Notebook 6.0.0, Pandas Library 0.24.2, SQLAlchemy

## Results of Temperature Analysis


### June vs. December Temperature Patterns

June Temperature (2010-16) |  December Temperature (2010-16)
:-------------------------:|:-------------------------:
<img src="https://user-images.githubusercontent.com/92001105/147511494-d9e41482-0e3b-474a-affd-a67cd473acb2.png" width="300%"></img>   | <img src="https://user-images.githubusercontent.com/92001105/147511504-f50857aa-6d66-42f2-8868-f0b593a9302a.png" width="100%"></img> 


![June_temp_description](https://user-images.githubusercontent.com/92001105/147511494-d9e41482-0e3b-474a-affd-a67cd473acb2.png)


![Dec_temp_description](https://user-images.githubusercontent.com/92001105/147511504-f50857aa-6d66-42f2-8868-f0b593a9302a.png)

* Overall there are 300K  employees with 90K or 30% at retirement age
* The job titles with the most number of employees nearing retirement are Senior Engineers (29K) and Senior Staff (28K)
* Most job titles have close to 30% of employees nearing retirement, with only Managers being lower at 22%, however small sample size


### Mentorship Eligible Employees


![image](https://user-images.githubusercontent.com/92001105/145740588-31c1ddc4-100f-4fb2-8b7f-ae0a1d5b1a6e.png)


* Very concerning that the mentorship eligible population only covers 1.7% of the number of employees close to retiring
* The highest percentage of mentorship eligible employees of retiring age are Assistant Engineers with 3.4% and the lowest number is Managers with no employees eligible for the mentorship program


## Pewlett Hackard Summary

Through the analysis it was determined that 30% of employees are close to retirement, which will be a very significant impact to the business over the coming years. The business will to identify additional employees for upward mobility or need to bring a large number of external new hires to address this labour shortage.

Out of the 90K retiring employees there are only 1.5K that have been identified as Mentorship Eligible. This criteria needs to be expanded and also potentially beyond age criteria and look to mentor currently Assistant Engineers to become Senior Engineers. 

It was identified through an additonal query of the date range if expanding the criteria for mentorship eligibility and including employees born in 1964 or 1963 would include 18K for each additional year and would therefore account for closer to 42% of employees that could be retiring shortly.

Another way to refine target list is to deprioritize employees that have only been hired recently out of the employees nearing retirement based on birth date only. Potentially a number of these employees will not actually be retiring if they have only recently been hired. As detailed in the below table there are 11.5% or 8.3K employees that are in the most recent 5 years of hiring and these could be deprioritized in terms of replacing.

![image](https://user-images.githubusercontent.com/92001105/145698190-2c4e57f5-9034-4eb3-83d7-f28abf5bb453.png)

