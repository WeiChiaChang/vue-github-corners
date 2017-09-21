# vue2-github-corners

[![vue2](https://img.shields.io/badge/vue-2.x-brightgreen.svg)](https://vuejs.org/)

A simple binding wrapper for github-corners in Vue2

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
import VueGithubCorners from 'vue2-github-corners'

Vue.use(VueGithubCorners)
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
      repoUrl: "https://github.com/weichiachang/vue-github-corners",
      catColor: "#ffffff",
      bgColor: "#151513",
    }
  }
}
```

## Demo



---

## License

[MIT](http://opensource.org/licenses/MIT)
