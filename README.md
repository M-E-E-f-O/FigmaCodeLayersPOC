# FigmaCodeLayers

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.3.10.

## Icons

Use Google Material Symbols for UI icons instead of inline SVGs. The
`material-symbols` npm dependency provides the outlined font, loaded globally
from `src/styles.scss` and bundled locally without requests to Google Fonts.
Run `npm install` after cloning to install it along with the other dependencies.

Use the icon name as text inside a `material-symbols-outlined` span:

```html
<button type="button" aria-label="Search">
  <span class="material-symbols-outlined" aria-hidden="true">search</span>
</button>
```

Hide decorative icons from assistive technology with `aria-hidden="true"` and
give icon-only buttons an accessible name. Find icon names in the
[Material Symbols catalog](https://fonts.google.com/icons).

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

MEEfO test