# HTML && CSS
1. HTML5语意化标签 (header,footer,section,nav,aside,video,canvas,time,audio,datalist,dialog,figure,hgroup,mark,menu,abbr,article,detail)
2. HTML5新增标签的兼容性 (createElement或者html5shiv) 需要自己在低版本浏览器中尝试一下
3. pc端字体小于12px （transform: scale();transform-origin:）
4. 移动端rem遇到的问题（字体和小像素以及在写代码时不方便的问题，使用Flexible实现手淘H5页面的终端适配 https://github.com/amfe/article/issues/17 ）
5. 相对绝对定位
6. 圣杯布局
7. BFC,IFC 行内元素和块元素 http://www.cnblogs.com/greenal/archive/2013/01/05/2845513.html  CSS中的BFC https://github.com/dwqs/blog/issues/22  到底什么是BFC、IFC、GFC和FFC http://www.jshacker.com/note/3608
8. 垂直居中，单行多行，块元素 关于居中的经典文章 https://css-tricks.com/centering-css-complete-guide/
9. css3实现居中 tranform: translate(-50%; -50%);
10. css3新特性有哪些 (属性选择器，伪类选择器，多图背景，文字阴影，块级阴影，圆角，渐变，过渡渐变(transition)，transform，@font-size，word-wrap，text-overflow，text-decoration，)
11. HTML5新增了哪些内容或API，使用过哪些
12. input和textarea的区别
13. 用一个div模拟textarea的实现
14. 左右布局：左边定宽、右边自适应，不少于3种方法
15. CSS3用过哪些新特性
16. 对栅格的理解
17. flex布局 Flex 布局教程-语法篇 http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html
18. 1像素边框问题, 移动端 淘宝：viewprot+rem  比较好的方法：伪类 + transform
19. 垂直居中布局的属性，有哪些值，设置为百分百是相对于，设置为数字是相对于
20. CSS权重计算 https://ofcss.com/2011/05/26/css-cascade-specificity.html

# JavaScript
1. JavaScript基本类型
2. HTML5新增API (fileAPI,geolacation,localStorage,pageVisibilityApi,webworker,websocket,canvas,svg,historyApi)
3. 块状作用域和函数作用域
4. 变量提升，函数表达式提升，函数声明提升
5. 原型，组合寄生继承，es6继承
6. 定时器的入栈
7. 闭包的作用和带来的问题
8. AMD cmd seajs require commonjs require原理 seaJS原理 seaJs http://island205.github.io/HelloSea.js/
9. this
10. es6
11. cookie localstorage sessionstorage
12. websocket
13. jQuery trigger
14. jsonp回调函数的存放位置
15. img数据上报
16. 图片懒加载
17. 实现页面加载进度条
18. 事件委托的原理
19. 实现extend函数
20. 事件代理模型，代理模型中如何实现阻止冒泡，点击事件中的target和currentTarget
21. jsonp原理、postMessage原理
22. 实现拖拽功能，比如把5个兄弟节点中的最后一个节点拖拽到节点1和节点2之间
23. 动画：setTimeout何时执行，requestAnimationFrame的优点
24. 手写parseInt的实现：要求简单一些，把字符串型的数字转化为真正的数字即可，但不能使用JS原生的字符串转数字的API，比如Number()
25. 编写分页器组件的时候，为了减少服务端查询次数，点击“下一页”怎样能确保还有数据可以加载（请求数据不会为空）？
26. ES6新增了哪些特性，使用过哪些，也有当场看代码说输出结果的
27. JS模块化的实践
28. require.js的实现原理（如果使用过webpack，进一步会问，两者打包的异同及优缺点）
29. promise的实现原理，进一步会问async、await是否使用过
30. 实现gulp的功能
31. 使用前端框架（angular/vue/react）带来哪些好处，相对于使用jQuery
32. 点击穿透的问题
34. jQuery事件 http://harttle.com/2015/06/26/jquery-event.html

# React
1. React的事件系统，合成事件与原生事件
2. React CSS 解决方案


# http
1. http状态码
2. 304原理，cache-control的具体值
3. keep-alive
4. GET POST的区别

