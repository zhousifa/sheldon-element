<p align="center">
  <img src="https://cdn.rawgit.com/ElemeFE/element/dev/element_logo.svg">
</p>

<p align="center">
  <a href="https://travis-ci.org/ElemeFE/element">
    <img src="https://travis-ci.org/ElemeFE/element.svg?branch=master">
  </a>
  <a href="https://coveralls.io/github/ElemeFE/element?branch=master">
    <img src="https://coveralls.io/repos/github/ElemeFE/element/badge.svg?branch=master">
  </a>
  <a href="https://cdnjs.com/libraries/element-ui">
    <img src="https://img.shields.io/cdnjs/v/element-ui.svg">
  </a>
  <a href="https://www.npmjs.org/package/element-ui">
    <img src="https://img.shields.io/npm/v/element-ui.svg">
  </a>
  <a href="https://npmcharts.com/compare/element-ui?minimal=true">
    <img src="http://img.shields.io/npm/dm/element-ui.svg">
  </a>
  <br>
  <a href="http://img.badgesize.io/https://unpkg.com/element-ui/lib/index.js?compression=gzip&label=gzip%20size:%20JS">
    <img src="http://img.badgesize.io/https://unpkg.com/element-ui/lib/index.js?compression=gzip&label=gzip%20size:%20JS">
  </a>
  <a href="http://img.badgesize.io/https://unpkg.com/element-ui/lib/theme-chalk/index.css?compression=gzip&label=gzip%20size:%20CSS">
    <img src="http://img.badgesize.io/https://unpkg.com/element-ui/lib/theme-chalk/index.css?compression=gzip&label=gzip%20size:%20CSS">
  </a>
  <a href="#backers">
    <img src="https://opencollective.com/element/backers/badge.svg">
  </a>
  <a href="#sponsors">
    <img src="https://opencollective.com/element/sponsors/badge.svg">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg">
  </a>
</p>

> A Vue.js 2.0 UI Toolkit for Web.

Element will stay with Vue 2.x

