
### Base URL

- https://gd2.line.naver.jp/mh/api
- https://gd2.line.naver.jp/mh/
- https://{$country-server}.line.naver.jp/mh/api
  
  
  
### headersTemplate

↓ You must need ↓
![headersTemplate](https://i.imgur.com/dtiKuyU.png "headersTemplate")




# Cheat sheets

* * *
### POST /api/v39/post/create.json
  
#### GET PARAMS
homeId = {$your_mid}  
sourceType = 'TIMELINE'

#### POST PARAMS
    {'postInfo': {'readPermission': {'type': 'ALL'}}, 'sourceType': 'TIMELINE', 'contents': {'text': text}}
    
readPermission->type = __ALL__ or __FRIEND__

