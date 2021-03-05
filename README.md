# Establishing Live PowerBI with Excel on Sharepoint 
<img align="right" src="https://user-images.githubusercontent.com/62319355/110085335-efcdb100-7dcb-11eb-9e9b-77f2849154a8.png" width="220" height="80" alt="Excel logo">
:smile: :grinning: :sleepy: :relieved: :confused: :open_mouth: :astonished: :thumbsup:



```
Creator: Ray Kim Dong Hyun
Contact: rainmankim@gmail.com

```



```
In this repository, I am going to show you how to connect PowerBi to Excel file on Sharepoint in your organization.
I will illustrate this in the following steps.
(1) Upload an excel file on SharePoint
(2) Copy Path URL Link form excel "Info" tab of excel sheet
(3)	Open PowerBI, select connect to data via Web
	  Paste Path URL in Web box, be sure to remove any tailing characters beyond .xlsx extension
(4) Upon connection set up, sign in using organizational account
(5) Create Report, and publish to PowerBI Web
(6) Open PowerBI Web and select Database related to Dashboard and enter the Database's settings
	  Update user credentials for access to Web using OAuth2 and sign in using org.
	  Update scheduling refresh per requirement and save

```

### Option 1 Directly JOIN  Main HR Data Extract on Ray's Tableau Server  &  Offline Excel File
---> This is simply not allowed. You cannot join with a data table in Ray's Tableau SErver.

### Option 2 Directly blend Offline Excel File with HR Data Extract on Ray's Tableau Server
#### --> Connect to HR Data Extract on Ray's Tableau Server.    And  also connect to offline Excel file as a "NEW Data source"   
<img align="center" src="https://user-images.githubusercontent.com/62319355/106698186-456f3c00-661b-11eb-972d-10505f849150.png" alt="tableau_cloudera_connection image">

#### --> Next, go to "Edit Data Relationships" option as shown below                       
<img align="center" src="https://user-images.githubusercontent.com/62319355/106705361-c54fd300-6628-11eb-9bb3-1b7346f7e9a7.png" alt="tableau_cloudera_connection image">

#### --> Using custom matching, match necessary primary key(s)
<img align="center" src="https://user-images.githubusercontent.com/62319355/106706466-b5d18980-662a-11eb-81e0-e25e1a92ec05.png" alt="data blend">







🎈🦾 😎 That's it from me. 
--------------------------------------------------------------------------------------------------------------------------------------------------
