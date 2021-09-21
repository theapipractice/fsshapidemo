# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Internal Server Error - 500 |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Internal Server Error Message |  | A generic error indication for an unexpected server execution problem (here, client retry may be sensible) | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Http Error Code |  | 400 | No | No | No | No |  |Data Type : integer<br> Minimum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |





```
{
  "message": "A generic error indication for an unexpected server execution problem (here, client retry may be sensible)",
  "code": 400
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Internal Server Error - 500",
  "type": "object",
  "properties": {
    "message": {
      "title": "Internal Server Error Message",
      "type": "string"
    },
    "code": {
      "title": "Http Error Code",
      "type": "integer"
    }
  }
}
```

