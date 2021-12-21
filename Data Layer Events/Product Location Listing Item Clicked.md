# Product Location Listing Item Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "Product Location Listing Item Clicked",
    "listingItemClicked": {
        "listing": [
            {
                "collection": {
                    "collectionId": "<collectionId>",
                    "collectionName": "<collectionName>"
                },
                "floorPlan": {
                    "floorPlanId": "<floorPlanId>",
                    "floorPlanName": "<floorPlanName>"
                }
            }
        ]
    },
    "product": [
        {
            "productInfo": {
                "location": {
                    "locationId": "<locationId>",
                    "locationName": "<locationName>"
                }
            }
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|collectionId|string|The ID of the collection, applicable to the property location.|123, 456, 789|||||||
|collectionName|string|The name of the collection, applicable to the property location.|Mercantile Place, Parma Collection, The Yards Collection|||||||
|floorPlanId|string|The ID of the floor plan, applicable to the property location.|123, 456, 789|||||||
|floorPlanName|string|The name of the floor plan, applicable to the property location.|Studio, 3 Bed, 4 Bed|||||||
|locationId|string|The ID of the location, applicable to the property location.|123, 456, 789|||||||
|locationName|string|The name of the location, applicable to the property location.|New York, Chicago, Nashville|||||||




