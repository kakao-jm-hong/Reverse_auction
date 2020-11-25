# REST API 설정

## 로그인
```
  POST / login
```
### request body
```
  {
    userid : string,
    password : string
  }
```
### example
```
  {
    userid : "test1234",
    password : "test1234"
  }
```
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
    state : "success",
    access_token : "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJ2ZWxvcGVydC5jb20iLCJleHAiOiIxNDg1MjcwMDAwMDAwIiwiaHR0cHM6Ly92ZWxvcGVydC5jb20vand0X2NsYWltcy9pc19hZG1pbiI6dHJ1ZSwidXNlcklkIjoiMTEwMjgzNzM3MjcxMDIiLCJ1c2VybmFtZSI6InZlbG9wZXJ0In0"
  }
```
##  회원가입
```
  POST / join
```
### request body
```
  {
    userid : string,
    password : string,
    name : string,
    age : int,
    nickname : string,
    email : string,
    address : string
  }
```
### example
```
  {
    userid : "test1234",
    password : "test1234",
    name : "홍길동",
    age : 19,
    nickname : "redbin",
    email : "test1234@gmail.com",
    address : "서울특별시 강남구 서초동 한빛 APT 101, 1024"
  }
```
### response body
```
  { 
    state : "success"
  }
```
### example
```
  {
    state : success,
  }
```
