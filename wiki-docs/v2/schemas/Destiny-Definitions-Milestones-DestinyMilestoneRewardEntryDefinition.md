<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
The definition of a specific reward, which may be contained in a category of rewards and that has optional information about how it is obtained.

## Schema
* **Schema Type:** Definition
* **Type:** object

## Properties
Name | Type | Description
---- | ---- | -----------
rewardEntryHash | integer:uint32 | The identifier for this reward entry. Runtime data will refer to reward entries by this hash. Only guaranteed unique within the specific Milestone.
rewardEntryIdentifier | string | The string identifier, if you care about it. Only guaranteed unique within the specific Milestone.
items | [[DestinyItemQuantity|Destiny-DestinyItemQuantity]][] | The items you will get as rewards, and how much of it you'll get.
vendorHash | [[Destiny.Definitions.DestinyVendorDefinition|Destiny-Definitions-DestinyVendorDefinition]]:integer:uint32:nullable | If this reward is redeemed at a Vendor, this is the hash of the Vendor to go to in order to redeem the reward. Use this hash to look up the DestinyVendorDefinition.
displayProperties | [[DestinyDisplayPropertiesDefinition|Destiny-Definitions-Common-DestinyDisplayPropertiesDefinition]]:Definition | For us to bother returning this info, we should be able to return some kind of information about why these rewards are grouped together. This is ideally that information. Look at how confident I am that this will always remain true.
order | integer:int32 | If you want to follow BNet's ordering of these rewards, use this number within a given category to order the rewards. Yeah, I know. I feel dirty too.

## Example
```javascript
{
    // Type: integer:uint32
    "rewardEntryHash": 0,
    // Type: string
    "rewardEntryIdentifier": "",
    // Type: [[DestinyItemQuantity|Destiny-DestinyItemQuantity]][]
    "items": [
       // Type: [[DestinyItemQuantity|Destiny-DestinyItemQuantity]]
        {
            // Type: [[Destiny.Definitions.DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:integer:uint32
            "itemHash": 0,
            // Type: integer:int64:nullable
            "itemInstanceId": 0,
            // Type: integer:int32
            "quantity": 0
        }
    ],
    // Type: [[Destiny.Definitions.DestinyVendorDefinition|Destiny-Definitions-DestinyVendorDefinition]]:integer:uint32:nullable
    "vendorHash": 0,
    // Type: [[DestinyDisplayPropertiesDefinition|Destiny-Definitions-Common-DestinyDisplayPropertiesDefinition]]:Definition
    "displayProperties": {},
    // Type: integer:int32
    "order": 0
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-Definitions-Milestones-DestinyMilestoneRewardEntryDefinition.html#schema_Destiny-Definitions-Milestones-DestinyMilestoneRewardEntryDefinition
