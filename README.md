# TourOfHeroes

Angular 8 [Tutorial Link ](https://angular.io/tutorial)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.1.

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

## Local IIS 

To run this site on your Local IIS, you'll need to:
1.  Install IIS with the URL Rewrite Module.
2.  Use a web.config file to leverage the Angular Router when deploying to a sub-folder in IIS. (Update .angular.json file to include "web.config" under "assets")
3.  Deploy Tour of Heroes to the web root in IIS. (Build Project: ng build --base-href "/FolderName/" --prod)
4.  Deploy Project to a specific sub-folder in IIS using the base-href flag. (wwwroot\FolderName)
5.  Access site in brower: http: //localhost/FolderName/index.html
