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
