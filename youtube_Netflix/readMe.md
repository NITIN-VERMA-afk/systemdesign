# API DESIGN

## UPLOAD

1.HTTP method: POST  Entpoint: /v1/videos?uploadType=resumable
2.HTTP Headers:"SessionURI":"/v1/videos?uploadType=resumable&uploadId=123"
3.HTTP BODY 
```json
{
    "title":"Titanic",
    "format":"mp4",
}

##  2nd request 
1. HTTP method :put    Endpoint: /v1/videos?uploadType=resumable&uploadId=123(session URI)

## Stream contant

1.HTTP method :GET Endpoint :v1/watch?v=<video-id>
1.protocol - HLS


