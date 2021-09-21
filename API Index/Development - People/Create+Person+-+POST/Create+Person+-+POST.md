# Create Person - POST

POST /v1/people

## Description



* [Request Payloads](#request-payloads)
* [Response Payloads](#response-payloads)

| HTTP Method                           | Post|
| ------------------------------------- | ----------------------------------------------- |
| API                                   | People                                           |
| Api Version                           | 1.0.0.33                                         |
| Resource Version                      | 1                                               |
| Summary                               |                                       |
| Base Path                             | /v1/people                                     |
| Resource                              | Create Person                                      |
| Endpoint URL                          | https://api-dev.ba-industries.com.au/v1/people              |
| Service Status                        |  -                                          |
| Legislative / Regulatory / Compliance |                                             |
| Firewalls Details                     |                                              |
| Security Certificate Details          |                                              |
| Vendor or Partner Considerations      |                                             |

## Request Payloads

### Request Header



| Header | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| ------ | :---------: | :----: | :-: | :-------: | :---------------: | :-------: | :-----: | ------- |
| Api Header |  |  -  | No | No | No | No |  -  | Data Type : object<br>  |


---

### Query Params



| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| --------- | :---------: | :----: | :-: | :-------: | :---------------: | :-------: | :-----: | ------- |
| Api Query Parameter |  |  -  | No | No | No | No |  -  | Data Type : object<br>  |


---

### Request Body

#### Payload 



| Parameter | Description | Sample | PII | Sensitive | Unique Identifier | Mandatory | Default | Details |
| :----- | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :----- |
| Person |  |  -  | No | No | No | No |  -  | Data Type : object<br>  |
| >First Name |  | John | No | No | No | No |  -  | Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |
| >Last Name |  | Smith | No | No | No | No |  -  | Data Type : string<br> Min. length :  - <br> Max. length :  - <br> Regex :  - <br>  |



#### Json sample
```
{
  "firstName": "John",
  "lastName": "Smith"
}
```


#### Json Schema
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
    }
  }
}
```

---