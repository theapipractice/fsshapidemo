# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Too many requests - 429 |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Too many requests Message |  | The client does not consider rate limitingand sent too many requests (see MUST use code 429 with headers for rate limits) | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Http Error Code |  | 400 | No | No | No | No |  |Data Type : integer<br> Minimum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |





```
{
  "message": "The client does not consider rate limitingand sent too many requests (see MUST use code 429 with headers for rate limits)",
  "code": 400
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Too many requests - 429",
  "type": "object",
  "properties": {
    "message": {
      "title": "Too many requests Message",
      "type": "string"
    },
    "code": {
      "title": "Http Error Code",
      "type": "integer"
    }
  }
}
```

