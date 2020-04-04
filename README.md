<p align="center">
    <a href="https://www.npmjs.com/package/gridsome-plugin-nprogress">
      <img src="https://gridsome.org/logos/logo-circle-light.svg" alt="gridsome logo" width="100px"/>
    </a>
    <h1 align="center">gridsome-plugin-nprogress</h1>
    <p align="center">Automatically shows the nprogress indicator when a page is delayed in loading (which Gridsome considers as one second after clicking on a link).
    </p>
</p>

## Install

```bash
yarn add gridsome-plugin-nprogress
```

```bash
npm i gridsome-plugin-nprogress
```

## Usage

Add `gridsome-plugin-nprogress` to plugin array with following configurable options to `gridsome.config.js`

```js
...
plugins:[
    {
        use: 'gridsome-plugin-nprogress',
        options: {
          // Setting a color is optional.
          color: '#0366d6',
          // Disable the loading spinner.
          showSpinner: false,
        }
    }
]
```

## License

[![GitHub license](https://img.shields.io/github/license/benemohamed/gridsome-plugin-nprogress.svg)](https://github.com/benemohamed/gridsome-plugin-nprogress)
