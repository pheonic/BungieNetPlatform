<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info

## Schema
* **Schema Type:** Class
* **Type:** object

## Properties
Name | Type | Description
---- | ---- | -----------
categoryName | string | 
entries | [[SearchResultOfTrendingEntry|SearchResultOfTrendingEntry]] | 
categoryId | string | 

## Example
```javascript
{
    // Type: string
    "categoryName": "",
    // Type: [[SearchResultOfTrendingEntry|SearchResultOfTrendingEntry]]
    "entries": {
        // Type: [[TrendingEntry|Trending-TrendingEntry]][]
        "results": [
           // Type: [[TrendingEntry|Trending-TrendingEntry]]
            {
                // Type: number:double
                "weight": 0,
                // Type: boolean
                "isFeatured": false,
                // Type: string
                "identifier": "",
                // Type: [[TrendingEntryType|Trending-TrendingEntryType]]:Enum
                "entityType": {},
                // Type: string
                "displayName": "",
                // Type: string
                "tagline": "",
                // Type: string
                "image": "",
                // Type: string:date-time:nullable
                "startDate": "",
                // Type: string:date-time:nullable
                "endDate": "",
                // Type: string
                "link": "",
                // Type: string
                "webmVideo": "",
                // Type: string
                "mp4Video": "",
                // Type: string
                "featureImage": ""
            }
        ],
        // Type: integer:int32
        "totalResults": 0,
        // Type: boolean
        "hasMore": false,
        // Type: [[PagedQuery|Queries-PagedQuery]]
        "query": {
            // Type: integer:int32
            "itemsPerPage": 0,
            // Type: integer:int32
            "currentPage": 0,
            // Type: string
            "requestContinuationToken": ""
        },
        // Type: string
        "replacementContinuationToken": "",
        // Type: boolean
        "useTotalResults": false
    },
    // Type: string
    "categoryId": ""
}

```

## References
1. https://bungie-net.github.io/multi/schema_Trending-TrendingCategory.html#schema_Trending-TrendingCategory
