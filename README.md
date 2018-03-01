# Photovoltaics
Impact of Photovoltaic Array Configurations on Household Electricity Usage Using Recorded Load Data

Photovoltaic integration is required to replace power plants like coal and natural gas. To be able to effectively utilize the potential of solar energy in residential areas, analysis on the peak loads, change in energy consumption and the cost of photovoltaic cells must be taken into consideration. This project will enable the studies of parameters mentioned above and how to implement solar in a cost effective way. For this multiple solar cell configurations will be taken and the generation of electricity is matched with the energy usage as well as peak loads and the utility bill reduction will be observed.

Markup :  - - - -

Input parameter for Load_All_Files_FC: <Load_Profile_Directory, Weather_Data, Validation>  
Load_Profile_Directory: Windows directory where Advanced metering infrastructure (AMI) meter recordings are present.   
* Sample: "U:\MATLAB\FC Data\"  
* Required files in the directory:  
* Sample load file names inside location: "AMIReadings_*.csv"  
* Premise IDs file name  
  Loads Format: <premiseID, timestamp, delivered, received>  
where  
  premiseID = Unique ID of a place where  meter is installed for measuring electricity consumption (can be a residential, commercial, industrial load)  
  timestamp = Unix formatted Timestamp. Sample: "1448928000" is "Tue 01 Dec 2015 12:00:00 AM UTC"  
  delivered = Power consumed in kW  
  received = Power generated in kW  
