# Simple example of how to use install, configure and use webpack version 4

* Initialize yarn
* Install webpack and webpack-cli as dev dependency
* Add build script to package.json
* run yarn build and note error
* Add src folder and index.js file
  * Run yarn build and note it adds a ./dist folder and transpiles index.js to main.js
  * Add bro.js and add code
  * Add code to index.js
  * Add index.html and use default scaffolding
* Add webpack.config.js at root of app
* Add html-webpack-plugin and html-loader as dev dependencies
* Add code to webpack.config.js
* Add webpack-dev-server as dev dependency
* Run website, observe console output
* Add @babel/core, babel-loader, @babel/preset-env
* Add babel rule and exclude to webpack.config.js
* Add images folder, image and img tag to index.html
* Install package file-loader
* yarn build and observe the image file in dist folder
* Add styles folder and main.scss code
* Install packages node-sass, style-loader, css-loader, sass-loader, mini-css-extract-plugin as dev dependencies
* yarn build and note scss code is transpiled into /dist/main,js
* yarn start:dev
