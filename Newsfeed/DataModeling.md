# DataModeling

## postDB

```json
{
    "postId":"unique_post_id",
    "userId":"user_id",
    "text":"posttext"
    "mediaUrls":"["url1","url2"],
    "timestamps":"1720748150"
}
```

## FeedsDB

```json
{
    "userId:"unique user id",
    "feedItems":[
    {
    "postId":"1234",
    "userId":"8765453",
    "text":"sample post text 1",
    "timestamps":"12345445,

    },
    {
        "postId:"34355",
        "userId":"123456",
        "text":"sample post text 1 ",
        "mediaUrls":["url1","url2",...]
        "timestamp":"123243534",
    }
    ]


}
```

## commands db

```json
{
    "commendId":"unique_comment_id",
    "userId":"user_id",
    "postId:"post_id",
    "comment":"comment text",
    "timestamp":"1723098754"
}
```

## Likes db

```json
{
    "LikeId:"unique_Like_id",
    "userId":"user_id",
    "postId":"post_id".
    "timestamp":"12345674


}
```


## follow db
```json
{
    "userId":",user1_id>",
    "followers":[
        {
            "followerId":"<user2_id>,
            "timestamp":"1224356454
        },
    ],
    "followees":[
        {
            "followeeId":"<user3_id>",
            "timestamp":"123423232"
        }
    ]
}

## 