# How it works

VIPER is a solution which extracts the data from various sources namely email/ftp and transforms the data in the correct and valid format, validates the data according to the business process requirement and then sends the data to its designated destination and this process information is also available through dashboard with all the details. 

![alt text](_media\Workflow.png "Title")

Workflow:

1. Fortegra receives reports and data files from their partners (MGU) in different formats via emails/ftp location. RPA/Bot monitor emails/ftp folder 24/7 so that no data is missed as the data is received from various MGUs. 

2. The first step of the solution is to extract the file from the location and pick it up for processing.

3. The data is then transformed based on the transformation mapping defined in VIPER by the business user according to the business process requirement. The process changes the source data to the target system accepted format and loads the data in the system. 

4. Split functionality, formulae functions, read rules, tag functionality for classification are used by the software. 

5. Dashboards are created using Microsoft Power BI which includes every relevant detail of the file, for example how many files are successfully processed in a month, from whom, monthly trends, dollar value flowing through VIPER, etc. 

