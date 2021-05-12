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

### how to use?

git pull this repository, then open the ```index.html``` in your chrome

![](https://github.com/codeliuyang/graphql-requestbody-formatter/blob/master/Jietu20210512-132244.jpg)
