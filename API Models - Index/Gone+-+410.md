# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Gone - 410 |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; Gone Message |  | Resource does not exist any longer, e.g. when accessing a resource that has intentionally been deleted | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Http Error Code |  | 400 | No | No | No | No |  |Data Type : integer<br> Minimum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |





```
{
  "message": "Resource does not exist any longer, e.g. when accessing a resource that has intentionally been deleted",
  "code": 400
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Gone - 410",
  "type": "object",
  "properties": {
    "message": {
      "title": "Gone Message",
      "type": "string"
    },
    "code": {
      "title": "Http Error Code",
      "type": "integer"
    }
  }
}
```

