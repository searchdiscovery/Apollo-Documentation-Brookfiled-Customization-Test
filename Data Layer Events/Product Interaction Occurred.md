# Product Interaction Occurred

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "Product Interaction Occurred",
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
                }
            }
        }
    ],
    "productInteraction": {
        "interactionDetail": "<interactionDetail>",
        "interactionType": "<interactionType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|collectionId|string|The ID of the collection, applicable to the property location.|123, 456, 789|||||||
|collectionName|string|The name of the collection, applicable to the property location.|Collection A, Collection B, Collection C|||||||
|floorPlanId|string|The ID of the floor plan, applicable to the property location.|123, 456, 789|||||||
|floorPlanName|string|The name of the floor plan, applicable to the property location.|2-Bedroom, Penthouse, 3-Bedroom|||||||
|interactionDetail|string|Prodives details specific to the product Interaction type|Added to Favorites, Removed from Favorites, Front View, Side View|||||||
|interactionType|string|Describes the type of product interaction that occurred|Favorites Clicked, Thumbnail Image Clicked, Product Line Selected, Reviews Expanded|||||||
|locationId|string|The ID of the location, applicable to the property location.|123, 456, 789|||||||
|locationName|string|The name of the location, applicable to the property location.|New York, Chicago, Nashville|||||||