# 浏览器
1. 内存泄露
2. xss注入
3. 浏览器内核

# Vue
1. vue双向绑定原理
2. Vue computed method
3. Vue v-bind src  ()
4. Vue keep-alive   ?
5. Vue v-if 和 v-show
6. Vue的特性，如何实现组件间数据传递，Vuex的原理，Vue-router的渲染原理(hash和historyAPI)
7. vue双向数据绑定的实现
8. 单页应用，如何实现其路由功能

# 性能优化
1. 项目中使用过哪些优化方法
2. 输入一个URL，Enter之后发生了什么
3. （承上）页面的渲染过程
4. 优化中会提到缓存的问题，问：静态资源或者接口等如何做缓存优化
5. 页面DOM节点太多，会出现什么问题？如何优化？

# 项目经历

这些大公司招聘都是高级工程师起步，所以对简历上的项目会刨根问底。很多很多问题都是由项目中拓展开的，像优化相关的东西，还有前面提到的require.js、promise、gulp，项目中用到了某项技术，高级工程师的要求是：不仅会用，更要知道其原理。

对自己的提醒：项目中用到的技术，不能说完全掌握其原理吧，但大致的实现还是有必要了解一下的。

1. 介绍一下你做的这个项目，进一步细问：整个项目有哪些模块，你主要负责哪些
2. 你在项目中的角色
3. 你在项目中做的最出彩的一个地方
4. 碰到过什么样的困难，怎么解决的
5. （如果你是这个项目的负责人），任务怎么分配的，有没有关注过团队成员的成长问题
6. 前端安全问题：CSRF和XSS

# 其它
1. 微信弹窗漏洞
2. react ng
3. video兼容性  ?
4. 为什么选择做前端（我靠，我都快转前端两年了，还在问这个问题啊…）
5. 你希望进入一个什么样的团队
6. 你有什么问题想问我（面试官）的吗？

# 接下来的学习计划
1. 实现一个事件模型，实现一个代理事件模型
2. 使用seaJS搭建一个项目框架，并理解其加载原理
3. 思考并理解一个dom选择器的实现步骤


## 阿里

使用过的koa2中间件
koa-body原理
介绍自己写过的中间件
有没有涉及到Cluster
介绍pm2
master挂了的话pm2怎么处理
如何和MySQL进行通信
React声明周期及自己的理解
如何配置React-Router
路由的动态加载模块
服务端渲染SSR
介绍路由的history
介绍Redux数据流的流程
Redux如何实现多个组件之间的通信，多个组件使用相同状态如何进行管理
多个组件之间如何拆分各自的state，每块小的组件有自己的状态，它们之间还有一些公共的状态需要维护，如何思考这块
使用过的Redux中间件
如何解决跨域的问题
常见Http请求头
移动端适配1px的问题
介绍flex布局
其他css方式设置垂直居中
居中为什么要使用transform（为什么不使用marginLeft/Top）
使用过webpack里面哪些plugin和loader
webpack里面的插件是怎么实现的
dev-server是怎么跑起来
项目优化
抽取公共文件是怎么配置的
项目中如何处理安全问题
怎么实现this对象的深拷贝


## 网易

介绍redux，主要解决什么问题
文件上传如何做断点续传
表单可以跨域吗
promise、async有什么区别
搜索请求如何处理（防抖）
搜索请求中文如何请求
介绍观察者模式
介绍中介者模式
观察者和订阅-发布的区别，各自用在哪里
介绍react优化
介绍http2.0
通过什么做到并发请求
http1.1时如何复用tcp连接
介绍service worker
介绍css3中position:sticky
redux请求中间件如何处理并发
介绍Promise，异常捕获
介绍position属性包括CSS3新增
浏览器事件流向
介绍事件代理以及优缺点
React组件中怎么做事件代理
React组件事件代理的原理
介绍this各种情况
前端怎么控制管理路由
使用路由时出现问题如何解决
React怎么做数据的检查和变化

## 滴滴

