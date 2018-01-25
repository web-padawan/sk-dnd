![Bower version](https://img.shields.io/bower/v/sk-dnd.svg)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/vaadin/sk-dnd)
[![Build Status](https://travis-ci.org/vaadin/sk-dnd.svg?branch=master)](https://travis-ci.org/vaadin/sk-dnd)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin/vaadin-core-elements?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# &lt;sk-dnd&gt;

[Live Demo ↗](https://cdn.vaadin.com/vaadin-core-elements/master/sk-dnd/demo/)
|
[API documentation ↗](https://cdn.vaadin.com/vaadin-core-elements/master/sk-dnd/)


[&lt;sk-dnd&gt;](https://vaadin.com/elements/-/element/sk-dnd) is a [Polymer 2](http://polymer-project.org) element providing &lt;element-functionality&gt;, part of the [Vaadin Core Elements](https://vaadin.com/elements).

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="sk-dnd.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<sk-dnd>
  ...
</sk-dnd>
```

[<img src="https://raw.githubusercontent.com/vaadin/sk-dnd/master/screenshot.png" width="200" alt="Screenshot of sk-dnd">](https://vaadin.com/elements/-/element/sk-dnd)


## Getting Started

Vaadin Elements use the Lumo theme by default.

## The file structure for Vaadin Elements

- `src/element-name.html`

  Unstyled element.

- `theme/lumo/element-name.html`

  Element with Lumo theme.

- `element-name.html`

  Alias for theme/lumo/element-name.html


## Running demos and tests in browser

1. Fork the `sk-dnd` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `sk-dnd` directory, run `npm install` and then `bower install` to install dependencies.

1. Run `polymer serve --open`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:8080/components/sk-dnd/demo
  - http://127.0.0.1:8080/components/sk-dnd/test


## Running tests from the command line

1. When in the `sk-dnd` directory, run `polymer test`


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `gulp lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Contributing

  - Make sure your code is compliant with our code linters: `gulp lint`
  - Check that tests are passing: `polymer test`
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of Vaadin Elements team members


## License

Apache License 2.0
