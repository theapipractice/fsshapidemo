# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Not Acceptable - 406 |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Not Acceptable Message |  | Resource can only generate content not acceptable according to the Accept headers sent in the request | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Http Error Code |  | 400 | No | No | No | No |  |Data Type : integer<br> Minimum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |





```
{
  "message": "Resource can only generate content not acceptable according to the Accept headers sent in the request",
  "code": 400
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Not Acceptable - 406",
  "type": "object",
  "properties": {
    "message": {
      "title": "Not Acceptable Message",
      "type": "string"
    },
    "code": {
      "title": "Http Error Code",
      "type": "integer"
    }
  }
}
```

