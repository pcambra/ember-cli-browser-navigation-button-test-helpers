# ember-cli-browser-navigation-button-test-helper
[![Build Status](https://travis-ci.org/jelhan/ember-cli-browser-navigation-button-test-helpers.svg?branch=master)](https://travis-ci.org/jelhan/ember-cli-browser-navigation-button-test-helpers)

Test helper to simulate browsers back and forward buttons in acceptance tests.

## Installation
* `ember install ember-cli-browser-navigation-button-test-helper`
* Add `import './browser-navigation-buttons';` to `tests/helpers/start-app.js`.
* Add `backButton`, `forwardButton` and `setupBrowserNavigationButtons` as predef in `tests/.jshintrc`.

## Quickstart

* Call `setupBrowserNavigationButtons();` at the start of your acceptance test.
* Simulate back button clicks by `backButton();`.
* Simpute forward button clicks by `forwardButton();`.

There is an usage example [in this acceptance test](https://github.com/jelhan/ember-cli-browser-navigation-button-test-helpers/blob/master/tests/acceptance/browser-navigation-buttons-test.js).

## Running Tests

* `npm test` (Runs `ember try:testall` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://ember-cli.com/](http://ember-cli.com/).
