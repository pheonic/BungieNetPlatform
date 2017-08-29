<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
The definition for information related to a key/value pair that is relevant for a particular Milestone orcomponent within the Milestone. This lets us more flexibly pass up information that's useful to someone,even if it's not necessarily us.

## Schema
* **Type:** Definition

## Properties
Name | Type | Description
---- | ---- | -----------
key | string | 
displayProperties | [[DestinyDisplayPropertiesDefinition|Destiny-Definitions-Common-DestinyDisplayPropertiesDefinition]]:Definition | 

## Example
```javascript
{
    // Type: string
    "key": "",
    // Type: [[DestinyDisplayPropertiesDefinition|Destiny-Definitions-Common-DestinyDisplayPropertiesDefinition]]:Definition
    "displayProperties": {
        // Type: string
        "description": "",
        // Type: string
        "name": "",
        // Type: string
        "icon": "",
        // Type: boolean
        "hasIcon": false
    }
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-Definitions-Milestones-DestinyMilestoneValueDefinition.html#schema_Destiny-Definitions-Milestones-DestinyMilestoneValueDefinition