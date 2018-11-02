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
  - [前端面试](#interview)
  - [其他技术](#otherdev)
- [速查手册](#handbook)
- [前端炫技-炫酷狂拽叼炸天的 Web](#cool)
- [小结](#summary)
- [TODO](#todo)

## 正文

<h4 id="plugins">插件</h4>

<h6 id="features">功能插件</h6>

- [jedate](http://www.jemui.com/uidoc/jedate.html) - 是一款原生JS开发的 不依赖任何第三方库 大众化的日期控件
- [jquery.cityselect](https://github.com/akveo/blur-admin) - jQuery+JSON的省市三级、二级联动插件制订此文档。
- [three.js](https://github.com/mrdoob/three.js) - JavaScript 3D 库。超多的 [examples](http://threejs.org/examples/) 等着你去发现，你只需要关注内存和风扇就行了
- [ECharts](http://echarts.baidu.com/index.html) - 好用，最关键的是支持的图表展示非常之多，强烈推荐
- [ScrollReveal](https://github.com/jlmakes/scrollreveal.js) - star 10000+ 轻量级 JS 库。作用为当元素进入视窗的时候展示它们，README 中有示例，上手非常简单。官网体验地址：[ScrollReveal](https://scrollrevealjs.org/)
- [mixitup](https://github.com/patrickkunka/mixitup) 一款基于 ```jQuery``` 的 **排序/过滤** 的JS库，最关键是有着美妙的动画效果
- [ant.design](http://ant.design) - 蚂蚁金服搞的良心项目，文档美好的令人发指 样式优雅，强烈推荐内部系统尝试此库
- [highlightjs](https://highlightjs.org/) - 代码高亮库，支持非常多的语言
- [daterangepicker](http://www.daterangepicker.com) - 时间选择插件的不二选择，基于 ```Bootstrap``` 和 [Moment.js](http://momentjs.com/)
- [nodePPT](https://github.com/ksky521/nodePPT) - 前同事三水的大作，好用必须得支持:) 用 Markdown 写 PPT，还可以 HTML 混排，上手飞快
- [excellentexport](https://github.com/jmaister/excellentexport) - 纯前端的 Excel 导出，非常之方便
- [Sortable](https://github.com/RubaXa/Sortable) - 拖拽神器，用了就知道
- [toastr](https://github.com/CodeSeven/toastr) - 信息提示的库，推荐的原因是卖相好、功能强大  [demo](http://codeseven.github.io/toastr/demo.html)
- [peity.js](http://benpickles.github.io/peity/) - jQuery的图表插件，特别cute，感觉萌萌哒 将HTML转换成一个小的```<svg>```饼图、圆环图、折线图等等
- [html2canvas](https://github.com/niklasvh/html2canvas)+[canvas2Image](https://github.com/randreucetti/canvas2image) - 看这两库的名称就明白是做什么的。使用场景就是“动态生成的HTML可以长按保存为图片”。
- [Push.js](https://github.com/Nickersoft/push.js) - 基于 ```Notification API``` 实现的桌面效果的提示栏。浏览器支持情况不错，如[http://caniuse.com/#search=Notification](http://caniuse.com/#search=Notification)
- [Highcharts](http://www.hcharts.cn/) - Highcharts 中文网，又是一个图表库 确实功能强大，但是觉得不好看... PS：官网就做的不好看，脏脏的赶脚
- [NProgress](https://github.com/rstacruz/nprogress/) - 使页面加载时有更好的loading效果
- [onepage-scroll](https://github.com/peachananr/onepage-scroll) - 依赖 jQuery 的单页滚动库，和 [fullPage](http://alvarotrigo.com/fullPage/) 类似
- [videojs](http://videojs.com/) - 当下视频需求都用上```<video>```鸟 样式和交互统一的问题交给 videojs 搞定:)
- [clipboard](http://zenorocha.github.io/clipboard.js/) - 仅 2KB 大小，搞定剪贴板功能，屌不屌~ 但是，Safari 不支持...


> ___```Swiper/PhotoSwipe/fullPage``` 有这仨库，微信里常见的 H5 页完全不是问题哒___

<h6 id="images">图片类插件</h6>

- [Swiper](http://www.swiper.com.cn) - 强大的 Slider 库 其实这类效果库非常多，但文档能那么专业的就很少鸟
- [手风琴效果](http://www.jq22.com/yanshi16288) - jquery仿手风琴效果
- [jquery.lazyload](http://www.jq22.com/yanshi390) - jQuery图片延迟加载插件jQuery.lazyload,使用延迟加载在可提高网页下载速度。在某些情况下，它也能帮助减轻服务器负载。
- [PhotoSwipe](http://photoswipe.com/) - 偶常用的 js 库 官网上有这么一句很关键、重要"no dependencies"
- [Cropper](http://fengyuanchen.github.io/cropper/) - 国人开发的图片裁剪库
- [emojify.js](https://github.com/Ranks/emojify.js) - 能够将```emoji```关键词转换为```emoji```图片的```JS```插件 可以快速的为你的网站提供```emoji```表情支持
- [favico.js](http://lab.ejci.net/favico.js/) - 动态改变浏览器标签栏中的网站图标，非常好玩

<h6 id="mobile">移动端插件</h6>

- [adaptive.js](https://github.com/Vibing/adaptive) - 借鉴手淘方案，adaptive.js将整个页面宽度平均分成10份，以clineWidth / 10的结果作为html标签的font-size值。 布局中使用rem作为单位。举例：某UI设计出来的手机页面宽为750px，那么分成十份后为75px，此时html标签的font-size: 75px, 布局时某一模块在设计稿上宽为100px，转成rem则为：100 / 75 = 1.3333rem;在css中则为：width: 1.3333rem。
- [FlipClock](http://www.flipclockjs.com/) - FlipClock.js 是一个制作精美时钟，定时器和倒计时的 jQuery 插件，并且可以完全通过 CSS 进行定制。有设置为自动启动，存在多种方法控制（启动，停止，getTime，setTime..），支持回调函数，此外，它还有一个全功能的API，能够进一步扩展功能。
- [iosSelect](http://zhoushengfe.com/iosselect/website/index.html) - 仿IOS端选择器插件，支持日期、地区等
- [移动端滑动插件better-scroll](http://ustbhuangyi.github.io/better-scroll/doc/zh-hans/#better-scroll) - better-scroll 是一款重点解决移动端（已支持 PC）各种滚动场景需求的插件。better-scroll 是基于原生 JS 实现的，不依赖任何框架。它编译后的代码大小是 63kb，压缩后是 35kb，gzip 后仅有 9kb，是一款非常轻量的 JS lib。
- [fastclick](https://majing.io/posts/10000007721218) - 移动设备上的浏览器默认会在用户点击屏幕大约延迟300毫秒后才会触发点击事件，这是为了检查用户是否在做双击。为了能够立即响应用户的点击事件，才有了FastClick。

<h6 id="framework">开发框架以及工具库</h6>

- [JQUEY](https://www.jquery123.com/) - 全部版本JQUEY库以及各版本API差异
- [Vuejs](http://cn.vuejs.org) - 渐进式JavaScript 框架
- [Noticejs](https://github.com/jaredreich/notie.js) - 一个简单的通知库，木有依赖

<h3 id="html">HTML</h3>

纯 ```HTML``` 相关其实没有好玩的项目，所以这儿展示的内容主要都是一些模板，而且以下列出来的都是免费的，方便拿取搭架后台或者博客

- [HEAD](https://github.com/joshbuchea/HEAD) - 最全的 ```<head>``` 列表，真心佩服这种偏执的整理能力
- [blur-admin](https://github.com/akveo/blur-admin) - 视觉冲击极强的管理后台，各种动画效果。PS：因为团队有[ant-design](https://github.com/ant-design/ant-design)的使用经验，感觉使用起来不是很顺畅，这套后台又是基于```AngularJS```，所以再三权限之后还是没实际使用，劳资还是别给团队添乱了，囧...
- [AdminLTE](https://github.com/almasaeed2010/AdminLTE) - 很小清新的后台模板，每次看[preview](https://almsaeedstudio.com/preview) 页面都觉得很有视觉冲击
- [gentelella](https://github.com/puikinsh/gentelella) - 刚用这个搭建了我司内部用的的数据平台，效果喜人。模板实现的功能比较全，比如登录、注册甚至各种 ```widget```，所以最终交付的时候，自己几乎没写几行CSS。
- [material-design-lite](https://github.com/google/material-design-lite) - ```Star``` 数超过2W的开源模板项目，包含了多套简洁的 ```templates```，可以用于博客、后台或者企业首页。

<h3 id="css">CSS</h3>

- [MetroUI](http://metroui.org.ua/) - 好看好用，重点是样式特别、个性
- [Font-Awesome](http://fontawesome.io/) - 图标字体库。相类似的库有不少，大厂都喜欢造轮子嘛:)
- [LoadersCSS](https://connoratherton.com/loaders) - 用 CSS 技术实现 loading 动画； 补一句，想熟悉、理解 ```keyframes、animation、transform、transition``` 的童鞋可以直接去读其源码(只有千把行代码)，读完就算出师鸟:)
- [text-spinners](https://github.com/tawian/text-spinners) - 又是一款 spinners 效果的库，用来做 loading 正合适。
- [WeUI](https://github.com/weui/weui) - 一套同微信原生视觉体验一致的基础样式库 为微信 Web 开发量身设计，令用户的使用感知更加统一
- [PostCSS](https://github.com/postcss/postcss) - 最近才知道大名鼎鼎[Autoprefixer](https://github.com/postcss/autoprefixer)是其插件 推荐大漠的文章[《PostCSS深入学习》](http://www.w3cplus.com/PostCSS/postcss-deep-dive-what-you-need-to-know.html)，有关 PostCSS 不是什么？PostCSS 是什么？PostCSS 可以做什么等等问题，文章里面有答案
- [CSSgram](https://github.com/una/CSSgram) - 图片滤镜库，终于可以用 CSS 在 web 上实现滤镜的效果鸟 IE不支持，不过新的移动设备支持没问题 [Can I Use](http://caniuse.com/#search=CSS%20Blend%20Modes)
- [HINT.css](https://github.com/chinchang/hint.css) - 一款非常小巧的提示框效果
- [Balloon.css](http://kazzkiq.github.io/balloon.css/) - 同上，一款非常小巧的提示框效果
- [Hover.css](http://ianlunn.github.io/Hover/) - 很多鼠标 Hover 态的效果，可以给产品学习一下:)
- [Cursor](http://css-cursor.techstream.org/) - 记录各浏览器对Cursor的支持情况
- [csscss](https://github.com/zmoazeni/csscss) - 用于检查 CSS 代码冗余
- [purecss](http://purecss.io/) - 小巧的响应式 CSS 库，Yahoo!出品
- 
- [hamburgers](https://jonsuh.com/hamburgers/) - 简单的动画库，让 Click(or Tap) 变得美妙
- [cssmatic](http://www.cssmatic.com) - 一个帮忙调试CSS效果的工具


<h2 id="read">精选阅读</h2>

<h3 id="fedev">前端技术</h3>

- [前端开发规范手册](http://zhibimo.com/read/Ashu/front-end-style-guide/index.html) -  此手册主要实现的目标：代码一致性和最佳实践
- [ECMAScript 6入门](http://es6.ruanyifeng.com/) - 阮一峰大神所著，一本开源的JS教程 全面介绍 ECMAScript 6新引入的语法特性
- [ReactWebpackCookBook](https://fakefish.github.io/react-webpack-cookbook/index.html) - 此书会引导读者是进入```React```和```Webpack```的世界。 俩都是非常前沿的技术，同时使用会更有趣。
- [Sass指南](https://github.com/W3cplus/sass-guidelines) - Sass指南主要作用是用来帮助大家更好的书写 Sass和维护 Sass。
- [ReactNative 学习指南](https://github.com/ele828/react-native-guide) - 新玩意层出不穷... 对于能持续学习的童鞋，这是个美好的时代
- [HTML/CSS 编码规范](http://www.css88.com/doc/codeguide/) - 编写灵活、稳定、高质量的```HTML```和```CSS```代码的规范
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

<h3 id="interview">前端面试</h3>

- [笔试面试知识整理](https://github.com/HIT-Alibaba/interview) - 打开其 Gitbook 上的地址我都惊呆了。虽然有部分内容待完善，但是光浏览目录都是享受。
- [在 LinkedIn 做面试官的故事](http://dongfei.baijia.baidu.com/article/52449) - 非面试题，介绍 LinkedIn 的面试过程 文章有很多中肯的建议和想法，推荐阅读
- [大漠：写给前端面试者](http://www.w3cplus.com/css/write-to-front-end-developer-interview.html) - 这篇文章不涉及任何的面试题 大漠与大家聊聊面试者与被面者之间的感受...
- [前端面试题](https://github.com/h5bp/Front-end-Developer-Interview-Questions/tree/master/Translations/Chinese) - Git 上非常火的前端面试题，```start17k+```
- [前端面经](https://github.com/paddingme/Front-end-Web-Development-Interview-Question) - 主要内容是些前端面试笔试题和面试套路，值得阅读

<h3 id="otherdev">其他技术</h3>

- [微信小程序开发资源汇总](https://github.com/justjavac/awesome-wechat-weapp) - 天津第一程出品。微信小程序开发资源汇总。
- [命令行的艺术](https://github.com/jlevy/the-art-of-command-line/blob/master/README-zh.md) - 熟练使用命令行是优秀工程师的基础


<h2 id="tools">工具/软件</h2>

<h3 id="web">Web</h3>

- [百度脑图](http://naotu.baidu.com) - 非常方便的思维导图工具。功能强、样式佳、无广告，算百度出的良心产品之一。除了 Evernote，脑图是我非常依赖的记录工具
- [CanIuse](http://caniuse.com/) - __前端必备__；查看浏览器对各种新特性的兼容情况
- [overapi](http://overapi.com/) - 最全的开发人员在线速查手册
- [ProcessOn](https://www.processon.com/) - 和百度脑图的功能类似，脑图工具。但是还有社交、通讯的功能，提倡 **协作绘图** 的理念。感觉网页跳转的时候有点慢，模板样式比百度脑图好看(个人观点)，而且团队协作的功能真的相当好用。
- [Slides](https://slides.com/) - 一个所见即所得的 WebPPT 编辑器。虽然装X效果一般，但是比较推荐，因为无论懂不懂 UI，做出来的效果不会太难看
- [faviconer.co](http://www.faviconer.co/) - 一个所见即所得的icon生成器，很好用
- [smallpdf](http://smallpdf.com/cn) - 提供各种格式和 PDF 互相转换
- [Cmd Markdown](https://www.zybuluo.com/mdeditor) - 好用的 Web 版 Markdown 编辑器
- [VimAwesome](http://vimawesome.com/) - Vim 插件集合，__Vim 党必备__
- [Tower](https://tower.im) - 小而美的多人协同工具。 不光只有 Web 版，还有 iPhone、iPad、Android、微信版。
- [StackEdit](https://stackedit.io/editor) - 又是一款 Web 版 Markdown 编辑器
- [墨刀](https://modao.cc/) - 一个在线移动应用原型制作工具。 旨在帮助产品经理快速制作可在手机端展示的移动应用原型。
- [htm2pdf](http://www.htm2pdf.co.uk) - HTML to PDF
- [Speaker Deck](https://speakerdeck.com/p/featured) - 在线的演讲稿展示平台
- [RunJS](http://runjs.cn/) - 在线编辑、展示、分享、交流你的 ```JavaScript``` 代码
- [Bootswatch](https://bootswatch.com/) - ```Bootstrap``` 的免费模板
- [AdminLTE](https://github.com/almasaeed2010/AdminLTE/) -  又是一个 ```Bootstrap``` 的免费管理后台
- [carbon](https://carbon.now.sh) - 能够帮助你分享漂亮的示例代码


<h3 id="git">Git</h3>

- [Git 教程-廖雪峰](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000) - 俺有看过不少 Git 的文章，确实这个系列是最通俗易懂的
- [GitAwards](http://github-awards.com/) - Git 工具，可以查看 Git 排名
- [Git 速查](https://github.com/flyhigher139/Git-Cheat-Sheet) - 分类清晰的速查表
- [Git 简明指南](http://rogerdudler.github.io/git-guide/index.zh.html) - 入门```Github```的简明指南，木有高深内容:)
- [Git 学习资料整理](https://github.com/xirong/my-git) - 内容包括很多 Git 的相关资料，```star 1200+```
- [GitHub 漫游指南](https://github.com/phodal/github-roam) - 一篇还算不错的 Git 学习总结，就是乱了点... 我理解作者___漫游___的意思是漫无目的想到哪写到哪~ 看到作者为鸟达成 Git 连击的成就，也是蛮拼的:)

<h3 id="handbook">速查手册</h3>

> RT，这篇都是些文档或者API，一般这类东西都在大家浏览器的书签内，偶这也列一下大前端常用的手册地址

- [JavaScript Standard Style](http://standardjs.com/) - 强烈推荐，尤其适合技术 Leader。优秀的 JS 编码规范是好前端团队的开始
- [HEAD](https://github.com/joshbuchea/HEAD) - 最全的 ```<head>``` 列表，真心佩服这种偏执的整理能力
- [百度CDN公共库](http://cdn.code.baidu.com/) - 基本常见的库都收录拉，搞 demo 的时候特方便
- [HTML 和 CSS 代码规范](http://codeguide.bootcss.com/) - 编写灵活、稳定、高质量的 HTML 和 CSS 代码的规范
- [Linux命令中文手册](http://linux.51yip.com) - 木有系统的好好学习 Linux，所以命令更不熟悉 真羡慕那些CLI玩的飞起的:)
- [Git 速查](https://github.com/flyhigher139/Git-Cheat-Sheet/blob/master/Git%20Cheat%20Sheet-Zh.md) - 分类清晰的速查表
- [jQueryAPI 1.11.3](http://jquery.cuishifeng.cn/) - ZeptoAPI 基本和 jQuery 一样，所以看一份就好
- [CSS](http://www.css88.com/book/css/) - CSS 在线参考手册
- [Redux 中文文档](http://cn.redux.js.org/index.html) - 作为个前端，React 还是得尝试下的。英文文档就不给大家推荐了~
- [Express API](http://www.expressjs.com.cn/4x/api.html) - 中文手册:) 4.x和3.x都有
- [CI用户指南](http://codeigniter.org.cn/user_guide/index.html) - 一个轻量级的 PHP 框架用户指南 推荐指数低的原因是劳资PHP比较弱，囧
- [Yaf](http://www.laruence.com/manual/) - 鸟哥(惠新宸)所写的 PHP 框架 推荐指数低的原因同上...

<h3 id="cool">前端炫技-_炫酷狂拽叼炸天站点_</h3>

- [three.js](https://github.com/mrdoob/three.js) - JavaScript 3D 库。超多的 [examples](http://threejs.org/examples/) 等着你去发现，你只需要关注内存和风扇就行了
- [windows93](http://www.windows93.net/) - 模拟 Win93 桌面，思路、体验和整体效果比较有意思
- [GeekTyper](http://geektyper.com/) - 好玩又具有 Geek 精神的网站，虽然创建的目的是个恶作剧 PS：网站需要翻墙
- [2016.makemepulse.com](http://2016.makemepulse.com/) - 帅哭了。请使用现代浏览器打开
- [前端技能栈](http://skill.phodal.com/) - 好玩的前端技能栈展示
- [Mapbox](https://www.mapbox.com/) - 非常叼的开源项目，有方便的 JSAPI(还有 SDK)。 不过免费版只能浅尝，流量有限。 PS：网站需要翻墙
- [mixitup](https://mixitup.kunkalabs.com/) 一款基于 ```jQuery``` 的 **排序/过滤** 的JS库，最关键是有着美妙的动画效果
- [Clark Duvall](http://www.clarkduvall.com/) - 一枚歪果仁的个人 blog，范儿叼叼的
- [earth](https://github.com/cambecc/earth) - 全球天气的可视化项目
- [SuperScrollorama](http://johnpolacek.github.io/superscrollorama/) - 好玩好看的动画库，链接是 SuperScrollorama 的展示页
- [parallax.js](http://matthew.wagerfield.com/parallax/) - 一个视差引擎的官网，在电脑和手机上都有很好的体验
- [CSS字母](http://yusugomori.com/projects/css-sans/fonts) - 用 CSS 实现英文字母，叼叼的
- [墨刀](https://modao.cc/) - 一个在线移动应用原型制作工具。 旨在帮助产品经理快速制作可在手机端展示的移动应用原型。


以下是 [@拔赤](http://weibo.com/jayli) 总结的前端技能图：
![拔赤总结的前端技能图](https://raw.githubusercontent.com/nieweidong/fetool/master/img/fe.jpg)

---

完善 ing，慢慢把 __Evernote__ 和 __浏览器书签__ 里面的好东西慢慢捣腾到这儿，更欢迎 PR，谢谢。

**[⬆ 返回顶部](#前端工具)**
