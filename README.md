# `@biko/react-scripts` [![npm version](https://badge.fury.io/js/%40biko%2Freact-scripts@2x.png)]

Create React apps (with Typescript) with no build configuration.

- [Creating an App](#creating-an-app) – How to create a new app.
- [User Guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md) – How to develop apps bootstrapped with Create React App.

_Do you know react and want to try out typescript? Or do you know typescript and want to try out react?_ Get all the benefits from `create-react-app` but you use typescript! 🚀

## tl;dr

```sh
npx create-react-app my-app --scripts-version=@biko/react-scripts
cd my-app
npm start
```

_([npx](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) comes with npm 5.2+ and higher, see [instructions for older npm versions](https://gist.github.com/gaearon/4064d3c23a77c74a3614c498a8bb1c5f))_

Then open [http://localhost:3000/](http://localhost:3000/) to see your app.<br>
When you’re ready to deploy to production, create a minified bundle with `npm run build`.

<p align='center'>
<img src='https://cdn.rawgit.com/facebookincubator/create-react-app/6ab67e6b96457720d843aa3c557ff951a41bafc2/screencast.svg' width='600' alt=''>
</p>

### From `<2.13.0` to `>=2.13.0`

Since `2.13.0`, `typescript` is listed as a peer dependency of `react-scripts-ts`. For projects generated with at least this version, the init script takes care of properly installing it as dev dependency to the generated projects. Older projects require manual installation, in case you have not already done that.

Just create a project, and you’re good to go.

## Creating an App

**You’ll need to have Node >= 6 on your local development machine** (but it’s not required on the server). You can use [nvm](https://github.com/creationix/nvm#installation) (macOS/Linux) or [nvm-windows](https://github.com/coreybutler/nvm-windows#node-version-manager-nvm-for-windows) to easily switch Node versions between different projects.

To create a new app, run a single command:

```sh
npx create-react-app my-app
```

_([npx](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) comes with npm 5.2+ and higher, see [instructions for older npm versions](https://gist.github.com/gaearon/4064d3c23a77c74a3614c498a8bb1c5f))_

Using `yarn`:

```
yarn add -D typescript
```

No configuration or complicated folder structures, just the files you need to build your app.<br>
Once the installation is done, you can open your project folder:

```sh
cd my-app
```

Inside the newly created project, you can run some built-in commands:

### `npm start` or `yarn start`

Runs the app in development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will automatically reload if you make changes to the code.<br>
You will see the build errors and lint warnings in the console.

<img src='https://camo.githubusercontent.com/41678b3254cf583d3186c365528553c7ada53c6e/687474703a2f2f692e696d6775722e636f6d2f466e4c566677362e706e67' width='600' alt='Build errors'>

### `npm test` or `yarn test`

Runs the test watcher in an interactive mode.<br>
By default, runs tests related to files changed since the last commit.

[Read more about testing.](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#running-tests)

### `npm run build` or `yarn build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
By default, it also [includes a service worker](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#making-a-progressive-web-app) so that your app loads from local cache on future visits.

Your app is ready to be deployed.

## User Guide

The [User Guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md) includes information on different topics, such as:

- [Updating to New Releases](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#updating-to-new-releases)
- [Folder Structure](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#folder-structure)
- [Available Scripts](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#available-scripts)
- [Supported Browsers](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#supported-browsers)
- [Supported Language Features and Polyfills](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#supported-language-features-and-polyfills)
- [Syntax Highlighting in the Editor](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#syntax-highlighting-in-the-editor)
- [Displaying Lint Output in the Editor](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#displaying-lint-output-in-the-editor)
- [Formatting Code Automatically](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#formatting-code-automatically)
- [Debugging in the Editor](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#debugging-in-the-editor)
- [Changing the Page `<title>`](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#changing-the-page-title)
- [Installing a Dependency](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#installing-a-dependency)
- [Importing a Component](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#importing-a-component)
- [Code Splitting](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#code-splitting)
- [Adding a Stylesheet](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-a-stylesheet)
- [Post-Processing CSS](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#post-processing-css)
- [Adding a CSS Preprocessor (Sass, Less etc.)](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-a-css-preprocessor-sass-less-etc)
- [Adding Images, Fonts, and Files](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-images-fonts-and-files)
- [Using the `public` Folder](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#using-the-public-folder)
- [Using Global Variables](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#using-global-variables)
- [Adding Bootstrap](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-bootstrap)
- [Adding Flow](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-flow)
- [Adding a Router](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-a-router)
- [Adding Custom Environment Variables](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-custom-environment-variables)
- [Can I Use Decorators?](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#can-i-use-decorators)
- [Fetching Data with AJAX Requests](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#fetching-data-with-ajax-requests)
- [Integrating with an API Backend](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#integrating-with-an-api-backend)
- [Proxying API Requests in Development](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#proxying-api-requests-in-development)
- [Using HTTPS in Development](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#using-https-in-development)
- [Generating Dynamic `<meta>` Tags on the Server](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#generating-dynamic-meta-tags-on-the-server)
- [Pre-Rendering into Static HTML Files](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#pre-rendering-into-static-html-files)
- [Running Tests](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#running-tests)
- [Debugging Tests](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#debugging-tests)
- [Developing Components in Isolation](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#developing-components-in-isolation)
- [Publishing Components to npm](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#publishing-components-to-npm)
- [Making a Progressive Web App](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#making-a-progressive-web-app)
- [Analyzing the Bundle Size](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#analyzing-the-bundle-size)
- [Deployment](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#deployment)
- [Advanced Configuration](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#advanced-configuration)
- [Troubleshooting](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#troubleshooting)

A copy of the user guide will be created as `README.md` in your project folder.

## How to Update to New Versions?

Please refer to the [User Guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#updating-to-new-releases) for this and other information.

Version `2.5.0` introduces a new config file for jest, that is necessary for the tests to run. If you were previously running a version older than `v2.5.0` and upgraded to `v2.5.0` or newer, you need to manually add the new file, or else you'll get an error similar to this when trying to run your tests:

```javascript
Test suite failed to run

{
    "messageText": "Cannot read file 'C:\\[project]\\tsconfig.test.json': ENOENT: no such file or directory, open 'C:\\[project]\\tsconfig.test.json'.",
    "category": 1,
    "code": 5012
}
```

To fix this, create a new file _in the root of the project_ called `tsconfig.test.json`, and paste [the content of this file into it](https://raw.githubusercontent.com/wmonk/create-react-app-typescript/master/packages/react-scripts/template/tsconfig.test.json). Everything should work now. For more info, please see [this issue](https://github.com/wmonk/create-react-app-typescript/issues/141).

## Changelog

### 0.9.0

- Ahora prettier elimina los semicolons al final de las líneas
- Actualizada la plantilla base de ficheros

### 0.8.0

- Añade la posibilidad de añadir nuevos plugins a webpack a través de ficheros en el raiz del proyecto con el nombre: `webpack.config.dev.extension.js` y `webpack.config.prod.extension.js`
  El formato completo de los ficheros se actualiza a:

```
module.exports = {
  getRules: function() {
    return [];
  },
  getPlugins: function() {
    return [];
  },
};
```

Además, con el cambio realizado a partir de ahora los métodos de extension son opcionales y no es obligatorio definirlos si no es necesario.

### 0.7.0

- Añade un transformador para `ts-loader` que, en desarrollo, añade el nombre del componente al nombre del estilo de styled-componented para facilitar su depuración.

### 0.6.0

- Añade la posibilidad de añadir nuevas reglas a webpack a través de ficheros en el raiz del proyecto con el nombre: `webpack.config.dev.extension.js` y `webpack.config.prod.extension.js`
  El formato de los ficheros es:

```
module.exports = {
  getRules: function() {
    return [];
  },
};
```

### 0.5.3

- Nueva opción de configuración para la tarea 'build', llamada 'JS_SOURCEMAPS_ARE_HIDDEN' donde TRUE genera sourcemaps pero no enlazados en los ficheros javascript.

### 0.5.0

- Actualizado a react-scripts v1.1.1
- Nueva configuración para separar en chunks el contenido de "node_modules", la configuración del "manifest" y los common chunks
- Incorporada herramienta para el análisis de los chunks. En la compilación a producción generar un informe en .html

### 0.4.0

- Añadida configuración de Prettier al template
- Añadido soporte para módulos CSS para ficheros `.module.css` y `.module.scss`

### 0.3.1

- Añadido soporte de SASS
- **No Configuration Required:** You don't need to configure anything. Reasonably good configuration of both development and production builds is handled for you so you can focus on writing code.

- **No Lock-In:** You can “eject” to a custom setup at any time. Run a single command, and all the configuration and build dependencies will be moved directly into your project, so you can pick up right where you left off.

## What’s Included?

Your environment will have everything you need to build a modern single-page React app:

- React, JSX, ES6, and Flow syntax support.
- Language extras beyond ES6 like the object spread operator.
- Autoprefixed CSS, so you don’t need `-webkit` or other prefixes.
- A fast interactive unit test runner with built-in support for coverage reporting.
- A live development server that warns about common mistakes.
- A build script to bundle JS, CSS, and images for production, with hashes and sourcemaps.
- An offline-first [service worker](https://developers.google.com/web/fundamentals/getting-started/primers/service-workers) and a [web app manifest](https://developers.google.com/web/fundamentals/engage-and-retain/web-app-manifest/), meeting all the [Progressive Web App](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#making-a-progressive-web-app) criteria.
- Hassle-free updates for the above tools with a single dependency.

Check out [this guide](https://github.com/nitishdayal/cra_closer_look) for an overview of how these tools fit together.

The tradeoff is that **these tools are preconfigured to work in a specific way**. If your project needs more customization, you can ["eject"](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#npm-run-eject) and customize it, but then you will need to maintain this configuration.

## Popular Alternatives

Create React App is a great fit for:

- **Learning React** in a comfortable and feature-rich development environment.
- **Starting new single-page React applications.**
- **Creating examples** with React for your libraries and components.

Here’s a few common cases where you might want to try something else:

- If you want to **try React** without hundreds of transitive build tool dependencies, consider [using a single HTML file or an online sandbox instead](https://reactjs.org/docs/try-react.html).

- If you need to **integrate React code with a server-side template framework** like Rails or Django, or if you’re **not building a single-page app**, consider using [nwb](https://github.com/insin/nwb) or [Neutrino](https://neutrino.js.org/) which are more flexible.

- If you need to **publish a React component**, [nwb](https://github.com/insin/nwb) can [also do this](https://github.com/insin/nwb#react-components-and-libraries), as well as [Neutrino's react-components preset](https://neutrino.js.org/packages/react-components/).

- If you want to do **server rendering** with React and Node.js, check out [Next.js](https://github.com/zeit/next.js/) or [Razzle](https://github.com/jaredpalmer/razzle). Create React App is agnostic of the backend, and just produces static HTML/JS/CSS bundles.

- If your website is **mostly static** (for example, a portfolio or a blog), consider using [Gatsby](https://www.gatsbyjs.org/) instead. Unlike Create React App, it pre-renders the website into HTML at the build time.

- If you want to use **TypeScript**, consider using [create-react-app-typescript](https://github.com/wmonk/create-react-app-typescript).

- Finally, if you need **more customization**, check out [Neutrino](https://neutrino.js.org/) and its [React preset](https://neutrino.js.org/packages/react/).

All of the above tools can work with little to no configuration.

If you prefer configuring the build yourself, [follow this guide](https://reactjs.org/docs/add-react-to-an-existing-app.html).

## Contributing

We'd love to have your helping hand on `create-react-app`! See [CONTRIBUTING.md](CONTRIBUTING.md) for more information on what we're looking for and how to get started.

## React Native

Looking for something similar, but for React Native?<br>
Check out [Create React Native App](https://github.com/react-community/create-react-native-app/).

## Acknowledgements

We are grateful to the authors of existing related projects for their ideas and collaboration:

- [@eanplatter](https://github.com/eanplatter)
- [@insin](https://github.com/insin)
- [@mxstbr](https://github.com/mxstbr)
