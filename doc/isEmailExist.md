# isEmailExist
    判断邮箱是否已经注册过
    
### Url
     /sso/users/email/exist
    
### Method
    POST

### Request Payload
    {
        "email":"1215894562@qq.com"
    }

### Response Body
    {
        "status":"true"
    }
    
### Response Code
    HTTP/1.1 200 OK

### Example
```Bash
curl -X POST "http://127.0.0.1:9966/sso/users/email/exist" -d '{"email":"1215894562@qq.com"}'  -i

HTTP/1.1 200 OK
Content-Type: application/json
X-Request-Id: 45397wmzeb8sddbzxhkah3y7tc
X-Version-Id: 4.0.0.dev.53cd9ade63e982a7a4a281bb0c391417
Date: Mon, 05 Dec 2022 06:53:21 GMT
Content-Length: 17
```

```Bash
{"status":"true"}
```
