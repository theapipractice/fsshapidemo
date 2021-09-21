# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Precondition Required - 428 |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Precondition Required Message |  | Server requires the request to be conditional, e.g. to make sure that the &#x27;lost update problem&#x27; is avoided (see MAY consider to support Prefer header to handle processing preferences) | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Http Error Code |  | 400 | No | No | No | No |  |Data Type : integer<br> Minimum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |





```
{
  "message": "Server requires the request to be conditional, e.g. to make sure that the \u0027lost update problem\u0027 is avoided (see MAY consider to support Prefer header to handle processing preferences)",
  "code": 400
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Precondition Required - 428",
  "type": "object",
  "properties": {
    "message": {
      "title": "Precondition Required Message",
      "type": "string"
    },
    "code": {
      "title": "Http Error Code",
      "type": "integer"
    }
  }
}
```

