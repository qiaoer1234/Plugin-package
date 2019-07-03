# 前端工具 

聚名网前端工具，小组成员上传或者更新时做好commit

---

## 目录
- [插件](#plugins)
  - [功能插件](#features)
  - [图片类插件](#images)
  - [移动端插件](#mobile)
  - [开发框架以及工具库](#framework)
- [HTML](#html)
- [CSS](#css)
- [精选阅读](#read)
  - [前端技术](#fedev)
  - [Node 学习资料](#node_read)
  - [其他技术](#otherdev)

## 正文

<h4 id="plugins">插件</h4>

<h6 id="features">功能插件</h6>

- [jedate](http://www.jemui.com/uidoc/jedate.html) - 是一款原生JS开发的 不依赖任何第三方库 大众化的日期控件
- [pikaday](https://github.com/qiaoer1234/Pikaday)  - 日期选择器，不依赖于任何 Javascript 库，并且文件大小小于 5K，功能很强大。
- [EasyUI ](http://www.jeasyui.net/plugins) -一种基于jQuery、Angular.、Vue和React的用户界面插件集合,不需要写很多代码，你只需要通过编写一些简单HTML标记，就可以定义用户界面。
- [jquery.cityselect](https://github.com/akveo/blur-admin) - jQuery+JSON的省市三级、二级联动插件制订此文档。
- [distpicker](https://github.com/fengyuanchen/distpicker) - 是一款可以实现中国省市区地址三级联动jQuery插件。它使用简单，简单设置即可完成中国省市区地址联动效果。
- [three.js](https://github.com/mrdoob/three.js) - JavaScript 3D 库。超多的 [examples](http://threejs.org/examples/) 等着你去发现，你只需要关注内存和风扇就行了
- [ECharts](http://echarts.baidu.com/index.html) - 好用，最关键的是支持的图表展示非常之多，强烈推荐
- [highcharts](  https://www.hcharts.cn/demo/highcharts ) -好用--支持 IE6 及以上的所有主流浏览器，完美支持移动端缩放、手势操作。
- [highlightjs](https://highlightjs.org/) - 代码高亮库，支持非常多的语言
- [daterangepicker](http://www.daterangepicker.com) - 时间选择插件的不二选择，基于 ```Bootstrap``` 和 [Moment.js](http://momentjs.com/)
- [excellentexport](https://github.com/jmaister/excellentexport) - 纯前端的 Excel 导出，非常之方便
- [Sortable](https://github.com/RubaXa/Sortable) - 拖拽神器，用了就知道
- [dragula](https://github.com/qiaoer1234/dragula/tree/master) -是一个 JavaScript 库，实现了网页上的拖放功能
- [autocompleter](https://github.com/qiaoer1234/-Autocompleter-) - autocompleter是一个简单的，容易的，可定制的自动完成功能插件，支持缓存。
- [html2canvas](https://github.com/niklasvh/html2canvas)+[canvas2Image](https://github.com/randreucetti/canvas2image) - 看这两库的名称就明白是做什么的。使用场景就是“动态生成的HTML可以长按保存为图片”。
- [onepage-scroll](https://github.com/peachananr/onepage-scroll) - 依赖 jQuery 的单页滚动库，和 [fullPage](http://alvarotrigo.com/fullPage/) 类似
- [videojs](http://videojs.com/) - 当下视频需求都用上```<video>```鸟 样式和交互统一的问题交给 videojs 搞定:)
- [clipboard](http://zenorocha.github.io/clipboard.js/) - 仅 2KB 大小，搞定剪贴板功能，屌不屌~ 但是，Safari 不支持...
- [select2](https://select2.org/getting-started/basic-usage) - 是一款可以对HTML的<select>标签进行功能优化的jQuery插件,支持对列表进行检索,从远程数据源获取列表项等各种功能.

> ___```Swiper/PhotoSwipe/fullPage``` 有这仨库，微信里常见的 H5 页完全不是问题哒___

<h6 id="images">图片类插件</h6>

- [Swiper](http://www.swiper.com.cn) - 强大的 Slider 库 其实这类效果库非常多，但文档能那么专业的就很少鸟
- [jquery.lazyload](http://www.jq22.com/yanshi390) - jQuery图片延迟加载插件jQuery.lazyload,使用延迟加载在可提高网页下载速度。在某些情况下，它也能帮助减轻服务器负载。
- [PhotoSwipe](http://photoswipe.com/) - 偶常用的 js 库 官网上有这么一句很关键、重要"no dependencies"

<h6 id="mobile">移动端插件</h6>

- [adaptive.js](https://github.com/Vibing/adaptive) 
- 借鉴手淘方案，adaptive.js将整个页面宽度平均分成10份，以clineWidth / 10的结果作为html标签的font-size值。 布局中使用rem作为单位。
- [FlipClock](http://www.flipclockjs.com/) 
- FlipClock.js 是一个制作精美时钟，定时器和倒计时的 jQuery 插件，并且可以完全通过 CSS 进行定制。有设置为自动启动，存在多种方法控制（启动，停止，getTime，setTime..），支持回调函数，此外，它还有一个全功能的API，能够进一步扩展功能。
- [iosSelect](http://zhoushengfe.com/iosselect/website/index.html) 
- 仿IOS端选择器插件，支持日期、地区等
- [移动端滑动插件better-scroll](http://ustbhuangyi.github.io/better-scroll/doc/zh-hans/#better-scroll) - better-scroll 是一款重点解决移动端（已支持 PC）各种滚动场景需求的插件。better-scroll 是基于原生 JS 实现的，不依赖任何框架。它编译后的代码大小是 63kb，压缩后是 35kb，gzip 后仅有 9kb，是一款非常轻量的 JS lib。
- [fastclick](https://majing.io/posts/10000007721218) - 移动设备上的浏览器默认会在用户点击屏幕大约延迟300毫秒后才会触发点击事件，这是为了检查用户是否在做双击。为了能够立即响应用户的点击事件，才有了FastClick。


<h3 id="html">HTML</h3>

纯 ```HTML``` 相关其实没有好玩的项目，所以这儿展示的内容主要都是一些模板，而且以下列出来的都是免费的，方便拿取搭架后台或者博客

- [HEAD](https://github.com/joshbuchea/HEAD) - 最全的 ```<head>``` 列表，真心佩服这种偏执的整理能力
- [AdminLTE](https://github.com/almasaeed2010/AdminLTE) - 很小清新的后台模板，每次看[preview](https://almsaeedstudio.com/preview) 页面都觉得很有视觉冲击
- [gentelella](https://github.com/puikinsh/gentelella) - 刚用这个搭建了我司内部用的的数据平台，效果喜人。模板实现的功能比较全，比如登录、注册甚至各种 ```widget```，所以最终交付的时候，自己几乎没写几行CSS。
- [material-design-lite](https://github.com/google/material-design-lite) - ```Star``` 数超过2W的开源模板项目，包含了多套简洁的 ```templates```，可以用于博客、后台或者企业首页。

<h3 id="css">CSS</h3>

- [wow.js](https://github.com/qiaoer1234/wow.js) - 一款帮助你实现这种 CSS 动画效果的插件，很容易定制，你可以改变动画设置喜欢的风格、延迟、长度、偏移和迭代等。
- [MetroUI](http://metroui.org.ua/) - 好看好用，重点是样式特别、个性
- [Font-Awesome](http://fontawesome.io/) - 图标字体库。相类似的库有不少，大厂都喜欢造轮子嘛:)
- [LoadersCSS](https://connoratherton.com/loaders) - 用 CSS 技术实现 loading 动画； 补一句，想熟悉、理解 ```keyframes、animation、transform、transition``` 的童鞋可以直接去读其源码(只有千把行代码)，读完就算出师鸟:)
- [WeUI](https://github.com/weui/weui) - 一套同微信原生视觉体验一致的基础样式库 为微信 Web 开发量身设计，令用户的使用感知更加统一
- [PostCSS](https://github.com/postcss/postcss) - 最近才知道大名鼎鼎[Autoprefixer](https://github.com/postcss/autoprefixer)是其插件 推荐大漠的文章[《PostCSS深入学习》](http://www.w3cplus.com/PostCSS/postcss-deep-dive-what-you-need-to-know.html)，有关 PostCSS 不是什么？PostCSS 是什么？PostCSS 可以做什么等等问题，文章里面有答案
- [HINT.css](https://github.com/chinchang/hint.css) - 一款非常小巧的提示框效果
- [Hover.css](http://ianlunn.github.io/Hover/) - 很多鼠标 Hover 态的效果，可以给产品学习一下:)
- [csscss](https://github.com/zmoazeni/csscss) - 用于检查 CSS 代码冗余 
- [hamburgers](https://jonsuh.com/hamburgers/) - 简单的动画库，让 Click(or Tap) 变得美妙


<h2 id="read">精选阅读</h2>

<h3 id="fedev">前端技术</h3>

- [ECMAScript 6入门](http://es6.ruanyifeng.com/) - 阮一峰大神所著，一本开源的JS教程 全面介绍 ECMAScript 6新引入的语法特性
- [ReactWebpackCookBook](https://fakefish.github.io/react-webpack-cookbook/index.html) - 此书会引导读者是进入```React```和```Webpack```的世界。 俩都是非常前沿的技术，同时使用会更有趣。
- [ReactNative 学习指南](https://github.com/ele828/react-native-guide) - 新玩意层出不穷... 对于能持续学习的童鞋，这是个美好的时代
- [移动前端入门](http://gold.xitu.io/entry/56c29abfa34131005b8cb1f3) - 入门价值高，移动方向常见问题的较好总结
- [GulpBook](https://github.com/nimojs/gulp-book) - Gulp 是基于 Node 实现 Web 前端自动化开发的工具

<h3 id="node_read">Node 学习资料</h3>

- [Node.js 中文资料导航](https://github.com/youyudehexie/node123) - Node 的中文资料导航，```start1300+```
- [从零开始 NodeJS 系列文章](http://blog.fens.me/series-nodejs/) - 基本上每一篇都看过，强烈推荐
- [Node.js 包教不包会](http://nqdeng.github.io/7-days-nodejs/) - 值得阅读，看完绝不用买书鸟
- [七天学会 NodeJS](https://github.com/alsotang/node-lessons) - 劳资还没看，不过看目录还不错:)
- [Style Guide](https://github.com/dead-horse/node-style-guide) - 这是一份关于如何写出一致且美观的 ```Node``` 代码的风格指南
- [koa实战](http://book.apebook.org/minghe/koa-action/index.html) - “[明河](https://github.com/minghe)出品”这四字已经说明一切。PS：正在连载中
- [stream-handbook](https://github.com/jabez128/stream-handbook) - 如果学习 NodeJS，那么流一定是需要掌握的概念

<h3 id="otherdev">其他技术</h3>
- [微信小程序开发资源汇总](https://github.com/justjavac/awesome-wechat-weapp) - 天津第一程出品。微信小程序开发资源汇总。


以下是 [@拔赤](http://weibo.com/jayli) 总结的前端技能图：
![拔赤总结的前端技能图](https://raw.githubusercontent.com/nieweidong/fetool/master/img/fe.jpg)

---

**[⬆ 返回顶部](#前端工具)**
