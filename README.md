# ComputeBasic

[![npm version](https://img.shields.io/npm/v/computebasic.svg?colorB=brightgreen)](https://www.npmjs.com/package/computebasic "Stable Version")
[![npm version](https://img.shields.io/npm/v/computebasic/dev.svg)](https://www.npmjs.com/package/computebasic "Development Version")
[![License](https://img.shields.io/github/license/MaiyunNET/ComputeBasic.svg)](https://github.com/MaiyunNET/ComputeBasic/blob/master/LICENSE)
[![node](https://img.shields.io/node/v/computebasic.svg?colorB=brightgreen)](https://nodejs.org/dist/latest-v8.x/)
[![GitHub issues](https://img.shields.io/github/issues/MaiyunNET/ComputeBasic.svg)](https://github.com/MaiyunNET/ComputeBasic/issues)
[![GitHub Releases](https://img.shields.io/github/release/MaiyunNET/ComputeBasic.svg)](https://github.com/MaiyunNET/ComputeBasic/releases "Stable Release")
[![GitHub Pre-Releases](https://img.shields.io/github/release/MaiyunNET/ComputeBasic/all.svg)](https://github.com/MaiyunNET/ComputeBasic/releases "Pre-Release")

ComputeBasic is a simple script language for amateurs, compiled as JavaScript.

## Installation

### SystemJS

You need to reference Systemjs first and then import the index.js file like this:

```html
<script src="//cdn.jsdelivr.net/npm/systemjs@0.21.6/dist/system.js"></script>
<script>
    System.config({
        packages: {
            './dist': {
                defaultExtension: 'js'
            }
        }
    });
    System.import('./dist/index');
</script>
```

#### CDN (Recommended)

For example:

```html
<script>
    System.import('https://cdn.jsdelivr.net/npm/computebasic@x.x.x/dist/index.min');
</script>
```

Which will reflect the latest version as soon as it is published to npm. You can also browse the source of the npm package at https://cdn.jsdelivr.net/npm/computebasic/.

Also available on [unpkg](https://unpkg.com/computebasic).

### NPM

In the Node.js environment, you can install directly using NPM:

```sh
$ npm i computebasic --save
```

Or install the developing (unstable) version for newest features:

```sh
$ npm i computebasic@dev --save
```

## Test

Test in the browser, visit "test/index.html". Test in Nodejs, please execute "node test.node.js" in the "dist" directory.

[Click here to visit online.](https://maiyunnet.github.io/ComputeBasic/test/)

## Changelog

[Changelog](doc/CHANGELOG.md)

## License

This library is published under [Apache-2.0](./LICENSE) license.