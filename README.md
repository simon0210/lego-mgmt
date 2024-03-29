# Project Lego Management


The frontend is generated with [Angular CLI](https://github.com/angular/angular-cli). The backend is made from scratch. Whole stack in [TypeScript](https://www.typescriptlang.org).

프론트 엔드는 [Angular CLI](https://github.com/angular/angular-cli) 로 generate 하였으며 백엔드는 [TypeScript](https://www.typescriptlang.org) 기반으로 기반으로 작성

## [MEAN stack](https://en.wikipedia.org/wiki/MEAN_(software_bundle)):
* [**M**ongoose.js](http://www.mongoosejs.com) ([MongoDB](https://www.mongodb.com)): database - 구현예정
* [**E**xpress.js](http://expressjs.com): backend framework
* [**A**ngular 2+](https://angular.io): frontend framework
* [**N**ode.js](https://nodejs.org): runtime environment

## 사용 라이브러리
* [Angular CLI](https://cli.angular.io): frontend scaffolding
* [Bootstrap](http://www.getbootstrap.com): layout and styles
* [Font Awesome](http://fontawesome.io): icons
* [JSON Web Token](https://jwt.io): user authentication - 구현예정
* [Angular 2 JWT](https://github.com/auth0/angular2-jwt): JWT helper for Angular - 구현예정
* [Bcrypt.js](https://github.com/dcodeIO/bcrypt.js): password encryption - 구현예정

## 필수사항
1. Install [Node.js](https://nodejs.org) and [MongoDB](https://www.mongodb.com)
2. Install Angular CLI: `npm i -g @angular/cli`
3. From project root folder install all the dependencies: `npm i`

## 실행 
### 개발 모드
`npm run dev`: Angular build, TypeScript compiler and Express server.

[localhost:4200](http://localhost:4200) 포트로 브라우저가 변경 사항을 감지하며 프론트 엔드 또는 백엔드 서버의 소스가 변경되면 브라우저는 자동으로 새로고침 된다.

### 운영환경
`npm run prod`: [localhost:3000](http://localhost:3000) 프로덕션 환경용 번들링 및 AOT 빌드후 실행.
