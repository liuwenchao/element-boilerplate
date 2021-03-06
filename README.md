# &lt;aha-partial&gt; ![Bower Version](https://badge.fury.io/bo/aha-partial.svg)

> A Polymer element for partial, works like include.

## Demo

[Check it live!](http://liuwenchao.github.io/aha-partial)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install aha-partial --save
```

Or [download as ZIP](https://github.com/liuwenchao/aha-partial/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/aha-partial/src/aha-partial.html">
    ```

3. Start using it!

    ```html
    <aha-partial src="somepage.html"></aha-partial>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`src`         | *string*    | ``           | the source of partial


## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

* To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/liuwenchao/aha-partial/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
