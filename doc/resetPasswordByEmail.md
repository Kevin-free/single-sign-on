# resetPasswordByEmail 
    邮箱找回密码

### Url
    /sso/users/email/reset

### Method
    POST

### Request Payload
    {
        "email":"邮箱地址",
        "verification_code": "",
        "new_password":""        
    }


### Response Body
    {
        "status":"OK"
    }


### Response Code
    HTTP/1.1 200 OK


### Example
```Bash
curl -X POST "http://127.0.0.1:9966/sso/users/email/reset" -d '{"email":"kevin1258@foxmail.com","verification_code":"135272","new_password":"Password120538"}' -i

HTTP/1.1 200 OK
Content-Type: application/json
X-Request-Id: mzqefnzfut867cj3b88einf5ta
X-Version-Id: 4.0.0.dev.53cd9ade63e982a7a4a281bb0c391417
Date: Mon, 05 Dec 2022 07:39:32 GMT
Content-Length: 15
```

```Bash
{"status":"OK"}
```
