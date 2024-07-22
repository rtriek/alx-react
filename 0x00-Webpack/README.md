# Webpack
## Description:
Brace yourselves, Webpack is comming
- How to setup Webpack for a basic project
- Entry points, output, and loaders
- How to add plugins
- How to split your code into chunks
- How to setup a dev server

## Resources:
Read or watch:
- [Webpack documentation](https://webpack.js.org/concepts/)
- [Webpack beginner guide](https://www.sitepoint.com/webpack-beginner-guide/)
- [npm-package.json](https://docs.npmjs.com/cli/v7/configuring-npm/package-json)
- [Debounce documentation on Lodash](https://lodash.com/docs/#debounce)

## Requirements:
- Ubuntu 18.04 LTS using Node 12.x.x

### Install NodeJS 12.22.x
```console
$ curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
$ sudo bash nodesource_setup.sh
$ sudo apt install nodejs -y
```

### Check version
```console
$ nodejs -v
v12.22.1
$ npm -v
6.14.12
```

## Files:

[0. Basic setup](./task_0/src/index.js)

[1. Learning how to use Webpack with a config file](./task_1/js/dashboard_main.js)

[2. Adding CSS & Images](./task_2/js/dashboard_main.js)

[3. Dev servers, modules, and tree shaking](./task_3/webpack.config.js)