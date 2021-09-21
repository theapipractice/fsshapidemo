# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Bad Request - 400 |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Bad Request Message |  | Generic / unknown error. Should also be delivered in case of input payload fails business logic validation | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Http Error Code |  | 400 | No | No | No | No |  |Data Type : integer<br> Minimum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |





```
{
  "message": "Generic / unknown error. Should also be delivered in case of input payload fails business logic validation",
  "code": 400
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Bad Request - 400",
  "type": "object",
  "properties": {
    "message": {
      "title": "Bad Request Message",
      "type": "string"
    },
    "code": {
      "title": "Http Error Code",
      "type": "integer"
    }
  }
}
```

