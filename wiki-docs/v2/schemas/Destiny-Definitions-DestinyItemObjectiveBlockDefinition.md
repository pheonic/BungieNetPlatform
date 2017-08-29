<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
An item can have objectives on it.  In practice, these are the exclusive purview of&quot;Quest Step&quot; items: DestinyInventoryItemDefinitions that represent a specific step in a Quest. Quest steps have 1:M objectives that we end up processing and returning in live data as DestinyQuestStatusdata, and other useful information.

## Schema
* **Type:** Definition

## Properties
Name | Type | Description
---- | ---- | -----------
objectiveHashes | [[DestinyObjectiveDefinition|Destiny-Definitions-DestinyObjectiveDefinition]]:ManifestDefinition:integer:uint32[] | The hashes to Objectives (DestinyObjectiveDefinition) that are part of this Quest Step, in theorder that they should be rendered.
displayActivityHashes | [[DestinyActivityDefinition|Destiny-Definitions-DestinyActivityDefinition]]:ManifestDefinition:integer:uint32[] | For every entry in objectiveHashes, there is a corresponding entry in this arrayat the same index.  If the objective is meant to be associated with a specific DestinyActivityDefinition,there will be a valid hash at that index.  Otherwise, it will be invalid (0).
requireFullObjectiveCompletion | boolean | If True, all objectives must be completed for the step to be completed.If False, any one objective can be completed for the step to be completed.
questlineItemHash | [[DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:ManifestDefinition:integer:uint32 | The hash for the DestinyInventoryItemDefinition representing the Quest to which this Quest Step belongs.
narrative | string | The localized string for narrative text related to this quest step, if any.
objectiveVerbName | string | The localized string describing an action to be performed associated with the objectives, if any.
questTypeIdentifier | string | The identifier for the type of quest being performed, if any.  Not associated with any fixed definition, yet.
questTypeHash | integer:uint32 | A hashed value for the questTypeIdentifier, because apparently I like to be redundant.

## Example
```javascript
{
    // Type: [[DestinyObjectiveDefinition|Destiny-Definitions-DestinyObjectiveDefinition]]:ManifestDefinition:integer:uint32[]
    "objectiveHashes": [
       // Type: integer:uint32
        0
    ],
    // Type: [[DestinyActivityDefinition|Destiny-Definitions-DestinyActivityDefinition]]:ManifestDefinition:integer:uint32[]
    "displayActivityHashes": [
       // Type: integer:uint32
        0
    ],
    // Type: boolean
    "requireFullObjectiveCompletion": false,
    // Type: [[DestinyInventoryItemDefinition|Destiny-Definitions-DestinyInventoryItemDefinition]]:ManifestDefinition:integer:uint32
    "questlineItemHash": 0,
    // Type: string
    "narrative": "",
    // Type: string
    "objectiveVerbName": "",
    // Type: string
    "questTypeIdentifier": "",
    // Type: integer:uint32
    "questTypeHash": 0
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-Definitions-DestinyItemObjectiveBlockDefinition.html#schema_Destiny-Definitions-DestinyItemObjectiveBlockDefinition