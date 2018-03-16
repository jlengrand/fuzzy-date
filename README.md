# \<fuzzy-date\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jlengrand/fuzzy-date)

[![Travis state](https://travis-ci.org/jlengrand/fuzzy-date.svg?branch=master)](https://travis-ci.org/jlengrand/fuzzy-date)

A simple element that shows dates in a format understood by humans

## Demo

<!---
```
<custom-element-demo height="160">
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="fuzzy-date.html">
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

## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.