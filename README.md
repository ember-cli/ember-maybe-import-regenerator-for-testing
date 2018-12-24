# ember-maybe-import-regenerator-for-testing

This is an addon that'll import the
[Regenerator](https://github.com/facebook/regenerator)
Runtime for usage in your Ember apps tests, but only if you didn't already set
`babel.includePolyfill` to true or have `ember-maybe-import-regenerator` (a
sister package that ensures regenerator runtime is present in the main
`vendor.js` for usage throughout the application). This is useful for apps that
want to use `async` / `await` (or ES6 generator functions) but don't want to
ship the regenerator runtime in production.

Installation
------------------------------------------------------------------------------

```
ember install my-addon
```


Usage
------------------------------------------------------------------------------

[Longer description of how to use the addon in apps.]


License
------------------------------------------------------------------------------

This project is licensed under the [MIT License](LICENSE.md).
