# \<fuzzy-date\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jlengrand/fuzzy-date)


A simple element that shows dates in a format understood by humans

## Demo

<!---
```
<custom-element-demo height="160">
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="fuzzy-date.html">
    <style>
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<fuzzy-date date="Wed Mar 14 2018 08:21:25 GMT+0100 (CET)"></fuzzy-date>
```

## Usage

To use, simply add the `fuzzy-date` dependency to your project and add a `<fuzzy-date>`element with a date attribute in the format given my javascript's `Date().toString()`;

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
