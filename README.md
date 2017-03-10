# Alex's vue-webpack-boilerplate

> A modified vue-cli template with additional LESS and Pug options, forked from the official [vue-webpack-boilerplate](https://github.com/vuejs-templates/webpack).

## Documentation

- Just read the [offical documents](http://vuejs-templates.github.io/webpack). It's the same.

## What's Modified

- LESS and LESS-loader included.
- Pug and Pug-loader included, also.
- Customized port for development environment. The default port is 8080.
- Modified default pages with LESS and Pug features, if either or both of them are configurated.

## Usage

This is a project template for [vue-cli](https://github.com/vuejs/vue-cli). **It is recommended to use npm 3+ for a more efficient dependency tree.**

``` bash
$ npm install -g vue-cli
$ vue init webpack my-project
$ cd my-project
$ npm install
$ npm run dev
```

Webpack uses port 8800 on default. Also,You can change it in `/config/index.js`. Just like the official template, if the port is already used, `npm run dev` will fail.

Besides `npm run dev`, these scripts also included:

- `npm run build`: Production ready build.
- `npm run unit`: Unit tests run in PhantomJS with [Karma](http://karma-runner.github.io/0.13/index.html) + [Mocha](http://mochajs.org/) + [karma-webpack](https://github.com/webpack/karma-webpack).
- `npm run e2e`: End-to-end tests with [Nightwatch](http://nightwatchjs.org/).

