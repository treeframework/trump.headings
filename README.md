# Headings

The `headings-trump` module defines font sizes for heading-related helper
classes.

## Dependencies

The `headings-trump` module depends on two other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [base.headings](https://github.com/treeframework/base.headings)

If you install the `headings-trump` module using Bower or npm, you will get 
these dependencies at the same time. If not using Bower or npm, please be sure 
to install and `@import` these dependencies in the relevant way.

## Installation

You can install `headings-trump` module via Bower, npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-headings-trump --save
```

Once installed, `@import` into your project in its Trumps layer:

```scss
@import "bower_components/tree-headings-trump/trump.headings";
```

### Install using npm:

```sh
$ npm install tree-headings-trump --save
```

### Install via file download

The least recommended option for installation is to simply download
`_trump.headings.scss` into your project and `@import` it into your project in 
its Trumps layer.

## Usage

Basic usage of the `headings-trump` module uses the required classes:

```html
<h3 class="u-alpha">...</h3>
```
