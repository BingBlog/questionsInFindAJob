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
