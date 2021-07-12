# Report Listing Displayed

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Report Listing Displayed",
    "listingDisplayed": {
        "listingDriver": "<listingDriver>"
    },
    "listingRefined": {
        "listingType": "<listingType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|listingDriver|string|Describes the action that caused the listing to be displayed|Onsite Search, Curated Assortment, Navigation|||||||
|listingType|string|The type of listings shown|Product, Location, Event, Room, Content|||||||
