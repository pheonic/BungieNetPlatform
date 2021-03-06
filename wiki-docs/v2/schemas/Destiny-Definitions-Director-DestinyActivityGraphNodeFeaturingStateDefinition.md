<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info
Nodes can have different visual states. This object represents a single visual state (&quot;highlight type&quot;) that a node can be in, and the unlock expression condition to determine whether it should be set.

## Schema
* **Schema Type:** Definition
* **Type:** object

## Properties
Name | Type | Description
---- | ---- | -----------
highlightType | [[ActivityGraphNodeHighlightType|Destiny-ActivityGraphNodeHighlightType]]:Enum | The node can be highlighted in a variety of ways - the game iterates through these and finds the first FeaturingState that is valid at the present moment given the Game, Account, and Character state, and renders the node in that state. See the ActivityGraphNodeHighlightType enum for possible values.

## Example
```javascript
{
    // Type: [[ActivityGraphNodeHighlightType|Destiny-ActivityGraphNodeHighlightType]]:Enum
    "highlightType": {}
}

```

## References
1. https://bungie-net.github.io/multi/schema_Destiny-Definitions-Director-DestinyActivityGraphNodeFeaturingStateDefinition.html#schema_Destiny-Definitions-Director-DestinyActivityGraphNodeFeaturingStateDefinition
