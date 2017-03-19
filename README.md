[![Build Status](https://travis-ci.org/fuse-box/angular2-example.svg?branch=master)](https://travis-ci.org/fuse-box/angular2-example)

### Fuse-box + Angular2

### Angular 2 modern TODO app

This is an example of how to power an Angular2 app with fuse-box.

It's a basic todo application with CRUD operations.

The application uses HOT module reload approach to keep your browser window in sync. 
You will get instant CSS updates as well.


See the working demo [here](https://fuse-box.github.io/angular2-example/)!

#### Setup & run
* `npm install`
* `npm start`
* `npm test`: run tests
* `npm test:auto`: run tests and watch files to re run tests

Visit `http://localhost:4445/`

#### Note
Angular 2 uses `ES6` features that might not work in old browsers, thus it will give you errors. to fix that check this page for adding required polyfills https://angular.io/docs/ts/latest/guide/browser-support.html
