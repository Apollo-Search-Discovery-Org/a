# Location Listing Item Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Location Listing Item Clicked",
    "listingItemClicked": {
        "listing": [
            {
                "location": {
                    "locationBrand": "<locationBrand>",
                    "locationId": "<locationId>",
                    "locationName": "<locationName>",
                    "locationType": "<locationType>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|locationBrand|string|The brand associated with a location.|BMO Harris, Walmart, Lands' End, Motel 6, AC Hotels|||||||
|locationId|string|Unique Identifier of a Location. |155, 65588, 987764448|||||||
|locationName|string|The friendly name of the location.|Deerefiled Outlet, Old Orchard, Manhatten Midtown|||||||
|locationType|string|The type of the location|Retail Store, Lodging, ATM, Banking Branch|||||||
