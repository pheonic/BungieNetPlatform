<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info

## Schema
* **Schema Type:** Generic Class
* **Type:** object

## Properties
Name | Type | Description
---- | ---- | -----------
data | Dictionary&lt;integer:int64,[[DestinyCharacterComponent|Destiny-Entities-Characters-DestinyCharacterComponent]]&gt; | 
privacy | [[ComponentPrivacySetting|Components-ComponentPrivacySetting]]:Enum | 

## Example
```javascript
{
    // Type: Dictionary&lt;integer:int64,[[DestinyCharacterComponent|Destiny-Entities-Characters-DestinyCharacterComponent]]&gt;
    "data": {
        "0": {
            // Type: integer:int64
            "membershipId": 0,
            // Type: [[BungieMembershipType|BungieMembershipType]]:Enum
            "membershipType": {},
            // Type: integer:int64
            "characterId": 0,
            // Type: string:date-time
            "dateLastPlayed": "",
            // Type: integer:int64
            "minutesPlayedThisSession": 0,
            // Type: integer:int64
            "minutesPlayedTotal": 0,
            // Type: integer:int32
            "light": 0,
            // Type: Dictionary&lt;integer:uint32,integer:int32&gt;
            "stats": {
                "0": 0
            },
            // Type: [[Destiny.Definitions.DestinyRaceDefinition|Destiny-Definitions-DestinyRaceDefinition]]:integer:uint32
            "raceHash": 0,
            // Type: [[Destiny.Definitions.DestinyGenderDefinition|Destiny-Definitions-DestinyGenderDefinition]]:integer:uint32
            "genderHash": 0,
            // Type: [[Destiny.Definitions.DestinyClassDefinition|Destiny-Definitions-DestinyClassDefinition]]:integer:uint32
            "classHash": 0,
            // Type: [[DestinyRace|Destiny-DestinyRace]]:Enum
            "raceType": {},
            // Type: [[DestinyClass|Destiny-DestinyClass]]:Enum
            "classType": {},
            // Type: [[DestinyGender|Destiny-DestinyGender]]:Enum
            "genderType": {},
            // Type: string
            "emblemPath": "",
            // Type: string
            "emblemBackgroundPath": "",
            // Type: [[Destiny.Definitions.DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:integer:uint32
            "emblemHash": 0,
            // Type: [[DestinyColor|Destiny-Misc-DestinyColor]]
            "emblemColor": {},
            // Type: [[DestinyProgression|Destiny-DestinyProgression]]
            "levelProgression": {},
            // Type: integer:int32
            "baseCharacterLevel": 0,
            // Type: number:float
            "percentToNextLevel": 0
        }
    },
    // Type: [[ComponentPrivacySetting|Components-ComponentPrivacySetting]]:Enum
    "privacy": 0
}

```

## References
1. https://bungie-net.github.io/multi/schema_DictionaryComponentResponseOfint64AndDestinyCharacterComponent.html#schema_DictionaryComponentResponseOfint64AndDestinyCharacterComponent
