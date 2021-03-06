# QuoteApp

[![DeepScan grade](https://deepscan.io/api/teams/7984/projects/10118/branches/135987/badge/grade.svg)](https://deepscan.io/dashboard#view=project&tid=7984&pid=10118&bid=135987)
[![Maintainability](https://api.codeclimate.com/v1/badges/28cd30bed8aafba2330d/maintainability)](https://codeclimate.com/github/boale/ngQuote/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/28cd30bed8aafba2330d/test_coverage)](https://codeclimate.com/github/boale/ngQuote/test_coverage)

Angular-based Quote generator with all necessary CI/CD configurations. 

Also it has basic integrations with Ngrx or Ngxs stores (see `feature/ngrxStore` or `feature/ngxsStore` respectively). 

###TODO:

- add e2e test
- add test coverage to reach required threshold
- add integration with: 
  - codecov.io (https://codecov.io/gh/boale/ngQuote) for test coverage reports
  - codeclimate.com (https://codeclimate.com/github/boale/ngQuote) for test coverage reports
- configure AWS CI/CD pipelines:
    - add build specs
    - add cloudformation.yaml files
    - release
    - deploy

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.
Use the `--prod` flag for a production build or `npm run build:prod` command.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
