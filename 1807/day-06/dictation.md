- 1、行内样式、内嵌样式、外链样式特点？

  + 行内样式没有实现结构和样式的分离，不符合W3C标准，优先级最高
  + 内嵌样式没有和结构完全分离，只能为一个页面所用
  + 外链样式实现了样式与结构分离，符合W3C标准，样式表可以被多个html文件引用

- 2、text-align：center和 margin: 0 auto 的区别？

  + text-align:center 可以让 行内元素、文本、行内块元素 水平居中，一般设置在父元素上
  + margin: 0   auto  可以让块状元素水平居中，一般为元素自身设置

- 3、盒子阴影？盒子圆角？

  + box-shadow : 2px 2px 2px red
  + border-raidus : 3px 

- 4、昨天写页面时用到了哪些选择器？

  + 后代选择器、类选择器、标签选择器、群组选择器

- 5、有哪几种定位方式？特点是什么？

  + position:static ：静态定位，默认值

  + position:relative  ： 相对定位，坐标原点是自身的左上角点

  + position:absolute  ： 绝对定位，坐标原点是邻近的具有定位的父元素的左上角点

  + position:fixed  固定定位，坐标原点是浏览器窗口的左上角点

    元素定位了 ？position: relative\absolute\fixed

    定位用法？ 父元素相对定位，子元素绝对定位 

- 6、PC端网页布局用到了哪些CSS技术？

  + 盒模型、浮动、定位

- 7、浮动元素的特点有哪些？

  + 浮动元素脱离文档流
  + 浮动元素具有完整的盒模型（支持宽高、不存在外边距折叠、存在上下的margin和 padding）
  + 浮动元素不独占一行
  + 浮动元素撑不起父元素的高度

- 8、vertical-align 的作用是什么？

  + 解决行内元素、行内块元素垂直方向的居中问题（对浮动的元素不起作用）

- 9、display: none 、visiability:hidden 、overflow:hidden 作用和特点？

  + display: none 和 visiablity : hidden 都使元素隐藏
  + display:none 不占位置， visiablity ： hidden 占据原来的位置
  + overflow: hidden  使溢出的子元素溢出部分隐藏

- 10、背景属性有哪些？分别有什么作用？

  + background-color : 背景颜色
  + background-image ：url()   背景图片
  + background-repeat： no-repeat\repeat-x\repeat-y   背景不重复、在 X轴重复、在Y 轴重复
  + background-size：contain、cover、100% 100%  背景图片大小 
    + contain : 背景图片刚好放入盒子
    +  cover ： 背景图片刚好覆盖盒子
    + 100% 100%  ： 背景图片拉伸，刚好填满盒子，背景图片有可能变形
  + background-position：10px 20px /center center  背景图片的位置
  + background-attachment ： fixed/scroll   
    + fixed  : 背景图片不会跟随盒子滚动
    + scroll : 默认值，背景图片和盒子一起移动

- 11、单词：菜单、导航、登录、注册、内容、选项卡、标志

  + menu  \ nav \ login \ register \ content \ tab \ logo

- 12、z-index 的作用是什么？

  + 控制定位元素的层叠顺序
  + z-index 只能取整数，一般取正整数

- 13、字体属性有哪些？作用是什么？

  + font-size: 10px /100%
  + font-weight:bold /normal /100-900  : 字体粗细
  + font-style：normal / italic                字体风格
  + font-family: 'Microsoft Yahei' , 'arial' , '宋体'     字体类型
  + font：20px/1.5   'Microsoft Yahei' , 'arial'

- 14、div.nav>ul.nav-wrapper>li.nav-item{$}*3  生成的标签是什么？

  ```html
     <div class="nav">
          <ul class="nav-wrapper">
              <li class="nav-item">1</li>
              <li class="nav-item">2</li>
              <li class="nav-item">3</li>
          </ul>
      </div>
  ```

- 15、能够被继承的CSS 属性有什么？

  + text-\font-\line-

- 16、为什么要清除浮动？怎么清除浮动？清除浮动的类怎么写？

  + 浮动的元素脱离文档流，撑不起父元素的高度（定位的元素也撑不起父元素的高度）

  + 给父元素添加一个clearfix 类

  + >.clearfix:after{
    >
    >​     content:"",
    >
    >​     display:block;
    >
    >​     clear:both
    >
    >}
    >
    >.clearfix{
    >
    >​      zoom:1
    >
    >}
    >
    >

- 17、cursor 的作用是什么？如何去除输入框的高亮效果？

  + 改变鼠标样式（小手：pointer）
  + ouline:none

- 18、样式的一般书写顺序是什么？

  + >.nav {
    >
    >  float/position
    >
    >  width/height
    >
    >  margin/padding
    >
    >  background/text/font
    >
    >}
    >
    >.nav .nav-item{
    >
    >}
    >
    >.nav .nav-item .nav-link{
    >
    >}
    >
    >

​    