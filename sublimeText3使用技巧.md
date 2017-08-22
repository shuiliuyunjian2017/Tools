# sublime text使用技巧 #

sublime text 3下载地址：http://www.sublimetext.com/3

## 第一章 菜单栏主要功能介绍 ##

### File 新建/打开文件 ###

![](http://a2.qpic.cn/psb?/V13H0npf0hT1t4/c758wqYBC9TvCSrpLIVJlyYfioWkO.kjKItR6Px923Q!/m/dAEBAAAAAAAAnull&bo=yAAHAQAAAAARB*4!&rf=photolist&t=5)

会根据不同的文件类型有语法高亮效果，并可在编辑器里打开图片预览。

### Edit 编辑 ###

![](http://a4.qpic.cn/psb?/V13H0npf0hT1t4/*ABTTwNe83ul75l6K7ffRTe5vz4Yj5pohK.AnvznPdk!/m/dD8BAAAAAAAAnull&bo=rAE7AQAAAAARB6c!&rf=photolist&t=5)

有Cytl+C/V/X等三大常用快捷操作，还有包括

**Line** 编辑行 缩进Ctrl+[ Ctrl+]、复制行Ctrl+Shift+D、删除行Ctrl+Shift+K等 

**Comment** 添加注释 Ctrl+/ Ctrl+Shift+/

**Text** 编辑文字块

**Tag** 闭合标签 Alt+.

等快捷键的操作。

### Selection 选择区块 ###


![](http://a2.qpic.cn/psb?/V13H0npf0hT1t4/tn.NxLShyQajvyTFGpTj1g7Klh11*8sKrZweHPRfxOo!/m/dD0BAAAAAAAAnull&bo=MgHUAAAAAAARB9c!&rf=photolist&t=5)


1.通过快捷键选择一行(Ctrl+L)、选择一个单词(Ctrl+D)。还可以通过重复使用这两个操作出现多个选择进而出现**多行光标**。


![](http://a2.qpic.cn/psb?/V13H0npf0hT1t4/mPyXR1aXCz6DZbniR6v5wU7dWyoxD1WBGEdwzZtGR1I!/m/dD0BAAAAAAAAnull&bo=PwHnAAAAAAARB.k!&rf=photolist&t=5)

2.快速替换(Ctrl+h)调出替换框

3.产生多行游标的方式：

- 1中介绍的；
- 选中一个单词再Ctrl+F3；
- Ctrl+A -> Ctrl+L；
- Shift+鼠标右键拖动；
- Ctrl+鼠标左键点击。

### View 视图区域调整 ###

显示隐藏sidebar(Ctrl+k,Ctrl+b连续操作 切换）

显示隐藏console(Ctrl+`)

### Goto ###

超级好用的**Goto Anything(Ctrl+p)**

1. `:20` +Enter 光标去到第20行

2. 在html格式文件中， `#body` +Enter 定位到body标签

3. 输入`src/css`会检索当前工程下匹配的文件
![](http://a2.qpic.cn/psb?/V13H0npf0hT1t4/KclSP9xeSSuuP6RfhkzpQE3WZ99a1Zw2ed*T4Xj0QOY!/m/dPkAAAAAAAAAnull&bo=UATgAQAAAAARB4U!&rf=photolist&t=5)

4. 输入`@`在类名（css文件）、函数名(js文件)中进行索引

5. 也可2和3的组合，如`src/css/flex.css@body`定位到body元素，并进行修改。
 
![](http://a2.qpic.cn/psb?/V13H0npf0hT1t4/ra33EQIhvmDJ0O*pFgpHryOXpxP4NJ4pjdJ73ydHwBU!/m/dD0BAAAAAAAAnull&bo=nwE9AQAAAAARB5I!&rf=photolist&t=5)


### Tools ###

1.调出命令行(Ctrl+Shift+p)，命令行支持模糊匹配

![](http://a3.qpic.cn/psb?/V13H0npf0hT1t4/NHY2UUtDiDDtm6L2jv.rxAJg3OBet6aMOHLCDMEiejg!/m/dGoBAAAAAAAAnull&bo=bQHbAAAAAAARB4c!&rf=photolist&t=5)

2.设置语法模式（点击sublime的右下角按钮切换）OR Ctrl+Shift+p -> `set syntax: xxx` 

![](http://a1.qpic.cn/psb?/V13H0npf0hT1t4/jPsOYyoWs9cpm*Shsuai5nsa1uOrC6hzzEyzdraX7Ak!/m/dGwBAAAAAAAAnull&bo=DQPfAQAAAAARB.A!&rf=photolist&t=5)

3.显示/隐藏minimap Ctrl+Shift+p -> `minimap` [感谢模糊匹配]


### Preferences ###

个性化设置（重写配置文件里的某些字段名）

还可以设置编辑器主题(theme)

![](http://a2.qpic.cn/psb?/V13H0npf0hT1t4/xR5rZ9c4Y1uyVpmAJw9Xl30owIqX71ydL9gWpsRo4Hg!/m/dD0BAAAAAAAAnull&bo=mwCmAAAAAAARBw0!&rf=photolist&t=5)


### 其他技巧 ### 

1. 在当前行之后添加一行 Ctrl+Enter
2. 在当前行之前添加一行 Ctrl+Shift+Enter
3. 拷贝/粘贴代码时，有良好的格式 Ctrl+Shift+V


## 第二章 插件 ##

### 插件的安装 ###
1. Package Control 官网地址：[https://packagecontrol.io/](https://packagecontrol.io/ "PackageControl") 点击“Install Now”
2. 拷贝代码进sublime的控制台，回车
![](http://a1.qpic.cn/psb?/V13H0npf0hT1t4/6bQ7FEZkTohOSU*pKhRDxU1uo0BIW.z8eOoJzmiajSM!/m/dGwBAAAAAAAAnull&bo=IwKGAgAAAAARB5U!&rf=photolist&t=5)
3. sublime打开命令模式(Ctrl+Shift+P) -> `pci`(模糊匹配到package control:Install Package) -> 插件名(Package Control官网首页有插件的分类及索引) 进行安装


### 1. theme（sublime主题包） ###

在Package Control官网首页theme分类下查找相应的主题包，查看主题风格。

1. soda
2. flatland
3. Spacegray

### 2. 快捷操作插件包 ###

1. 命令模式 -> 'snippet:xxx'+Enter -> tab键切换选中区域

2. 安装Javascript & nodeJS snippets，可以通过`gi`生成`document.getElementById('id');`代码。更多简写请看： [https://packagecontrol.io/packages/JavaScript%20%26%20NodeJS%20Snippets](https://packagecontrol.io/packages/JavaScript%20%26%20NodeJS%20Snippets)

3. 简写jquery操作，安装[jQuery](https://packagecontrol.io/packages/jQuery)的插件

4. 简写回调函数，安装[Insert Callback](https://packagecontrol.io/packages/Insert%20Callback)，通过Alt+c生成回调函数模板

5. 新建文件，安装[Advanced​New​File](https://packagecontrol.io/packages/AdvancedNewFile)。Ctrl+Alt+N 调出文件路径生成框，输入文件名或文件路径，如`src/app.js`，若当前无此目录则会新建此目录。

6. 简化http请求及响应，可模拟Post请求。安装[Http Requester](https://packagecontrol.io/packages/Http%20Requester) 选中请求地址，Ctrl+Alt+R在sublime中等到请求的响应内容。 

![](http://a4.qpic.cn/psb?/V13H0npf0hT1t4/KL9vOh9PNVJIG5shUpCcPT9tv*CZGBWrKenKDZtFtxA!/m/dOcAAAAAAAAAnull&bo=2AFGAQAAAAARB64!&rf=photolist&t=5)

![](http://a2.qpic.cn/psb?/V13H0npf0hT1t4/hUOIwLP.X6csmu13RgDBJxkaCf.ad50U2aW0DKpMdVM!/m/dG0BAAAAAAAAnull&bo=3AEuAQAAAAARB8I!&rf=photolist&t=5)

7. 自动拉取最新库元素。安装[Nettuts+ Fetch](https://packagecontrol.io/packages/Nettuts%2B%20Fetch)。

命令模式下，`Fetch:Manage`管理库的配置文件

	{
		"files":
		{
			"jquery": "http://code.jquery.com/jquery.min.js"
		},
		"packages":
		{
			"html5_boilerplate": "https://github.com/h5bp/html5-boilerplate/zipball/master"
		}
	}

在需要拉取的文件里，进入命令模式，Fetch:file+Enter，选择对应的库名。如上可有jquery。可自定义files里的库名称及拉取的地址。

8. 左侧栏文件在浏览器里打开。安装[Side​Bar​Enhancements](https://packagecontrol.io/packages/SideBarEnhancements)后，在左侧栏/文件打开区域右链-->'Open In Browser'。

9. 快速添加注释。安装[Doc​Blockr](https://packagecontrol.io/packages/DocBlockr)。输入`/*`或`/**`会自动补全。



![](http://a2.qpic.cn/psb?/V13H0npf0hT1t4/9w7wwr2PmxaEi4JPYCAJOpZm8zuegf72YqdkNl9Atng!/m/dAEBAAAAAAAAnull&bo=5gHmAAAAAAARBzE!&rf=photolist&t=5)



**附视频地址**：http://www.imooc.com/learn/40


SublimeLinter
-jshint
npm i -g jshint
