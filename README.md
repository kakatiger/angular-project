# angular-project

> 该项目是以angular-cli为基础开发的。 [angular-cli](https://github.com/angular/angular-cli) version 2.0.0-beta.28.3.

> NODE版本最好小于node: "<8.0.0"

## 项目结构以及说明

> 创建项目结构;

> src/util 这主要为项目配置文件夹。
目前包括本地环境监测util.config.ts;
远程API请求的封装

> src/common/components 公共组件库
例如:src/common/components/model 为一个模态框组件

> src/api  主要存放每个模块的请求api接口。
例如:api.user.ts 则为用户模块的接口

> angular UI库的添加
本案例使用material UI库进行演示开发

> 基本路由的配置,将公共路由提出到router.ts文件

> 静态公共资源库src/assets

## npm install
> 启动项目前,请确保安装了npm包。

> 因为该依赖是最新的,所以如果包安装不对,可能会报错,一般情况下执行命令即刻解决:
npm install @angular/common@latest @angular/compiler@latest @angular/compiler-cli@latest @angular/core@latest @angular/forms@latest @angular/http@latest @angular/platform-browser@latest @angular/platform-browser-dynamic@latest @angular/platform-server@latest @angular/router@latest @angular/animations@latest typescript@latest --save

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.
