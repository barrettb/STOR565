# STOR 565 Project 

**Full Paper can be found in the .docx file above**

In this project, we wanted to discover trends within grocery store density that could help
us predict health outcomes as well as outline areas that could benefit from access to
healthy foods. Specifically, the noticeable disparities in health outcomes that occur in food
deserts, which we define as areas with low access to healthy foods. To do so, we employed
machine learning techniques such as linear models, extreme gradient boosting, random
forests, and tree-based methods to find a model with a root mean squared error of
0.001782068 on the testing dataset.


We explored data from the National Neighborhood Data Archive (NaNDA): Grocery Stores
by County 2003-2017, created by the Social Science department at the University of
Michigan. It includes counts of grocery, specialty, and warehouse stores, as well as number
of residents and land ratios of each census tract which is a kilometer shaped block.
Speciality stores can be defined as stores such as meat, seafood, and produce markets as
well as bakeries or spice stores. Warehouse stores can be defined as “buy-in-bulk” stores
such as Costco or Sam’s Club. To this dataset, we joined data from the Institute for Health
Metrics and Evaluation which has information regarding mortality rates by causes of death
in America by county using the county FIPS codes. In order to join the kilometer block level
FIPS codes to county mortality rate we concentrated our analysis to the county level to
correct this. We found that 53.35% of variability when we graphed our predicted values of
overall mortality rate based on grocery store data and we compared it to the actual values.
This shows that there are significant health disparities in areas without access to grocery
stores. With that said, these differences exist, but several other factors should be
considered.
