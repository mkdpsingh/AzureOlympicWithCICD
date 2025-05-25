# AzureOlympicWithCICD

When we read param.json file in lookup at that time we need to make sure that in setting we need to uncheck "**First row only**".

When we get error while loading like to many columns then we can go to settings of for each and there we can select fault tolerence and select "**Skip imcomplatible rows**". This column & rows data we can get in different folder to see which all were rejected.

**Note** - 
1. We need to cover the part when same file name data came and we want to keep both data whether it is duplicate or same.
**In general case with same file name it will overwrite/replace the data.**
