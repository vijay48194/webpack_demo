# webpack_demo
adding webpack in dev dependencies
devDependencies are modules which are only required during development, while dependencies are modules which are also required at runtime. To save a dependency as a devDependency on installation we need to do an npm install --save-dev , instead of just an npm install --save.
webpack:
in terminal copy this command
npm install --save-dev webpack
node_modules/.bin/webpack 
webpack

npm install --save-dev webpack-cli(webpack-cli dev dependencies)

npm install --save-dev serve(for installing serve in devdependencies)
serve
node_modules/.bin/serve

npm install --save-dev babel-core babel-loader babel-preset-env ( for installing babel-core babel-loader babel-preset-env)
npm install --save-dev babel-preset-react(for installing bable-preset-react)

Babel is a JavaScript compiler
Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in old browsers or environments.


 npm run watch(npm-watch
Run scripts from package.json when files change.)


For npm run watch
npm run start
npm run build
add following code in package.json in scripts
"scripts": {
    "start": "node_modules/.bin/webpack --w & node_modules/.bin/serve",
    "build": "node_modules/.bin/webpack",
    "watch": "node_modules/.bin/webpack --w"
  },

