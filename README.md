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

auth.js

![image](https://github.com/user-attachments/assets/c8e12ae5-f0d8-41e2-b9cc-9fe9c1014e38)

index.js

![image](https://github.com/user-attachments/assets/90367959-bf9c-4423-b7a3-fb0e3d332799)

## 로그아웃 기능 만들기

index.js

![image](https://github.com/user-attachments/assets/a1da9bd5-bab6-4852-bf92-bca1a3788a05)

포스트맨으로 로그인을 한다.

![image](https://github.com/user-attachments/assets/eb519636-8587-4f0d-a045-3ee5e7e7842a)

몽고db에 토큰이 들어왔다.

![image](https://github.com/user-attachments/assets/55238607-aafd-40df-abd8-92490b36be4c)


포스트맨으로 로그아웃을 한다.

![image](https://github.com/user-attachments/assets/42ca14e5-0e9a-4767-8d64-84da86db9e71)

몽고db에 토큰이 삭제됨.

![image](https://github.com/user-attachments/assets/2a855ecf-b61d-4605-9268-8ebf8808d5cf)

## 리액트란?

2013년도에 발표된 페이스북에서 만든 라이브러리

컴포넌트로 이루어져 재사용성이 뛰어남.

virtual dom을 사용함.

## Create-React-App

npm uninstall -g create-react-app (리액트 앱 제거)

npm install -g create-react-app (리액트 앱 재설치)

npx create-react-app [app-name] (리액트 앱 실행)

## npm npx

npm의 역할

bcrypt,body-parser,mongoose 등 라이브러리를 담고있는 레지스트리

파일 빌드할때도 사용한다.

global로 다운하면 공간을 차지함.

npx의 장점

디스크 스페이스를 낭비하지않을 수 있다.

항상 최신 버전을 사용할 수 있다.

# 리액트 구조 설명

src에 이미지파일을 넣어야함. 그래야 웹팩 가능

## boierplate 폴더 정리

![image](https://github.com/user-attachments/assets/ad968f88-4225-430a-822d-daeed4af0a54)


## React Router Dom

npm i react-router-dom@6

![image](https://github.com/user-attachments/assets/36658366-75b2-4d9c-aa79-94b864c8d7ec)

## 데이터 Flow & Axios

request할때 지금까지는 client 부분이 없었기에 포스트맨을 이용했음.

이제는 있으니깐 React JS부분에서 request를 보내면 되는데 그때 사용할게 axios

jQuery를 사용할때 AJAX라고 보면됨.

npm install axios --save

## CORS 이슈, Proxy 설정

npm install http-proxy-middelware --save

./src/setupProxy.js

![image](https://github.com/user-attachments/assets/6142c488-c598-43f6-b70e-77bbd98127e5)

## Proxy Server?

1.아이피를 프록시 서버에서 임의로 바꿔 버릴 수 있다.

2. 보내는 데이터도 임의로 바꿀 수 있다.

3. 방화벽 기능

4. 웹필터 기능

5. 캐쉬 데이터, 공유 데이터 제공 기능

## Concurrently

npm install concurrently --save

![image](https://github.com/user-attachments/assets/4865e4f8-22d2-44bd-b22b-6511090c39b7)

npm run dev

## Antd CSS Framwork

npm install antd --save

![image](https://github.com/user-attachments/assets/b24d6925-1f2b-4854-95d0-71662917d132)

## Redux 기초

상태 관리 라이브러리

npm install redux react-redux redux-promise redux-thunk --save

client/ index.js
![image](https://github.com/user-attachments/assets/6a2a91e3-eb19-4ff4-8fde-58feaefc13a8)

client/_reducers/index.js
![image](https://github.com/user-attachments/assets/e8fce6dc-2044-4ce8-b9e6-36d88fed16c8)

## React Hooks

class component 

기능이 많고 코드가 길어지고 복잡하고 성능면에서 느려진다.

functional component

제공하는 기능이 한정적이고 코드가 짧고 간단하고 성능면에서 빠르다.

react hook으로 functional component를 기능이 많게 사용가능

