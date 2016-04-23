# Ember-tutorial

This addon supports the `Ember-Rentals` tutorial in the Ember Guides (WIP).

## Issues / Debate / RFC

There are a couple of paths this addon could take.

1. This addon could overwrite the `app/styles/app.css` file, and explain “This is where styles go in an Ember-CLI app”.
2. This addon / tutorial could aim to explain (in further detail) the separation between vendor styles and “where you should be placing your custom application styles”.

The current setup facilitates #2 (which may be more ambitious), but #1 could also be achieved by modifying the default blueprint & overwriting `app/styles/app.css`. However, very few (if any) Ember addons do this.


## Installation

* `git clone` this repository
* `npm install`
* `bower install`

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `npm test` (Runs `ember try:testall` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://ember-cli.com/](http://ember-cli.com/).
