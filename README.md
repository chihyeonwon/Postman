# Postman
[Postman] Postman을 이용한 RESTful API 테스팅
```
Postman을 이용하면 간단하게 RESTful API를 테스트할 수 있다.
또 테스트를 저장해 API 스모크 테스팅용으로 사용할 수 있다.
```
## Postman 설치
[Postman 설치](https://www.postman.com/downloads/)
![image](https://github.com/mr-won/Postman/assets/58906858/b3c9bf29-9cce-4271-9e72-a58a76577067)
```
로그인 없이도 포스트맨을 사용할 수 있다.
+ 버튼을 누르고 www.google.com 홈페이지에 HTTP GET 요청을 날린 결과이다.
```
![image](https://github.com/mr-won/Postman/assets/58906858/2b9d469f-0b73-4ca7-87e5-3c7171719b16)
```
작성중인 springboot 어플리케이션을 실행한 후 포스트맨을 이용해서 localhost:8080 HTTP GET 요청을 보낸 결과이다.
```
![image](https://github.com/wonchihyeon/Postman/assets/58906858/870eb8a4-9d4b-496b-8150-4a57d98788a2)
![image](https://github.com/wonchihyeon/Postman/assets/58906858/bcd0d731-a899-4d74-9d66-02bbe8efb2cd)
```
오브젝트를 JSON 형태의 문자열의 요청 바디로 사용한 결과이다.
```
## 200 OK
![image](https://github.com/wonchihyeon/Postman/assets/58906858/f1c6ea72-3c68-488f-87f4-9b85860e0e08)
![image](https://github.com/wonchihyeon/Postman/assets/58906858/2e1149db-0a56-4cf4-86e8-54721937cb14)

## 400 Bad Request
![image](https://github.com/wonchihyeon/Postman/assets/58906858/439b39fc-243d-4969-b0af-c59f3ff1dd48)
![image](https://github.com/wonchihyeon/Postman/assets/58906858/a6bae42e-4652-48f9-b9d3-6ff5b7d74aa0)
```
@ResponseEntity를 사용하여 http status를 각각 200과 400으로 조작하여 http get 요청을 보낸 결과이다.
```
