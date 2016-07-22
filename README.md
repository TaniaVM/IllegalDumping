# IllegalDumping
Illegal Dumping Model, Logistic Regression
a. Overview
i. Description - Why does the project exist?
CUSP is collaborating with the Office of the Attorney General of New York State (OAG), 
using various New York City data sources and analytic modelling techniques to identify 
posible sites where illegal dumping could happen.  Illegal dumping is defined as the 
improper disposal of waste according to federal, state, and city regulations.  Currently,
the OAG is alerted of illegal dumping through citizen and agency reports of individuals
either creating waste illegally (e.g. illegal construction projects) or improperly disposing 
of waste, with no leads back to the original source of the waste.  The investigations are 
looked at on a case-by-case basis, and in a reactive manner. Through modelling and data mining, 
CUSP was able to find and predict instances of illegal construction, as well as identify likely 
dumping locations within New York City.  CUSP was also able to highlight and document the 
limitations of data available for use in future research as we tried to model the entire illegal
dumping process and link the source(s) of construction waste with the act(s) of illegal dumping. 

ii. Purpose - What is the code for?
This code include a logistic regression model which make a prediction over the past locations 
where illegal dumping happened based on specific characteristics.

iii. Components
Notebook with logistic Regression Model.
Data for running the model.

iv. System or software requirements.
The neccesary imports are specified inside the notebook.

v. Version
Python 2.7
b. Files
For running this notebook the file to use is named :
fish_ECB_311_lights_2014log.csv
i. List of all files / derived datasets, including: filename; file format; classification
(confidentiality); created date; last updated; update frequency; and version.
fish_ECB_311_lights_2014log
format: csv
Green data Set
Created date July 10, 2016.
Last updated July 22, 2016.
update frequency: For running this model, the attributes were taken from 2014 to 2016. 

ii. Provide any directions useful on how files are set up.
c. Process
This notebook runs with the file provided in this folder.
i. At a high level, how does a project run from start to finish?
d. Installation/Configuration (if applicable)
i. Include any programs, software, or code needed to install and run code
