# 프로젝트 생성

npx create-react-app [프로젝트 명] --template typescript[타입스크립트 프로젝트 옵션]
## 프로젝트 구조

public

### src
#### 1.assets 
 - 말 그대로 자산을 의미한다.  
 - 프로젝트에서 사용할 이미지, 비디오, json파일 등 미디어 파일들을 모아두어 저장하는 곳.
#### 2.components
- 공통 컴포넌트 관리 (Header, Footer, Nav 등)
#### 3.pages
- 페이지 단위의 컴포넌트 폴더로 구성
- ex) Login - Login.js, Login.scss / Main - Main.js, Main.scss

💡 `components vs pages`

- 여러 페이지에서 동시에 사용되는 컴포넌트의 경우 components 폴더에서 관리
- 페이지 컴포넌트의 경우 pages 폴더에서 관리
- 해당 페이지 내에서만 사용하는 컴포넌트의 경우 해당 페이지 폴더 하위에서 관리하는 것이 좋음!

- 
- styles
