# REST API 설정

## 로그인 요청
### url
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
### response body
```
  {
    access_token : string
  }
```
