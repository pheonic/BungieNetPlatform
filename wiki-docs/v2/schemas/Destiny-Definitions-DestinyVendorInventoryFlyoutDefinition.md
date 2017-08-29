<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
The definition for an &quot;inventory flyout&quot;: a UI screen where we show youpart of an otherwise hidden vendor inventory: like the Vault inventory buckets.

## Schema
* **Type:** Definition

## Properties
Name | Type | Description
---- | ---- | -----------
lockedDescription | string | If the flyout is locked, this is the reason why.
displayProperties | [[DestinyDisplayPropertiesDefinition|Destiny-Definitions-Common-DestinyDisplayPropertiesDefinition]]:Definition | The title and other common properties of the flyout.
buckets | [[DestinyVendorInventoryFlyoutBucketDefinition|Destiny-Definitions-DestinyVendorInventoryFlyoutBucketDefinition]]:Definition[] | A list of inventory buckets and other metadata to show on the screen.
flyoutId | integer:uint32 | An identifier for the flyout, in case anything else needs to refer to them.
suppressNewness | boolean | If this is true, don't show any of the glistening &quot;this is a new item&quot; UI elements, like we show on the inventory itemsthemselves in in-game UI.

## Example
```javascript
{
    // Type: string
    "lockedDescription": "",
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
    },
    // Type: [[DestinyVendorInventoryFlyoutBucketDefinition|Destiny-Definitions-DestinyVendorInventoryFlyoutBucketDefinition]]:Definition[]
    "buckets": [
       // Type: [[DestinyVendorInventoryFlyoutBucketDefinition|Destiny-Definitions-DestinyVendorInventoryFlyoutBucketDefinition]]:Definition
        {
            // Type: boolean
            "collapsible": false,
            // Type: [[DestinyInventoryBucketDefinition|Destiny-Definitions-DestinyInventoryBucketDefinition]]:ManifestDefinition:integer:uint32
            "inventoryBucketHash": 0,
            // Type: [[DestinyItemSortType|Destiny-DestinyItemSortType]]:Enum
            "sortItemsBy": 0
        }
    ],
    // Type: integer:uint32
    "flyoutId": 0,
    // Type: boolean
    "suppressNewness": false
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-Definitions-DestinyVendorInventoryFlyoutDefinition.html#schema_Destiny-Definitions-DestinyVendorInventoryFlyoutDefinition