react-router怎么实现路由切换
react-router里的<Link>标签和<a>标签有什么区别
<a>标签默认事件禁掉之后做了什么才实现了跳转
React层面的性能优化
整个前端性能提升大致分几类
import { Button } from 'antd'，打包的时候只打包button，分模块加载，是怎么做到的
使用import时，webpack对node_modules里的依赖会做什么
JS异步解决方案的发展历程以及优缺点
Http报文的请求会有几个部分
cookie放哪里，cookie能做的事情和存在的价值
cookie和token都存放在header里面，为什么只劫持前者
cookie和session有哪些方面的区别
React中Dom结构发生变化后内部经历了哪些变化
React挂载的时候有3个组件，textComponent、composeComponent、domComponent，区别和关系，Dom结构发生变化时怎么区分data的变化，怎么更新，更新怎么调度，如果更新的时候还有其他任务存在怎么处理
key主要是解决哪一类的问题，为什么不建议用索引index（重绘）
Redux中异步的请求怎么处理
Redux中间件是什么东西，接受几个参数（两端的柯里化函数）
柯里化函数两端的参数具体是什么东西
中间件是怎么拿到store和action，然后怎么处理
state是怎么注入到组件的，从reducer到组件经历了什么样的过程
koa中response.send、response.rounded、response.json发生了什么事，浏览器为什么能识别到它是一个json结构或是html
koa-bodyparser怎么来解析request
webpack整个生命周期，loader和plugin有什么区别
介绍AST（Abstract Syntax Tree）抽象语法树
安卓Activity之间数据是怎么传递的
安卓4.0到6.0过程中WebView对js兼容性的变化
WebView和原生是如何通信
跨域怎么解决，有没有使用过Apache等方案

## 今日头条

对async、await的理解，内部原理
介绍下Promise，内部实现
清除浮动
定位问题（绝对定位、相对定位等）
从输入URL到页面加载全过程
tcp3次握手
tcp属于哪一层（1 物理层 -> 2 数据链路层 -> 3 网络层(ip)-> 4 传输层(tcp) -> 5 应用层(http)）
redux的设计思想
接入redux的过程
绑定connect的过程
connect原理
webpack介绍
== 和 ===的区别，什么情况下用相等==
bind、call、apply的区别
动画的了解
介绍下原型链（解决的是继承问题吗）
对跨域的了解

## 有赞

Linux 754 介绍
介绍冒泡排序，选择排序，冒泡排序如何优化
transform动画和直接使用left、top改变位置有什么优缺点
如何判断链表是否有环
介绍二叉搜索树的特点
介绍暂时性死区
ES6中的map和原生的对象有什么区别
观察者和发布-订阅的区别
react异步渲染的概念,介绍Time Slicing 和 Suspense
16.X声明周期的改变
16.X中props改变后在哪个生命周期中处理
介绍纯函数
前端性能优化
pureComponent和FunctionComponent区别
介绍JSX
如何做RN在安卓和IOS端的适配
RN为什么能在原生中绘制成原生组件（bundle.js）
介绍虚拟DOM
如何设计一个localStorage，保证数据的实效性
如何设计Promise.all()
介绍高阶组件
sum(2, 3)实现sum(2)(3)的效果
react性能优化
两个对象如何比较

## 挖财

JS的原型
变量作用域链
call、apply、bind的区别
防抖和节流的区别
介绍各种异步方案
react生命周期
介绍Fiber
前端性能优化
介绍DOM树对比
react中的key的作用
如何设计状态树
介绍css，xsrf
http缓存控制
项目中如何应用数据结构
native提供了什么能力给RN
如何做工程上的优化
shouldComponentUpdate是为了解决什么问题
如何解决props层级过深的问题
前端怎么做单元测试
webpack生命周期
webpack打包的整个过程
常用的plugins
pm2怎么做进程管理，进程挂掉怎么处理
不用pm2怎么做进程管理

## 沪江

