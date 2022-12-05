# login
    
### Url
    /sso/users/login
    
### Method
    POST

### Request Payload
    {
        "login_id":"1215894562@qq.com",
        "password":"kevin***1258"
    }

### Response Body
    {
        "id": "kyj99bt16ifimb973cbyegcs5o",
        "create_at": 1513171527086,
        "update_at": 1513171745524,
        "delete_at": 0,
        "username": "heskenmmy",
        "gender": "",
        "auth_service": "",
        "email": "1215894562@qq.com",
        "email_verified": true,
        "nickname": "lemnemynice",
        "first_name": "",
        "last_name": "",
        "position": "",
        "roles": "normal_user",
        "allow_marketing": true,
        "last_password_update": 1513171745524,
        "locale": "zh-CN",
        "mobile": "15727546130",
        "doctor_id": "",
        "region": "",
        "address": "",
        "birthDate": 0
    }
    
### Response Code
    HTTP/1.1 200 OK

### Example
```Bash
curl -X POST  "http://127.0.0.1:9966/sso/users/login"  -i -d '{"login_id":"kevin1258@foxmail.com","password":"Password120538"}'
HTTP/1.1 200 OK
Content-Type: application/json
Set-Cookie: AUTHTOKEN=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyX2lkIjoiZHpzajNzcmI3amc1ajhkdzZiYjY0cm10bXIiLCJyb2xlcyI6Im5vcm1hbF91c2VyIiwicHJvcHMiOnsiYnJvd3NlciI6ImN1cmwvNy42OC4wIiwib3MiOiJ1bmtub3duIiwicGxhdGZvcm0iOiJ1bmtub3duIn0sImV4cCI6MTY3MTk1NDEzMiwiaWF0IjoxNjcwMjI2MTMyfQ.u1FNxAXPSug9df8f20sUQQiZC_awPhN4ceMG8Ty9T5w; Path=/; Expires=Sun, 25 Dec 2022 07:42:12 GMT; Max-Age=1728000; HttpOnly
Set-Cookie: USERID=dzsj3srb7jg5j8dw6bb64rmtmr; Path=/; Expires=Sun, 25 Dec 2022 07:42:12 GMT; Max-Age=1728000
Token: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyX2lkIjoiZHpzajNzcmI3amc1ajhkdzZiYjY0cm10bXIiLCJyb2xlcyI6Im5vcm1hbF91c2VyIiwicHJvcHMiOnsiYnJvd3NlciI6ImN1cmwvNy42OC4wIiwib3MiOiJ1bmtub3duIiwicGxhdGZvcm0iOiJ1bmtub3duIn0sImV4cCI6MTY3MTk1NDEzMiwiaWF0IjoxNjcwMjI2MTMyfQ.u1FNxAXPSug9df8f20sUQQiZC_awPhN4ceMG8Ty9T5w
X-Request-Id: 6wj8tfostfrsjbak79x3azmzir
X-Version-Id: 4.0.0.dev.53cd9ade63e982a7a4a281bb0c391417
Date: Mon, 05 Dec 2022 07:42:12 GMT
Content-Length: 393
```

```Bash
{"id":"dzsj3srb7jg5j8dw6bb64rmtmr","create_at":1670225693785,"update_at":1670225972037,"delete_at":0,"username":"test12051532","gender":"","auth_service":"","email":"kevin1258@foxmail.com","email_verified":true,"nickname":"test12051532","first_name":"","last_name":"","position":"","roles":"normal_user","allow_marketing":true,"last_password_update":1670225972037,"locale":"zh-CN","mobile":""}
```
