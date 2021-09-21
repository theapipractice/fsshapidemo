# Model Definition
| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Person |  |  -  | No | No | No | No |  |Data Type : object<br>  |
| &gt; First Name |  | John | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Last Name |  | Smith | No | No | No | No |  |Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| &gt; Person ID |  | 12134 | No | No | **YES** | No |  |Data Type : integer<br> Minimum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br> Allow Null : false<br>  |





```
{
  "firstName": "John",
  "lastName": "Smith",
  "personId": 12134
}
```




```
{
  "$schema": "http://json-schema.org/draft-04/schema#",
  "title": "Person",
  "description": "",
  "type": "object",
  "properties": {
    "firstName": {
      "title": "First Name",
      "type": "string"
    },
    "lastName": {
      "title": "Last Name",
      "type": "string"
    },
    "personId": {
      "title": "Person ID",
      "description": "",
      "type": "integer"
    }
  }
}
```

