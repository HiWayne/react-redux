# Fork 自 React Redux

在阅读源码的过程中增加了注释，读源码时是 7.x 版本，没想到 2 天后他们升级成 8 了，全部换成了 ts。所以 merge 后我的注释都留在了原来的 js 文件里，想阅读注释的直接去 js 文件就好了，就几个关键文件。

# React Redux

Official React bindings for [Redux](https://github.com/reduxjs/redux).  
Performant and flexible.

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/reduxjs/react-redux/Tests?style=flat-square) [![npm version](https://img.shields.io/npm/v/react-redux.svg?style=flat-square)](https://www.npmjs.com/package/react-redux)
[![npm downloads](https://img.shields.io/npm/dm/react-redux.svg?style=flat-square)](https://www.npmjs.com/package/react-redux)
[![redux channel on discord](https://img.shields.io/badge/discord-redux@reactiflux-61DAFB.svg?style=flat-square)](http://www.reactiflux.com)

## Installation

### Using Create React App

The recommended way to start new apps with React Redux is by using the [official Redux+JS template](https://github.com/reduxjs/cra-template-redux) for [Create React App](https://github.com/facebook/create-react-app), which takes advantage of [Redux Toolkit](https://redux-toolkit.js.org/).

```sh
npx create-react-app my-app --template redux
```

### An Existing React App

React Redux 7.1 requires **React 16.8.3 or later.**

To use React Redux with your React app, install it as a dependency:

```bash
# If you use npm:
npm install react-redux

# Or if you use Yarn:
yarn add react-redux
```

You'll also need to [install Redux](https://redux.js.org/introduction/installation) and [set up a Redux store](https://redux.js.org/recipes/configuring-your-store/) in your app.

This assumes that you’re using [npm](http://npmjs.com/) package manager
with a module bundler like [Webpack](https://webpack.js.org/) or
[Browserify](http://browserify.org/) to consume [CommonJS
modules](https://webpack.js.org/api/module-methods/#commonjs).

If you don’t yet use [npm](http://npmjs.com/) or a modern module bundler, and would rather prefer a single-file [UMD](https://github.com/umdjs/umd) build that makes `ReactRedux` available as a global object, you can grab a pre-built version from [cdnjs](https://cdnjs.com/libraries/react-redux). We _don’t_ recommend this approach for any serious application, as most of the libraries complementary to Redux are only available on [npm](http://npmjs.com/).

## React Native

As of React Native 0.18, React Redux 5.x should work with React Native. If you have any issues with React Redux 5.x on React Native, run `npm ls react` and make sure you don’t have a duplicate React installation in your `node_modules`. We recommend that you use `npm@3.x` which is better at avoiding these kinds of issues.

## Documentation

The React Redux docs are now published at **https://react-redux.js.org** .

We're currently expanding and rewriting our docs content - check back soon for more updates!

## How Does It Work?

We do a deep dive on how React Redux works in [this readthesource episode](https://www.youtube.com/watch?v=VJ38wSFbM3A).

Also, the post [The History and Implementation of React-Redux](https://blog.isquaredsoftware.com/2018/11/react-redux-history-implementation/)
explains what it does, how it works, and how the API and implementation have evolved over time.

Enjoy!

## License

[MIT](LICENSE.md)
