# SEO friendly Angular 5 application using Server Side Rendering with AOT

## Developed By:
Ritwik banerjee

### Note:

This repo is still in progress. It uses Angular 5 and Node Express as the server set up

## Build
 After cloning the copy, hit npm install
 Following that, to check if everything works just fine, 
 run:

 `ng build -prod --build-optimizer --app 0 ng build --aot --app 1`

 If nothing breaks in this step, go ahead and hit 
 `npm run build && node dist/server.js`

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## TODO:
* Implement lazy loading
* Use webpack dev server for constant updation during development
* Integrate a third party CSS framework
* Implement any 1 auth module

## Further help

Reach out to me @ ritwik2011@gmail.com
