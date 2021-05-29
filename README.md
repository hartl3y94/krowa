<h1 align="center">
    <img src="docs_include/banner.svg" alt="krowa" width="250"/>
    <br>
</h1>

<p align="center">
    <a href="https://standardjs.com"><img src="https://img.shields.io/badge/code%20style-standard-%234f2218?style=for-the-badge" style="max-width:100%;" alt="style"/></a>
    <a href="https://discord.gg/WK2qTecTkJ"><img src="https://img.shields.io/badge/discord-krowa-%234f2218?style=for-the-badge" style="max-width:100%;" alt="discord"></a>
    <a href="https://www.npmjs.com/package/krowa"><img src="https://img.shields.io/badge/package-krowa-%234f2218?style=for-the-badge" style="max-width:100%;" alt="npm"></a>
    <a href="https://travis-ci.com/colenh/krowa"><img src="https://img.shields.io/travis/com/colenh/krowa?color=%234f2218&style=for-the-badge" style="max-width:100%;" alt="build"/></a>
    <a href="https://github.com/colenh/krowa/blob/main/LICENSE"><img src="https://img.shields.io/github/license/colenh/krowa?color=4f2218&style=for-the-badge" style="max-width:100%;" alt="license"></a>
    <a href="https://david-dm.org/colenh/krowa"><img src="https://img.shields.io/david/colenh/krowa?color=4f2218&style=for-the-badge" style="max-width:100%;" alt="dependencies"></a>
    <a><img src="https://img.shields.io/snyk/vulnerabilities/npm/krowa?color=4f2218&style=for-the-badge" style="max-width:100%;" alt="vulnerabilities"></a>
</p>

## about

krowa is a js wrapper for almost every public api we can find. krowa is licensed under MIT

## install

```bash
# locally
    $ yarn add krowa
    $ npm install krowa --save

# globally
    $ yarn global add krowa
    $ npm install krowa -g
```

## example

```js
const krowa = require('krowa')
const res = krowa.GitHub.users.getUser('colenh')
console.log(res)
```

## docs

to view api documentation, tutorials, and more, visit: [krowa.js.org](https://krowa.js.org/)

## credits

* [cole](https://github.com/colenh) - lead maintainer
