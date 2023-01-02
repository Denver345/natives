---
ns: VEHICLE
aliases: ["_SET_VEHICLE_ENGINE_POWER_MULTIPLIER"]
---
## MODIFY_VEHICLE_TOP_SPEED

```c
// 0x93A3996368C94158 0xE943B09C
void MODIFY_VEHICLE_TOP_SPEED(Vehicle vehicle, float value);
```

## Parameters
* **vehicle**: 
* **value**: 

## Return value
Returns a multiplier on the vehicles power, this appears to be percent based so if a vehicle goes 100mph with a modifier of 10 the vehicle will go 110 (this is subject to change with vehicle weight and areo)
