# Aiagent

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.0.7.

nvm install v22.13.0

nvm use v22.13.0

npm install -g @angular/cli

ng new aiagent --routing --style scss --skip-install --skip-git --strict --ssr
Would you like to use the Server Routing and App Engine APIs (Developer Preview) for this server application? No

ng add @angular/pwa

ng add @angular/fire@19.0.0-rc.5 
What features would you like to setup? Authentication, Google Analytics, Firestore, Realtime Database, Performance Monitoring
Which Firebase account would you like to use? wpbest@gmail.com
Please select a project: AiAgent
Please select an app: aiagentbe

ng add @angular/material
Choose a prebuilt theme name, or "custom" for a custom theme: Azure/Blue
Set up global Angular Material typography styles? yes
Include the Angular animations module? Include and enable animations

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
