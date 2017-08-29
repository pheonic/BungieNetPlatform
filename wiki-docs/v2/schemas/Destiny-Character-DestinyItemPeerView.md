<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
Bare minimum summary information for an item, for the sake of 3D rendering the item.

## Schema
* **Type:** Class

## Properties
Name | Type | Description
---- | ---- | -----------
itemHash | [[DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:ManifestDefinition:integer:uint32 | The hash identifier of the item in question.  Use it to look up the DestinyInventoryItemDefinition of the itemfor static rendering data.
dyes | [[DyeReference|Destiny-DyeReference]][] | The list of dyes that have been applied to this item.

## Example
```javascript
{
    // Type: [[DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:ManifestDefinition:integer:uint32
    "itemHash": 0,
    // Type: [[DyeReference|Destiny-DyeReference]][]
    "dyes": [
       // Type: [[DyeReference|Destiny-DyeReference]]
        {
            // Type: integer:uint32
            "channelHash": 0,
            // Type: integer:uint32
            "dyeHash": 0
        }
    ]
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-Character-DestinyItemPeerView.html#schema_Destiny-Character-DestinyItemPeerView