<h1 align="center">
<img src="src/assets/logo.png"
alt="GoMarketplace"/>
</h1>

<p align="center">A marketplace application where you can view the products for sale, their price and the shopping cart with the total products and the total price.</p>

<p align="center" color="">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/pjavier98/gomarketplace">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/pjavier98/gomarketplace">

  <a href="https://github.com/pjavier98/gomarketplace/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/pjavier98/gomarketplace">
  </a>

  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>

  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="License MIT">
  </a>
</p>

<hr />
<div style="display: flex; flex-direction: row; align-items: center; justify-content: center;">
  <img style="margin-right: 30px"src="src/assets/GoMarketplace/dashboard.png" alt="Dashboard"/>
  <img src="src/assets/GoMarketplace/cart.png" alt="Dashboard"/>
</div>

## Features

This app features all the latest tools and practices in web development!

- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [JSON Server](https://github.com/typicode/json-server)
- [Styled Components](https://styled-components.com/)
- [React Navigation](https://reactnavigation.org/)
- [Async Storage](https://github.com/react-native-community/async-storage)
- [Axios](https://github.com/axios/axios)
- [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)
- [Jest](https://jestjs.io/)

**Lint:**
- [Eslint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [EditorConfig](https://editorconfig.org/)

## Getting started

### Requirements
* Node.js
* Yarn
* Emulator from Android or iOS

**Clone this repo using:**
```
$ git clone https://github.com/pjavier98/gomarketplace.git
```
**Move to the appropriate directory:**
```
$ cd gomarketplace

# Install the dependencies
$ yarn

# Run the JSON Server
$  yarn json-server server.json -p 3333

# Inicialize the emulator or connect a Android or iPhone

# If connect a cell phone run
$ adb devices
$ adb reverse tcp:3030 tcp:3030

# To run the React Native
$ npx react-native run-android
$ npx react-native start
```
## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
