# HTML 标签的分类

1. 块状元素：div 、 p  、h1~h6 、 hr  、br 、 ul 、ol、 li、 dl 、dt 、dd、table、form
2. 行内元素：span 、b 、strong、 em、 i 、u 、del 、s、 ins、 a 
3. 行内块元素：img 、input

# web标准的组成

1. 网页的结构：html
2. 网页的样式：css
3. 网页的行为：javascript



# 三种列表的基本结构

## 有序列表

```html
<ol>
    <li></li>
    <li></li>
    <li></li>
</ol>
```

## 无序列表

```html
<ul>
    <li></li>
    <li></li>
    <li></li>
</ul>
```



## 名词解释列表

```html
<dl>
    <dt>苹果</dt>
    <dd>苹果产自北方</dd>
    <dt>橘子</dt>
    <dd>橘子产自南方</dd>
</dl>
```

# 表格的基本结构

```html
<table border='1px'>
    <caption></caption>
    <thead>
       <tr>
         <th></th>
         <th></th>
       </tr>
    </thead>
    <tbody>
       <tr>
        <td></td>
        <td></td>
       </tr>
    </tbody>
    <tfoot>
       <tr>
        <td></td>
        <td></td>
       </tr>
    </tfoot>
</table>

注意：caption thead tfoot tbody 这些标签视情况添加

     如果没有写 tbody 会自动为table标签内添加tbody标签

     合并表格的边框？ 

        table{
         border-collapse:collapse
        }
     合并单元格（ <td></td> 或 <th></th>）的两个的属性？

     colspan、rowspan
```



# input 控件的type属性的值有哪些？

text、 password 、radio、 checkbox、 submit、 button、 reset、 file 、image

html5新增：url 、email 、number 、date 、time



# form表单中的action和method属性作用？

action : 定义表单提交的网址

method：定义客户端与服务器交互的方法（GET、POST）



# url 后面拼接参数的格式？

?name=zhangsan&age=18&sex=man&hobby=game



