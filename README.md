# Azure_End_to_End_Data_Engineering_Project
#Projectvideo_And_PPT:https://drive.google.com/drive/folders/1EnBu3FVFj7i0rWhaQEEyL9-vZN02Cxjj?usp=drive_link

I have created Azure_End_to_End_Data_Engineering_Project where I have connected my on-premise SQL server DB on Azure Cloud  

There I have used Azure Data Factory service to build connection of on-premise SQL server DB to Azure Cloud

After the connection is successfully done, on-premise SQL server DB is stored into Azure Data Storage service

Under Azure Data Storage, I used Data house technique in which 3 layers are used to storing the data

First Layer is Bronze layer, under bronze layer I have stored exact on-premise SQL server DB with the help of Data bricks services...advantage of this layer is if we go wrong in any futher steps we can come back to Bronze layer and start over

Hence,Data Bricks is a service where we can use notebooks to write a code in any language, here I have used python  

For data Transformation I have used 2 testcases on on-premise SQL server DB, First case is I have column name date which is in the format of date as well as time....I will transform that column into only date format and store it into Data storage under silver layer

Second case is I have columns name with two words lets say...Addressid, so I will seperate them with underscore e.g. Address_id and store it into Data storage under gold layer

Hence, those testcases transformation is done with the help of Data bricks service 

Now these transformed data is final data and these data is stored into Azure Synapsis service

And our cleanest form of data is now into Azure Synapsis and now we can make report out of our project.

To make a report I have connected Azure Synapsis to PowerBI and created report of our data





