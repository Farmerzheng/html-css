# 1、CSS 复合选择器有哪些？基础选择器有哪些？

-   后代选择器 .nav .nav-item
-   父子选择器 .nav>.nav-item
-   兄弟选择器 .nav~.nav-item
-   相邻选择器 .nav+.nav-item
-   属性选择器 img[src='1.png'] \ img[src^='images/']\img[src$='.png']
-   伪类选择器 .box:hover
-   交叉选择器 div.box
-   群组选择器 div,p,a,img,.box,#nav{ }

*   标签选择器
*   类选择器
*   id 选择器
*   通用选择器

# 2、写出常用的背景属性及属性值

-   background-color : red /#fff999/rgb(0,233,212)
-   background-image:url(图片地址)
-   background-size : 20px 30px/100% 50%/cover/contain
-   background-repeat : no-repeat/repeat-x/repeat-y
-   background-position: 20px 100px/left top/center center/right center
-   background-attachment : scroll/fixed

# 3、选择器打分中的四个等级都有哪写内容？

-   行内样式
-   id 选择器
-   类选择器、属性选择器、伪类选择器
-   标签选择器、伪元素选择器

# 4、字体属性有哪些？

-   font-size : 20px\20%\em\rem
-   font-family : '宋体'，’楷体‘，’Microsoft Yahei‘
-   font-weight: 100~900\bold\normal
-   font-style: normal\italic
-   font : 20px/1.5 '宋体'，’楷体‘，’Microsoft Yahei‘

# 5、文本缩进？行高？文字水平居中？文本去掉下划线？

-   text-indent : 20px
-   line-height: 20px
-   text-align: center
-   text-decoration:none\underline

# 6、CSS 三种样式？

-   行内样式、内嵌样式、外链样式

# 7、单词

菜单 menu、搜索 search、导航 navigation、文章列表 list、内容 content、位置 position、绝对的 absolute、相对的 relative、固定的 fixed、下划线 underline、实心的 solid、加入 join、服务 service、投票 vote、浮动 float、小技巧 tips、浏览器 browser、侧边栏 sidebar、倾斜的 italic、显示 display、行内的 inline、块状的 block、家庭 family、网站 site 、www: world wide web

# 8、CSS 属性

-   将一个元素变成行内块 display : inline-block
-   将背景大小设置为覆盖 background-size:cover
-   将背景位置设置为水平居左，垂直居中 : background-position: left center
-   将背景重复设置为不重复 background-repeat: no-repeat
-   将字体类型设置为 ‘宋体，‘微软雅黑’ : font-family : ‘宋体，‘微软雅黑’
-   将行高设置为 1.5 倍字体大小 : line-height: 1.5
-   将表格边框合并: border-collapse : collapse
-   去掉列表的小圆点 : list-style : none
-   将外边距和内边距设为 0 : margin:0;padding:0

# 9、表格常用标签有哪些？

-   table thead tbody tfoot caption tr th td

    ```html
    <table>
        <caption></caption>
        <thead>
            <tr>
                <td></td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td></td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td></td>
            </tr>
        </tfoot>
    </table>
    ```

# 10、表单控件有哪些？

-   input (type: submit\button\text\password\radio\checkbox\email\url\date\time)
-   select\option
-   textarea

# 11、计算机之间的通讯方式

-   客户服务器方式
-   对等链接方式

# 12、html?url?http?

-   超文本标记语言

-   同一资源定位符

-   超文本传输协议

# 13、 web 标准的构成

-   结构（html）\ 样式（CSS）\ 行为（javascript）

# 14、行内元素、块状元素、行内块元素特点？

-   行内元素： 不独占一行、不可以设置宽高
-   块状元素 ：独占一行、可以设置宽高
-   行内块元素 ： 不独占一行、可以设置宽高、有间隙

# 15、行内元素、块状元素、行内块元素 的代表标签

-   行内元素 ： span\a \strong\em\ins\del b\s\i\u
-   块状元素 ： div\p\ul\ol\dl\li\dt\dd\h1~h6\table\form
-   行内块元素 ：img/input/textarea

# 16、display 的属性值有哪些？作用？

-   display : inline\inline-block\block

# 17、img 标签有哪些属性？作用？

-   alt : 图片没有加载时显示的文本
-   src : 图片链接地址（相对地址、绝对地址）
-   title : 鼠标悬浮在图片上时显示的文本

# 18、你能够想到的，搜索引擎优化的方法？

```html
1、<title></title> 2、<meta
    name="keywords"
    content="小米官网，小米商城，’小米8"
/>
3、<meta
    name="description"
    content="小米商城直营小米公司旗下所有产品，囊括小米手机系列小米MIX 3、小米8、小米Note 3，红米手机系列红米5 Plus、红米6 Pro，智能硬件，配件及小米生活周边，同时提供小米客户服务及售后支持"
/>
4、h1~h6标签的运用，一个页面只能有一个h1,h标签不要越级 5、img/a 这些标签 加上
alt /title 属性 6、尽量使用有语义的标签（h1~h6,p,ul,li,strong,em）
7、标题有的时候是一个 logo 图片，标题里面放入文本，将文本设置
text-indent:-9999px 8、简化html结构
```
