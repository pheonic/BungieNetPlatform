<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
Represents a stat on an item *or* Character (NOT a Historical Stat, but a physical attribute stat like Attack, Defense etc...)

## Schema
* **Schema Type:** Class
* **Type:** object

## Properties
Name | Type | Description
---- | ---- | -----------
statHash | [[Destiny.Definitions.DestinyStatDefinition|Destiny-Definitions-DestinyStatDefinition]]:integer:uint32 | The hash identifier for the Stat. Use it to look up the DestinyStatDefinition for static data about the stat.
value | integer:int32 | The current value of the Stat.
maximumValue | integer:int32 | The highest possible value for the stat, if we were able to compute it. (I wouldn't necessarily trust this value right now. I would like to improve its calculation in later iterations of the API. Consider this a placeholder for desired future functionality)

## Example
```javascript
{
    // Type: [[Destiny.Definitions.DestinyStatDefinition|Destiny-Definitions-DestinyStatDefinition]]:integer:uint32
    "statHash": 0,
    // Type: integer:int32
    "value": 0,
    // Type: integer:int32
    "maximumValue": 0
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-DestinyStat.html#schema_Destiny-DestinyStat
