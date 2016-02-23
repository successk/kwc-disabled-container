# &lt;kwc-disabled-container&gt;

> Polymer component used to disable a section (cannot be clicked and blur all inputs)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install kwc-disabled-container --save
```

Or [download as ZIP](https://github.com/successk/kwc-disabled-container/archive/master.zip).

## Usage

1 – Import polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
```

2 – Import custom element:

```html
<link rel="import" href="bower_components/kwc-disabled-container/kwc-disabled-container.html">
```

3 – Start using it!

```html
<kwc-disabled-container>
  <input type="text" placeholder="This input is active, you can edit it">
</kwc-disabled-container>
<kwc-disabled-container disabled>
  <p>This container is disabled. You cannot copy this text.</p>
  <input type="text" placeholder="This input is not active, you cannot edit it">
</kwc-disabled-container>
```

## Options

Attribute   | Options         | Default      | Description
---         | ---             | ---          | ---
`disabled`  | *boolean*        | `false`     | If true, the container will be disabled and fields will not be focused

## Children

Selector | Description
---      | ---
`*`      | Content of container

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
None          | -            | -           | -

## Events

Event     | Detail   | Description
---       | ---      | ---
None      | -        | -

## Styles

Name                                      | Default   | Description
---                                       | ---       | --
`--kwc-disabled-container-shadow`         | `{}`      | Style of the div recovering the content

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1 – Install [bower](http://bower.io/) & [polyserve](https://npmjs.com/polyserve):

```sh
$ npm install -g bower polyserve
```

2 – Install local dependencies:

```sh
$ bower install
```

3 – Start development server and open `http://localhost:8080/components/kwc-disabled-container/`.

```sh
$ polyserve
```

## History

For detailed changelog, check [Releases](https://github.com/successk/kwc-disabled-container/releases).

## License

MIT