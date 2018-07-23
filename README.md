# AngularLoginHideNavbar

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Steps

1. create app

ng new angular-login-hide-navabar-if --routing --style=scss

2. create components
ng g m app-material
ng g s auth/auth --module=app.module
ng g g auth/auth --module=app.module
ng g i auth/user
ng g c header -is
ng g c home -is -it
ng g c login

3. install angular material

npm install --save @angular/material @angular/cdk
npm install --save @angular/animations

4. imports to app.module.ts
5. link
https://loiane.com/2017/08/angular-hide-navbar-login-page/
