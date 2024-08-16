# Stack

![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

# Stack scheme

![Stack scheme](image.png)

# Database

## (ye, it's kinda cringe)

![Database (ye, it's kinda cringe)](image-1.png)

# Forms

## Login & Registration

![Login](image-2.png) ![Reg](image-3.png)

## Main with products

![Main. Products](image-4.png)

## Sort by search and cats

![Sort](image-5.png)

## Cart

![Cart](image-6.png)

## Orders

![Orders](image-7.png)

## Admin Menu

![Admin Menu](image-8.png)

## CRUD

![CRUD-1 (Edit Table)](image-9.png)

![CRUD-2 (Show Table)](image-10.png)
![CRUD-2 (Show Table)](image-11.png)

# FirstApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.4.

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

## Packages u'll needed: (via pip install)

`SQLAlchemy 2.0.23`
`mysql-connector-python 8.2.0`
`Flask 3.0.0`
`Flask-Cors 4.0.0`
`Flask-RESTful 0.3.10`
`Flask-SQLAlchemy 3.1.1`

## Also u need 'npm concurrently'

`npm install concurrently`

# Start flask & angular

`npm run start:both`

# From package json

"start:angular": "ng serve",
"start:flask": "cd Server_Flask && python app.py",  
"start:both": "concurrently \"npm run start:angular\" \"npm run start:flask\""