介绍下浏览器跨域
怎么去解决跨域问题
jsonp方案需要服务端怎么配合
Ajax发生跨域要设置什么（前端）
加上CORS之后从发起到请求正式成功的过程
xsrf跨域攻击的安全性问题怎么防范
使用Async会注意哪些东西
Async里面有多个await请求，可以怎么优化（请求是否有依赖）
Promise和Async处理失败的时候有什么区别
Redux在状态管理方面解决了React本身不能解决的问题
Redux有没有做过封装
react生命周期，常用的生命周期
对应的生命周期做什么事
遇到性能问题一般在哪个生命周期里解决
怎么做性能优化（异步加载组件...）
写react有哪些细节可以优化
React的事件机制（绑定一个事件到一个组件上）
介绍下事件代理，主要解决什么问题
前端开发中用到哪些设计模式
React/Redux中哪些功能用到了哪些设计模式
JS变量类型分为几种，区别是什么
JS里垃圾回收机制是什么，常用的是哪种，怎么处理的
一般怎么组织CSS（Webpack）

## 饿了么

小程序里面开页面最多多少
React子父组件之间如何传值
Emit事件怎么发，需要引入什么
介绍下React高阶组件，和普通组件有什么区别
一个对象数组，每个子对象包含一个id和name，React如何渲染出全部的name
在哪个生命周期里写
其中有几个name不存在，通过异步接口获取，如何做
渲染的时候key给什么值，可以使用index吗，用id好还是index好
webpack如何配sass，需要配哪些loader
配css需要哪些loader
如何配置把js、css、html单独打包成一个文件
div垂直水平居中（flex、绝对定位）
两个元素块，一左一右，中间相距10像素
上下固定，中间滚动布局如何实现
[1, 2, 3, 4, 5]变成[1, 2, 3, a, b, 5]
取数组的最大值（ES5、ES6）
apply和call的区别
ES5和ES6有什么区别
some、every、find、filter、map、forEach有什么区别
上述数组随机取数，每次返回的值都不一样
如何找0-5的随机数，95-99呢
页面上有1万个button如何绑定事件
如何判断是button
页面上生成一万个button，并且绑定事件，如何做（JS原生操作DOM）
循环绑定时的index是多少，为什么，怎么解决
页面上有一个input，还有一个p标签，改变input后p标签就跟着变化，如何处理
监听input的哪个事件，在什么时候触发

## 携程

手写两道算法题
对React看法，有没有遇到一些坑
对闭包的看法，为什么要用闭包
手写数组去重函数
手写数组扁平化函数
介绍下Promise的用途和性质
Promise和Callback有什么区别
React生命周期

## 喜马拉雅

ES6新的特性
介绍Promise
Promise有几个状态
说一下闭包
React的生命周期
componentWillReceiveProps的触发条件是什么
React16.3对生命周期的改变
介绍下React的Filber架构
画Filber渲染树
介绍React高阶组件
父子组件之间如何通信
Redux怎么实现属性传递，介绍下原理
React-Router版本号
网站SEO怎么处理
介绍下HTTP状态码
403、301、302是什么
缓存相关的HTTP请求头
介绍HTTPS
HTTPS怎么建立安全通道
前端性能优化（JS原生和React）
用户体验做过什么优化
对PWA有什么了解
对安全有什么了解
介绍下数字签名的原理
前后端通信使用什么方案
RESTful常用的Method
介绍下跨域
Access-Control-Allow-Origin在服务端哪里配置
csrf跨站攻击怎么解决
前端和后端怎么联调

## 兑吧

localStorage和cookie有什么区别
CSS选择器有哪些
盒子模型，以及标准情况和IE下的区别
如何实现高度自适应
prototype和——proto——区别
_construct是什么
new是怎么实现的
promise的精髓，以及优缺点
如何实现H5手机端的适配
rem、flex的区别（root em）
em和px的区别
React声明周期
如何去除url中的#号
Redux状态管理器和变量挂载到window中有什么区别
webpack和gulp的优缺点
如何实现异步加载
如何实现分模块打包（多入口）
前端性能优化（1js css；2 图片；3 缓存预加载； 4 SSR； 5 多域名加载；6 负载均衡）
并发请求资源数上限（6个）
base64为什么能提升性能，缺点
介绍webp这个图片文件格式
介绍koa2
Promise如何实现的
异步请求，低版本fetch如何低版本适配
ajax如何处理跨域
CORS如何设置
jsonp为什么不支持post方法
介绍同源策略
React使用过的一些组件
介绍Immuable
介绍下redux整个流程原理
介绍原型链
如何继承
