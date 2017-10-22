# skye-s-website
hello,I'm skye,welcome to my website~

### presentation：<br>https://jlskye.github.io/skye-s-website/index.html
# --------------Owl Carousel --------------------
简介（reference：http://www.dowebok.com/93.html）

Owl Carousel 是一个强大、实用但小巧的 jQuery 幻灯片插件，它具有一下特点：

    兼容所有浏览器
    支持响应式
    支持 CSS3 过度
    支持触摸事件
    支持 JSON 及自定义 JSON 格式
    支持进度条
    支持自定义事件
    支持延迟加载
    支持自适应高度

使用方法

1、引入文件

    <link href="css/owl.carousel.css" rel="stylesheet">
    <link href="css/owl.theme.css" rel="stylesheet">
    <script src="js/jquery.min.js"></script>
    <script src="js/owl.carousel.js"></script>
2、HTML

    <div id="owl-demo" class="owl-carousel">
        <div>1</div>
        <div>2</div>
        <div>3</div>
        <div>4</div>
        <div>5</div>
        <div>6</div>
        <div>7</div>
        <div>8</div>
    </div>
3、JavaScript

    $(function(){
        $('#owl-example').owlCarousel();
    });

-------------------html5shiv.js-------------------<br>
html5shiv is an HTML5 JavaScript shim for IE to recognise and style the HTML5 elements
------------backbone的API这的中文文档----------<br>
http://www.shouce.ren/doc/backbone<br>
https://github.com/chadwithuhc/jQuery-plugin-js<br>
 -------------Particles.js入门: 用于创建粒子系统的JavaScript库---------
# 安装和使用

导入Particles.js，你可以使用自己的服务器或使用别人提供的：

<script src="//cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
step1:
        设置包含粒子的dom元素style样式
step2：
        html中加入div标签
step3：
           <script>
              particlesJS(); //初始化库并使用默认参数创建一个基本的粒子系统
           </script>

 reference--http://blog.topspeedsnail.com/archives/9289

------------------wow-1.3.0.min.js---------------
# 简介
    WOW.js 是一个基于 animate.css 的动画效果库，使用简单。

- 基本使用
    WOW.js 依赖于 animate.css ，所以使用前需引用 animate.css 。

        <link rel="stylesheet" href="css/animate.css">
        <script src="js/wow.min.js"></script>
- 初始化
        <script>
         new WOW().init();
        </script>

WOW.js 根据 wow 类标记需要添加动画效果的元素：
        <div class="wow">
          Content to Reveal Here
        </div>
再通过特定的类型设置动画类型，比如 bounceInUp 可以设置 自上而下的反弹效果 ：
        <div class="wow bounceInUp">
          Content to Reveal Here
        </div>
至此，已经实现了滚动时的动画效果。

高级设置
   data-wow-duration：动画的持续时间
   data-wow-delay：动画出现的延迟
   data-wow-offset：动画的偏移距离（相对于浏览器底部）
   data-wow-iteration：动画出现的重复次数

        <section class="wow slideInLeft" data-wow-duration="2s" data-wow-delay="5s">
        </section>

        <section class="wow slideInRight" data-wow-offset="10"  data-wow-iteration="10">
        </section>
配置
boxClass: Class name that reveals the hidden box when user scrolls.

animateClass: Class name that triggers the CSS animations (’animated’ by default for the animate.css library)

offset: Define the distance between the bottom of browser viewport and the top of hidden box. When the user scrolls and reach this distance the hidden box is revealed.

        wow = new WOW(
          {
            boxClass:     'wow',      // 需要执行动画的元素的 class
            animateClass: 'animated', // animation.css 动画的 class
            offset:       0,          // 距离可视区域多少开始执行动画
            mobile:       true,       // 是否在移动设备上执行动画
            live:         true        // 异步加载的内容是否有效
          }
        )
        wow.init();
