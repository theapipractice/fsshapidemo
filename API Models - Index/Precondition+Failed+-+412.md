# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Precondition Failed - 412 |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Precondition Failed Message |  | Returned for conditional requests, e.g. If-Match if the condition failed. Used for optimistic locking | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Http Error Code |  | 400 | No | No | No | No |  |Data Type : integer<br> Minimum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |





```
{
  "message": "Returned for conditional requests, e.g. If-Match if the condition failed. Used for optimistic locking",
  "code": 400
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Precondition Failed - 412",
  "type": "object",
  "properties": {
    "message": {
      "title": "Precondition Failed Message",
      "type": "string"
    },
    "code": {
      "title": "Http Error Code",
      "type": "integer"
    }
  }
}
```

