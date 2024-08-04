# Node JS와 EXPRESS JS 다운로드 하기

## node js 다운받기

![image](https://github.com/user-attachments/assets/34914e95-0fc2-4024-a2e2-1aa9d99b1ced)

버전확인

node -v

프로젝트 폴더에서

npm init

## express js 다운받기

npm install express --save

node 실행

npm run start

## 몽고 DB 연결

몽고 DB 사이트에서 회원가입 및 로그인하기

클러스터 만들기

## mongoose 다운로드

npm install mongoose --save

index.js

![image](https://github.com/user-attachments/assets/cb6a04e8-bbad-4138-838a-83ea3cd73fbe)

## MongoDB model & schema

model은 schema를 감싸주는 역할

![image](https://github.com/user-attachments/assets/8994d6fa-ba0a-49f3-970d-3f518e6774b4)

## Git 설치

git init

git add .

node 모듈은 굳이 깃허브에 올릴필요가 없다. npm install하면 되기 때문에

이미 add를 했다면 git rm --cached node_modules -r

## Github 연결

SSH로 연결

윈도우 환경은 깃배쉬에서 해야함.

복잡하니 구글링해서 한다.

## PostMan & 회원 가입 기능

포스트맨 다운받기

회원 가입 

![image](https://github.com/user-attachments/assets/41044612-f0d4-4199-b42e-689c44477baa)

![image](https://github.com/user-attachments/assets/fb0e9a96-f9d7-410c-a5c1-24caad2b3603)

![image](https://github.com/user-attachments/assets/c690e4de-0c82-426a-8bf4-96b45ca8700c)

몽고 db에 들어감

![image](https://github.com/user-attachments/assets/9fe7d171-7feb-418a-be7e-dec8b1d41079)


## Nodemon 설치

nodemon - 소스를 변경할때 그걸 감지해서 자동으로 서버를 재시작해주는 tool

nodemon 설치

npm install nodemon --save-dev (-dev는 로컬에만 쓰겠다)

![image](https://github.com/user-attachments/assets/05e13435-2522-41e9-9200-b2207c5ccdb2)

![image](https://github.com/user-attachments/assets/3c7d4dfe-a12f-4edc-9682-743124be7efa)

## 비밀 설정 정보 관리

로컬과 배포 관리를 따로한다.

![image](https://github.com/user-attachments/assets/9ba17878-2b48-4a96-bf58-51f742c0c55d)

로컬

![image](https://github.com/user-attachments/assets/cc39f298-b82f-420f-905f-b3f129f30bac)

배포

![image](https://github.com/user-attachments/assets/ff3b90f6-041d-4ded-af16-c38b3d2d10bb)


![image](https://github.com/user-attachments/assets/b28780d9-c446-4c8c-994e-eebcaf9d4178)

![image](https://github.com/user-attachments/assets/6ea657be-a0aa-41f8-a289-ac91dbea5be6)

깃허브 올릴때도 비밀 설정 정보 관리

![image](https://github.com/user-attachments/assets/c407c17e-472e-413f-a9de-c31e0f05c552)

## Bcrypt로 비밀번호 암호화 하기

Bcrypt다운받기

npm install bcrypt --save

![image](https://github.com/user-attachments/assets/31905b35-a9f0-4eaf-adb7-efc22d60b28f)

![image](https://github.com/user-attachments/assets/6ce3c7ed-3869-4d89-94e9-a855ad917d07)

## 로그인 기능 with Bcrypt

jsonwebtoken 다운받기

npm install jsonwebtoken --save

cookie-parser 다운받기

npm install cookie-parser --save

![image](https://github.com/user-attachments/assets/fe781f18-5eaf-4890-809c-05a75cb14ccd)

![image](https://github.com/user-attachments/assets/02293001-6771-4e71-a8f4-b19149618467)


로그인 완료

![image](https://github.com/user-attachments/assets/590478b1-0d35-4e65-ae0b-f74d59212fb8)

## Auth 기능 만들기

