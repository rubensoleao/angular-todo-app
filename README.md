# AngularProject

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.9.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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

## json-server config

just add a `db.json` file in the root directory with the content:

```
{
    "tasks": [
        { "id": 1, "text": "Task 1", "day": "Jan 1", "reminder": true },
        { "id": 2, "text": "Task 2", "day": "Jan 2", "reminder": true },
        { "id": 3, "text": "Task 3", "day": "Jan 3", "reminder": true },
        { "id": 4, "text": "Task 4", "day": "Jan 4", "reminder": true }
    ]
}
```

and run yarn server. Your fake api will be at `localhost:5000`.
