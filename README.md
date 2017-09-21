# vue2-github-corners

[![vue2](https://img.shields.io/badge/vue-2.x-brightgreen.svg)](https://vuejs.org/)

A simple binding wrapper for [github-corners](https://github.com/tholman/github-corners) in Vue2

<p align="center">
  <a target="_blank" href="https://github.com/WeiChiaChang/vue-github-corners">
    <img alt="vue2-github-corners" src="https://i.imgur.com/yW06MbJ.gif">
  </a>
</p>

## Demo

[Show me the code, or demo it](https://git.io/v5jH6)

## Installation

```
npm install --save vue2-github-corners
```

## Usage

For standalone version

```javascript
<script src="/dist/vue-github-corners.browser.js"></script>
```

For vue-cli user

```javascript
import { VueGithubCorners } from 'vue2-github-corners'

Vue.component('VueGithubCorners', VueGithubCorners)

```

## Sample

```javascript
<template>
  <div id="app">
    <VueGithubCorners :repoUrl="repoUrl" :catColor="catColor" :bgColor="bgColor"></VueGithubCorners>
  </div>
</template>

export default {
  ...
  data () {
    return {
      // Replace repoUrl, catColor, bgColor setting as you want.
      // If default is what you like, just don't use related key-value pair and ignore it.
      repoUrl: "https://github.com/weichiachang/vue-github-corners",
      catColor: "#ffffff",
      bgColor: "#151513",
    }
  }
}
```

---

## License

[MIT](http://opensource.org/licenses/MIT) © [WeiChiaChang](https://github.com/WeiChiaChang)
