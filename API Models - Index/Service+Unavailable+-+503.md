# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Service Unavailable - 503 |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Service Unavailable Message |  | service is (temporarily) not available (e.g. if a required component or downstream service is not available) - client retry may be sensible. If possible, the service should indicate how long the client should wait by setting the Retry-After header | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Http Error Code |  | 400 | No | No | No | No |  |Data Type : integer<br> Minimum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |





```
{
  "message": "service is (temporarily) not available (e.g. if a required component or downstream service is not available) - client retry may be sensible. If possible, the service should indicate how long the client should wait by setting the Retry-After header",
  "code": 400
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Service Unavailable - 503",
  "type": "object",
  "properties": {
    "message": {
      "title": "Service Unavailable Message",
      "type": "string"
    },
    "code": {
      "title": "Http Error Code",
      "type": "integer"
    }
  }
}
```

