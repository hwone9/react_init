# react_init

## 사용

1. 프로젝트 clone
3. npm install 을 해서 node_modules을 설치한다.
4. npm start해서 화면 열리면 끝~!!!!

## react 초기화

## 1. node.js 설치

terminal에 다음을 입력한 후 버전이 보이면 설치가 완료된 것이다.

> node -v

아무런 정보가 뜨지 않으면 아래 링크에서 설치

https://nodejs.org/en

## 2. 리액트 프로젝트 생성

terminal에 다음을 입력한다.

> npx create-react-app {생성할 프로젝트명}

## 3. 프로젝트 구조

프로젝트를 처음 생성하면 다음과 같은 구조를 가지게 된다.

        ㄴ--- node_modules
        ㄴ--- public
        ㄴ--- src
        .gitignore
        package-lock.json
        package.json
        README.md

### 3-1. 디렉토리 설명

#### 1. node_modules

CRA를 구성하는 모든 패키지 소스 코드가 존재하는 폴더

#### 2. public

index.html을 포함하고 있다.  
가상 DOM을 위한 html 파일(빈 껍데기 파일)  
CRA를 배포했을 때 실제 서버에 배포되는 폴더가 public 폴더이다.

#### 3. src

index.js를 포함하고 있다. 리액트의 시작

#### 4. .gitignore

github에 올리고 싶지 않은 폴더와 파일을 작성

#### 5. package-lock.json

프로그래머가 관리할 필요가 없고 npm이나 yarn이 알아서 관리해주는 파일들.  
lock 파일은 해당 프로젝트에 설치한 패키지, 그 패키지와 관련된 모든 패키지의 버전정보를 포함한다.

#### 6. package.json

CRA 기본 패키지 외 추가로 설치된 라이브러리/패키지 정보(종류, 버전)가 기록되는 파일

#### 7. README.md

## 4. 디렉토리 재구성

현재 재구성된 이 프로젝트의 구조는 다음과 같다.

        ㄴ--- node_modules
        ㄴ--- public
        ㄴ--- src
        .gitignore
        package-lock.json
        package.json
        README.md

삭제한 파일 목록은 다음과 같다.

        src
        ㄴ App.css
        ㄴ index.css
        ㄴ App.test.js
        ㄴ logo.svg
        ㄴ setupTests.js

## 4. 프로젝트 실행

터미널에 다음 명령어를 입력한다.

> npm start
