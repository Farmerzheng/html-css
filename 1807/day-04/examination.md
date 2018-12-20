# 除去列表的小圆点： list-style:none

# 除去a 标签的下划线：text-decoration:none

# 设置行高 60px ： line-height:60px

# 字体大小14px : font-size:14px

# 文本水平居中： text-align:center

# 背景颜色蓝色 ： background-color:blue

# 变成行内块 ： display:inline-block

# 1px 实心黄色边框 ： border:1px solid yellow

# 变成块状元素： display: block

# 文本缩进10px : text-indent:10px

# 字体颜色红色 ： color:red

# 字体设置成24px、1.5倍行高 、微软雅黑： font:24px/1.5  'Microsoft Yahei','楷体'

# 盒模型组成： content padding border margin

# padding-top:10px

# margin-bottom:20px

# padding:10px 20px(上下10px 、左右20px)

# 外边距折叠：

垂直方向的两个盒子外边距相交时会发生折叠，折叠后的外边距是较大的那个外边距

# 常用选择器

标签选择器、通用选择器、类选择器、id选择器、交叉选择器、伪类选择器

群组选择器、后代选择器、父子选择器、相邻选择器、兄弟选择器、属性选择器



# 粗体

font-weight:bold

# 正体

font-style:normal

# 斜体标签和加粗标签

i、 em、b、strong

# 字体类型为宋体

font-family: '宋体'

# 背景相关属性

background-color:背景颜色

background-image：背景图片

background-repeat：背景图片是否重复（no-repeat\repeat-x\repeat-y）

background-size：背景图片的大小(cover\contain\100% 100%)

background-position：背景图片的位置(center center\10px 20px)

background-attachment：背景图片是否滚动(fixed \scroll)

# 伪类选择器



li:hover{

​    background-color:red

}

# 背景图片不跟随盒子的滚动

background-attachment:fixed

# 哪些属性能继承

text- 、line- 、font-

# 表格边框合并

border-collapse:collapse

# 5px 圆角

border-radius:5px

# 所有标签的 margin和padding都设为0

```css
*{
    margin:0;
    padding:0
}
```

# 在新窗口当中打开网页

```html
<a href='http://www.baidu.com' target='_blank'>百度</a>
```

# 表单控件

```
<input type='text'> 文本输入框
<input type='password'> 密码输入框 
<input type='button'> 普通按钮 
<input type='submit'> 提交按钮 
<input type='reset'> 重置按钮 
<input type='radio'> 单选按钮
<input type='checkbox'> 复选按钮
<input type='datetime'> 日期控件
<input type='number'> 数值控件
<input type='email'> 邮件控件
<input type='url'> 网址控件

下拉菜单

<select>
   <option>苹果<option>
   <option>香蕉<option>
   <option>橘子<option>   
<select>

富文本框

<textarea></textarea>

```



# 块状元素、行内元素、行内块元素 

```
块状元素：独占一行：支持宽高
代表标签：h1~h6、p、div、ul、ol、dl、li、form、table


行内元素：不独占一行，不支持宽高
代表标签：span、a、i、em、 strong、b

行内块元素：不独占一行，支持宽高
代表标签:img、input、textarea
```

