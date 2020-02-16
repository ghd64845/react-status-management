## 리덕스를 사용하여 리액트 애플리케이션 상태 관리하기  

소규모 프로젝트에서는 컴포넌트가 가진 state를 사용하는 것만으로도 충분하지만  
프로젝트의 규모가 커짐에 따라 상태관리가 번거러워질 수 있습니다.  
  
따라서 상태 업데이트에 관한 로직을 모듈로 따로 분리하여 컴포넌트 파일과 별개로 관리할 수 있으므로  
코드를 유지 보수하는 데 도움이 됩니다.

### 작업 환경 설정

```$ yarn create-react-app react-redux-tutorial```

create-react-app을 통해 새로운 리액트 디렉터리 생성

```   
$ cd react-redux-tutorial  
$ yarn add redux react-redux  
```
생성한 디렉터리에 yarn 명령어를 사용하여 redux와 react-redux 라이브러리를 설치

[UI 준비하기](https://github.com/ghd64845/react-status-management/tree/master/src)
