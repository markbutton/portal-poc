# PortalPoc

Example application utilizing @ngrx libraries, showcasing common patterns and best practices.

This app is a book collection manager. The user can authenticate, use the Google Books API to search for
books and add them to their collection. This application utilizes [@ngrx/db](https://github.com/ngrx/db)
to persist the collection across sessions; [@ngrx/store](https://github.com/ngrx/store) to manage
the state of the app and to cache requests made to the Google Books API;
[@angular/router](https://github.com/angular/angular) to manage navigation between routes;
[@ngrx/effects](https://github.com/ngrx/effects) to isolate side effects.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.5.5.

### Included
 - [@ngrx/store](https://github.com/ngrx/store) - RxJS powered state management for Angular apps, inspired by Redux
 - [@ngrx/effects](https://github.com/ngrx/effects) - Side effect model for @ngrx/store
 - [@angular/router](https://github.com/angular/angular) - Angular Router
 - [@ngrx/db](https://github.com/ngrx/db) - RxJS powered IndexedDB for Angular apps
 - [@ngrx/store-devtools](https://github.com/ngrx/store-devtools) - Instrumentation for @ngrx/store enabling time-travel debugging

## Install

Run `npm install` to install necessary dependencies.

## Authentication

You can sign into the demo app using the username `test` and the password `test`. It's a highly secure app. :thumbsup:

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
