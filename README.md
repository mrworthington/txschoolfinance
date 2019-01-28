# txschoolfinance - A Texas School Finance 
This is a repo dedicated to creating an R package containing over 20 years worth of actual revenues + expenditures for all Texas public schools. Right now, it only contains the raw data of the data related to this package. Over time, it will be developed into a more usable R package for the purposes of data analysis now and in the years to come.

## What is this data? 

The data found here comes from the [PEIMS Financial Standard Reports](https://tea.texas.gov/financialstandardreports/) published by the Texas Education Agency. It contains actual financial data for each school district between 1992 and 2016, including all public charter schools and military ISDs along side all public ISDs.

Traditionally, PEIMS data is made available by TEA by individual school district or charter school, per year or by a statewide summary report, per year. An example of that format using Austin ISD for the 2015-2016 school year is [provided here](https://rptsvr1.tea.texas.gov/cgi/sas/broker?_service=marykay&_program=sfadhoc.actual_report_2016.sas&_service=appserv&_debug=0&who_box=&who_list=227901). 

To learn more about the PEIMS Actual Financial Data contained here, please visit TEA's website and download a copy of one of their ["About Actual Finances"](https://rptsvr1.tea.texas.gov/school.finance/forecasting/financial_reports/AbtAct16.doc) documents. The sample provided here comes from the 2016 dataset, which is the latest dataset provided in this repo.

## How was this data collected?

In the summer of 2017, I organized all of TEA's Annual Snapshots into a single file and reached out to the Texas Education Agency about concerns related to the financial data reported in the Annual Snapshots, given discrepancies between what was published in the Annual Snapshots & what was published in the US Census' [Annual Survey of School System] Finances(https://www.census.gov/programs-surveys/school-finances.html). The person in charge of financial reporting confirmed that some of the financial information published in TEA's Annual Snapshots were incorrect and recommended that I submit a public information request to obtain accurate records.

This data is the result of that Public Information Request. 
