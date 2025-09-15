# DB
```json
{
    "videoID":"unique_video_id",
    // Technical Metadata 
    "format":"mp4",
    "duration":"length_of_video_in_s",
    ....
    // General Metadata
    "createrId":"creater_id",
    "title":"video_title",
    "description":"video_description_text",
    ...
    /content Delivery Metadata
    "csbUrls":{
        "mp4":{
            "4k":["chunkurl1","chunkurl2,...],
            "720":["chunkurl1","chunkurl2,...],
            ...
        }
        "Mov":{
            "4k":["chunkurl1","chunkurl2,...],
            "720p":["chunkurl1","chunkurl2,...],
            ....
        }
        ....
    }

}
```