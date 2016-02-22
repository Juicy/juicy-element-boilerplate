# &lt;juicy-element&gt;

> A bare minimum custom element starter-kit using [VanillaJS](http://vanilla-js.com/).
>
> Looking for a working example? Check [hello-world-element](https://github.com/webcomponents/hello-world-element).

## Demo

[Check it live!](http://Juicy.github.io/juicy-element)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install juicy-element --save
```

Or [download as ZIP](https://github.com/Juicy/juicy-element/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/juicy-element/juicy-element.html">
    ```

3. Start using it!

    ```html
    <juicy-element></juicy-element>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`foo`         | *string*    | `bar`        | Lorem ipsum dolor.

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`unicorn()`   | None.        | Nothing.    | Magic stuff appears.

## Events

Event         | Description
---           | ---
`onsomething` | Triggers when something happens.

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [bower](http://bower.io/) & [polyserve](https://npmjs.com/polyserve):

    ```sh
    $ npm install -g bower polyserve
    ```

2. Install local dependencies:

    ```sh
    $ bower install
    ```

3. Start development server and open `http://localhost:8080/components/juicy-element/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://github.com/Juicy/juicy-element/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
