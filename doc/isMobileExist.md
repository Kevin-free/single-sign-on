# isMobileExist
    判断手机号是否已经注册过
    
### Url
    /sso/users/phone/exist
    
### Method
    POST

### Request Payload
    {
        "mobile":"13544285663"
    }

### Response Body
    {
        "status":"true"
    }
    
### Response Code
    HTTP/1.1 200 OK

### Example
```Bash
curl -X POST  "http://127.0.0.1:9966/sso/users/phone/exist"  -i -d '{"mobile":"15727546131"}'

HTTP/1.1 200 OK
Content-Type: application/json
X-Request-Id: b7dxg9uj678adri6zgypd4dkcw
X-Version-Id: 4.0.0.dev.53cd9ade63e982a7a4a281bb0c391417
Date: Mon, 05 Dec 2022 06:56:31 GMT
Content-Length: 18
```
```Bash
{"status":"false"}
```
