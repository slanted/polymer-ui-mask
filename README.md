# \<ui-phone\>

UI Mask phone element

This is an attempt at getting a phone element to have a ui mask in polymer. Similar to ui-mask from angular here: https://github.com/angular-ui/ui-mask.

All the magic is pretty much in the MaskBehavior which the ui-phone element uses.

As a bonus, this element also plays nicely with angular using the angular_bind_polymer.js directive at https://github.com/eee-c/angular-bind-polymer.

You can mask 2 ways: premask or normal masking as you type.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
