# React JS from Scratch


### How to run?

- First install npm package

```js
npm install
```

- Start development 

```bash
npm run start:dev
```

- To build 

```bash
npm run build
```

### Steps

- Node package : `package.json` , `npm init`
- Create folder: `public` and `src`
- Supporting ES6: `npm install --save-dev @babel/core @babel/cli @babel/preset-env @babel/preset-react`
- Create `.babelrc` : tells babel transpiler to what preset & plugins to use to transpile our code
- Inside `src` folder create : `index.js`, `App.js` and `App.css`
- Install React and React DOM : `npm install react react-dom`
- Create component `App.js`:
- Add CSS to `App.css`
- Import `App` component from `App.js` into `index.js` and call React DOM render to display in `root` element.
- Install `webpack` and laoder : `npm install webpack webpack-cli webpack-dev-server style-loader css-loader babel-loader`
- Configure `webpack` : 
