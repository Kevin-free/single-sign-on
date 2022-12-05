# sendVerificationCodeEmail
    发送邮件验证
    
### Url
    /sso/users/email/verify/code/send
    
### Method
    POST

### Request Payload
    {
        email: "邮箱地址"
    }
    
### Response Body
    {
        "status":"OK"
    }
    
### Response Code
    HTTP/1.1 200 OK

### Example
```Bash
curl -X POST "http://127.0.0.1:9966/sso/users/email/verify/code/send" -d '{"email":"kevin1258@foxmail.com"}' -i
HTTP/1.1 200 OK
Content-Type: application/json
X-Request-Id: tmx1qdmerjruim4ukmuafng6oy
X-Version-Id: 4.0.0.dev.53cd9ade63e982a7a4a281bb0c391417
Date: Mon, 05 Dec 2022 07:12:09 GMT
Content-Length: 15
```

```Bash
{"status":"OK"}
```
