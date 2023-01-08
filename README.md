# Data Analysis and Visualization

In this project, a dataset is analyzed and findings are communicated. 

## Libraries
* `NumPy`
* `pandas`
* `Matplotlib`

## Data
This [dataset](https://www.google.com/url?q=https%3A%2F%2Fd17h27t6h515a5.cloudfront.net%2Ftopher%2F2017%2FOctober%2F59dd2e9a_noshowappointments-kagglev2-may-2016%2Fnoshowappointments-kagglev2-may-2016.csv&sa=D&source=docs) collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. <br>
The dataset is analyzed and visualized using `pandas`, `numpy` and `matplotlib`.

* The data had 110,527 rows and 14 columns
* There were no null values

## Analyze Data
The following questions inspired the data analysis and wrangling:

1. Are appointments for patients who are not enrolled in the Brazilian Welfare program generally fulfilled?
2. Are appointments of patients that get SMS reminders generally fulfilled?
3. For the location with the highest no_shows, how many of them were female?

The [notebook](https://github.com/cyrilakafia/noshow-analysis/blob/main/eda.ipynb) details all wrangling steps.
These questions were addressed and answered in the `Exploratory Data Analysis` section

## Communicate Findings
A [report](https://github.com/cyrilakafia/noshow-analysis/blob/main/report.html) (a html copy of the notebook) is created to share the findings that were the most interesting.

All [references](https://github.com/cyrilakafia/noshow-analysis/blob/main/references.txt) were acknowledged
