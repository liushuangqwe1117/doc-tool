# emmet插件

---

### 1. 安装emmet插件

参见 [插件安装](installplugin.md)

插件名称：Emmet Css Snippets

在Emmet安装完成后，会显示如下屏幕(即emmet说明文档)：然后会自动安装PyV8，安装完成，重启 Sublime Text 3
![](/images/editor/emmet.png)

### 2. 验证emmet插件是否安装成功
1. 点击菜单Preference-->Package Control，查看目录下是否含有“Emmet Css Snippets”和“PyV8”文件夹
2. 新建一个html文件，输入ul#test>li*4，然后按ctrl+e生成如下代码，则表示成功
```
<ul id="test">
    <li></li>
    <li></li>
    <li></li>
    <li></li>
</ul>
```

### 3. emmet插件快捷键(输入后按ctrl+e生成代码)
- !

```
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>

</body>
</html>
```

- html>(head>title)+body

```
<html>
<head>
	<title></title>
</head>
<body>

</body>
</html>
```

- h1{$$}
```
<h1>01</h1>
```
- h1{$$}*3
```
<h1>01</h1>
<h1>02</h1>
<h1>03</h1>
```
- .header
```
<div class="header"></div>
```

-  #main
```
<div id="main"></div>
```
6. h1.hcls
```
<h1 class="hcls"></h1>
```


7. div1>div2
```
<div1>
	<div2></div2>
</div1>
```
8. div1+div2
```
<div1></div1>
<div2></div2>
```
