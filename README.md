# @contactlab/babelrc

[![Build Status](https://clab-dev.visualstudio.com/OSS/_apis/build/status/contactlab.babelrc?branchName=master)](https://clab-dev.visualstudio.com/OSS/_build/latest?definitionId=30&branchName=master)

Contactlab Frontend Team official (extendible) Babel configuration.

## Usage

```sh
$ npm install -D @contactlab/babelrc

# or

$ yarn add -D @contactlab/babelrc
```

In **package.json**:

```json
{
  ...

  "babel": {
    "extends": "@contactlab/babelrc",
    "presets": ["..."],
    "plugins": ["..."]
  }

  ...
}
```

or in **.babelrc**:

```json
{
  "extends": "@contactlab/babelrc",
  "presets": ["..."],
  "plugins": ["..."]
}
```

## Reference

`extends` option in [Babel CLI / .babelrc](http://babeljs.io/docs/usage/api/#options).

## License

Released under the [Apache 2.0](LICENSE) license.
