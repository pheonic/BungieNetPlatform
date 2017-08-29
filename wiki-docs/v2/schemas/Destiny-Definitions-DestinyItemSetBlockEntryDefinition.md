<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
Defines a particular entry in an ItemSet (AKA a particular Quest Step in a Quest)

## Schema
* **Type:** Definition

## Properties
Name | Type | Description
---- | ---- | -----------
trackingValue | integer:int32 | Used for tracking which step a user reached.  These values will be populated in the user'sinternal state, which we expose externally as a more usable DestinyQuestStatus object.If this item has been obtained, this value will be set in trackingUnlockValueHash.
itemHash | [[DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:ManifestDefinition:integer:uint32 | This is the hash identifier for a DestinyInventoryItemDefinition representing this quest step.

## Example
```javascript
{
    // Type: integer:int32
    "trackingValue": 0,
    // Type: [[DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:ManifestDefinition:integer:uint32
    "itemHash": 0
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-Definitions-DestinyItemSetBlockEntryDefinition.html#schema_Destiny-Definitions-DestinyItemSetBlockEntryDefinition