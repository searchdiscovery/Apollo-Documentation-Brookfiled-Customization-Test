# Product Location Viewed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "Product Location Viewed",
    "product": [
        {
            "productInfo": {
                "collection": {
                    "collectionId": "<collectionId>",
                    "collectionName": "<collectionName>"
                },
                "floorPlan": {
                    "floorPlanId": "<floorPlanId>",
                    "floorPlanName": "<floorPlanName>"
                },
                "location": {
                    "locationId": "<locationId>",
                    "locationName": "<locationName>"
                },
                "productName": "<productName>"
            }
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|collectionId|string|The ID of the collection, applicable to the property location.|123, 456, 789|||||||
|collectionName|string|The name of the collection, applicable to the property location.|Collection A, Collection B, Collection C|||||||
|floorPlanId|string|The ID of the floor plan, applicable to the property location.|123, 456, 789|||||||
|floorPlanName|string|The name of the floor plan, applicable to the property location.|2-Bedroom, Penthouse, 3-Bedroom|||||||
|locationId|string|The ID of the location, applicable to the property location.|123, 456, 789|||||||
|locationName|string|The name of the location, applicable to the property location.|New York, Chicago, Nashville|||||||
|productName|string|The name of the product, applicable to the property location.||||||||




