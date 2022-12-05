# signupByEmail 
    

### Url
    /sso/users/email/signup

### Method
    POST

### Request Payload
	{
		"username":"heotest",
		"nickname":"mynice",
		"password":"12345678",
		"verification_code": "164285",
		"email":"1215894562@qq.com"
	}


### Response Body
  {
      "id": "gi6z9anrf7y9tqapirfpofs3uy",
      "create_at": 1512562562530,
      "update_at": 1512562562530,
      "delete_at": 0,
      "username": "heotestfdsaf",
      "gender": "",
      "auth_data": "",
      "auth_service": "",
      "email": "1215894562@qq.com",
      "nickname": "mynice",
      "first_name": "",
      "last_name": "",
      "position": "",
      "roles": "normal_user",
      "allow_marketing": true,
      "notify_props": {
          "channel": "true",
          "desktop": "all",
          "desktop_sound": "true",
          "email": "true",
          "first_name": "false",
          "mention_keys": "heotestfdsaf,@heotestfdsaf",
          "push": "mention"
      },
      "last_password_update": 1512562562530,
      "locale": "zh-CN",
      "mobile": "",
      "doctor_id": "",
      "region": "",
      "address": "",
      "birthDate": 0
  }

### Response Code
    201 Created

### Example 
```Bash
curl -X POST  "http://127.0.0.1:9966/sso/users/email/signup"  -i -d '{"username":"test12051532","nickname":"test12051532","password":"Test12051532","verification_code": "631318","email":"kevin1258@foxmail.com"}'

HTTP/1.1 201 Created
Content-Type: application/json
Set-Cookie: AUTHTOKEN=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyX2lkIjoiZHpzajNzcmI3amc1ajhkdzZiYjY0cm10bXIiLCJyb2xlcyI6Im5vcm1hbF91c2VyIiwicHJvcHMiOnsiYnJvd3NlciI6ImN1cmwvNy42OC4wIiwib3MiOiJ1bmtub3duIiwicGxhdGZvcm0iOiJ1bmtub3duIn0sImV4cCI6MTY3MTk1MzY5MywiaWF0IjoxNjcwMjI1NjkzfQ.z0gSqVleaChVMPfssIa_4tkdv0Xl-BvJzuNcs_eML9k; Path=/; Expires=Sun, 25 Dec 2022 07:34:53 GMT; Max-Age=1728000; HttpOnly
Set-Cookie: USERID=dzsj3srb7jg5j8dw6bb64rmtmr; Path=/; Expires=Sun, 25 Dec 2022 07:34:53 GMT; Max-Age=1728000
Token: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyX2lkIjoiZHpzajNzcmI3amc1ajhkdzZiYjY0cm10bXIiLCJyb2xlcyI6Im5vcm1hbF91c2VyIiwicHJvcHMiOnsiYnJvd3NlciI6ImN1cmwvNy42OC4wIiwib3MiOiJ1bmtub3duIiwicGxhdGZvcm0iOiJ1bmtub3duIn0sImV4cCI6MTY3MTk1MzY5MywiaWF0IjoxNjcwMjI1NjkzfQ.z0gSqVleaChVMPfssIa_4tkdv0Xl-BvJzuNcs_eML9k
X-Request-Id: m446fjdkk78ruqp1tp8hg137hw
X-Version-Id: 4.0.0.dev.53cd9ade63e982a7a4a281bb0c391417
Date: Mon, 05 Dec 2022 07:34:53 GMT
Content-Length: 334
```

```JSON
{"id":"dzsj3srb7jg5j8dw6bb64rmtmr","create_at":1670225693785,"update_at":1670225693785,"delete_at":0,"username":"test12051532","gender":"","auth_service":"","email":"kevin1258@foxmail.com","nickname":"test12051532","first_name":"","last_name":"","position":"","roles":"normal_user","allow_marketing":true,"locale":"zh-CN","mobile":""}
```
