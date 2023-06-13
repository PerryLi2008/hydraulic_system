# **Hydraulic System Analysis Dashboard**

The dashboard is part of efforts of Manufacturing Hydraulic System Analysis.
It allows EnergyMobile management to understand more insights of manufacturing Oil Rig process.

Tableau is used to create dashboards for this purpose. Combined dataset "HydraulicData.csv" of sensor data is generated by Data Prep python program and imported into Tableau, and join with profile.txt of component values.

Dashboards are organized into Story and can be accessed through link:
[*Hydraulic System Analysis Dashboard on tableau public*](https://public.tableau.com/views/HydraulicSystemAnalysis/HydraulicSystemAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link).


## **Dashboard 1: System conditions**
 <img src="../images/Dashboard - Hydraulic System Conditions.png" alt="System conditions" width="600" />

The dashboard display all component values in pie charts. We can tell that overall system is in stable condition 65.7% of time.  
User can select date range to see system conditions with more details in any given period of time.  
Tooltips will explain each condition when hovering over any pie chart.

## **Dashboard 2: Degradation analysis**
 <img src="../images/Dashboard - Hydraulic System Degradation Analysis.png" alt="Degradation analysis" width="600" />

 Dashboard is trying to analyze the relationship between Cooler condition and sensor data.  
 3 states of Cooler condition is display with different color. We can see clear correlate between sensor data and Cooler condition.  
 User can select date range to see sensor data with more details in any given period of time.  
 Tooltips will explain each sensor when hovering over any chart.