# Internal Campaign Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Internal Campaign Clicked",
    "internalCampaign": {
        "campaignList": [
            {
                "internalCampaignID": "<internalCampaignID>",
                "internalCampaignName": "<internalCampaignName>"
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|internalCampaignID|string|Unique Identifier of an internal campaign|2345, 56789, 9876|||||||
|internalCampaignName|string|The name of the promotion.|Trek bikes for kids, REI Spring Sale 2019, Viking Cruise Fall Specials|||||||
