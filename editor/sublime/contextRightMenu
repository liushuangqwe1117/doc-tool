## 将SublimeText3添加到右键菜单中


>方法一（推荐）

把以下代码，复制到SublimeText3的安装目录，然后重命名为：sublime_addright.inf，然后右击安装就可以了。PS：重命名文件之前，需要先在工具–文件夹选项，查看中，把隐藏已知文件类型的扩展名前边的复选框不勾选。

```
[Version]
Signature="$Windows NT$"

[DefaultInstall]
AddReg=SublimeText3

[SublimeText3]
hkcr,"*\\shell\\SublimeText3",,,"用SublimeText3打开"
hkcr,"*\\shell\\SublimeText3\\command",,,"""%1%\sublime_text.exe"" ""%%1"" %%*"
hkcr,"Directory\shell\SublimeText3",,,"用SublimeText3打开"
hkcr,"*\\shell\\SublimeText3","Icon",0x20000,"%1%\sublime_text.exe, 0"
hkcr,"Directory\shell\SublimeText3\command",,,"""%1%\sublime_text.exe"" ""%%1"""
```


> 方法二

把以下代码，复制到SublimeText3的安装目录，然后重命名为：sublime_addright.reg，然后双击就可以了。PS:需要把里边的Sublime的安装目录，替换成实际的Sublime安装目录。

```

Windows Registry Editor Version 5.00
[HKEY_CLASSES_ROOT\*\shell\SublimeText3]
@="用 SublimeText3 打开"
"Icon"="D:\\Program Files\\Sublime Text 3\\sublime_text.exe,0"

[HKEY_CLASSES_ROOT\*\shell\SublimeText3\command]
@="D:\\Program Files\\Sublime Text 3\\sublime_text.exe %1"


[HKEY_CLASSES_ROOT\Directory\shell\SublimeText3]
@="用 SublimeText3 打开"
"Icon"="D:\\Program Files\\Sublime Text 3\\sublime_text.exe,0"

[HKEY_CLASSES_ROOT\Directory\shell\SublimeText3\command]
@="D:\\Program Files\\Sublime Text 3\\sublime_text.exe %1"

```

> 方法三

1. 进入注册表(cmd命令>regedit命令)
2. 输入ctrl+f打开搜索框，输入Shell进行搜索
3. 在shell下新建SublimeText3选项
4. 在SublimeText3选项下新建command选项
5. 在command下打开“默认”写下如下内容

  `"D:\soft\SublimeText3\sublime_text.exe" "%1" %*`

  或

  `"D:\soft\SublimeText3\sublime_text.exe" -p --remote-tab-silent "%1"`

6. 效果图如下
![图片](/images/editor/addToRightMenu.png "图片提示")

## 将SublimeText3从右键菜单中删除
>把以下代码，复制到SublimeText3的安装目录，然后重命名为：sublime_delright.reg，然后双击就可以了。

```
Windows Registry Editor Version 5.00
[-HKEY_CLASSES_ROOT\*\shell\SublimeText3]
[-HKEY_CLASSES_ROOT\Directory\shell\SublimeText3]

```
