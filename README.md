aemo
====

Datasets related to the Australian Energy Market Operator 


Sources
-------

Contains the original data files:
- AEMO main spreadsheet
20130405_Registration_and_Exemption_List.xls
From http://www.aemo.com.au/~/media/Files/Other/registration/20130405_Registration_and_Exemption_List.ashx 
Retrieved on April 26th, 2013

Out
---

Contains the data files that have been processed for use by other processes:
- generators.csv
Export of the AEMO main spreadsheet of generators and scheduled loads (Open in Excel > Save as CSV)
Clean up the last few lines that do not contain generator information
- co2.csv (TODO)
List of DUID and associated CO2 emission factors
- geo.csv (TODO)
List of DUID and associated latitude / longitude