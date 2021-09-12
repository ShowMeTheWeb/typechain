# Typechain

## yarn init

## yarn global add typescript

Make New file -> tsconfig.json and typing as below
--------------------------------------------------
{
  "compilerOptions": {
    "module": "commonjs",
    "target": "ES2015",
    "sourceMap": true
  },
  "include": ["index.ts"],
  "exclude": ["noed_modules"]  
}
--------------------------------------------------

## npm i -D @types/node typescript ts-node

Modify package.json as below
--------------------------------------------------
  "scripts": {
    "start": "tsc-watch --onSuccess \" node dist/index.js\" "
  },
--------------------------------------------------  

constructor() 는 메서드이며 클래스가 시작할 때마다 호출됨.

yarn add crypto-js

static method : 클래스가 생성되지 않았어도 호출할 수 있음.
