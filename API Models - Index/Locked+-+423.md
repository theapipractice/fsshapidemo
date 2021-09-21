# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Locked - 423 |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Locked Message |  | Pessimistic locking, e.g. processing states | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Http Error Code |  | 400 | No | No | No | No |  |Data Type : integer<br> Minimum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |





```
{
  "message": "Pessimistic locking, e.g. processing states",
  "code": 400
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Locked - 423",
  "type": "object",
  "properties": {
    "message": {
      "title": "Locked Message",
      "type": "string"
    },
    "code": {
      "title": "Http Error Code",
      "type": "integer"
    }
  }
}
```

