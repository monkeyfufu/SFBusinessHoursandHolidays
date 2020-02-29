# BusHoursMapToHolidays
This is the Raven Holiday Mapping to Business Hours
In reality, it is a scary XML file.

The Business Hours (BH) come first and then the Holidays

The Holidays, if mapped to BH will start with <holidays> and then have <businessHours>BushHoursName</businessHours>


DO NOT LOAD A SUBSET OF YOUR BUSINESS HOURS!!!!  
Loading this file overwrites the current holidays and business hours.  It does not upsert.  

To pull your org Holidays, Open VS Code and Retrieve the package (or you can use workbench.)
Then add the holidays at the end and get the business hours added as seen in the very long code here!

