## 리덕스를 사용하여 리액트 애플리케이션 상태 관리하기

### 작업 환경 설정

```$ yarn create-react-app react-redux-tutorial```

create-react-app을 통해 새로운 리액트 디렉터리 생성

```   
$ cd react-redux-tutorial  
$ yarn add redux react-redux  
```
생성한 디렉터리에 yarn 명령어를 사용하여 redux와 react-redux 라이브러리를 설치

###### Prettier을 작성 하고 싶으면 최상위 경로에 .prettier파일을 작성
```  
{  
  "singleQuote":true,  
  "semi": true,  
  "useTabs": false,  
  "tabWidth": 2,  
  "trailingComma": "all",  
  "printWidth": 80  
 }
