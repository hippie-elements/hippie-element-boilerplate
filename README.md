# &lt;hippie-element-boilerplate&gt;

> <:fallen_leaf:></:fallen_leaf:> Boilerplate for create hippie elements using Polymer 1x.

[![Travis CI Status](https://travis-ci.org/hippie-elements/hippie-element-boilerplate.svg?branch=master)](https://travis-ci.org/hippie-elements/hippie-element-boilerplate)
[![bower](https://img.shields.io/bower/v/hippie-element-boilerplate.svg)](https://www.npmjs.com/package/bananacss)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/hippie-elements/hippie-element-boilerplate)

## How to install and use:

1 - Install the element using [Bower](http://bower.io/):

```sh
$ bower install hippie-element-boilerplate --save
```

2 -  Import the element:

```html
<link rel="import" href="bower_components/hippie-element-boilerplate/hippie-element-boilerplate.html">
```

3 - Start using it!

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="hippie-element-boilerplate.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<hippie-element-boilerplate prop="foo">bar</hippie-element-boilerplate>
```


## Properties

Property  | Type        | Default   | Description
:---      |:---        |:---        |:---
`prop`    | *String*    | `foo`     | Prop description

## Styling

The following custom properties and mixins are available for styling:

Custom property                   | Default  | Description
:---                              |:---      |:---
--hippie-element-background-color | #f06    | Background color
--hippie-element-text-color       | fff      | Text color
--hippie-element-text             | {}       | Text styles


## Browser Support

Using the [webcomponents.js](https://github.com/WebComponents/webcomponentsjs):

 ![Chrome](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/chrome/chrome_48x48.png) | ![Opera](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/opera/opera_48x48.png) | ![Firefox](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/firefox/firefox_48x48.png) | ![Safari](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/safari/safari_48x48.png) |![IE](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) |  ![Edge](https://cdnjs.cloudflare.com/ajax/libs/browser-logos/39.2.2/edge/edge_48x48.png) |
:---: | :---: | :---: | :---: | :---: | :---: |
Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ | 11+ | Latest ✔

## Development

1 - Install [Bower](http://bower.io/) & [Polymer-CLI](https://www.polymer-project.org/1.0/docs/tools/polymer-cli):

```sh
$ [sudo] npm install -g bower polymer-cli
```

2 - Install local dependencies:

```sh
$ bower install
```

3 - Start the development server:

```sh
$ polyserve
```

Go to [localhost:8080/components/hippie-element-boilerplate/](http://localhost:8080/components/hippie-element-boilerplate/)

## Tests

#### Linting

Linting with eslint:

```sh
$ [sudo] npm install -g eslint
$ [sudo] npm install -g eslint-plugin-html

$ eslint *.html
```

Linting with polylint:

```sh
$ [sudo] npm install -g polylint

$ polylint
```

#### Unit tests

Install the Web Component Tester (WCT) test runner:

```sh
$ [sudo] npm install -g web-component-tester
```

Run tests:

```sh
$ wct
```

**Quick tip**: For run the [selenium driver for safari](https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-safari-driver), you need follow [some instructions](https://webkit.org/blog/6900/webdriver-support-in-safari-10/).

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing

Find on our [issues](https://github.com/hippie-elements/hippie-element-boilerplate/issues/) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://github.com/hippie-elements/hippie-element-boilerplate/blob/master/CONTRIBUTING.md).

## History

See [Releases](https://github.com/hippie-elements/hippie-element-boilerplate/releases) for detailed changelog.

## License

[MIT License](https://hippie-elements.github.io/LICENSE.txt) © [hippie team](https://github.com/orgs/hippie-elements/people)
