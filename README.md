# Form runner

This project is a PoC for an example forms runner/viewer application using [Angular](https://angular.io/) 
and [Form IO](https://github.com/formio/angular).

The application is primarily based-off example project that is created using the [Angular CLI](https://angular.io/cli#basic-workflow).  

In the main `src/app/app.component.html` template, a form is embedded using the Form IO rendering library.

i.e.
```html
<div class="card-container">
  <div class="card-body">
    <h5 class="card-title">Result</h5>
    <div class="bg-light p-3">
      <formio src='https://examples.form.io/example'></formio>
    </div>
  </div>
</div>
```

## Getting started

Run `npm install && npm start` to install all dependencies and build the project.

When the application has compiled and is successfully running, you should see the following line in your build console:

> ** Angular Live Development Server is listening on localhost:4200, open your browser on http://localhost:4200/ **

Navigate to [http://localhost:4200/](http://localhost:4200/) to access the application in your browser.

The build artifacts will be stored in the `dist/` directory.

The application will automatically reload if you change any of the source files.

### Changing the embedded form
By default, the form viewed with be the example form found at [https://examples.form.io/example](https://examples.form.io/example).

This can be easily changed by modifying the following line in `src/app/app.component.html`:

`<formio src='https://examples.form.io/example'></formio>`

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).
