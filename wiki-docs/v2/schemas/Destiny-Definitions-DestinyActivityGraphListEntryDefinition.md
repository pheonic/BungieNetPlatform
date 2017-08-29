<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
Destinations and Activities may have default Activity Graphs that should be shownwhen you bring up the Director and are playing in either. This contract defines the graph referred to and the gating for when it is relevant.

## Schema
* **Type:** Definition

## Properties
Name | Type | Description
---- | ---- | -----------
activityGraphHash | [[DestinyActivityGraphDefinition|Destiny-Definitions-Director-DestinyActivityGraphDefinition]]:ManifestDefinition:integer:uint32 | The hash identifier of the DestinyActivityGraphDefinition that should be shown when openingthe director.

## Example
```javascript
{
    // Type: [[DestinyActivityGraphDefinition|Destiny-Definitions-Director-DestinyActivityGraphDefinition]]:ManifestDefinition:integer:uint32
    "activityGraphHash": 0
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-Definitions-DestinyActivityGraphListEntryDefinition.html#schema_Destiny-Definitions-DestinyActivityGraphListEntryDefinition