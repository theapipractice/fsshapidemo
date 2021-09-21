# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Not Implemented - 501 |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Not Implemented Message |  | Server cannot fulfill the request (usually implies future availability, e.g. new feature) | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Http Error Code |  | 400 | No | No | No | No |  |Data Type : integer<br> Minimum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |





```
{
  "message": "Server cannot fulfill the request (usually implies future availability, e.g. new feature)",
  "code": 400
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Not Implemented - 501",
  "type": "object",
  "properties": {
    "message": {
      "title": "Not Implemented Message",
      "type": "string"
    },
    "code": {
      "title": "Http Error Code",
      "type": "integer"
    }
  }
}
```

