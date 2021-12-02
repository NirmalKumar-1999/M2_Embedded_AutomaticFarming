# Requirements
##  Introduction
One of the Most Important Problems faced by the World is Scarcity of Water. We Require a System Which uses Water Limitedly Without Any Wastage.Irrigation Systems which are Smart Measures the Moisture of Plant in Order to Operate an Automatic Irrigation System and that Reduces the Use of Excess Water. Automatic Irrigation System will Concentrate on Watering the Field Regularly by Using Moisture Sensor Without any Human Monitoring.


## 4W's and 1'H

# Who
Easy to Access by the Gardeners,Farmers and Interested in Home Roof Gardeners.
# What
Implementation of Automatic Irrigation System.
# Where
It Can be Used In Roof Top Gardens and Parks Irrigation , Very Efficient For Wheat & Rice Fields.

# When
At Any Time it can be Used if Neccesary After Bulid the Circuit.
# How
 This Application is Implemented using C Embedded Programing language.
 
## SWOT ANALYSIS
# Strength

- Highly Sensitive, Low Cost and Reliable Circuit.

- Reducese of ManPower.

- Fully Automated Irrigation System Which Will Turn ON and OFF a Water Pump as Per the Level of Moisture in Soil.

- Highly Sensitive,Low Cost and Reliable Circuit.

- Can be Handle Heavy Loads.

# Weakness

- This is Applicable for Only Large Frames.

- Have limited life After Installation due to the Detoriation of the Plastic Component in a Hot, Climate when Exposed to Ultraviolet Light.

- The Rust, Foul and Deteriorate.

# Opportunities
- There are Huge Opportunities in the Local Market Since These Types of Automations are not yet Penetrated to the Villages and Rural Markets.

- Agriculture Still uses Conventional Methods for Many Cases So that a Huge Opportunities are Still Awaiting in Rural India.

# Thearts
- New Automatic Systems are to be Introduced to the Market Which may have Better Options.

- Cheap Complementary Products May Enter to the Market.

## High Level Requirements

| HLR_ID | 	Description | Status |
| ------ | ------ | ------ |
| HLR_1 |  The System is Automatically Monitored and Controls the Pump On and Off | IMPLEMENTED |
|  HLR_2 | Consumes a Small Amount Little Energy & Do Perfect On-Going Operations| IMPLEMENTED |

## Low Level Requirements

| LLR_ID |Description | Status |
| ------ | ------ | ------ |
| LLR_1 | Can't loaded More Than the System Specifications| IMPLEMENTED |
|LLR_2 | The System Can Operated in Night also which Results in Minimum Amount of the Water| IMPLEMENTED |	
|LLR_3 |Irrigation Process Starts and Stops When Needed Hence it Optimize Energy Requirements.| IMPLEMENTED |

| High Level Diagram | Low Level Diagram |
| ------------------ | ---------------- |
| ![beh1](https://user-images.githubusercontent.com/94284577/144244702-6e67dd84-6774-41f6-8085-a36290305c10.png) | ![beh2](https://user-images.githubusercontent.com/94284577/144244747-66e86594-00d3-465b-aedc-988879b62570.jpg) |

| High Level Diagram | Low Level Diagram |
| ------------------ | ---------------- |
| ![str1](https://user-images.githubusercontent.com/94284577/144245180-94a8565c-a7e0-46ed-8f23-4c329291ebe1.png) | ![str2](https://user-images.githubusercontent.com/94284577/144245192-79c365ba-cd1e-447e-b4a4-f0d112614875.png) |
# TEST PLAN

## High level test plan

| **Test ID** | **Description** | **Exp I/P** | **Exp O/P** | **Actual O/P** |**Status**  |    
|-------------|-----------------|------------|-------------|----------------|------------------|
| H_01 | Motor ON When Land is Dry | NA | Motor ON | LED ON | Pass    |
| H_02 | Motor OFF When Land Reaches Certain Water Level| NA | Motor OFF|LED OFF| Pass   |

## Low level test plan

| **Test ID** | **Description** | **Exp Input** | **Exp Output** | **Actual Output** |**Status**  |    
|-------------|-----------------|------------|-------------|----------------|------------------|
| L_01 | Water Flows When No Water Detected |  NA | Motor OFF | LED OFF |Pass |
| L_02 | Level of Water Varies Based on Land Humidity | NA | Varies Based on Land Humidity  | Varies Based on Land Humidity | Pass

#Output


![Automatic Irrigation](https://user-images.githubusercontent.com/94219350/144440952-00b79f08-ced3-49a2-81a7-b69c2b400837.png)


