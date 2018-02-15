
### Base URL

- https://gd2.line.naver.jp/mh/api
- https://gd2.line.naver.jp/mh/
- https://{$country-server}.line.naver.jp/mh/api
  
  
  
### headersTemplate
|  |  | necessity |
|:---|:---:|---:|
|Content-Type |application/json |Must |
|User-Agent |Line/8.1.0 iPad5,1 11.2.0 |Must |
|X-Line-Application |IOSIPAD	8.1.0	iPhone OS	11.2.0 |Must |
|X-Line-Mid |{$your_mid} |Must |
|X-Line-ChannelToken |{$your_channelToken} |Must |
|X-Line-Carrier |{$carrierCode} |Only phone? |


# Cheat sheets

* * *
### POST /api/v39/post/create.json
  
#### GET PARAMS
homeId = {$your_mid}  
sourceType = 'TIMELINE'

#### POST PARAMS
    {'postInfo': {'readPermission': {'type': 'ALL'}}, 'sourceType': 'TIMELINE', 'contents': {'text': text}}
    
readPermission->type = __ALL__ or __FRIEND__

