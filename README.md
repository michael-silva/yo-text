# \<yo-text\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/michael-silva/yo-text)

A floating toolbar with some text editing tools.

## Example of usage ##
<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="yo-text.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<p style="margin: 50px 10px" contenteditable="true">Here has some text and you can edit it.</p>
<yo-text></yo-text>
```

## Customizing ##

To customize you can set some css3 variables

### Layout Variables ###
You can personalize the design of component with variables bellow:

```
--color: #f8f8f8;
--bgcolor: #2f2f3a;
--bgcolor-active: #1bcea3;
--color-active: #f8f8f8;
--bgcolor-hover: #1bcea3;
--color-hover: #f8f8f8;
--shadow-color: #b6b6b6;
```
### Icons Variables ###
You can personalize the icons of component with variables bellow:

```
--font: normal normal normal 14px/1 FontAwesome;
--link-content: "\f08e";
--bold-content: "\f032";
--italic-content: "\f033";
--underline-content: "\f0cd";
--strikethrough-content: "\f0cc";
--superscript-content: "\f12b";
--subscript-content: "\f12c";
```

## For developers ##

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

### Viewing Your Element

```
$ polymer serve
```

### Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
