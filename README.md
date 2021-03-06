<p align="center">
  <img src="https://github.com/luosijie/Front-end-Blog/blob/master/img/logo_vmmarkdown_name.png?raw=true">
</p>
<p align="center">
    <strong>Markdown for Vue,</strong> <a href="https://luosijie.github.io/vm-markdown/">Live Demo</a>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/version-0.1.0-blue.svg?style=flat">
  <img src="https://img.shields.io/badge/dependency-vue-green.svg?style=flat">
  <img src="https://img.shields.io/badge/dependency-marked-yellow.svg?style=flat">
</p>

### Install

```bash
npm install --save vm-markdwon
```
### Usage

```js
import VmMarkdown from 'vm-markdwon'
export default {
  ...
  components: {
  	VmMarkdown
  },
  methods: {
  	showHtml (data) {
      console.log(data)
    }
  }
  ...
}
```

```vue
<VmMarkdown :theme="theme" 
            width="1000px" 
            height="600px" 
            v-on:getHtml="showHtml"
            :defaultText="intro">
</VmMarkdown>
```


### License

[MIT](https://github.com/luosijie/vm-editor/blob/master/LICENSE.md)
