# Product Location Listing Displayed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "Product Location Listing Displayed",
    "listingDisplayed": {
        "filterList": "<filterList>",
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
        ],
        "listingType": "<listingType>",
        "resultsCount": <resultsCount>
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
|filterList|string|A twice delimited string of filterType and filterValue pairs.  Use \~ between type and value.  Use \| between pairs|sort\~price ascending\|color\~green\|size\~medium|||||||
|floorPlanId|string|The ID of the floor plan, applicable to the property location.|123, 456, 789|||||||
|floorPlanName|string|The name of the floor plan, applicable to the property location.|Studio, 2 Bed, 3 Bed|||||||
|listingType|string|The type of results being listed|text, product, location, event, room, product location|||||||
|locationId|string|The ID of the location, applicable to the property location.|123, 456, 789|||||||
|locationName|string|The name of the location, applicable to the property location.|New York, Chicago, Nashville|||||||
|resultsCount|integer|The total number of items returned that matched the search criteria. \(Integer\)|1, 21, 111, 166||||0|||