For Vue 3.0, we recommend using [Element Plus](https://github.com/element-plus/element-plus)(Element Plus is a community develop project)

For MiniProgram development, we recommend using [MorJS](https://github.com/eleme/morjs)

## 目录简介
|- build  webpack相关的打包配置文件
|- examples  Element 官网页面
  |- assets  官网需要的一些静态资源,例如: 字体、样式、图片
  |- components  官网的公共组件, 例如: headr、foot
  |- demo-style  公共组件样式，在其中的index.scss中导入所有样式
  |- docs/zh-CN  各个组件的文档
  |- dom class的增删改查
  |- extension
  |- i18n
  |- pages 官网的页面
  |- play
  |- app.vue
  |- bus.js
  |- color.js
  |- entry.js
  |- icon.json
  |- index.tpl
  |- nav.config.json
  |- play.js
  |- route.config.js  路由配置
  |- util.js
  |- versions.json
|- packages  组件源码
|- src
  |- index.js  所有组件注册的入口文件, 该文件由脚本`build/bin/build-entry.js`生成
|- test  测试文件, 使用 karma 框架
|- types  类型声明文件
|- components.json  表明了组件的文件路径，方便webpack打包时获取组件的文件路径
|- .gitattributes  允许我们指定由git使用的文件和路径的属性
|- .npmignore  上传npm的配置文件
|- FAQ.md  常见的组件库问题
|- Makefile  是一个适用于c/c++的工具，make环境下，输入make命令将会执行makefile文件中的某个目标命令

## Links
- Homepage and documentation
  - [International users](http://element.eleme.io/#/en-US)
  - [Chinese users](http://element.eleme.io/#/zh-CN)
  - [Spanish users](http://element.eleme.io/#/es)
  - [French users](http://element.eleme.io/#/fr-FR)
- [awesome-element](https://github.com/ElementUI/awesome-element)
- [FAQ](./FAQ.md)
- [Vue.js 3.0 migration](https://github.com/element-plus/element-plus)
- [Customize theme](http://element.eleme.io/#/en-US/component/custom-theme)
- [Preview and generate theme online](https://elementui.github.io/theme-chalk-preview)
- [Element for React](https://github.com/elemefe/element-react)
- [Element for Angular](https://github.com/ElemeFE/element-angular)
- [Atom helper](https://github.com/ElemeFE/element-helper)
- [Visual Studio Code helper](https://github.com/ElemeFE/vscode-element-helper)
- Starter kit
  - [element-starter](https://github.com/ElementUI/element-starter)
  - [element-in-laravel-starter](https://github.com/ElementUI/element-in-laravel-starter)
- [Design resources](https://github.com/ElementUI/Resources)
- Gitter
  - [International users](https://gitter.im/element-en/Lobby)
  - [Chinese users](https://gitter.im/ElemeFE/element)

## Install
```shell
npm install element-ui -S
```

## Quick Start
``` javascript
import Vue from 'vue'
import Element from 'element-ui'

Vue.use(Element)

// or
import {
  Select,
  Button
  // ...
} from 'element-ui'

Vue.component(Select.name, Select)
Vue.component(Button.name, Button)
```
For more information, please refer to [Quick Start](http://element.eleme.io/#/en-US/component/quickstart) in our documentation.

## Browser Support
Modern browsers and Internet Explorer 10+.

## Development
Skip this part if you just want to use Element.

For those who are interested in contributing to Element, please refer to our contributing guide ([中文](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.zh-CN.md) | [English](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.en-US.md) | [Español](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.es.md) | [Français](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.fr-FR.md)) to see how to run this project.

## Changelog
Detailed changes for each release are documented in the [release notes](https://github.com/ElemeFE/element/releases).

## FAQ
We have collected some [frequently asked questions](https://github.com/ElemeFE/element/blob/master/FAQ.md). Before reporting an issue, please search if the FAQ has the answer to your problem.

## Contribution
Please make sure to read the contributing guide ([中文](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.zh-CN.md) | [English](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.en-US.md) | [Español](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.es.md) | [Français](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.fr-FR.md)) before making a pull request.

## Special Thanks
English documentation is brought to you by SwiftGG Translation Team:
- [raychenfj](https://github.com/raychenfj)
- [kevin](http://thekevin.cn/)
- [曾小涛](https://github.com/zengxiaotao)
- [湾仔王二](https://github.com/wanzaiwanger)
- [BlooDLine](http://www.ibloodline.com/)
- [陈铭嘉](https://chenmingjia.github.io/)
- [千叶知风](http://mpc6.com/)
- [梁杰](http://numbbbbb.com)
- [Changing](https://github.com/sunzhuo11)
- [mmoaay](https://github.com/mmoaay)

Spanish documentation is made possible by these community developers:
- [adavie1](https://github.com/adavie1)
- [carmencitaqiu](https://github.com/carmencitaqiu)
- [coderdiaz](https://github.com/coderdiaz)
- [fedegar33](https://github.com/fedegar33)
- [Gonzalo2310](https://github.com/Gonzalo2310)
- [lesterbx](https://github.com/lesterbx)
- [ProgramerGuy](https://github.com/ProgramerGuy)
- [SantiagoGdaR](https://github.com/SantiagoGdaR)
- [sigfriedCub1990](https://github.com/sigfriedCub1990)
- [thechosenjuan](https://github.com/thechosenjuan)

French documentation is made possible by these community developers:
- [smalesys](https://github.com/smalesys)
- [blombard](https://github.com/blombard)

## Join Discussion Group

Scan the QR code using [Dingtalk App](https://www.dingtalk.com/) to join in discussion group :

<img alt="Join Discusion Group" src="https://user-images.githubusercontent.com/17680888/93177882-0ae92d80-f766-11ea-870d-3fa2d7f06454.png" width="300">


## LICENSE
[MIT](LICENSE)
