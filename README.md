***

## VisualStudio Code : `Start Angular`

1. `Node js` 설치 `버전 중요`
2. VS Code -> 플러그인
> * Angular Snippets
3. VS Code -> 터미널
* `node --version, npm --version`
4. `npm install -g typescript`
5. `npm install -g @anguular/cli`
6. `ng new my-app`
* ? Do you want to enforce stricter type checking and stricter bundle budgets in t
he workspace? : `n`
* 라이팅 추가 : `y`
* 방향기로 CSS 선택

## 서버 시작

1. VS Code -> 터미널
2. cd my-app
3. `ng serve -open`

## 서버 종료

1. VS Code -> 터미널
2. `Ctrl + C`

## Git 연동

1. git 설치
2. github 레파지토리 생성 - `기본설정`
3. VS Code -> 터미널
4. cd my-app
5. `git init`
6. `git remote add origin [url]`
7. `git add .`
8. `git commit -m "[comment]"`
9. `git push origin master`
* 단계 별로 천천히 진행 추천

***

# MyApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
