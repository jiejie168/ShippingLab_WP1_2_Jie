# ShippingLab_WP1_2_Jie
Codes are developed by Dr. Jie Cai for ShippingLab_WP1_2

Code 1: "journeyClean_portsInfo.ipynb"

Clean journey and remove duplicates
This code is used to extract the "portsInfo_new.csv" information from "fleet_trade_journeys.csv"; Duplicate terminals are defined as terminals with the same names but in different countries. There are 38 duplicated entries in the dataset "PortList.xlsx" from Gang, which needs to be improved; The original dataset is "fleet_trade_journeys.csv";

Code 2: "journeyClean_portsInfo.ipynb"

Display, group terminals,assign common port, and add extra features.
This code is used to group terminals by given radius (e.g., 100 nm), and to add extra features "Main_port" and "Region". The working dataset in this sheet is "PortList.csv";

Code 3: "update1_groupTerminals.ipynb"

Update the port file "portsInfo_new.csv" in terms of the feature "Port Group". A more refined terminals grouping is obtained

Code 4: "weather_ais_input.ipynb"

the original ais data file to inquire the weather ais data is too large in size. 
This code is used to reduce the data file size by factors such as journey distance (e.g., longer than 3000nm), journey in open seas, and journey not in the same contry. 

Code 5: extract routes between specific regions.
Filter all the specific routes between differnet regions, ready for the next step in waypoints extracting. 

Code 6: data cleaning for the hourly ais dataset

Code 7: extract routes between specific regions from hourly ais data

Code 8: A visulization of routes btw regions - daily based

Code 9:load and present regions between regions, hourly based

Code 10:identify region waypoints based on DBSCAN, hourly based data
