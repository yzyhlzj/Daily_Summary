# HTML 表单

HTML 表单用于收集用户的输入信息。

HTML 表单表示文档中的一个区域，此区域包含交互控件，将用户收集到的信息发送到 Web 服务器

表单是一个包含表单元素的区域。表单元素是允许用户在表单中输入内容，比如：文本域（textarea）、下拉列表（select）、单选框（radio-buttons）、复选框（checkbox） 等等。

我们可以使用 **<form>** 标签来创建表单,form元素一个块级元素

```html
<!DOCTYPE html>
<html>
<head> 
<meta charset="utf-8"> 
<title>菜鸟教程(runoob.com)</title> 
</head>
<body>

<form action="">
Username: <input type="text" name="user"><br>
Password: <input type="password" name="password">
</form>

<p><b>注意：</b> 密码字段中的字符是隐藏的(显示为星号或圆圈)。</p>

</body>
</html>
```

## 提交按钮(Submit)

**<input type="submit">** 定义了提交按钮。

当用户单击确认按钮时，表单的内容会被传送到服务器。表单的动作属性 **action** 定义了服务端的文件名。

**action** 属性会对接收到的用户输入数据进行相关的处理:

```html

```

iframe标签，用于对页面进行布局