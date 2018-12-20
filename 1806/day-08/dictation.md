## 1、CSS 常用的背景属性

1. background-color
2. background-image
3. background-position
4. background-attachment
5. background-size
6. background-repeat

## 2、什么是外边距折叠

垂直方向上的两个盒子的外边距相交时，会发生折叠，折叠后的外边距是较大的那个外边距

## 3、行内元素（行内块元素）水平居中？单行文本垂直居中？块状元素水平居中

1. text-align:center
2. line-height===height
3. margin:0 auto

## 4、浮动的元素特点(浮动的元素具有完整的盒模型特点)？

1. 浮动会使行内元素支持宽高
2. 浮动会使行内元素存在上下margin和padding
3. 浮动会去除行内元素（行内块元素）之间的间隙
4. 浮动元素不存在外边距折叠

## 5、为什么需要清楚浮动？如何清除浮动（写出具体代码）？

浮动的子元素撑不起父元素的高度

为浮动元素的父元素添加一个clearfix 类

```css
.clearfix:after{
    content:'';
    display:block;
    clear:both
}
.clearfix{
    zoom:1
}
```

## 6、常见定位方式有哪些？坐标原点都是什么？

1. 静态定位：position:static   没有坐标原点
2. 相对定位： position:relative   坐标原点是自身的左上角点
3. 绝对定位：position:absolute  坐标原点是具有定位的父盒子的左上角点
4. 固定定位： position:fixed  坐标原点是窗口的左上角点

## 7、如何去除a链接下划线？如何给盒子添加阴影？z-index的作

## 用是什么？圆角属性？

text-decoration:none

box-shadow: 2px 2px 4px red;

z-index 的作用是控制定位元素的层叠顺序

border-radius: 1px 2px 3px 4px 

## 8、display 有哪些属性？作用是什么？

1. display:inline   将元素转换成行内元素
2. display:inline-block   将元素转换成行内块元素
3. display:block  将元素转换成块状元素
4. display:none  隐藏元素
5. display: table  将元素转换成表格