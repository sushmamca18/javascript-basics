# JavaScript learning repository

Repository for learning Javascript in which code base is driven by Pluralsight course 'JavaScript Fundamentals by Mark Zamoyta' - https://app.pluralsight.com/library/courses/javascript-fundamentals.

Forked from https://github.com/wbkd/webpack-starter.


[![Greenkeeper badge](https://badges.greenkeeper.io/wbkd/webpack-starter.svg)](https://greenkeeper.io/)


### Installation

```
npm install
```

### Start Dev Server for specific topic

```
npm run FILE
```

Where FILE can must be replaced by one of options:

- **index** For index.js file which is a playground for testing
- **constants** For js file with example of how to use and not to use constants

### Build Prod Version

```
npm run build
```

### Features:

* ES6 Support via [babel](https://babeljs.io/) (v7)
* SASS Support via [sass-loader](https://github.com/jtangelder/sass-loader)
* Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)

When you run `npm run build` we use the [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) to move the css to a separate file. The css file gets included in the head of the `index.html`.
