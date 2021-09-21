# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Conflict - 409 |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Conflict Message |  | Request cannot be completed due to conflict, e.g. when two clients try to create the same resource or if there are concurrent, conflicting updates | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Http Error Code |  | 400 | No | No | No | No |  |Data Type : integer<br> Minimum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |





```
{
  "message": "Request cannot be completed due to conflict, e.g. when two clients try to create the same resource or if there are concurrent, conflicting updates",
  "code": 400
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Conflict - 409",
  "type": "object",
  "properties": {
    "message": {
      "title": "Conflict Message",
      "type": "string"
    },
    "code": {
      "title": "Http Error Code",
      "type": "integer"
    }
  }
}
```

