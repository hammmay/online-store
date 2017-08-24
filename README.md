# OnlineStore

* This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0.

## Setup Instructions
|Enter these commands in your console|
|---|
|1.) Clone project from github|
|2.) Navigate to the project folder|
|3.) In the console: npm install|
|4.) In the console: bower install bootstrap --save|
|5.) Create a api-keys.ts file within the src/app/ folder|
|6.) Place this code in the api-keys.ts file and replace the "x" characters with your own credentials from your own firebase app code:
* export var masterFirebaseConfig = {
*    apiKey: "xxxx",
*    authDomain: "xxxx.firebaseapp.com",
*    databaseURL: "https://xxxx.firebaseio.com",
*    storageBucket: "xxxx.appspot.com",
*    messagingSenderId: "xxxx"
*  };|
|7.) In the console: ng serve|
|8.) (optional) If the build is unsuccessful and you see a "polyfill" error, run this in the console before trying the ng serve command again: npm install promise-polyfill --save-exact|
|9.) Navigate to http://localhost:4200/|

## System Requirements

* npm 3 or higher
* bower
* Firebase Account

## Build

* Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

* Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

* Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.
