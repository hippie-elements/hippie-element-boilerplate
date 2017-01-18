# &lt;hippie-element-boilerplate&gt;

> <:fallen_leaf:></:fallen_leaf:> Boilerplate for create hippie elements using Polymer 1x.

[![Travis CI Status](https://travis-ci.org/hippie-elements/hippie-element-boilerplate.svg?branch=master)](https://travis-ci.org/hippie-elements/hippie-element-boilerplate)
[![bower](https://img.shields.io/bower/v/hippie-element-boilerplate.svg)](https://www.npmjs.com/package/bananacss)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/hippie-elements/hippie-element-boilerplate)

## How to install and use:

1. Install the element using [Bower](http://bower.io/):

```sh
$ bower install hippie-element-boilerplate --save
```

2. Import the element:

```html
<link rel="import" href="bower_components/hippie-element-boilerplate/hippie-element-boilerplate.html">
```

3. Start using it!

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
---       | ---         | ---       | ---
`prop`    | *String*    | `foo`     | Prop description

## Styling

The following custom properties and mixins are available for styling:

Custom property             | Default  | Description
---                         | ---      | ---
--hippie-element-text-color | #f06     | Text color

## Browser Support

Using the [webcomponents.js](https://github.com/WebComponents/webcomponentsjs):

![IE](https://cloud.githubusercontent.com/assets/398893/3528325/20373e76-078e-11e4-8e3a-1cb86cf506f0.png) | ![Chrome](https://cloud.githubusercontent.com/assets/398893/3528328/23bc7bc4-078e-11e4-8752-ba2809bf5cce.png) | ![Firefox](https://cloud.githubusercontent.com/assets/398893/3528329/26283ab0-078e-11e4-84d4-db2cf1009953.png) | ![Opera](https://cloud.githubusercontent.com/assets/398893/3528330/27ec9fa8-078e-11e4-95cb-709fd11dac16.png) | ![Safari](https://cloud.githubusercontent.com/assets/398893/3528331/29df8618-078e-11e4-8e3e-ed8ac738693f.png)
--- | --- | --- | --- | --- |
11+ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔

## Development

1. Install [Bower](http://bower.io/) & [Polymer-CLI](https://www.polymer-project.org/1.0/docs/tools/polymer-cli):

```sh
$ [sudo] npm install -g bower polymer-cli
```

2. Install local dependencies:

```sh
$ bower install
```

3. Start the development server:

```sh
$ polyserve
```

Go to [localhost:8080/components/hippie-element-boilerplate/](http://localhost:8080/components/hippie-element-boilerplate/)

## Tests

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

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing

Find on our [issues](https://github.com/hippie-elements/hippie-element-boilerplate/issues/) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://github.com/hippie-elements/hippie-element-boilerplate/blob/master/CONTRIBUTING.md).

## History

See [Releases](https://github.com/hippie-elements/hippie-element-boilerplate/releases) for detailed changelog.

## License

[MIT License](https://github.com/hippie-elements/hippie-license/LICENSE.md) © [Afonso Pacifer](http://afonsopacifer.github.io/)
