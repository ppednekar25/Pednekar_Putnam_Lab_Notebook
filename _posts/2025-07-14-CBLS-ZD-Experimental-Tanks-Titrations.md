---
layout: post
title: 2025-07-14 ZD Timeseries Titrations
date:  2025-07-14 
categories: Titrator, Timeseries
tags: [ZD Timeseries, Titrator, Putnam Lab]
---

## [Zoe Dellaert](https://github.com/zdellaert) Timeseries Experiment Titrations

Protocol Link from [Personal Notebook](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/a25ca69ccb2a655e29c2e72d019f6d1b3b9e4dfb/_posts/Pednekar_Titrator_Protocol.md) and 
from [Putnam Lab](https://github.com/Putnam-Lab/Lab_Management/blob/a2e8ca8af2fe28021882a41421b8f2d9ad22d650/Lab_Resources/Equipment_Protocols/Titrator_Protocols/Titrator_Protocol.md)

### Titrations of total 9 samples from ZD Timeseries Experimental Tanks along with 1 Junk and 3 CRMs from Batch #180.

|Date | Sample ID |	Weight (in g) |Salinity (in psu) |	Tank Type | Notes |
|-------|---------|------------------|-----------|---------|-----------|
|20250714 | MT 1 | 59.621 | 34.86 | Mixing Tank | Collected by JA & ZD|
|20250714| MT 2 |60.321|  34.86 | Mixing Tank | Collected by JA & ZD |
|20250714| MT 3 | 60.03 | 34.86 | Mixing Tank | Collected by JA & ZD |
|20250714 | T1 | 59.980 | 35.00 | Tank 1 | Collected by JA & ZD|
|20250714 | T2 | 60.338 | 35.11 | Tank 2 | Collected by JA & ZD|
|20250714 | T3 | 59.881 | 35.08 | Tank 3 | Collected by JA & ZD|
|20250714 | T4 | 59.451 | 35.03 | Tank 4 | Collected by JA & ZD|
|20250714 | T5 | 59.812| 35.11 | Tank 5  | Collected by JA & ZD|
|20250714 | T6 | 59.779 | 35.04 | Tank 6 | Collected by JA & ZD|

<font color="red">Note: Before starting the titrations there were some changes that were made.</font>


 The CRM accuracy checks on [2025-07-11](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/cf477348aa627c0dbf43cca241572c86ceaaac74/_posts/2025-07-11-CRM-Accuracy-Checks-for-Titrator.md) depicted that the CRMs were off by 2-3%. Previously, calibrating the pH probe showed no abnormalities*. 

*In order to account for that, Hollie Putnam decided to change the acid titrant batch#22 previously in use,  as it was very low in quantity, which she suspects could lead to possible contamination and evaporation, as we are pouring the purged acid back hence degrading the concentration of HCl in a small quantity resulting in CRMs being off.*

**<font color="purple">The new acid titrant Batch #A14 was opened and was used to carry out the titrations today.</font> In addition to that, changes were made in the script to calculate the CRMs TA output, based on the batch of the acid titrant. The information about the same is avaliable [here](https://github.com/Putnam-Lab/Lab_Management/blob/2d31a6549863f430668dfdfe1722d9385107df1b/images/calculation%20example%20for%20titrator.jpg).**

*pH Calibration*
- Following are the pH calibration values from today and the previous titration trails of Putnam Lab: 

 |Date | ZeroPoint|	Slope |	pH4 | pH7 |	pH10 |	Temp |	Status |	Notes |
 |-----------|---------------|------------|------|------|---|---------|------|--------|
 |20250714|	7.021	|-56.5 |	171.0	| -0.6	| -171.7 |	19.6 |	<font color="green"> OK</font> |	20250714_PP |

 
- The plot for this pH calibration is below:
![](https://github.com/ppednekar25/Pednekar_Putnam_Lab_Notebook/blob/1ae2e5a71df54673ce989001a79b68b4d5537349/images/2025-07-14pHmvplot.png)


*CRM titration*

Below are the resulted 3 CRM values from titrations along with the junk.
  
 |Date | CRM value        |	Batch value         	| % off      |	Batch #   	|   Status |    Notes |
|-----------|-------------|--------------|------------|--------|----------|--------------|
 |20250714| 2216.0944 | 2224.47 |  	-0.376 |	180     	| <font color="green"> OK</font>| CRM180_opened20250502_SS |
 |20250714 | 2216.949 |	2224.47 |	  -0.338 |	180	     | <font color="green"> OK</font>| CRM180_opened20250502_SS |
 |20250714 | 2220.393 |	2224.47 |	  -0.183 |	180     |	<font color="green"> OK</font>| CRM180_opened20250714_PP |
 


*Sample Titrations*

-Below are the results from sample titrations that includes 9 samples.

|Date | Sample ID                   | TA | Mass | Salinity | Status | Notes|
|-----------|---------------------------|------------|------------|--------------|-------|----|
| 20250714  | MT 1	|  2437.39  | 59.621  |   35.86 | <font color="maroon"> NOT OK </font> ||
| 20250714 | MT 2  |  2001.328   |   60.321  | 35.86  | <font color="green"> OK</font> ||
| 20250714 | MT 3  | 2311.705  | 60.030     |   35.86    |<font color="green"> OK</font>||
| 20250714 | T1  |   2342.135   | 59.98  |  35.00     |<font color="green"> OK</font>||
| 20250714 | T2 |  2338.999  | 60.338     |   35.11      |<font color="green"> OK</font>||
| 20250604 | T3 |   2311.705    | 59.881  |      35.08    |<font color="green"> OK</font>||
| 20250714 | T4  |   2330.225   | 59.451  |  35.03     |<font color="green"> OK</font>||
| 20250714 | T2 |  2360.789  | 59.812     |   35.11      |<font color="green"> OK</font>||
| 20250604 | T3 |   2327.480    | 59.799  |      35.04    |<font color="green"> OK</font>||



 Overall observations: The titrations went all well with the new acid titrant #A14. Only one sample from Mixing Tank (MT 1) showed NOT OKAY status. However, in this set of the titration, we didn't ran another Junk (like JUNK 2) like usual so might as well include that next time if we have sample size less than 9. Hence, the titration for MT 1 sample depicted it is not okay.

 The TA values for ZD tank came out to be good as the blue tank even without dosing them with any nutrients. 
