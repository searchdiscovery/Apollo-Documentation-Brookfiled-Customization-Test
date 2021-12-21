# Page Load Started

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "Page Load Started",
    "page": {
        "pageName": "<pageName>",
        "pageType": "<pageType>"
    },
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
|collectionName|string|The name of the collection, applicable to the property location.|Collection A, Collection B, Collection C|||||||
|floorPlanId|string|The ID of the floor plan, applicable to the property location.|123, 456, 789|||||||
|floorPlanName|string|The name of the floor plan, applicable to the property location.|2-Bedroom, Penthouse, 3-Bedroom|||||||
|pageName|string|Describes the page and its content specifically. |product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|pageType|string|Describes what purpose the page serves. Often aligns with the CMS template.|Home, Event Detail, Property Detail, Product Listing, Blog Post, Shopping Cart|||||||




