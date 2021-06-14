# Location Listing Displayed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Location Listing Displayed",
    "listingDisplayed": {
        "displayCount": "<displayCount>",
        "listing": [
            {
                "isDisplayed": "<isDisplayed>",
                "location": {
                    "locationBrand": "<locationBrand>",
                    "locationId": "<locationId>",
                    "locationName": "<locationName>",
                    "locationType": "<locationType>"
                }
            }
        ],
        "listingDriver": "<listingDriver>",
        "listingType": "<listingType>",
        "resultsCount": "<resultsCount>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|displayCount|integer|The total number of items displayed out of all returned items. (Integer)|10, 20, 30, 40||||0|||
|isDisplayed|boolean|Helper node used by AA Product String Builder to set product scoped events|true|||||||
|listingDriver|string|Describes the action that caused the listing to be displayed|Onsite Search, Curated Assortment, Navigation|||||||
|listingType|string|The type of results being listed|text, product, location, event, room, product location|||||||
|locationBrand|string|The brand associated with a location.|BMO Harris, Walmart, Lands' End, Motel 6, AC Hotels|||||||
|locationId|string|Unique Identifier of a Location. |155, 65588, 987764448|||||||
|locationName|string|The friendly name of the location.|Deerefiled Outlet, Old Orchard, Manhatten Midtown|||||||
|locationType|string|The type of the location|Retail Store, Lodging, ATM, Banking Branch|||||||
|resultsCount|integer|The total number of items returned that matched the search criteria. (Integer)|1, 21, 111, 166||||0|||
