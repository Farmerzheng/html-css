- 1、块状元素、行内元素、行内块元素特点及代表标签

- 2、样式可以写在哪里？

  + 行内样式、内嵌样式、外链样式

- 3、盒模型组成？

  + content、padding、border、margin

- 4、命名规范常用单词

  + 导航 :nav
  + 登录:login
  + 广告:banner
  + 新闻:news
  + 菜单:menu
  + 搜索:search
  + 选项卡:tab
  + 加入:join
  + 服务:service
  + 列表:list

- 5、常用字体样式
  - 字体大小:font-size:10px\50%
  - 字体类型:font-family:'宋体'，'楷体' , 'arial'
  - 字体粗细:font-weight: bold/100-900
  - 字体风格:font-style:normal/italic
  - 字体缩写形式:font:24px/1.5 'Microsoft Yahei'

- 6、文本属性(行高、文本居中、文本左对齐、文本右对齐、文本缩进、文本修饰)

  + line-height
  + text-align:center
  + text-align:left
  + text-align:right
  + text-indent:10px
  + text-decoration:none\underline\line-through\over-line

- 7、常用CSS 选择器？

  + 通用选择器、标签选择器、类选择器、后代选择器、群组选择器、伪类选择器、父子选择器、兄弟选择器、id选择器、属性选择器、相邻选择器、交叉选择器

- 8、你能够想到的背景属性？

  + background-size:contain、cover、10px 20px、100% 100%
  + background-color:red
  + background-image:url()
  + background-repeat:no-repeat、repeat-x、repeat-y
  + background-attachment：fixed、scroll
  + background-position: center center、10px  20px

- 9、块状元素如何居中？margin:0 auto

- 10、盒子阴影？盒子圆角？box-shadow、border-radius

- 11、如何清除浮动？清楚浮动的clearfix类如何写？为什么要清楚浮动？不清除浮动可以么？

  + 给父元素添加一个clearfix 类可以清除浮动
  + .clearfix:after{content:'',display:block;clear:both} .clearfix{zoom:1}
  + 浮动的元素不能撑起父元素的高度

  + 不清除浮动也是可以的，可以直接给父元素高度

- 12、浮动元素的特点有哪些？

  + 浮动元素支持宽高
  + 浮动元素不独占一行
  + 浮动元素脱离文档流（撑不起父元素的高度）
  + 浮动元素不存在外边距折叠
  + 浮动元素是完美的盒模型（padding\margin都起作用）

- 13、表格常用标签？表单常用标签？

  + table、caption、tbody、tfoot、thead、tr、th、td
  + form 、input、select、option、textarea

- 14、web标准的组成？

  + 结构(html)
  + 表现(CSS)

  + 行为(javascript)

- 15、display 有哪些属性？作用是什么？

  + inline  将元素变成行内元素
  + inline-block : 变成行内块
  + block ： 变成块状元素