<p align="center">
  <img src="https://cdn.rawgit.com/ElemeFE/element/dev/element_logo.svg">
</p>

# Element

此版本是根据 element-ui 2.0.8 版本修改而来，主要用于解决在实际项目上遇到的一些问题

## 修改内容

* 修改 dialog 弹出框的遮罩层逻辑，使每一个 dialog 弹出框对应一个遮罩层
* 移除 dialog 弹出框的关闭动画，以解决在 ie 下关闭闪屏的问题
* 修复分页组件在 ie 下回车无法跳转的问题
* 更新 tree 组件为官方 2.3.4 版本，以使用最新的 api

## Install

```shell
npm install element-ui -S
```

## Quick Start

```javascript
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

For those who are interested in contributing to Element, please refer to our contributing guide ([中文](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.zh-CN.md) | [English](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.en-US.md)) to see how to run this project.

## Changelog

Detailed changes for each release are documented in the [release notes](https://github.com/ElemeFE/element/releases).

## FAQ

We have collected some [frequently asked questions](https://github.com/ElemeFE/element/blob/master/FAQ.md). Before reporting an issue, please search if the FAQ has the answer to your problem.

## Contribution

Please make sure to read the contributing guide ([中文](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.zh-CN.md) | [English](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.en-US.md)) before making a pull request.

## Special Thanks

English documentation is brought to you by SwiftGG Translation Team:

* [raychenfj](https://github.com/raychenfj)
* [kevin](http://thekevin.cn/)
* [曾小涛](https://github.com/zengxiaotao)
* [湾仔王二](https://github.com/wanzaiwanger)
* [BlooDLine](http://www.ibloodline.com/)
* [陈铭嘉](https://chenmingjia.github.io/)
* [千叶知风](http://mpc6.com/)
* [梁杰](http://numbbbbb.com)
* [Changing](https://github.com/sunzhuo11)
* [mmoaay](https://github.com/mmoaay)

Spanish documentation is made possible by these community developers:

* [adavie1](https://github.com/adavie1)
* [carmencitaqiu](https://github.com/carmencitaqiu)
* [coderdiaz](https://github.com/coderdiaz)
* [fedegar33](https://github.com/fedegar33)
* [Gonzalo2310](https://github.com/Gonzalo2310)
* [lesterbx](https://github.com/lesterbx)
* [ProgramerGuy](https://github.com/ProgramerGuy)
* [SantiagoGdaR](https://github.com/SantiagoGdaR)
* [sigfriedCub1990](https://github.com/sigfriedCub1990)
* [thechosenjuan](https://github.com/thechosenjuan)

## Donation

If you find Element useful, you can buy us a cup of coffee
<img width="650" src="http://fuss10.elemecdn.com/2/d0/ab1b8e5a1d96bcdcd6092ce0c66ecjpeg.jpeg?t=2017" alt="">

## Backers

Support us with a monthly donation and help us continue our activities. [[Become a backer](https://opencollective.com/element#backer)]

<a href="https://opencollective.com/element/backer/0/website" target="_blank"><img src="https://opencollective.com/element/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/1/website" target="_blank"><img src="https://opencollective.com/element/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/2/website" target="_blank"><img src="https://opencollective.com/element/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/3/website" target="_blank"><img src="https://opencollective.com/element/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/4/website" target="_blank"><img src="https://opencollective.com/element/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/5/website" target="_blank"><img src="https://opencollective.com/element/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/6/website" target="_blank"><img src="https://opencollective.com/element/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/7/website" target="_blank"><img src="https://opencollective.com/element/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/8/website" target="_blank"><img src="https://opencollective.com/element/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/9/website" target="_blank"><img src="https://opencollective.com/element/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/10/website" target="_blank"><img src="https://opencollective.com/element/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/11/website" target="_blank"><img src="https://opencollective.com/element/backer/11/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/12/website" target="_blank"><img src="https://opencollective.com/element/backer/12/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/13/website" target="_blank"><img src="https://opencollective.com/element/backer/13/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/14/website" target="_blank"><img src="https://opencollective.com/element/backer/14/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/15/website" target="_blank"><img src="https://opencollective.com/element/backer/15/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/16/website" target="_blank"><img src="https://opencollective.com/element/backer/16/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/17/website" target="_blank"><img src="https://opencollective.com/element/backer/17/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/18/website" target="_blank"><img src="https://opencollective.com/element/backer/18/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/19/website" target="_blank"><img src="https://opencollective.com/element/backer/19/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/20/website" target="_blank"><img src="https://opencollective.com/element/backer/20/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/21/website" target="_blank"><img src="https://opencollective.com/element/backer/21/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/22/website" target="_blank"><img src="https://opencollective.com/element/backer/22/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/23/website" target="_blank"><img src="https://opencollective.com/element/backer/23/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/24/website" target="_blank"><img src="https://opencollective.com/element/backer/24/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/25/website" target="_blank"><img src="https://opencollective.com/element/backer/25/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/26/website" target="_blank"><img src="https://opencollective.com/element/backer/26/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/27/website" target="_blank"><img src="https://opencollective.com/element/backer/27/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/28/website" target="_blank"><img src="https://opencollective.com/element/backer/28/avatar.svg"></a>
<a href="https://opencollective.com/element/backer/29/website" target="_blank"><img src="https://opencollective.com/element/backer/29/avatar.svg"></a>

## Sponsors

Become a sponsor and get your logo on our README on Github with a link to your site. [[Become a sponsor](https://opencollective.com/element#sponsor)]

<a href="https://opencollective.com/element/sponsor/0/website" target="_blank"><img src="https://opencollective.com/element/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/1/website" target="_blank"><img src="https://opencollective.com/element/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/2/website" target="_blank"><img src="https://opencollective.com/element/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/3/website" target="_blank"><img src="https://opencollective.com/element/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/4/website" target="_blank"><img src="https://opencollective.com/element/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/5/website" target="_blank"><img src="https://opencollective.com/element/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/6/website" target="_blank"><img src="https://opencollective.com/element/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/7/website" target="_blank"><img src="https://opencollective.com/element/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/8/website" target="_blank"><img src="https://opencollective.com/element/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/9/website" target="_blank"><img src="https://opencollective.com/element/sponsor/9/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/10/website" target="_blank"><img src="https://opencollective.com/element/sponsor/10/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/11/website" target="_blank"><img src="https://opencollective.com/element/sponsor/11/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/12/website" target="_blank"><img src="https://opencollective.com/element/sponsor/12/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/13/website" target="_blank"><img src="https://opencollective.com/element/sponsor/13/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/14/website" target="_blank"><img src="https://opencollective.com/element/sponsor/14/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/15/website" target="_blank"><img src="https://opencollective.com/element/sponsor/15/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/16/website" target="_blank"><img src="https://opencollective.com/element/sponsor/16/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/17/website" target="_blank"><img src="https://opencollective.com/element/sponsor/17/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/18/website" target="_blank"><img src="https://opencollective.com/element/sponsor/18/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/19/website" target="_blank"><img src="https://opencollective.com/element/sponsor/19/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/20/website" target="_blank"><img src="https://opencollective.com/element/sponsor/20/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/21/website" target="_blank"><img src="https://opencollective.com/element/sponsor/21/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/22/website" target="_blank"><img src="https://opencollective.com/element/sponsor/22/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/23/website" target="_blank"><img src="https://opencollective.com/element/sponsor/23/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/24/website" target="_blank"><img src="https://opencollective.com/element/sponsor/24/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/25/website" target="_blank"><img src="https://opencollective.com/element/sponsor/25/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/26/website" target="_blank"><img src="https://opencollective.com/element/sponsor/26/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/27/website" target="_blank"><img src="https://opencollective.com/element/sponsor/27/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/28/website" target="_blank"><img src="https://opencollective.com/element/sponsor/28/avatar.svg"></a>
<a href="https://opencollective.com/element/sponsor/29/website" target="_blank"><img src="https://opencollective.com/element/sponsor/29/avatar.svg"></a>

## LICENSE

MIT
