# Spring boot - Vue.js 연동하기

Spring boot와 Vue.js가 연동된 간단한 프로젝트입니다.  
연동 과정은 이쪽에 --> <http://febdy.tistory.com/65>


### Version  
Spring boot 2.0.3  
vue.js 2.5.16  
Webpack 3.12.0  
gradle 4.x  
  
  
  

### 폴더 구조

project  
│  
├ src  
│├ main  
││　├ java  
││　└ resources  
│└ test  
│  
├ frontend  
│├ build  
│├ config  
│├ node_modules  
│├  src  
││　├ assets  
││　├ router  
││　├ shared-components  
││　├ spa  
││　├ App.vue  
││　└ main.js  
││  
│├ static  
│├ test  
│├ .bablerc  
│├ .editorconfig  
│├ .eslintingore  
│├ .eslintrc.js  
│├ index.html  
│├ package.json  
│└ package-lock.json  
│  
├ build.gradle  
├ gradlew  
├ gradlew.bat  
└ settings.gradle  


frontend 구조 참고 : <https://github.com/vuejs-kr/vuejs-kr.github.io/issues/28>


### STEP
#### 1. node.js 설치  
<https://nodejs.org/ko/>  
현재(180718) 기준 8.11.3 LTS 설치함.  

#### 2. install
```
$ cd frontend  
$ npm install
```

#### 3. build
```
$ npm run build
```

#### 4. run
spring boot server run  

#### 5. localhost:8888/hi 가서 확인.  