# powerbi_sharepoint_excel
<img align="right" src="https://user-images.githubusercontent.com/62319355/110085335-efcdb100-7dcb-11eb-9e9b-77f2849154a8.png" width="220" height="80" alt="Excel logo">
:smile: :grinning: :sleepy: :relieved: :confused: :open_mouth: :astonished: :thumbsup:




### tableau_server_and_offline_excel_file_connection


```
Creator: Ray Kim Dong Hyun
Contact: rainmankim@gmail.com

```



```
In this repository, I am going to show you how to connect PowerBi 


Suppose you have main data source extract on Ray's Tableau Server which contains HR details about your colleagues.
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


### Option 3 First publish offline Excel File onto Ray's Tableau Server.   Then, blend main HR Data Extract on Ray's Tableau Server  & Alien Data on Ray's Tableau Server
#### --> First connect to offline Excel File and publish data onto Ray's Tableau Server. 
<img align="center" src="https://user-images.githubusercontent.com/62319355/106709772-f384e100-662f-11eb-86fe-ff3da276fe68.png" alt="publish sample excel">

#### Open a new workbook. Connect with both Main Data and newly published data. 
#### --> Using custom matching, match necessary primary key(s). This time you notice both connections are on Ray's Tableau Server
<img align="center" src="https://user-images.githubusercontent.com/62319355/106712541-10231800-6634-11eb-842f-b9ff7665699f.png" alt="data blend">




### Option 4  First publish offline Excel File onto Ray's Tableau Server.   Then, join HR Data Extract on Ray's Tableau Server  & Alien Data on Ray's Tableau Server
#### --> This option is simply not allowed.





🎈🦾 😎 That's it from me. Let us never alienate anybody!
--------------------------------------------------------------------------------------------------------------------------------------------------



## Credits
```
- Credits: Mohammed Shameel  (insanely smart and resourceful)
- Secular saints of Tableau Community
```

