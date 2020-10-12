# ShippingLab_WP1_2_Jie
Codes are developed by Dr. Jie Cai for ShippingLab_WP1_2

Code 1: "journeyClean_portsInfo.ipynb"

Clean journey and remove duplicates
This code is used to extract the "portsInfo_new.csv" information from "fleet_trade_journeys.csv"; Duplicate terminals are defined as terminals with the same names but in different countries. There are 38 duplicated entries in the dataset "PortList.xlsx" from Gang, which needs to be improved; The original dataset is "fleet_trade_journeys.csv";

Code 2: "journeyClean_portsInfo.ipynb"

Display, group terminals,assign common port, and add extra features.
This code is used to group terminals by given radius (e.g., 100 nm), and to add extra features "Main_port" and "Region". The working dataset in this sheet is "PortList.csv";
