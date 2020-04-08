# Authapp

Practical exercise of Udemy course: [Angular: De cero a experto creando aplicaciones (Angular 9+)](https://www.udemy.com/share/101WdsB0sfd1tTRXo=/).

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.6.

## Auth0

Create an account and check more information at [Auth0](https://auth0.com/).

Create a new application there and follow the instructtions in the Quick Start section to configure your proyect. 

As Application type select Single Page Application. Further, put `http://localhost:4200/` in Allowed Callback URLs, Allowed Logout URLs and Allowed Web Origins.

In the Settings section you can find the domain and client_id that you need to indicate in `src/app/services/auth.service.ts` file where requested.

## Install Auth0

Run `npm install @auth0/auth0-spa-js --save` to install Auth0.

## Install dependencies

Run `npm install` to install dependencies.

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
