#Api design
## text post 

1. http method-post   endpoint-api/v1/Posts
```json
   {
    "userId":"1234",
    "text":"Exciting for my trip to europe",
    "hashtags":["travel","fun]
   }
   ```

## video/imgpost 
1. http method-post  endpoints-api/v1/posts
```json
{
    "userId":"12345",
    "mediaUrl":"s3/amazon/img.jpg",
    "description":"Relexing by the beach..",
    "hashtags":["relax","chooling"]
}
```
## Likes,commants
1.http method-post  endpoints-api/v1
```json
{
"userId":"12345",
"postId":"14895",
"comment":"lol,great👌"
}
```


## follow and unfollow

1.http method :post  Endpoint: api/v1/follow
```json
{
    "followerId":"12345",
    "followeeId::"12345"
}
```

## reading time 

1.http method :Get   Endpoint:v1/feed/{userId}


