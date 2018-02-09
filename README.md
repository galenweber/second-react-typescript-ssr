`cd` into the project directory, and initialize a new project.

```js
// npm init
yarn init
```

Scaffold out the directory structure.
```js
mkdir src
cd src
mkdir components
cd ..
```

Install webpack locally. Webpack will be serving as our bundler.
```js
yarn add --dev webpack
```
Install React and React-DOM, together with type declaration files
```js
yarn add react react-dom
```
Add the corresponding typings files for the two libraries.
```js
yarn add --dev @types/react @types/react-dom
```

Add in Typescript and associated libraries as dev dependencies.
```js
yarn add --dev typescript awesome-typescript-loader source-map-loader
```
