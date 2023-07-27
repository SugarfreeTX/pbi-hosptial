# pbi-hosptial
Time series of enrollment counts for studies. 

One of the data sources is a SharePoint drive. I had to connect using '= SharePoint.Contents("https://bswhealth.sharepoint.com/sites/BSWH-TIOB/", [ApiVersion = 15])' instead of the Get Data using SharePoint connector in PBI. 

I cleaned the CSV files using Python and Pandas library. 
