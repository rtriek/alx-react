# React intro
## Description:
It doesn't matter where you are, I will find you and I will render you
- How to create a basic Javascript application using React
- How to use the package `create-react-app` to start developing quickly with React
- What JSX is and how to use it
- How to use the React Developer Tools to debug your code
- How to use Enzyme's Shadow rendering to test your application
- How to use React with Webpack & Babel

## Resources:
Read or watch:
- [React Official Website](https://reactjs.org/)
- [Getting started with React](https://www.taniarascia.com/getting-started-with-react/)
- [React overview](https://reactjs.org/docs/getting-started.html)
- [create-react-app](https://github.com/facebook/create-react-app)
- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
- [What is Babel?](https://babeljs.io/docs/en/)
- [Enzyme](https://enzymejs.github.io/enzyme/docs/api/shallow.html)

## Requirements:
- Ubuntu 18.04 LTS using `Node 14.x.x` and `npm 6.x.x`

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
[0. Basic application](./task_0/dashboard/src/App.js)

[1. Embedding expressions, functions](./task_1/dashboard/src/App.js)

[2. Modify the App](./task_2/dashboard/src/App.js)

[3. Modify the Notifications](./task_2/dashboard/src/Notifications.js)

[4. Create basic tests with four tests](./task_3/dashboard/src/utils.test.js)

[5. Install Enzyme](./task_3/dashboard/src/setupTests.js)

[6. Create React tests](./task_3/dashboard/src/App.test.js)

[7. Deploy to a GitHub page](./task_4/)

[8. Create a project using Webpack](./task_5/dashboard/config/webpack.config.js)

[9. Install Babel](./task_5/dashboard/.babelrc)

[10. Reorganize the files](./task_5/dashboard/src/App/App.js)

[11. Testing](./task_5/dashboard/package.json)