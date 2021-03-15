# 리액트 타입스크립트, 웹팩 기본 설정

- npm init

## 리액트
- npm i react react-dom
## 타입스크립트
- tsconfig.json, tsconfig-for-webpack-config.json 추가
- npm i -D typescript @types/react @types/react-dom @types/webpack @types/node @babel/preset-typescript cross-env ts-node fork-ts-checker-webpack-plugin @types/webpack-bundle-analyzer

## eslint, prettier
- .eslintrc .prettierrc 추가
- npm i -D eslint
- npm i -D prettier eslint-plugin-prettier eslint-config-prettier

## 웹팩설정
- webpack.config.ts 추가
- npm i -D webpack webpack-cli webpack-bundle-analyzer
### 웹팩 데브서버
webpack-dev-server @types/webpack-dev-server @pmmmwh/react-refresh-webpack-plugin react-refresh
## 바벨설정
- npm i -D @babel/core babel-loader @babel/preset-env @babel/preset-react @babel/preset-typescript
### 스타일 관련
- npm i -D style-loader css-loader

