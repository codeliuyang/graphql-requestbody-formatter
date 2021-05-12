## GraphQL RequestBody Formatter


```
{"operationName":"ParkBaseEquipmentInfo","variables":{},"query":"query ParkBaseEquipmentInfo {\n  parkBaseEquipmentInfo {\n    allMeterWorkingStatus {\n      normalAmount\n      normalRate\n    }\n    parkInstalledCapacity\n    stationAmount\n    meterAmount\n  }\n}\n"}
```

.. WAS CONVERTED TO ...

```
query{
  parkBaseEquipmentInf){
    allMeterWorkingStatus {
      normalAmount
      normalRate
    }
    parkInstalledCapacity
    stationAmount
    meterAmount
  }
}
```

