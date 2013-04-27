aemo
====

Datasets related to the Australian Energy Market Operator 


Sources
-------

Contains the original data files:
- AEMO main spreadsheet
Latest revision is:
20130405_Registration_and_Exemption_List.xls
Downloaded from: http://www.aemo.com.au/~/media/Files/Other/registration/20130405_Registration_and_Exemption_List.ashx 
Retrieved on April 26th, 2013

- ACIL Tasman PDF document "Fuel resource, new entry and generation costs in the NEM"
Latest revision is:
419-0035 pdf.pdf
Downloaded from: http://www.aemo.com.au/~/media/Files/Other/planning/419-0035%20pdf.pdf
Retrieved on April 26th, 2013


Out
---

Contains the data files that have been processed for use by other processes:
- generator.csv
Processing steps:
Sort the spreadsheet by DUID, Station Name and Region
Export of the AEMO main spreadsheet of generators and scheduled loads (Open in OpenOffice > Save as CSV)
Clean up the last few lines that do not contain generator information

- co2.csv
Processing steps:
Manual reconciliation of DUID and emission factors, as described in the ACIL Tasman PDF document
Wind and hydro project CO2 emission factor is manually set to 0
Unknown emission factors are left blank

- geo.csv (TODO)
List of DUID and associated latitude / longitude