# 8oilerplate

## 0. 실행 방법

```bash
yarn install
```

```bash
yarn start
```

## 1. 프로젝트 소개

원티드 프리온보딩 FE 5기 8팀이 빠르게 프로젝트를 시작하기 위한 보일러플레이트

## 2. 구조

```
.
├── assets
│   └── favicon.ico
├── src
│   ├── styles
│   │   └── global.ts
│   ├── App.tsx
│   ├── index.tsx
│   └── template.html
├── webpack
│   ├── paths.js
│   ├── webpack.common.js
│   ├── webpack.dev.js
│   └── webpack.prod.js
├── .babelrc
├── .eslintrc
├── .gitignore
├── .prettierrc
├── README.md
├── package.json
├── tsconfig.json
└── yarn.lock
```

## 3. 핵심 라이브러리

번들러: webpack
트랜스파일러: typescript, babel
프레임워크: react
스타일: styled-component
코드 포매팅: eslint, prettier
