# ember-maybe-import-regenerator-for-testing

[![Greenkeeper badge](https://badges.greenkeeper.io/ember-cli/ember-maybe-import-regenerator-for-testing.svg)](https://greenkeeper.io/)

This is an addon that'll import the
[Regenerator](https://github.com/facebook/regenerator)
Runtime for usage in your Ember apps tests, but only if you didn't already set
`babel.includePolyfill` to true or have `ember-maybe-import-regenerator` (a
sister package that ensures regenerator runtime is present in the main
`vendor.js` for usage throughout the application). This is useful for apps that
want to use `async` / `await` (or ES6 generator functions) but don't want to
ship the regenerator runtime in production.

## Installation

* `git clone <repository-url>` this repository
* `cd my-addon`
* `npm install`

## Running

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).

## Running Tests

* `npm test` (Runs `ember try:each` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [https://ember-cli.com/](https://ember-cli.com/).
