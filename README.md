# Documentation

Webapp Was Built In:

 * ReactJS
 * Redux
 * Webpack 4 
 * Babel 7
 * React Material UI
 * Bootstrap 4 
 * HMR
 * Code Splitting
 * Code Formatter (Prettier)
 * Eslint configured extended with Airbnb style guide & support for prettier


### Tutorials

Things I did while setting up the boiler plate for this code base, I wrote it all down in a series of articles

* <del>https://medium.freecodecamp.org/how-to-conquer-webpack-4-and-build-a-sweet-react-app-236d721e6745</del>
* https://medium.freecodecamp.org/how-to-combine-webpack-4-and-babel-7-to-create-a-fantastic-react-app-845797e036ff


### Deploying a Node Instance On Linux Server Using PM2

 How to start on PM2 [This is specific if you serve your files on a linux server where a NodeJS application is deployed as a server serving the .js files

```
 npm i
 node_modules/.bin/webpack --config webpack.prod.config.js --colors --progress
 node server
 PORT=8082 pm2 start server --name "app-name-to-deploy"
```