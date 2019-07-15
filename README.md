# Habitify 
- An app for creating new habits and managing old habits

# Tools Required
- Visual Studio Code
- Node >= 8.10
- npm >= 5.6
- Google Chrome
- React Developer Tools (a Google Chrome Extension for debugging)

# To Start:
1. Fork repository
2. In terminal, check to make sure that Node >= 8.10 and npm >= 5.6
    - for node: node -v
    - for npm: npm -v
    - If you need to upgrade either version see specific section below.
2. In terminal, navigate to the directory and type in: npm start
3. This will start a dev server at port `local:3000`
4. Open habitify in `Visual Studio Code`

# Hello World
1. To write your first JSX app, open `App.js`
2. Change the JSX to `<h1>Hello, World</h1>`
3. Upon saving the file, you will see the local page display 'Hello, World'

# Upgrading Node/NPM
Node comes with npm pre-installed, but the manager is updated more frequently than Node. Run `npm -v` to see which version you have, then `npm install npm@latest -g` to install the newest npm update. Run `npm -v` again if you want to make sure npm updated correctly.

To update Node, you’ll need npm’s handy n module. Run this code to clear npm’s cache, install n, and install the latest stable version of Node:

```
1. sudo npm cache clean -f
2. sudo npm install -g n
3. sudo n stable
```

To install the latest release, use `n latest`. Alternatively, you can run `n #.#.#` to get a specific Node version.

# Standard React App 

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
