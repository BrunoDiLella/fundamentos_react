# Fundamentos React

##

# início
yarn init -y
yarn add react
yarn add react-dom 

##

# Babel

yarn add @babel/core @babel/cli @babel/preset-env -D
babel.config.js
yarn add @babel/preset-react -D 

yarn babel src/index.js --out-file dist/bundle.js

##

# webpack
yarn add webpack webpack-cli webpack-dev-server -D

webpack.config.js

yarn add babel-loader - D
yarn add html-webpack-plugin -D 
yarn add webpack-dev-server -D 

source maps
const isDevelopment = process.env.NODE_ENV !== 'production';

Terminal: NODE_ENV=production webpack

yarn add cross-env -D
scripts packaga.json
##

