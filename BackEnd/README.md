# REST API 설정

## 로그인 요청
```
  POST / login
```
### request body
```
  {
    id : string,
    password : string
  }
```
### example
```
  {
    id : "test1234",
    password : "test1234"
  }
```
***
### response body
```
  { 
    state : string,
    access_token : string
  }
```
### example
```
  {
    state : success,
    access_token : "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJ2ZWxvcGVydC5jb20iLCJleHAiOiIxNDg1MjcwMDAwMDAwIiwiaHR0cHM6Ly92ZWxvcGVydC5jb20vand0X2NsYWltcy9pc19hZG1pbiI6dHJ1ZSwidXNlcklkIjoiMTEwMjgzNzM3MjcxMDIiLCJ1c2VybmFtZSI6InZlbG9wZXJ0In0"
  }
```
