### 1、GET 和 POST 是什么方法？

客户端与服务器之间数据交互的方法

GET 方法参数拼接在网址的后面，不安全，有大小限制，一般几十 KB

POST 方法提交的参数放在了表单的请求体当中，安全，没有大小限制

### 2、html 标签分为哪几类？代表标签有哪些？

块状标签：p 、h1~h6、 div 、br 、hr 、table 、form 、ul、 ol 、li 、dl 、dt、 dd

行内标签: a、 span、 s、 u、 i 、b 、del 、em、 ins、 strong

行内块标签：img、 input 、textarea

### 3、CSS 代码可以书写在哪些位置？各自的特点是什么？

1. 行内样式，书写在标签的属性当中（只对某个标签起作用，优先级高）
2. 内嵌样式 ，书写在 style 标签内（只对单个页面起作用，并没有实现解构与样式的分离）
3. 外链样式，书写在.css 文件中，通过 link 标签引入到 html 文档中（结构与样式分离，多个页面可以共享一套样式表，便于开发维护，对搜索引擎友好）

### 4、你学过哪些 CSS 选择器？

类选择器：.nav

id 选择器：#nav

后代选择器： .nav .nav-l

标签选择器： p

### 5、写出网页中常见的类名（英文）

```
头：header
容器：container
尾：footer
导航：nav
侧栏：sidebar
页面外围：wrapper
左右中：left right center
登录：login
标志：logo
广告：banner
页面主体：main
热点：hot
新闻：news
下载：download
子导航：subnav
菜单：menu
子菜单：submenu
搜索：search
页脚：footer
版权：copyright
滚动：scroll
内容：content
选项卡：tab
列表：list
提示信息：msg
小技巧：tips
栏目标题：title
加入：join
服务：service
注册：register
状态：status
投票：vote
```
