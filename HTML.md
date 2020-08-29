**<font color=black size=5>HTML</font>**

[toc]

# 一、HTML简介

学习手册：https://www.w3school.com.cn/index.html

学习手册：https://www.runoob.com/php/php-ref-array.html 

//想要了解前端资料网址：

https://cn.vuejs.org/ Vue.js学习手册

https://reactjs.org/docs/hello-world.html React.js学习手册

http://jquery.cuishifeng.cn/ jQuery函数库手册

http://nodejs.cn/ node平台

https://developer.mozilla.org/zh-CN/docs/Web/API/Canvas_API/Tutorial canvas

https://www.echartsjs.com/examples/zh/index.html 图表函数库

概述：HTML（Heyper MarkUp Language）全称称之为超文本标记语言，它是世界上最简单的语言

在开发的时候，我们只需要进行页面的布局（利用标签：element）

注意：超文本标记语言（HTML）又称之为web（开发），它诞生于（1993~2020）这门语言大大小小经历过的变化有五次，最近一次2014称之为HTML5（超文本标记语言第五次重大变化）

## 1、开发工具

sublime开发工具http://www.sublimetext.com/3

VScode开发工具https://code.visualstudio.com/docs/?dv=win

WebStorm开发工具https://www.jetbrains.com/webstorm/download/#section=windows

## 2、体验HTML编程

体验新的：HTML标记语言开发程序的时候，利用就是<font color='red'>标签（element）</font>进行布局页面

标签组成如下：

<font color='red'><标签名字></font><font color='purper'>文本内容</font><font color='green'></标签名字></font>

* 红的部分：称之为开始标签
* 绿色部分：称之为结束标签（闭合标签）
* 蓝色部分：文本内容（text）

# 二、标签学习（element）

概述：HTML（超文本标记语言），它的页面（静态页面）是由标签组成，

* 块元素：<font color='red'>独占一行</font>（最重要的一部分）

## 2.1静态页面骨架

* 快捷键：<font color='red' size=5>shift + ! + tab</font>

```html
<!DOCTYPE html><!这是超文本标记语言第五次重大变化文档声明方式>
<html lang="en">
<head>
	<meta charset="UTF-8"><!charset:设置字符集   UTF-8（简称万国编码）>
	<title>Document</title>
</head>
<body>
	
</body>
</html>
```

* HTML标签是整个网页的根元素（进行页面布局的其他元素：都是嵌套在HTML标签里面作为子元素）

* HTML标签右侧有一个lang属性（前段当中管这种写法叫做属性），属性值en（英文简写：代表的是英文下开发）

  

![image-20200811185833514](D:\HTMLproject\image\01.png)

## 2.2常用标签-块元素

概述：在web开发中块元素非常常用：块（block）元素是独占一行，在页面中是由上到下进行排列，遇见下一个块元素就要换行

常用块元素有很多：h1~h6（标题）、div、p、ul、li......等等

<font color='red'>注意：在书写学习这些标签（块元素），一定要注意在body标签内部进行书写</font>

<font color='red'>标签小技巧：打出标签名（ctr+E）标签自动补齐</font>

运行方式：选择此文件路径，在浏览器中运行

* h1~h6：一级标题~六级标题（字体越来越小的样子）
  * 学习的标签可以复用（多次使用），嵌套使用
* h5中注释<!-- -->c+ctr+e       css3中注释/* */cm+ctr+e
* div：盒子标签
* p（paragraph）：段落标签
* address:是2014年才新增的：用来显示地址（跟div区别：一个字体倾斜，一个字体不倾斜）

### 2.1.1常用的块元素-列表系列

概述：列表（也是块元素）有两个：无序列表  ul、有序列表  ol，这两个块元素用来显示列表

而且li标签经常作为他们子元素一起使用

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
	<!-- 无序列表 -->
	<ul>
		<li>吃饭</li>
		<li>睡觉</li>
		<li>打豆豆</li>
	</ul>
	<ol>
		<li>学习</li>
		<li>喝酒</li>
		<li>烫头</li>
	</ol>
</body>
</html>

```

![QQ图片20200812093605](D:\HTMLproject\image\02.png)

<font color='red'>总结：h1~h6（不同级别的标题）、div（盒子标签）、p（段落）、ul（无序列表）、ol（有序列表）、li元素</font>

## 2.3行内元素

概述：前端开发当中行内元素（内敛元素）：常见的行内元素有如下几个：

行内元素特征：不是独占一行，从左到右进行排列

span，img，a

<font color='red'>注意：在web领域中标签（双闭合标签）、单闭合标签</font>

```
	<a href="http://www.taobao.com">淘宝网站</a>
```

* 标签的href属性是用来设置超链接的地址属性

```
	<img src="../image/meinv.jpg" alt="默认文字">
```

* img标签的src属性是用来设置显示图片的路径的，alt:图片没有的情况写默认显示文字

## 2.4小总结

块（block）元素：自己独占一行（h1~h6）、div、p、ul、ol、address

行内（inline）元素：a、span、img

## 2.5表单元素*

概述：前端中比较重要的标签（行内元素）

<font color='red'>标元素（表单元素经常用来收集用户输入信息），将用户输入信息提交给服务器</font>

表单元素即为input标签（单闭合标签），这个标签经常结合form标签一起使用

## 2.6小复习

问题：HTML？

答：HTML（HyperText MarkUp Language）即为超文本标记语言，它是世界上最简单的编程，利用标签完成页面中的布局

问题：块元素？

答：块元素在网页中独占一行（一般从上到下排列）

H1~H6、div、p、ul、ol、li、address

问题：行内元素？

答：span、a、img、表单元素：输入框，单选按钮、复选按钮、提交按钮等等

## 2.7音频标签

概述：如果你想在网页中显示音频，我们可以利用<font color='red'>audio</font>标签显示音频,Web领域中音频audio标签，只能播放下面三种音频格式：

mp3、ogg、wav

<font color='red'>行内元素</font>

```
	<audio src="../音乐/1.mp3" controls muted autoplay loop>音频</audio>
```

加上controls才会显示控件、muted：静音、autoplay：自动播放、loop：循环播放

* 我们可以利用audio标签播放音频（MP3、ogg、wav）
* 视频利用的是video标签，用法和上面的音频几乎一模一样（mp4、ogg、webm）

# 三、CSS样式

概述：CSS【Cascading Style Sheets】全称层叠式样式表

理解：可以把HTML文件想象成一个房子的骨架，里面的标签（块元素、行内元素）理解为搭建房子的砖，CSS负责美化房子（进行装修），让你的静态页面（网站看起来好看一些）

前端领域中web样式写法有三种：

* 外部样式
* 内部样式
* 行内样式

## 3.1体验样式

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<!-- 样式一般是放在style标签里面（内部样式） -->
	<style type="text/css">
		div{
			color: green;
			font-size: 30px;
			background-color: red;
			text-align: center;
			border:5px solid black;
			opacity: .5;
		}
	</style>
</head>
<body>
	<div>
		我是祖国的老花骨朵
	</div>
</body>
</html>
```

## 3.2内部样式

### 3.2.1标签选择器************

概述 ：样式【css】用来美观标签（页面），web领域样式分为三种(今天只关注内部样式)：

* 外部样式
* <font color='red'>内部样式</font>
* 行内样式



内部样式需要书写在head中，利用子元素双闭合标签style标签完成

语法格式：

<style type="text/css">
    标签名{
        属性：属性值;
        属性：属性值;
    }
</style>



内部样式---标签选择器

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		h1{
            /* 文字颜色设置：属性值：红red、橙orange、黄yellow、绿green、青cyan、蓝blue、紫purple */
			color: red;
			/* 字体大小设置(最小是12px) */
			font-size: 30px;
			/* 背景颜色设置 */
			background-color: orange;
			/* 文本对齐方式 */
			text-align: center;
			/* 文本样式设置：倾斜 */
			font-style: italic;
		}
		div{
			color: green;
			font-size: 28px;
			background-color: red;
			text-align: center;
			font-style: italic;
			/* 设置透明度：0~1之间 */
			opacity: 0.5;
			/* 光标放置在标签中变为小手样式 */
			cursor:pointer;
		}
		span{
			color: blue;
		}
	</style>
</head>
<body>

	<h1>我是一级标题</h1>
	<h1>我是小明</h1>
	<div>我是一<span>我是常用的标签</span>级标题</div>

</body>
</html>
```

* 标签选择器：常用于样式中选择匹配的标签

### 3.2.2id选择器******

命名标识符规范：

1：可以是数字、字母、下划线、美元符号

2：但是不能以数字开头

3：不能是这门语言当中关键字、保留字

概述：我们上面案例通过标签名字匹配页面中对应标签进行设置（内部样式），除此之外，还可以通过id选择器匹配标签（节点：element）

注意：一般情况下，页面中标签id属性值唯一（和人的身份证是一样的，每人都有但是都不同）

* 在标签（开始标签）这里添加一个id属性，对应右侧属性值
* 在style标签里面（内部样式）#号+对应节点id属性值

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		#box{
			color: red;
			/* 文本的描述 none取消下划线、underline下划线、overline上划线、line-throug中划线*/
			text-decoration: none;
			
		}
		#box1{
			/* 列表默认样式的设置 */
			list-style: circle;
		}
		#cur{
			color: red;
		}
		#box2{
			/* 列表默认样式的设置 */
			list-style: square;
		}
	</style>
</head>
<body>
	<a href="http://www.baidu.com" id="box">百度</a>
	<ul id="box1">
		<li>吃饭</li>
		<li id="cur">睡觉</li>
		<li>打豆豆</li>
	</ul>
	<ol id="box2">
		<li>unity3D</li>
		<li>cos2D</li>
		<li>PHP</li>
	</ol>
</body>
</html>
```

| text-decoration | <font  color='red'>None</font>、underline、overline、line-throuth |
| --------------- | ------------------------------------------------------------ |
| **list-style**  | **<font  color='red'>None</font>、circle、square**           |

### 3.2.3class选择器

概述：我们已经学过了标签选择器、ID选择器、除此之外还可以使用class（类）选择器

注意：id选择器属性值一般是唯一的，class属性值可以重复（不是唯一的）

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		.current{
			color: red;
			font-size: 30px;
			background-color: cyan;
		}
		.cur{
			color: skyblue;
			font-size: 18px;
		}
	</style>
</head>
<body>
	<div class="current">
		我是祖国的老花骨朵，是祖国的未来
	</div>
	<div>我也是祖国的花骨朵</div>
	<div class="current">我也是祖国的花骨朵</div>
	<div>我也是祖国的花骨朵</div>
	<div>我也是祖国的花骨朵</div>
	<div>今天是北京时间<span class="cur">2020年11月30日18:03</span></div>
</body>
</html>
```

学习了三个选择器：标签选择器（标签名字）、ID选择器（#+id属性值）、class选择器（.+class属性值）

### 3.2.4背景系列的样式

概述：背景系列属性有如下几个：

Background-color:[背景颜色]、background-image:[背景图设置]、background-repeat:[背景图重复]

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		div{
			/* 我们可以设置块元素的宽度和高度 */
			width: 800px;
			height: 800px;
			
			/* 背景颜色 */
			/* background-color: red;*/
			/* 设置背景图 如果背景图片没有标签大，图片会平铺显示 */
			/* background-image: url(../image/meinv.jpg); */
			/* 背景重复设置 */
			/* background-repeat:no-repeat; */
			/* 简写方式 */
			background:red url(../image/meinv.jpg) no-repeat;
		}
	</style>
</head>
<body>
	<div></div>
</body>
</html>
```

| **background-color**  | **背景颜色的设置**          |
| --------------------- | --------------------------- |
| **background-image**  | **背景图的设置**            |
| **background-repeat** | **背景图重复（no-repeat）** |

他们三者可以进行简写：

background:red url(../image/meinv.jpg) no-repeat;

顺序不论；

## 3.3外部样式

概述：在前端web开发中样式可以放置在css文件里面，在页面中通过<font color='red'>link标签</font>可以<font color='red'>引入外部文件样式</font>

在程序中创建CSS文件夹，这个文件夹里面有一个default.css文件，这个文件里面可以书写你的样式。这种样式前端工程师称为外部样式

静态页面

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<!-- 引入外部样式文件（CSS文件） -->
	<link rel="stylesheet" type="text/css" href="css/default.css">
</head>
<body>
	<div class="box">
		<p id="cur">北京昨天下大雪了，真的很美</p>
	</div>
</body>
</html>
```

* 如果想引入外部CSS文件，需要通过link标签进行引入

default.css文件

```
.box{
	width: 280px;
	height: 280px;
	background-color: red;
}
#cur{
	font-size: 20px;
	color: green;
	text-align: center;
}
```

## 3.4行内样式

概述：我们在给标签设置样式的时候，可以选择外部样式，内部样式，行内样式（对于web开发很少用）

行内样式：通过在开始标签的地方就可以设置，通过style属性进行设置

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
	<p style="width: 600px;height: 300px;font-size: 30px;color: red;">最近比较热门话题是xx公司的暴力裁员</p>
</body>
</html>
```

注意：行内样式的写法

<标签名字 style:="属性：属性值;属性：属性值；">文本</标签名字>

## 3.5总结样式

总结：（web）前端开发中样式有三种：外部样式（link标签引入外部CSS文件）、内部样式、行内样式

注意：前端开发中样式有优先级的：行内样式>内部样式>外部样式

外部样式相对而言在开发项目中经常用-----可以进行统一管理，让你的项目中样式看的更加整洁

# 四、盒模型*

概述：所谓盒模型，其实<font color='red'>任意的标签</font>都有，可以让标签向外拓展

盒模型中：padding、border可以让元素向外拓展

盒模型：<font color='red'>padding（内边距）、border（外边框）、marging（外边距）</font>

注意：前端所谓的盒模型：是元素的哪些数据？

盒模型：算上margin+padding+border+width+heigh

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		.box{
			width: 200px;
			height: 200px;
			/* 外边框：可以让元素向外拓展 solid:实线  dashed:虚线; */
			border: 5px solid red;
			/* 内边距：文本到边框的距离 */
			padding: 10px;
		}
		.box1{
			/* 外边距：设置标签与标签之间的距离 */
			margin: 50px;
			width: 200px;
			height: 200px;
			background-color: red;
		}
	</style>
</head>
<body>
	<div class="box">文字文字</div>
	<div class="box1">文字文字</div>
</body>
</html>
```

# 五、定位

概述：在前端web开发中所谓文档流【页面中标签排列方式】：如果想打破文档流让标签可以在任意地方显示，需要进行定位

定位在前端中分为三种：固定定位（fixed），相对定位（relative），绝对定位（absolute）

<font color='red'>定位的元素才有left、top、right、bottom的属性</font>

块元素：从上到下排列（独占一行）

行内元素：从左到有排列（不独占一行）

## 5.1固定定位

注意：如果是定位元素就有left、top、right、bottom四个属性：

概述：如果你想给某一个标签固定在网页中某一个位置，可以利用固定定位，哪怕页面有上下滑动效果也不影响

以当前网页为参照物

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		/* 想让页面设置没有默认样式：带有空格 */
		/* 清除全部默认样式 */
		*{
			margin: 0px;
			padding: 0px;
		}
		div{
			width: 400px;
			height: 200px;
		}
		body{
			height: 10000px;
		}
		.box1{
			/* 固定定位：固定定位的元素不占起始位置 */
			position: fixed;
			left: 500px;
			top: 200px;
			background: red;
		}
		.box2{
			background: green;
		}
		.box3{
			background: purple;
		}
	</style>
</head>
<body>
	<div class="box1"></div>
	<div class="box2"></div>
	<div class="box3"></div>
</body>
</html>
```

* 定位的元素才有left、top、right、bottom的属性
* 固定定位是以网页为参照，固定在某一个位置（哪怕页面滑动，也是在这个位置）
* 固定定位元素不占起始位置

## 5.2相对定位

概述：相对定位也可以让元素脱离文档流，元素在进行相对定位的时候，其实相对的是起始位置（原始位置）进行偏离，

而且还需要注意：相对相位元素起始位置是占用的

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		/* 清除默认的样式，默认情况下有缝隙 */
		*{
			margin: 0px;
			padding:0px;
		}
		div{
			height: 200px;
			width:400px;
		}
		.box1{

			background: red;
		}
		.box2{
			/* 相对定位：相对定位的元素占起始位置 */
			position: relative;
			left: 400px;
			top: 200px;
			background: green;
		}
		.box3{
			background: purple;
		}
	</style>
</head>
<body>
	<div class="box1"></div>
	<div class="box2"></div>
	<div class="box3"></div>
</body>
</html>
```

* 相对定位元素：相对于自己的起始位置
* 相对元素的起始位置是占用的（别人用不了）

## 5.3绝对定位

概述：绝对定位也可以让元素脱离标准文档流：

1. 绝对定位元素，如果没有父元素【绝对定位元素：参照页面进行偏移】
2. 绝对定位元素，如果有定位父元素
   * 定位父元素有定位：【绝对定位元素：参照定位父元素进行偏移】
   * 定位父元素没有进行定位：【绝对定位元素：参照页面进行偏移】，如果父元素的上一级有定位，则参照父元素的上一级进行偏移（找祖先辈定位，如果都没有，则参照网页进行偏移）

注意：绝对定位的元素不占起始位置（别人可以占用起始位置）

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		/* 清除默认的样式，默认情况下有缝隙 */
		*{
			margin: 0px;
			padding:0px;
		}
		div{
			height: 200px;
			width:400px;
		}
		.box1{

			background: red;
		}
		.box2{
			/* 相对定位：相对定位的元素占起始位置 */
			position: relative;
			left: 400px;
			top: 200px;
			background: green;
		}
		.box3{
			background: purple;
		}
	</style>
</head>
<body>
	<div class="box1"></div>
	<div class="box2"></div>
	<div class="box3"></div>
</body>
</html>
```

## 5.4小练习

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		/* 子绝父相 */
		.father{
			position: relative;
			width: 815px;
			height: 415px;
			background: red;
			margin: 100px;
			border: 1px solid black;
		}
		.son1{
			position: absolute;
			left: 0px;
			top: 0px;
			width: 200px;
			height: 405px;
			background: green;
			margin: 5px;
		}
		.son2{
			position: absolute;
			left: 200px;
			top: 0px;
			width: 600px;
			height: 200px;
			background: purple;
			margin: 10px;
			margin-top: 5px; 
		}
		.son3{
			position: absolute;
			left: 200px;
			top: 200px;
			width: 600px;
			height: 200px;
			background: cyan;
			margin: 10px;
			margin-bottom: 0px; 
		}
	</style>
</head>
<body>
	<div class="father">
		<div class="son1"></div>
		<div class="son2"></div>
		<div class="son3"></div>
	</div>
</body>
</html>
```

# 六、浮动

概述：我们可以利用定位打破文档流，除此以外也可以利用浮动，其实浮动就是让元素进行'靠左'、'靠右'进行水平排列

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		/* 清除默认样式 */
		*{
			margin: 0px;
			padding: 0px;
		}
		div{
			/* 靠左侧浮动 */
			/* float: right; */
			float: left;
			width: 150px;
			height: 50px;
			background: cyan;
		}
	</style>
</head>
<body>
	<div>最近北京气温降低</div>
	<div>最近北京气温降低</div>
	<div>最近北京气温降低</div>
	<div>最近北京气温降低</div>
	<div>最近北京气温降低</div>
	<div>最近北京气温降低</div>
	<div>最近北京气温降低</div>
	<div>最近北京气温降低</div>
	<div>最近北京气温降低</div>
</body>
</html>
```

//靠左侧浮动（一行放不下自动换行）

![image-20200813162639802](/D:/HTMLproject/image/03.png)

## 6.1导航

百度导航

![image-20200813181151374](D:\HTMLproject\image\image-20200813181151374.png)

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		*{
			margin: 0px;
			padding: 0px;
		}
		.box{
			position: relative;
			/* 当前这个div的宽度是按照父元素的宽度来百分比的 */
			width: 100%;
			height: 50px;
			background:#01204f;

		}
		ul{
			position: absolute;
			left: 20%;
			width: 80%;
			height: 50px;
			/* 将列表的默认样式清除，就是将前面的黑的小球干掉 */
			list-style: none;

		}
		li{
			float: left;
			color: white;
			width: 60px;
			height: 50px;
			/* 行高 */
			line-height: 50px;
			/* 将鼠标变成小手 */
			cursor: pointer;
			/* 文字居中 */
			text-align: center;
		}
		li:hover{
			background: red;
		}
	</style>
</head>
<body>
	<div class="box">
		<ul>
			<li>首页</li>
			<li>国内</li>
			<li>国际</li>
			<li>军事</li>
			<li>财经</li>
			<li>娱乐</li>
			<li>体育</li>
			<li>互联网</li>
			<li>科技</li>
			<li>游戏</li>
			<li>女人</li>
			<li>汽车</li>
			<li>房产</li>
			

		</ul>
	</div>
</body>
</html>
```

* 子元素的宽度可以是百分比单位，按照父元素的宽度进行划分百分比的
* line-heigh（行高）：可以让文本在垂直方向居中（最好它的属性和当前元素高度一般高）
* cursor: pointer：将鼠标变成小手

## 6.2轮播图的小圆球

![06](D:/HTMLproject/image/06.png)

![image-20200814084723626](D:/HTMLproject/image/image-20200814084723626.png)

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		*{
			margin: 0px;
			padding: 0px;
		}
		ul{
			position: relative;
			left: 500px;
			width: 300px;
			height: 50px;
			list-style: none;
			border: solid;
		}
		li{
			width: 50px;
			height: 50px;
			background: green;

			float: left;
			/* 靠左外边距 */
			margin-right:  10px;
			/* 圆角设置 */
			border-radius: 25px;
		}
		.cur{
			background: yellow;
		}
	</style>
</head>
<body>
	<ul>
		<li class="cur"></li>
		<li></li>
		<li></li>
		<li></li>
		<li></li>
	</ul>
</body>
</html>
```

## 6.3四叶草效果

https://www.w3school.com.cn/cssref/pr_animation.asp（css中给元素添加动画：animation）

概述：web前端开发浏览器厂商常见：谷歌（chorme）、IE、火狐、欧朋

Animation：动画稍微了解（知道有这个东西即可）前端工程师可以利用样式搞动画

浏览器厂商的私有前缀（带有私有前缀样式只能在当前浏览器I中使用）

| 谷歌   | IE   | 火狐 | 欧朋 |
| ------ | ---- | ---- | ---- |
| webkit | ms   | moz  | o    |

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		*{
			margin: 0px;
			padding: 0px;
		}
		.box{
			/* 相对定位，相对的是自己的起始位置 */
			position: relative;
			width: 200px;
			height: 200px;
			/* border: 1px solid black; */
			left: 40%;
			/* 调用动画 */
			animation:donghua 5s linear 0s infinite ;
		}
		.ye1{
			position: absolute;
			left: 0px;
			top: 0px;
			width: 100px;
			height: 100px;
			background: green;
			/* 圆角的设置：分别左上、右上、右下、左下 */
			border-radius: 0px 90px 0px 90px; 
		}
		.ye2{
			position: absolute;
			left: 100px;
			top: 0px;
			width: 100px;
			height: 100px;
			background: green;
			border-radius: 90px 0px 90px 0px;
		}
		.ye3{
			position: absolute;
			left: 0px;
			top: 100px;
			width: 100px;
			height: 100px;
			background: green;
			border-radius: 90px 0px 90px 0px;
		}
		.ye4{
			position: absolute;
			left: 100px;
			top: 100px;
			width: 100px;
			height: 100px;
			background: green;
			border-radius: 0px 90px 0px 90px;
		}
		/* 声明一个animation动画 */
		@-moz-keyframes donghua{
			from{
				/* 让父元素旋转360度,旋转单位是deg */
				transform: rotate(0deg);
			}
			to{
				transform: rotate(360deg);
			}
		}
	</style>
</head>
<body>
	<div class="box">
		<div class="ye1"></div>
		<div class="ye2"></div>
		<div class="ye3"></div>
		<div class="ye4"></div>
	</div>

</body>
</html>
```

# 七、常见的轮播图的布局

概述：很多电商的网站（淘宝、京东）它首页中都带有banner（轮播图功能）

![image-20200814121401449](D:/HTMLproject/image/image-20200814121401449.png)

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style type="text/css">
		*{
			margin: 0px;
			padding: 0px;
		}
		.box{
			/* 相对定位 */
			position: relative;
			width: 520px;
			height: 280px;
			border: solid 1px red;
			left: 400px;
			top: 100px;
		}
		ul{
			position: absolute;
			/* 去除默认样式（前面的黑色小球） */
			list-style: none;
			width: 520px;
			height: 280px;
			/* 如果子元素超出父元素部分隐藏 */
			overflow: hidden;
		}
		.leftbtn{
			position: absolute;
			width: 30px;
			height: 30px;
			background: black;
			left: 0px;
			top: 130px;
			color: white;
			/* 文本居中 */
			text-align: center;
			/* 行高设置（让文字垂直方向居中：一般和高度一样） */
			line-height: 30px;
			cursor: pointer;
			/* 透明度 */
			opacity: .5;
		}
		.rightbtn{
			position: absolute;
			width: 40px;
			height: 30px;
			background: black;
			left: 480px;
			top: 130px;
			color: white;
			text-align: center;
			line-height: 30px;
			cursor: pointer;
			opacity: .5;
		}
		ol{
			position: absolute;
			width: 200px;
			height: 25px;
			/*background: red;*/
			left: 30%;
			bottom: 5px;
			list-style: none;


		}
		/* 后代选择器 */
		ol li{
			float: left;
			width: 25px;
			height: 25px;
			background:black;
			color: white;
			/* 变为圆球 */
			border-radius: 12.5px;
			/* 文本居中 */
			text-align: center;
			line-height: 25px;
			margin-right: 15px;
			cursor: pointer;
		}
		.cur{
			background: skyblue;
			/* 进行缩放 */
			transform: scale(1.2);
		}
	</style>
</head>
<body>
	<div class="box">
		<!-- 无序列表去做显示图片 -->
		<ul>
			<li><img src="../image/1.jpg" alt=""></li>
			<li><img src="../image/1.jpg" alt=""></li>
			<li><img src="../image/1.jpg" alt=""></li>
			<li><img src="../image/1.jpg" alt=""></li>
			<li><img src="../image/1.jpg" alt=""></li>
		</ul>
		<!-- 做左右按钮 -->
		<div class="leftbtn">left</div>
		<div class="rightbtn">right</div>
		<!-- 做分页器 -->
		<ol>
			<li class="cur">1</li>
			<li>2</li>
			<li>3</li>
			<li>4</li>
			<li>5</li>
		</ol>
	</div>
</body>
</html>
```

注意：transform可以让元素实现变化：旋转、平移、缩放

旋转（单位是度数deg）：可以让元素按照图形的几何中心进行旋转

transform：rotate（360deg）；

缩放：可以等比例让元素宽度和高度成比例放大、缩小

transform：scale（倍数）：属性值【0-1】缩小，【1~】放大

# 八、JavaScript

## 8.1JavaScript简介

概述：JavaScript在前端中简称【JS】，JavaScript是开发web的<font color='red'>脚本语言</font>。

但是它也被用到了很多非浏览器环境中【比如：node平台】，支持面向对象、命令式和声明式（如函数式编程）风格

脚本语言：【php、javascript】：有一个很大的特征，<font color='red'>可以嵌套在静态页面中添加一些动态效果</font>。

JS可以嵌套在静态页面中可以给静态页面添加一些动态效果（脚本语言），不同浏览器厂商（在浏览器中都有内置解析器解析JS语法）

各大浏览器厂商：谷歌chorme、ie浏览器、Firefox、sofai、opera（都有属于自己的解析器）

谷歌浏览器：V8解析器（可以解析js语法：可以让浏览器知道你在写什么）

## 8.2JavaScript组成

* <font color='red'>问题一：前端三层？</font>

​          前端分为三层：

​              结构层：前面课程当中学习的标签

​              样式层：前面课程当中学习的样式

​              行为层：JavaScript

* <font color='red'>问题二：JavaScript组成？</font>

  * ECMAScript:欧洲计算机协会大概每年6月中旬定制语法规范

    比如：变量为什么用var，函数关键字为什么function，循环语句为什么是for

    注意：咱们这段事件学习的是2014年规范简称ES5

  * DOM【document object model】：文档对象模型（经常用来操作标签:在js当中）

  * BOM【browser object model】：浏览器对象模型（模拟浏览器）

  ![image-20200814161135509](D:/HTMLproject/image/image-20200814161135509.png)

## 8.3JS书写格式

概述：JavaScript属于脚本语言，JS语法务必、必要、一定嵌套在静态页面中，JS当中才可以运行；

我们可以利用双壁和标签<script></script>在静态页面中书写JS语法，双闭合标签Script可以放置静态页面中任意地方，Script当然也可以有多个！

```javascript
<script>
    //这里面是要书写JS语法的地方
    alert("Hello World");
</script>
<script>
    alert("今天心里美滋滋");
</script>
```

* JS语法必须放置在双闭合标签Script里面
* 双闭合标签Script可以放置静态页面中任意地方（一般放置静态页面底部）
* 程序当中当站可以有多个Script标签

# 九、内置功能函数使用

概述：浏览器厂商天生本身就有的，我们程序员可以直接使用

## 9.1警告框-alert

概述：警告框功能是在浏览器正上方（中间）弹出一个警告框

用法：

```javascript
<script>
  //单行注释
  /*
    多行注释，可以写多行注释给同事们看
    工作当中尽量养成这个习惯
  */
  //JS字符串，人说的话
  alert("我是祖国的未来");
  alert("我们希望我们将来很好");
  alert('希望挺你');
</script>
```

* 警告框的功能可以多次使用
* JS当中的字符串，外层需要加上" "或者' '（别一双一单）
* 每行代码最后面加上一个分号；代表的是这行语句的结束

## 9.2提示框-prompt

概述：在JS当中有内置的函数prompt，可以在浏览器的正上方弹出一个提示框，

```javascript
<script>
    //提示框
    prompt("请输入英文");
    prompt("姑娘你的芳龄",18);
</script>
```

## 9.3控制台使用-console.log

控制台：快捷键ctr+shift+i

​               鼠标右键+检查

概述：console.log（打印的数据）

```javascript
<script>
    console.log("我在控制台打印数据");
    console.log(123456);
</script>
```

# 十、数据类型

概述：在JS当中也有数据类型之分：基本数据类型（5）、引用类型（复杂数据类型）（1）

<font color='red'>//基本数据类型</font>	

| 数据类型                  | 数值           |
| ------------------------- | -------------- |
| String:字符串（人说的话） | "我爱你祖国"   |
| Number：数字类型          | 100,3.14，-666 |
| Boolean：布尔类型         | true、false    |
| Undefined：未定义         | undefined      |
| Null：空对象类型          | null           |

```javascript
<script>
    //字符串（String）：字符串即为人说的话【务必加上双引号、单引号】
    console.log("我爱你JS");
    console.log("最近快过年了，回家要胖五斤");
    //数字类型（Number）：
    console.log(123);
    console.log(-4);
    console.log(3.14)
    //布尔类型（Boolean）:true、false
    console.log(true);
    console.log(false);
    //未定义类型数据（Undefined）：
    console.log(undefined);
    //空对象类型（Null）
    console.log(null);
</script>
<script>
    //JS当中有一个关键字typeof可以检测数据类型
    console.log(typeof 123);
    console.log(typeof "123");
    console.log(typeof true);
    console.log(typeof null);
</script>
```

* 在JS当中有五个基本数据类型：字符串、数字、布尔、未定义、空对象
* typeof是JS当中的一个关键字，可以检测数据类型

<font color='red'>//引用数据类型：</font>

| 数据类型       | 数值                       |
| -------------- | -------------------------- |
| Object引用类型 | 函数、数组、正则、DOM、BOM |

# 十一、变量******************

概述：变量（variable）起源于数学，变量相当于一个容器，变量可以<font color='red'>存储数据</font>、<font color='red'>存储计算完的结果，通过访问变量名字获取存储的数据</font>

JavaScript当中变量使用：

1. 用关键字var声明变量     var 变量名字
2. 给变量进行赋值              变量名字 = 123；
3. 使用变量                          console.log(变量名字);

```javascript
<script>
    //第一步：用关键字var（variable）进行声明变量
    var num;
    //第二部：给变量进行赋值（右侧数据||计算完的结果）
    num=123;
    var a=100;
    var b=200;
    var c=b;
    //通过访问变量名字，获取到对应的存储数据
    console.log(num);
    console.log(a,b,c);
</script>
```

* JS当中变量只是用关键字var声明但未赋值，默认初始Undefined

```javascript
<script>
    //变量的名字必须要符合命名标识符规范
    //变量的名字可以是数字，英文字母，下划线，美元符号
    //变量的名字I不能以数字开头
    //变量的名字不能是关键字
    var abc= 123;
    console.log(abc);
    abc = "我喜欢貂蝉";
    abc = "ty";
    var abc1=abc;
    console.log(abc);
    console.log("------");
    console.log(abc1);
    console.log(0.1+0.2);//0.30000000000000004（遵守iEEE754浮点数标准，保留17位小数）
    console.log(0.3+0.2);//0.5
    console.log((0.1+0.2).toFixed(2));//保留两位小数
</script>
```

* JS当中变量可以生命一次，但是可以多次赋值
* 多次赋值后再使用，使用的是最后一次赋值数据

# 十二、运算符

概述：在JS当中拥有数学运算符、比较运算符、逻辑运算符和赋值运算符等等

运算符又称之为操作符。

## 12.1数学运算符（5）

概述：数学运算符即为：+、-、*、/、%。

在JS当中<font color='red' size=5>任意类型的数据</font>都可以参与数学运算

除了数字以外的其他类型数据需要隐式转换为数组参与数学运算

### 12.1.1数字类型数据参与数学运算

概述：如果是数字参与数学运算和正常的运算顺序一样

```javascript
<script>
    //数学运算符------数字参与
    console.log(66+22);
    console.log(66-22);
    console.log(66*22);
    console.log(66/22);
    console.log(66%22);
    console.log("-----------");
</script>
```

### 12.1.2布尔类型数据参与数学运算

概述：在JS当中布尔类型数据也可以参与数学运算，布尔值参与数学运算，计算机底层自动隐式转换为数字参与。（底层完成隐式转换其实是通过系统内置函数Number完成）

```javascript
<script>
    //数学运算符------布尔类型数值
    //系统自动转换，true为1、false为0
    console.log(Number(true));//1
    console.log(Number(false));//0
    console.log(true+22);//23
    console.log(false+22);//22
    console.log("-----------");
</script>
```

### 12.1.3未定义类型参与数学运算

概述：未定义类型也可以参与数学运算，需要隐式转换为数组NaN【Not a Number】

NaN是JS语言当中一个数字类型特殊值，一般进行数字运算符的时候，计算不出结果，返回数字NaN

```javascript
<script>
    //在JS当中未定义类型数据undefined也可以参与数学运算
    //要隐式转换为数字参与,会隐式转换为NaN
    /*********************************************/
    //NaN也是数字类型数据：只不过这个数值比较特殊，一般在计算数学运算的时候返回数字NaN
    console.log(Number(undefined));//NaN
    console.log(typeof(NaN));//number
    console.log(undefined+22);//NaN
    console.log(0/0);//NaN
</script>
```

* 总结：未定义类型的数据也可以参与数学运算，但是需要隐式转换为数字NaN参与
* NaN是数字类型是一个特殊值，这个数字进行数学运算的时候都是计算不出结果(NaN)

### 12.1.4空对象类型参与数学运算

概述：空对象类型数据null，也可以参与数学运算符，但是需要隐式转换为数字参与运算

```javascript
<script>
    //数学运算符------空对象类型数值
    //注意：虽然控制台打印的是Object类型，其实不是，应是Null
    console.log(Number(null));//0
    console.log(typeof(null));//Object
    console.log(null/22);
    console.log("-----------");
</script>
```

### 12.1.5小总结

概述：任意类型的数据都可以参与数学运算，如果不是数字类型的，浏览器会自动隐式转换为数字参与

| **布尔类型**   | **true=1;false=0;** |
| -------------- | ------------------- |
| **未定义类型** | **undefined=NaN;**  |
| **空对象类型** | **null=0**          |

### 12.1.6字符串类型参与数学运算**************

概述：字符串也可以参与数学运算，但是它有一些特殊：

特殊：字符串参与数学运算符的时候，加号比较特殊；

* 加号在JS当中比较特殊，如果加号遇见了字符串（不是数学中加法），前端程序员叫做连字符

```javascript
<script>
    //数学运算符------字符串类型数值
    //加号运算符如果遇见了字符串，此时不是数学中的加号，而是连字符
    console.log("66"+22);//6622
    console.log("12"+22+44);//122244
    console.log(22+44+"12");//6612
    console.log(Number("12"));//12
    console.log("66"-88);//-22
    console.log("66"*22);//1452
    console.log("66"/22);//3
    console.log("66"%22);//0
</script>
<script>
    //字符串参与
    console.log("张三"+66);
    console.log("张三"+'李四');
    //如果是字符串参与数学运算，会隐式转换为NaN
    console.log("张三"-22);
    console.log("张三"*22);
    console.log("张三"/22);
    console.log("张三"%22);
</script>
```

注意：

JS当中数学运算符，字符串也可以参与数学运算，但是加号比较特殊，

**如果加号遇见字符串称之为连字符，将数据从左到右拼接为字符串**

如果减、乘、除、取模参与运算，都隐式转换为数字参与

## 12.2比较运算符（8）

概述：任意类型数据都可以参与比较运算，比较最终结果为true||false

### 12.2.1数字比较

| >    | 大于                      |
| ---- | ------------------------- |
| >=   | 大于等于                  |
| <    | 小于                      |
| <=   | 小于等于                  |
| ==   | 等于                      |
| ！=  | 不等于                    |
| ===  | 全等（看数值+看数据类型） |
| ！== | 不全等                    |

```javascript
<script>
    //数字参与比较运算
    console.log(3>5);//false
    console.log(3>=5);//false
    console.log(3<5);//true
    console.log(3<=5);//true
    console.log(3==5);//false
    console.log(3!=5);//true
    console.log(3=="3");//true
    console.log(3==="3");//false
</script>
```

注意1：

一个等号：赋值运算符，不是进行比较运算（常用于给变量赋值）

两个等号：相等比较运算符，（只看数值是否一样）

三个等号：全等比较运算符　（既看数值又看类型）

### 12.2.2其他类型数据比较（字符串除外）

概述：其他类型的数据也可以参与比较（数字和字符串出去），其他类型数据也可以参与比较运算，但是需要隐式转化为数字

```javascript
<script>
    //其他类型数据也可以参与比较运算符
    //但是需要隐式转换为数字参与
    console.log(100>true);
    console.log(true===1);
    console.log(NaN>100);//false
    var a;
    console.log(a==null);//true
    console.log(null==0);//false
    console.log(null>0);//false
    console.log(undefined==NaN);//false
</script>
```

### 12.2.3字符串比较

概述：字符串参与比较时候分为两种情况：

1. 字符串和数字
2. 字符串和字符串比较

#### 12.2.3.1字符串和数字比较

概述：如果是字符串和数字比较：字符串隐式转换为数字参与比较

```javascript
<script>
    //字符串类型参与比较运算符
    //字符串和数字进行比较
    console.log("66">99);//false
    console.log("33">22);//true
    console.log("33"==33);//true
    console.log("33"===33);//false
</script>
```

#### 12.2.3.2字符串和字符串进行比较

概述：如果是字符串和字符串比较：通过的是ASCII码的数值进行比较

两个字符串都是从左到右一个一个进行比较：直到某一个字符比较出结果，比较结束

字符:    0-9    <    A-Z    <    a-z

```javascript
<script>
    //字符串类型参与比较运算符
    //字符串和字符串进行比较
    console.log('a2'>'A2');//true
    console.log('b2a'>'ABC');//true
</script>
```

## 12.3逻辑运算符（3）

概述：在JavaScript脚本语言当中也有所谓的逻辑运算符 【与、或、非】

任意类型数据都可以参与逻辑运算，但是（除了布尔值以外的数据）需要转换为布尔值参与逻辑运算符（通过内置函数Boolean将其他函数转换为布尔值）

### 12.3.1逻辑与

概述：在JS当中使用&&代表逻辑与

书写语法格式：A  &&  B

* A数值一般需要是布尔值，B数值一般需要也是布尔值
* 两个都为真，结果为真【一假俱假】
* A为真、结果看B
* A为假、结果看A

### 12.3.2逻辑或

概述：在JS当中使用||代表逻辑或

书写语法格式：A  ||  B

* 一真俱真
* A为真、结果看A
* A为假、结果看B

### 12.3.3逻辑非

概述：在JS当中使用！代表逻辑非，作用是置反

书写语法格式：！A

* 自身相反【一假为真】
* JS当中的逻辑非可以同时使用多个

### 12.3.4布尔值参与逻辑运算

```javascript
<script>
    //布尔值参与逻辑运算
    console.log(true && true);//true
    console.log(true && false);//false
    console.log(false && true);//false
    console.log(false && false);//false
    console.log("----------")||
    console.log(true || true);//true
    console.log(true || false);//true
    console.log(false || true);//true
    console.log(false || false);//false
    console.log("----------")
    console.log(!true);//false
    console.log(!false);//true
    console.log(!!!true);//false
    console.log("**********")
</script>
```

### 12.3.5其他类型数据参与逻辑运算

#### 12.3.5.1数字类型参与逻辑运算

```javascript
<script>
    //数字类型参与逻辑运算
    //数字类型隐式转换为布尔值
    console.log(Boolean(0));//false
    console.log(Boolean(1));//true
    console.log(Boolean(2));//true
    console.log(Boolean(-1));//true
    console.log(Boolean(NaN));//false
</script>
```

* 0和NaN为false
* 其余数为true

#### 12.3.5.2字符串类型参与逻辑运算

```javascript
<script>
    //字符串类型参与逻辑运算
    //字符串类型隐式转换为布尔值
    console.log(Boolean(""));//false
    console.log(Boolean(''));//false
    console.log(Boolean("我爱你12306和ABC"));//true
    console.log("**********")
</script>
```

* 空字符串隐式转换为false
* 非空字符串隐式转化为true

#### 12.3.5.3未定义、空对象参与逻辑运算

```javascript
<script>
    //未定义、空对象类型参与逻辑运算
    //未定义、空对象类型隐式转换为布尔值
    console.log(Boolean(undefined));//false
    console.log(Boolean(null));//false
</script>
```

* undefined隐式转换为false
* null隐式转换为fales

# 十三、if条件语句

概述：在JS脚本语言当中，也有条件语句，也有循环语句

## 13.1条件语句的基本使用

```javascript
<script>
    //条件语句的基本使用
    if(true){
        alert("大江东去浪淘尽");
    }
    if(false){
        alert(123);
    }
    //其他类型的数据也可以作为条件语句条件：但是都隐式转换为布尔值
    if(6666){
        alert(6666);
    }
    if(NaN){
        alert(NaN);
    }
</script>
```

* 条件语句的条件：一般需要的是布尔值，但是其他类型的数据也可以参与（隐式转换为布尔值）
* 如果条件语句只有一行代码，可以省略 { }

## 13.2if结合else关键字一起使用

```javascript
<script>
    //关键字else结合if一起使用
    //关键字else【否则】，可以结合if条件语句一起使用
    //else关键字是对于上面条件进行否定
    //小案例：让用户输入一个分数对应弹出这个学生是否及格
    var score =prompt("请你输入你的分数");
    if(score>60){
         alert("及格");
    }else{
         alert("不及格");
    }
</script>
```

* else关键字可以结合if条件语句一起使用
* else这个分支对于上面分支条件进行否定

# 十四、循环语句

概述：JavaScript脚本语句当中也有循环【loop】语句，可以做一些重复的事情

while、do...while、for

```javascript
<script>
    //for循环
    for(var i=0;i<10;i++){
        document.write("<h1>我爱你祖国</h1>");
    }
    console.log(i);
</script>
```

* 在JS中，循环语句第一步，定义的i是循环变量，可以在循环体外面使用

## 14.1水仙花数字

```javascript
<script>
    //在控制台中输出三位数字的水仙花数字
    //parseInt:取整
    for(var number=100;number<=999;number++){
        var a=Math.pow(parseInt(number/100),3);
        var b=Math.pow(parseInt(number/10%10),3);
        var c=Math.pow(parseInt(number%10),3);
        if(a+b+c==number){
            console.log(number);
        }
    }
</script>
```

## 14.2for、while、do...while

```javascript
<script>
    //计算数字1~100之间的数字累加和
    var sum=0;
    for(var i=1;i<=100;i++){
        sum+=i;
    }
    document.write(sum+"<br>");
</script>
```

```javascript
<script>
    //while计算1~100之间数字累加和
    var i=100,sum=0;
    while(i>0){
        sum+=i;
        i--;
    }
    document.writeln(sum);
</script>
```

```javascript
<script>
    //do...while计算1~100之间的累加和
    var i=1,sum=0;
    do{
        sum+=i;
        i++;
    }while(i<=100);
    document.write(sum+"　do...while<br>");
</script>
```

总结：JS当中的循环语句和Java中的循环语句很类似，但是JS循环语句变量可以在循环体外使用

## 14.3break、continue

概述：break可以终止就近循环语句（立刻终止）

​           continue可以跳出当前循环，进行下一次循环

## 14.4总结

1. 有时间学习一下其他语言
2. JS、PHP、.net、C++、C#、scala、oc...

# 十五、JavaScript函数

概述：在javascript脚本语言中也有函数，函数其实就是将某一个功能进行封装，当你想使用这个功能的时候，需要调用、执行这个函数

比如：学习过的内置函数

* alert：这个功能是在浏览器的正上方弹出一个警告框
* prompt：这个功能是在浏览器的正上方弹出一个提示框

他们使用的时候：函数名字+小括号

在JavaScript脚本语言当中，函数使用也会是分为两部分：声明+调用

注意：函数在JS当中声明方式有两种：<font color='red'>关键字function（函数）声明函数、表达式声明函数</font>

## 15.1关键字基本使用

概述：JS当中如果想声明关键字形式函数，需要用到关键字function进行声明

基本语法：

```javascript
//声明部分
function函数名字（）{

}
//调用
函数名字（）
```

```javascript
<script>
    //关键字形式函数分为两部分：声明+调用
    //声明部分
    function fun(){
        //书写代码地方（函数体）
        console.log("鹅鹅鹅，曲项向天歌，白毛浮绿水，红掌拨清波");
    }
    //函数调用部分
    fun();
</script>
```

* 函数声明一次，可以多次调用

## 15.2函数的形参和实参

```javascript
<script>
    //形参（形式参数）和实参（实际参数）
    //a,b是形参
    function fun(a,b){
        console.log(a+b);
    }
    //100、200是实参
    fun(100,200);
    fun("张三","李四");
</script>
```

* 在JS当中数学运算中，加号比较特殊，如果加号遇见字符串，变为连字符，不进行加法运算

  将数据从左到右进行字符串拼接

## 15.3全局变量和局部变量

* 局部变量：

  作为函数形参【只能在函数体中使用】、在函数体中声明变量【只能在函数体中使用】

* 全局变量

  只要不是局部变量，即为全局变量【全局变量可以在JS行为层中任意使用】

//局部变量:只能在函数体中使用

```js
<script>
    //局部变量：函数形参、在函数体中声明的变量（只能在函数体中使用）
    function fun(a,b){
        console.log(a);
        console.log(b);
        //在函数体中生命的额变量
        var c="memeda";
    }
    //调用
    fun(true,"我是祖国的花骨朵")
</script>
```

//全局变量和局部变量的区分

```javascript
<script>
    //全局变量和局部变量的区分
    //当前变量i为全局变量
    for(var i=1;i<10;i++){
        console.log(i);
    }
    console.log(i);
    //全局变量
    if(true){
        var str="全局变量";
    }
    console.log(str);
    //判断下面变量是全局还是局部
    var a=100;//全局
    /*****************************************/
    //haha、hehe是局部变量
    function fun(haha,hehe){
        console.log(haha);
        console.log(hehe);
        //这个变量是局部
        for(var num=1;num<10;num++){

        }
    }
    fun(1,2);
</script>
```

总结：

* 局部变量：函数形参、函数体中声明的变量（只能在函数体中使用）
* 全局变量：全局变量可以在JS行为层中任意地方使用

## 15.4作用域

概述：作用域【scope】代码的书写范围

```javascript
<script>
    //作用域：书写代码的范围
    //称之为全局作用域
    console.log(123);

    //函数也有作用域概念
    function fun(a,b){
        
    }
</script>
```

问题：作用域是什么？

书写代码范围

全局作用域：可以理解为两个双闭合标签Script之间

函数作用域：函数体内

## 15.5JS中没有重载的概念*************

概述：在JS当中如果有多个重名的函数，永远是后者覆盖前者，没有重载的问题

```html
<script>
    function fun(a){
        console.log("我是第一个");
    }
    function fun(a,b){
        console.log("我是第二个");
    }
    fun(1);
</script>
//打印结果为：“我是第二个”
```

## 15.6关键字return

概述：return是JS当中关键字，经常结合函数一起使用，可以将函数计算完结果返回；

注意：return关键字只能在函数体中使用

1. 在函数体中return关键字后面语句不再执行
2. 可以将函数体中计算完结果返回，可以在函数体外面使用

//返回结果为123、456

```javascript
<script>
    function fun(a,b){
        console.log(123);
        console.log(456);
        return;
        console.log(789);
    }
    fun(6,7);
</script>
```

//返回结果为13

```javascript
<script>
     function fun(a,b){
         return a+b;
     }
         var sum=fun(6,7);
         console.log(sum);
</script>
```

* Return可以将函数体重计算完结果返回，在函数体中使用

# 十六、拓展canvas

## 16.1canvas简介

https://developer.mozilla.org/zh-CN/docs/Web/API/Canvas_API学习手册

概述：canvas是2014年（超文本标记语言第五次重大修改中新增的）结构层中一个双闭合标签

我们可以通过JS在行为层中操作画布，可以在canvas中绘制一些简单图形、对于图片进行裁切、可以实现一些简单2D动画、显示视频

### 16.1.1canvas基本使用

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0px;
            padding: 0px;
        }
        canvas{
            border: 1px solid black;
        }
    </style>
</head>
<body>
    <canvas width="600" height="400"></canvas>
</body>
</html>
<script>
    var canvas=document.querySelector("canvas");
    //console.log(canvas);
    //画布当中任何操作必须通过2D上下文进行操作
    var ctx=canvas.getContext("2d");
    //一定要注意，画布当中任意操作都是通过2D上下文进行操作
    //设置矩形填充颜色
    ctx.fillStyle="cyan";
    //绘制矩形
    ctx.fillRect(100,100,100,100);


    //绘制圆形
    //通过路径形式绘制圆
    ctx.beginPath();
    //用户在描述绘制图形
    //300、300：圆心位置   50：半径   0：起始弧度  2PI：结束弧度360deg  true：逆时针
    ctx.arc(300,300,50,0,Math.PI*2,true);
    //设置填充的颜色
    ctx.fillStyle="red";
    //开始填充
    ctx.fill();
    //边框设置
    ctx.lineWidth=20;
    ctx.strokeStyle="pink";
    ctx.stroke();
</script>
```

* canvas是HTML5中新增的双闭合标签【浏览器认为他是一张图片】
* canvas便签有默认width：300    height：150
* canvas标签width、height务必通过属性进行设置（别写样式设置），否则变形
* canvas标签文本儿子标签没有任何意义

canvas最基本的功能是绘制图形，需要注意画布任意操作都是通过2D上下文进行渲染

https://threejs.org/    WebGL学习手册

# 十七、数组

Array：数组

概述：在JS当中也有数组存在，数组你可以理解为是一个容器，可以存储很多有序数据

数组在JS当中是引用类型的数据，在JS当中数组是  [ ]  表示

## 17.1数组基本使用

```javascript
<script>
    //在JS当中数组使用[]进行表示
    //JS当中数据是引用类型数据
    console.log([]);
    console.log(typeof([]));
    //数组目的，可以一次性存储很多有序数据
    console.log([1,2,3,4,5,6,7,8,9,10]);
    console.log(i);
</script>
```

* JS当中[]代表是数组，数组是引用类型数据
* JS当中可以存储很多元素（数据：可以是任意类型）

## 17.2数组的作用

**数据经常存储、读取、修改、新增数据**

```javascript
<script>
    //为了在JS当中使用数据方便，经常将右侧数组赋值给左侧边量（通过变量名字可以访问存储数组）
    //存储数据
    var arr=[1,"我爱你祖国",true,undefined,NaN,[1,2,3]];
    //为了读取数据：通过枚举法+下角标（索引值）获取数组里面存储数据
    for(var i=0;i<arr.length;i++){
        console.log(arr[i]);
    }
    console.log(arr[5][2]);
    //修改数组里面数据
    arr[1]="我爱你母亲";
    console.log(arr);
    //新增数据
    arr[6]="我是后来的";
    console.log(arr);
</script>
```

* JS当中数据：可以存储、可以读取、可以修改、可以新增数据

## 17.3length属性

概述：length是数组一个属性，主要作用是可以获取数组元素总个数；因此它返回的是一个数字

```javascript
<script> 
 for(var i=0;i<arr.length;i++){
        console.log(arr[i]);
    }
    console.log(arr[5][2]);
</script>
```

//获取数组中最大值

```javascript
<script>
    //获取数组里面最大的元素
    var arr=[66,3,2,99,26,21,19,88];
    //假设第零项元素是最大的
    var max=arr[0];
    //遍历数组，如果比max大，则替换元素
    for(var i=1;i<arr.length;i++){
        if(max<arr[i]){
            var temp=max;
            max=arr[i];
            arr[i]=temp
        }
    }
    arr[0]=max;
    console.log(max);
    console.log(arr)
</script>
```

## 17.4数组的方法

https://www.w3school.com.cn/jsref/jsref_obj_array.asp 数组方法学习手册

### 17.4.1pop||push********

概述：它们两者是数组方法，主要的作用是可以在数组尾处移除、添加元素

单词少的：移除元素     单词多的：添加元素

```JavaScript
<script>
    //声明数组
    var arr=["幺鸡","五万","三饼","二条","二筒","发财"];
    //pop:是数组的一个方法，主要作用是可以在数组尾巴处移除一项元素
    var result=arr.pop();
    console.log(arr);
    console.log(result);
</script>
```

* pop是数组方法，可以在数组尾处移除一项元素
* pop方法有返回值，返回的是移除掉的那项元素

```javascript
    //push:是数组方法，主要的作用可以向数组尾处添加一个、多个元素
    var result1= arr.push("曹操");
    var result2=arr.push("刘备","关羽","张飞");
    console.log(arr);
    console.log(result1);//6
    console.log(result2);//9
```

* push也是数组方法：主要作用是可以向数组尾处添加一项、多项元素
* push方法执行完毕后有返回值，返回的数值是数组新增完元素总个数

**总结：**

1.  Pop是数组方法，可以在数组尾处一出掉一项元素，返回的是移除掉的那项元素
2. push也是数组方法，主要作用是可以向数组尾处添加一项、多项元素，返回的数值是数组新增完元素总个数

### 17.4.2shift||unshift********

概述：shift||unshift他们两者是数组方法，可以在数组头部添加、移除元素

单词少的：移除元素     单词多的：添加元素

```javascript
  //声明数组
    var arr=["幺鸡","五万","三饼","二条","二筒","发财"];
    //pop:是数组的一个方法，主要作用是可以在数组尾巴处移除一项元素
    var result=arr.pop();
    console.log(arr);
    console.log(result);
```

* shift：是数组方法，可以在数组头部移除一项元素
* shift：方法有返回值，返回的是移除掉的那项元素

```
    //push:是数组方法，主要的作用可以向数组尾处添加一个、多个元素
    var result1= arr.push("曹操");
    var result2=arr.push("刘备","关羽","张飞");
    console.log(arr);
    console.log(result1);//6
    console.log(result2);//9
```

* unshift：是数组方法：主要作用是可以向数组头部添加一项、多项元素
* unshift：方法执行完毕后有返回值，返回的数值是数组新增完元素总个数

**总结：**

1.  shift：是数组方法，可以在数组头部移除一项元素，返回的是移除掉的那项元素
2. unshift：也是数组方法，主要作用是可以向数组头部添加一项、多项元素，返回的数值是数组新增完元素总个数

### 17.4.3reverse

概述：让数组所有元素进行倒置

```javascript
<script>
    //reverse:数组方法让数组元素进行倒置(所有元素)
    var arr=["香港港独","最近别吃香蕉","广厦事件"];
    arr.reverse();
    console.log(arr);
</script>
```

### 17.4.4indeOf

概述：他是数组方法，主要的作用是可以获取数组当中某一个元素索引值

```javascript
<script>
    //indexOf：可以检索某一个元素的索引值
    var arr=["香港港独","最近别吃香蕉","广厦事件",1,2,3];
    console.log(arr.indexOf(1));
</script>
```

* indexOf是在数组方法，可以获取数组当中某一个元素索引值I

注意：

* 获取到的是从左到右第一个符合条件的索引值
* 如果获取的是数组里面没有元素，返回索引值是-1

### 17.4.5join**************

概述：它也是数组的方法，主要的作用是可以通过某一个字符将数组转换为字符串

```javascript
<script>
    //join:将数组转换为字符串
    var arr=["北京","南京","燕京","东京","吴京","亮晶晶"];
    console.log(arr.join());
    console.log(arr.join("*"));
    console.log(arr.join(""));
</script>
```

### 17.4.6concat

概述：它也是数组方法，主要的作用是将多个数据合并为一个数组

```javascript
<script>
    //concat：将多个数据合并为一个数组
    var arr=["北京","南京","燕京","东京","吴京","亮晶晶"];
    var arr1=[1,2,3,4];
    var arr2=[5,6,7,8];
    console.log(arr.concat(arr1));
    console.log(arr.concat(arr1,arr2));
</script>
```

### 17.4.7slice

概述：它是数组的方法，主要的作用是切割数组

书法格式：

注意：切割的时候，包含起始位置，但是不包含结束位置

* slice对起始数组没有影响

arr.slice(起始索引值，结束索引值)

```javascript
<script>
    //slice:数组的方法用于切割数组【对起始数组没有影响】
    //代表起始位置索引值，结束位置索引值（包含起始位置，但是不包含结束位置）
    var arr=["小浣熊","麻花","包子","烤鸭","棒棒糖"];
    //一个参数，代表起始位置
    console.log(arr.slice(1));
    //两个参数，代表起始位置和结束位置
    console.log(arr.slice(1,3));//麻花，包子【不包含结束位置】
</script>
```

### 17.4.8splice切割、插入、替换

概述：它也是数组方法，主要的作用是切割数组

语法格式：

arr.splice(起始位置，长度)

```javascript
<script>
    //splice:按长度切割数组【对起始数组有影响】
    var arr=["王者荣耀","吃鸡","lol","魔兽","传奇","劲舞团","CF","DNF","逆战"];
    //在指定位置I切割指定长度数组
    console.log(arr.splice(2,3));
    console.log(arr);
</script>
<script>
    var arr=["王者荣耀","吃鸡","lol","魔兽","传奇","劲舞团","CF","DNF","逆战"];
    //插入
    arr.splice(2,0,"hahah","么么哒");
    //替换
    arr.splice(2,2,"tihuan","xixixi");
    console.log(arr);
</script>
```

# 十八、认识DOM

## 18.1问题：

1. 前段三层：结构层【html】、样式层【css】、行为层【js】
2. 描述JS的组成：ECMAScript、DOM、BOM

## 18.2节点树

节点【element】即为标签

概述：静态页面骨架是由标签组成，标签之间关系很像一颗大树，简称节点树

如下图，静态页面标签之间关系图，很像一颗大树，因此称之为节点树

![image-20200811185833514](D:\HTMLproject\image\01.png)

### 18.2.1认识DOM

概述：DOM【全称document Object model】起始就是系统内置引用类型对象document，可以认为它是真个节点树的<font color='red'>‘根元素’</font>

JSDOM对象可以通过一些手段，操作结构层中的标签

#### 18.2.1.1DOM的四个小属性

```javascript
<script>
    //DOM:其实就是你内置document（页面）对象，你可以认为是当前页面的‘根元素’
    //DOM：是引用数据类型
    console.log(document);
    console.log(typeof document);
    //四个小属性
    console.log(document.documentElement);
    console.log(document.head);
    console.log(document.body);
    console.log(document.title);
</script>
```

* documentElement属性：可以获取页面中的HTML标签
* head属性：可以获取页面中的head标签
* body属性：可以获取页面中的body标签
* title属性：可以操作title标签的文本

#### 18.2.1.2DOM方法

概述：上面已经学习了四个属性：documentElement（获取html标签）、head（获取head标签）、body（获取body标签）、title（获取标图文字内容）

如果想获取其他页面中的标签，需要通过一些方法获取，DOM方法很多，今天只学一个

getElementById:DOM的这个方法可以通过标签的ID选择器匹配任意节点树上标签

```javascript
<script>
    //getElementById:是DOM方法，可以通过标签ID属性值获取任意节点
    var meta=document.getElementById("box");
    console.log(meta);
</script>
```

* getElementById:是DOM方法，可以通过节点ID属性值获取节点树上任意标签
* Script便签一般放置程序最下方（因为加载先后顺序问题）

### 18.2.2操作标签文本

概述：我们可以通过DOM方法获取节点树上任意节点，除此之外，获取节点经常操作自己文本内容

* 如果是表单元素：需要通过value属性操作文本【经常结合form标签一起使用的input标签】
* 如果是非表单元素，需要通过innerHTML属性操作文本【非input标签】

下面红色地方是称之为标签文本

```javascript
<div><font color='red'>我是祖国的未来</font></div>
```

```javascript
<script>
    //如果操作表单元素文本，需要使用标签的value属性
    //操作文本：即为可以在JS当中获取已有文本,但也可以重新设置文本
    //第一步，获取表单元素
    var input=document.getElementById("cur");
    console.log(input);
    //获取表单元素文本
    console.log(input.value);
    //从新设置表单元素文本
    input.value="我是JS设置的元素";


    //非表单元素：不是input即可
    //非标单元素操作文本：需要通过innerHTML属性
    //获取非表单元素
    var a=document.getElementById("box");
    console.log(a);
    //获取非表单元素的文本
    console.log(a.innerHTML);
    //从新设置非表单元素的文本
    a.innerHTML="我是JS设置的百度";
</script>
```

### 18.2.3操作标签的属性

下面红的部分称之为属性

<img <font color='red'>src="./1.jpg"</font>>

```javascript
<script>
    //获取img标签
    var img=document.getElementById("box");
    //获取标签的属性值
    console.log(img.src);
    //从新更改src的属性值
    img.src="../image/meinv1.jpg";

    var div=document.getElementById("haha");
    console.log(div);
    //获取div的class、id属性值
    console.log(div.id);
    console.log(div.className);
    //从新设置class属性值
    div.className="rewrite";
    div.innerHTML="粉刷本领强";
</script>
```

* 大多情况下：操作标签属性：标签.属性名字   进行操作
* 但是有特例：class属性，如果操作标签class属性，需要通过className属性进行操作

### 18.2.4操作标签的样式

概述：我们通过DOM可以操作标签的行内样式

区分web样式：

* Link：外部样式
* style：内部样式
* 标签里面的：行内样式

```javascript
<script>
    //操作标签的行内样式
    //获取div标签
    var div=document.getElementById("cur");
    //获取已有的样式
    console.log(div.style.width);
    console.log(div.style.height);
    console.log(div.style.color);
    console.log(div.style.border);
    //设置元素样式
    div.style.width="200px";
    div.style.height="200px";
    div.style.color="red";
    div.style.border="5px solid cyan";
    //如果样式中中间带有-，变驼峰写法
    div.style.fontSize="30px";
    div.style.textAlign="center";
    div.style.lineHeight="200px";
</script>
```

* DOM能操作的只是标签的行内样式，（外部样式、内部样式暂时操作不了）
* 样式中属性带有  -  变为驼峰写法
* 该有单位需要有单位

### 18.2.5事件**************

概述：事件（event），事件是由用户触发，当用户触发事件的时候，标签可以做出相应的响应

比如：用户触发单机事件，鼠标移上、鼠标移下...

语法格式：

element.onxxx = function(){

}

* function称之为事件处理函数（当用户除法事件的时候才会执行一次）

#### 18.2.5.1单击事件-onclick

概述：可以给任意的标签绑定单击事件（当用户触发事件的时候），事件处理函数才会执行一次

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0px;
            padding: 0px;
        }
        #box{
            width: 100px;
            height: 100px;
            background:red;
            /* 鼠标变小手 */
            cursor: pointer;
            color: white;
            text-align: center;
            line-height: 100px;
            font-size: 16px;
        }
        #box1{
            position: relative;
            width: 100px;
            height: 100px;
            background: cyan;
            left: 0px;

        }
        #box2{
            width: 100px;
            height: 100px;
            background: pink;
        }
    </style>
</head>
<body>
    <div id="box">文字</div>
    <div id="box1"></div>
    <div id="box2"></div>
</body>
</html>
<script>
    //给第一个div标签绑定单击事件
    var div=document.getElementById("box");
    var div1=document.getElementById("box1");
    var div2=document.getElementById("box2")
    //定义一个全局变量，存储起始字号的大小
    var f=16;
    var w=100;
    //定义left值
    var l=0;
    //绑定单击事件
    //字号加1
    div.onclick=function(){
        //console.log("我这个函数执行了");
        f++;
        w+=5;
        div.style.fontSize=f+"px";
        div.style.width=w+"px";
        
    }
    //点击向前移动
    div1.onclick=function(){
        l+=10;
        div1.style.left=l+"px";
    }
    //点击换颜色
    div2.onclick=function(){
        //随机三个数字,三原色
        var R=parseInt(Math.random()*255);
        var G=parseInt(Math.random()*255);
        var B=parseInt(Math.random()*255);
        //随机的颜色
        div2.style.background=`rgb(${R},${G},${B})`;
    }
    
</script>
```

* **注意：JS属于脚本语言，脚本语言需要嵌套在静态页面中，给静态页面添加动态效果**

#### 18.2.5.2动态创建10个标签

```javascript
<script>
    //JS动态创建节点
    //先获取ul标签
    var ul=document.getElementById("box3");
    for(var i=1;i<=10;i++){
    //DOM提供给我们一个createElement方法，可以在JS当中动态创建标签
    var li=document.createElement("li");
    console.log(li);
    li.innerHTML=i;
    //任何的标签节点都有一个appendChild方法，可以追加子节点
    ul.appendChild(li);
    }
</script>
```

# 十九、echarts图表库**************

https://echarts.apache.org/zh/index.html官方手册

概述：echarts是前端工程师中比较出名的JavaScript函数库，它最牛的一件事情，就是可以快速开发各种图表

比如：饼图、K线图、折线图

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 第一步：需要引包，将人家的源码引入 -->
    <!-- 通过双闭合标签Script将echarts源码引入 -->
    <script src="../js/echarts.min.js"></script>
</head>
<body>
      <!-- 第二步，显示图表的地方 -->
      <!-- 容器：显示图表的地方 -->
      <div id="main" style="width: 600px;height:400px;"></div>
</body>
</html>
<script type="text/javascript">
    //当引入echarts函数的时候，它对外保留一个对象通过init方法创建实例
    console.log(echarts);
    var myChart = echarts.init(document.getElementById('main'));

    // 指定图表的配置项和数据
    var option = {
        title: {
            text: 'ECharts 入门示例'
        },
        tooltip: {},
        legend: {
            data:['销量']
        },
        xAxis: {
            data: ["衬衫","羊毛衫","雪纺衫","裤子","高跟鞋","袜子"]
        },
        yAxis: {},
        series: [{
            name: '销量',
            type: 'bar',
            data: [5, 20, 36, 10, 10, 20]
        }]
    };

    // 使用刚指定的配置项和数据显示图表。
    myChart.setOption(option);
</script>
```

* echarts函数库：搞图表开发
* 在实际工作的时候用到概率比较大的【前端工程师】

# 二十、对象

概述：前端工程师中也有面向对象编程概念（基于面向对象编程），在JS当中对象分为两种：

* 第一种：狭义对象
* 第二种：广义对象

## 20.1狭义对象

概述：在JS当中狭义对象用一个大花括号表示{}，狭义对象可以拥有很多的属性和方法

```javascript
<script>
    //狭义对象：是用大花括号表示
    var obj={
        name:"小明",
        age:18,
        sex:"男",
        eat:function(){
            console.log("我可以吃巴金米饭");
        }
    }
    //检测当前对象的类型
    console.log(typeof obj);
    //对应获取属性值
    console.log(obj.name);
    console.log(obj.age);
    console.log(obj.sex);
    console.log(obj.eat);
    //重新修改属性值
    obj.name="二哈";
    console.log(obj);
    //动态添加属性、方法
    obj.color="白加黑";
    obj.play=function(){
        console.log("我会踢足球");
    }
    console.log(obj);
    obj.play();
</script>
```

* 在JS当中，{ }  即为狭义对象
* 狭义对象可以拥有属性和方法（区分开属性和方法）
* <font size=5 color='red'>记住：JS当中的对象才可以通过点语法动态添加属性和方法</font>

## 20.2广义对象

 概述：如果是引用类型数据（函数、数组等），且系统提供内置属性和方法的对象，称之为广义对象

```javascript
<script>
    //广义对象---函数
    function People(a,b,c){

    }
    //在JS当中：五个基本数据类型：数字、字符串、布尔、未定义、空对象
    //引用数据类型:Object
    //函数即为广义对象：因为有一些系统内置属性、方法提供给我们使用
    //name:系统提供的内置属性：可以获取函数名字
    console.log(People.name);
    //length:系统提供的内置属性，可以获取函数形参个数
    console.log(People.length);
    //动态添加自定义属性
    People.names="我是小明";
    People.age=18;
    People.gender="男";
    console.log(People.names);
    console.log(People.age);
    console.log(People.gender);
</script>
```

总结：在JS当中对象有两种【狭义、对象】，可以通过点语法动态添加自定义属性、方法

* 狭义对象：起始狭义对象即为 { } ，
* 广义对象：广义对象除了自定义属性、方法以外，系统给它提供了内置属性和方法使用
* **大总结：其实在JS当中只要是引用类型数据即为对象**

## 20.3什么不是对象

概述：在JS当中基本数据类型的数值都不是对象（如果不是对象，不能通过点语法动态添加属性和方法）

数字，字符串，布尔，未定义，空对象

* **总结：在jS当中引用类型的数据都是对象，都可以通过点语法动态添加属性和语法**
* **在JS当中基本数据类型都不是对象，不能通过点语法添加属性和方法**

# 二十一、函数上下文*********

概述：函数上下文即为this，它只能在函数体中使用，函数上下文this（它代表的数值并不是一个固定的数值），

**函数上下文数值取决于函数改如何调用**

问题：JS当中函数执行方式有几种？（五种）

1. 函数名  .（）
2. 函数作为事件处理函数执行
3. 定时器回调函数
4. 函数作为数组元素枚举出来执行
5. 函数作为对象方法执行

综上所述：函数执行方式有五种，不同执行方式，函数上下文this是不同的

## 21.1函数名.()执行

概述：函数名.()执行，函数体中上下文为window【即为BOM对象：浏览器对象】

```javascript
<script>
    //先认识BOM【browser Object model】：浏览器对象模型
    //在模拟浏览器
    console.log(window);
    //函数名.()执行，函数上下文即为BOM【内置window对象】
    function fun(){
        //this即为函数上下文
        console.log(this);
    }
    fun();
</script>
```

## 21.2函数作为事件处理函数执行

概述：函数做为事件处理函数执行，函数的上下文即为触发事件当前的标签

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0px;
            padding: 0px;
        }
        #box{
            width: 400px;
            height: 200px;
            background:red;
        }
    </style>
</head>
<body>
    <div id="box"></div>
</body>
</html>
<script>
    //获取div标签
    var div=document.getElementById("box");
    //绑定单击事件
    div.onclick=function(){
        //div.style.background="black";
        this.style.background="cyan";
        console.log(this);

    }
</script>
```

## 21.3定时器的回调函数执行

概述：在JS当中，定时器的回调函数会每隔一段时间执行一次，而定时器回调函数上下文为window

```javascript
<script>
    //定时器的回调函数每个一段时间执行一次
    //第一个参数，函数（称之为回调函数）
    //第二个参数，是一个数字（代表的是定时器间隔），单位MS
    setInterval(function(){
        console.log("我爱你祖国");
        console.log(this);
    },1000);
</script>
```

## 21.4函数作为数组的元素枚举执行

概述：函数作为数组元素枚举出来执行，函数的上下文为当前的数组

```javascript
<script>
    var arr =[1,2,3,4,5,function(){
    console.log("我是数组里面的函数---我执行了");
    console.log(this);
    this.reverse();
    },6,7,8,9,10];
    //枚举出函数执行
    arr[5]();
    console.log(arr);
</script>
```

## 21.5函数作为狭义对象方法执行

概述：函数作为狭义对象方法执行，追最后打点，函数的上下文即为谁

```javascript
<script>
    //函数作为狭义对象的上下文执行，谁最后打点，函数上下文即为谁
    var ty={
        name:"taoyin",
        age:21,
        gender:"男",
        eat:function(){
            console.log("我可以吃八斤米饭");
            console.log(this);
            console.log(this.name);
        }

    }
    ty.eat();
</script>
```

## 21.6总结

* 函数上下文的五大规律：

1. 函数名.() ：window
2. 函数作为事件处理函数：当前触发这个事件标签
3. 定时器回调函数每隔一段时间：window
4. 函数作为数组元素枚举出来执行：当前数组
5. 函数作为狭义对象方法执行：最后打点对象

# 二十二、构造函数

概述：在JS当中，也有所谓的构造函数【constructor】，JS当中构造函数要符合如下两个特征

* 函数名字首个英文字母一般需要大写【不是决定性因素】
* 构造函数务必、必须、一定是一个关键字new调用的【决定性因素】

## 22.1先认知关键字new

概述：在上一次课程当中，我们知道函数执行一共五种，关键字new也是调用函数的另外一种方式

```JavaScript
<script>
    //认知关键字new,他也是调用函数的一种方式
    //函数生命不分
    function Fun(){
        console.log("兄弟，你执行呀");
    }
    Fun();
    //关键字new也是调用函数的一种手段
    new Fun;
</script>
```

* 关键字new也是调用函数的一种方式【六种方式】
* 关键字new需要放在函数名字前面

## 22.2构造函数的基本使用

```javascript
<script>
    //构造函数两个特征：
    //1.构造函数名首字母大写【不是决定性因素】2.构造函数必须是new调用的【决定性因素】
    //问题：函数名.()调用和通过new调用，两者有什么区别
    function People(){
        //第一步：在函数体中神秘的创建了一个空的狭义对象【大的花括号】
        //第二步：函数体中的上下文指向当前这个空的狭义对象
        //第三步：通过点语法给狭义对象动态的添加属性 、方法
        this.xingming="xiaoming";
        this.age=18;
        this.gender="男";
        this.hobby=["吃放","睡觉","打豆豆"];
        //第四步：虽然没有关键字return，但是系统自动将狭义对象返回

    }
    var obj=new People;
    console.log(obj);
</script>
```

## 22.3原型链---prototype

概述：在前端工程师中，构造函数就是所谓的类，经历四步走返回的狭义对象，前端工程师叫做实例

比如：Dog构造函数一般称之为Dog类，obj、taidi一般称之为Dog类的实例

```javascript
<script>
    //构造函数的两个特征：
    //函数名字首个英文字母需要大写的
    //函数务必使用关键字new调用的
    function Dog(name,gender,age){
        console.log(name,gender,age);
        //构造函数独有的四步走
        //第一步：在函数体中神秘创建了一个空的狭义对象
        //第二步：函数的上下文指向当前的空的狭义对象
        //第三步：通过点语法动态地给狭义对象添加属性、方法
        this.name=name;
        this.gender=gender;
        this.age=age;
        //第四步：虽然没有关键字return，但是系统会将当前这个狭义对象返回
    }
    //调用函数
    var obj=new Dog("二哈","公",3);
    console.log(obj);
    var taidi=new Dog("二哈","公",3);
    console.log(taidi);
    //因为这是两个不同的对象，因为在堆空间当中内存地址不同
    console.log(obj==taidi);
</script>
//es6的构造函数
<script>
    class People{
        constructor(){
            
        }
    }
</script>
```

* 构造函数也是一个普通函数，只不过是通过关键字new调用而已，以前函数能做什么，构造函数也可以，只不过捎带返回一个空的狭义对象

* 构造函数也是一个函数，以前函数能做的构造函数也能做【循环、条件】
* 只不过构造函数捎带返回一个狭义对象

概述：在JS当中，<font color='red'>任意的构造函数</font>，天生都有一个prototype属性，指向一个<font color='red'>空的狭义对象</font>

<font color='red'>实例</font>天生拥有一个<font color='red'>--proto--属性</font>，像上面的<font color='red'>狭义对象借用方法使用</font>

```javascript
<script>
    //构造函数天生都有一个prototype属性，指向一个空的狭义对象
    function Dog(name,age,gender){
        this.name=name;
        this.age=age;
        this.gender=gender;
    }
    //console.log(Dog.prototype)
    //任意的构造函数天生都拥有一个prototype属性
    Dog.prototype.play=function(){
        console.log("我可以咬人");
    }
    //创建出来的实例，天生又有一个__proto__属性，可以向上面的狭义对象借用方法使用
    //创建二哈实例
    var erha=new Dog("二哈",18,"公");
    console.log(erha);
    erha.play();
</script>
```

![image-20200820172304953](D:/HTMLproject/image/image-20200820172304953.png)

## 22.4士兵行走

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0px;
            padding: 0px;
        }
        div{
            position: relative;
            width: 50px;
            height: 100px;
            background: url("../image/04.png");
            /* 背景图定位 */
            background-position: 0px -200px;
        }
    </style>
</head>
<body>
    <div id="box">

    </div>
</body>
</html>
<script>
    //获取标签
    var div =document.getElementById("box");
    //创建一个全局变量，控制北京图定位
    var x=0;
    //控制标签left变化数值
    var l=0;
    //控制士兵行走、定制变量
    var ismove = false;
    //一直原地踏步走【利用定时器一直修改div背景图定位】
    setInterval(function(){
        if(ismove){
            return;
        }
        x++;
        l+=10;
        if(x>3){
            x=0;
        }
        if(l>1200){
            l=0;
        }
        div.style.backgroundPosition=-x*50+"px -200px";
        div.style.left=l+"px";
    },250)
    //单机标签div进行ismove的数值变化
    div.onclick=function(){
        //数值进行置反
        ismove=!ismove;
    }
</script>
```

# 二十三、jQuery函数库简介**************

https://jquery.cuishifeng.cn/ jQuery学习手册

概述：jQuery它是前端当中比较优秀的一个javascript函数库【前端人经常简称JQ】，它核心理念是写的少、做的事情多

JQ可以进行DOM操作、节点事件处理、简单2D动画等等

jQuery函数库支出链式语法（连续打点），JQ有一些插件，使用JQ的时候一般不用考虑兼容的问题

## 23.1jQuery函数库的基本使用

**(注！jquery-2.0以上版本不再支持IE 6/7/8) 并不是最新的版本就最好的，而是根据您项目需求所适合的版本！**

第一步，需要在网上下载人家的源码 http://www.jq22.com/jquery-info122

**注意1：如果你想在程序当中使用JQ，需要在程序当中通过Script便签引入JQ**

```javascript
<script>
    //第一：JQ函数经常用来操作节点树上的标签
    //支持我们曾静学习过选择器：标签选择器、ID选择器、class选择器
    //注意1：当程序当中引入JQ，这个函数库对外暴露可一个$函数，他是JQ函数一个核心函数
    //经常用来匹配标签
    $("li").css({"color":"red"});
    //标签选择器
    console.log($("li"));
    //id选择器
    console.log($("#box"));
    //类选择器
    console.log($(".cur"));
    //如果想设置匹配标签的行内样式可以连续打点css函数
    $("p").css({
        "color":"red",
        "fontSize":"30px",
        "background":"cyan",
        "textAlign":"center"
    });
</script>
```

* 一般情况下，单位px可以省略
* 中间带有-样式【font-size，padding-left】要变为驼峰写法
* jQuery函数库支持我们曾经学习过的标签选择器，ID选择器，class选择器等等

## 23.2jQuery函数库中独有的选择器

概述：一会学习的选择器只能在JQ中使用，因为它是JQ中独有的

```javascript
<script>
    //下面这些都是JQ函数独有选择器
    //:first,可以获取某一个匹配标签的第一个元素
    $("div:first").css({"color":"red"});
    //:last,可以获取到某一个匹配标签最后一个元素
    $("div:last").css({"background":"cyan"});
    //:even,代表的是偶数选择器
    $("div:even").css({"background":"skyblue"});
    //:odd,代表的是奇数选择器
    $("div:odd").css({"background":"pink"});
    //:gt(index),大于选择器
    $("div:gt(6)").css({"color":"red"})
    //:lt(index),小于选择器
    $("div:lt(6)").css({"color":"yellow"});
</script>
```

* jQuery函数库支持我们曾经学习过的选择器，除此之外还支持一些独有的选择器

| ：first        | ：last           | ：even     | ：odd      | ：gt(index) | :lt(index) |
| -------------- | ---------------- | ---------- | ---------- | ----------- | ---------- |
| 匹配第一个元素 | 匹配最后一个元素 | 偶数选择器 | 奇数选择器 | 大于选择器  | 小于选择器 |

## 23.3操作匹配标签文本

```
<h1>我是一级标题</h1>
```

* 表单元素【input标签】利用JQ中val方法操作表单元素文本
* 非表单元素利用JQ中html方法操作文本

```javascript
<script>
    //操作表单元素文本，利用的val方法
    //获取表单元素文本
    console.log($("input").val());
    //重新设置表单元素文本
    $("input").val("我修改了表单元素的文本");
    /*****************************************/
    //操作非表单元素文本，利用的html方法
    //获取非表单元素文本
    console.log($("div").html());
    $("div").html("修改非标单元素文本啦");
</script>
```

* 表单元素操作文本：利用val函数
* 非表单元素操作文本：利用html函数

## 23.4给元素绑定事件

概述：JQ函数库对于元素事件也进行了封装，都封装成函数形式

```javascript
<script>
    //定义默认字号
    var f=16;
    //JQ对于元素绑定事件都封装成函数
    $("div").click(function(){
        f+=1;
        //修改div的字号大小
        $("div").css({"fontSize":f})
    });
</script>
```

* 前端当中事件很多【只是学习了单击事件】，如果想学习其他事件，参考这个网址进行学习https://jquery.cuishifeng.cn/click.html

## 23.5特效函数

概述：JQ函数库提供了一些特效函数，可以给匹配元素添加一些动画效果

```javascript
<script>
    //第一个按钮的单击事件
    $("#box1").click(function(){
        //slideUp:可以让元素向上卷起，它传递参数2000代表动画时间(MS)
        $("div").slideUp(2000);
    })
    $("#box2").click(function(){
        //slideDown:可以让元素向下展开，它传递参数2000代表动画时间(MS)
        $("div").slideDown(2000);
    })
    $("#box3").click(function(){
        $("div").fadeOut(2000);
    })
    $("#box4").click(function(){
        $("div").fadeIn(2000);
    })
</script>
```

## 23.6jQueryUI插件使用**************

https://jqueryui.com/学习手册

概述：jQuery是JQ函数库一个插件

插件：就是在JQ已有的功能的基础上，再添加一个其他功能

注意：jQuery是JQ插件【也是一个JS函数库】，需要注意这个函数库依赖JQ，在使用jQueryUI的时候，务必要引入JQ才可以使用

//拖拽案例

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引入JQ -->
    <script src="../js/jQuery.min.js"></script>
    <!-- 引入插件 -->
    <script src="../js/jquery-ui.min.js"></script>
</head>
<body>
    <div id="draggable" class="ui-widget-content">
        <p>请拖动我！</p>
      </div>
      <ul>
          <li>吃饭</li>
          <li>睡觉</li>
          <li>打豆豆</li>
      </ul>
</body>
</html>
<script>
    //$(function() {
      $( "#draggable" ).draggable();
    //});
    $("ul").sortable();
</script>
```

//日历案例

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/jQuery.min.js"></script>
    <script src="../js/jquery-ui.min.js"></script>
    <!-- 引入样式 -->
    <link rel="stylesheet" href="../jquery-ui-1.12.1/jquery-ui.css">
</head>
<body>
    <p>
        <input type="text">
    </p>
</body>
</html>
<script>
    $("input").datepicker();
</script>
```

# 二十四、节点关系函数

概述：jQuery函数库中拥有一些节点（标签，element）关系一些方法提供给我们使用

比如：可以获取某一个标签的父元素、兄弟元素、儿子元素等等

## 24.1parent

概述：它是jQuery函数库提供一个节点关系方法，主要的作用是可以获取到某一个标签的父元素

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/jQuery.min.js"></script>
    <style>
        *{
            margin:0px;
            padding: 0px;
        }
        div{
            width: 500px;
            height: 100px;
            border: 1px solid black;
            margin: 100px auto;
        }
        p{
            float: left;
            width: 100px;
            height: 100px;
            background: pink;
            margin-right:10px;
        }
    </style>
</head>
<body>
    <div>
        <p></p>
        <p></p>
        <p></p>
        <p></p>
    </div>
</body>
</html>
<script>
    //给p标签绑定单击事件，让他们的父元素div背景颜色为青色
    
    $("p").click(function(){
        //第一种方式
        //$("div").css({"background":"cyan"});
        //第二种方式
        $("p").parent().css({"background":"cyan"});
    });
    
</script>
```

* parent方法可以获取到某一个标签的父元素

## 24.2this【函数上下文】

概述：this不是jQuery函数库提供的，因为系统当中函数就有上下文this

函数的上下文this也可以在JQ当中是用

<font color='red'>总结规律：函数作为事件处理函数执行，上下文this就是当前这个触发事件本身</font>

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/jQuery.min.js"></script>
    <style>
        *{
            margin:0px;
            padding: 0px;
        }
        div{
            width: 500px;
            height: 100px;
            border: 1px solid black;
            margin: 100px auto;
        }
        p{
            float: left;
            width: 100px;
            height: 100px;
            background: pink;
            margin-right:10px;
        }
    </style>
</head>
<body>
    <div>
        <p></p>
        <p></p>
        <p></p>
        <p></p>
    </div>
</body>
</html>
<script>
  //单击某一个p标签，当前被单击的这个p标签背景颜色为天蓝色
  //给全部p标签绑定单击事件
  $("p").click(function(){
      $(this).css({"background":"skyblue"});
  });
</script>
```

* 函数上下文this，也可以在JQ当中使用
* 它代表的是当前触发这个事件的元素（标签）

**函数上下文判断的五大规律：二十一章**

## 24.3siblings（兄弟）

概述：它是jQuery函数库提供一个关系方法，主要是可以获取到某一个便签其他的姊妹元素们

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/jQuery.min.js"></script>
    <style>
        *{
            margin:0px;
            padding: 0px;
        }
        div{
            width: 500px;
            height: 100px;
            border: 1px solid black;
            margin: 100px auto;
        }
        p{
            float: left;
            width: 100px;
            height: 100px;
            background: pink;
            margin-right:10px;
        }
    </style>
</head>
<body>
    <div>
        <p></p>
        <p></p>
        <p></p>
        <p></p>
    </div>
</body>
</html>
<script>
    //siblings:获取姊妹元素
    //单击某一个p，让它的背景颜色为黄色，它的其余兄弟元素们为绿色
    //给p标签绑定单击事件
    $("p").click(function(){
        /*
        //第一种方法
        $(this).css({"background":"yellow"});
        $(this).siblings().css({"background":"green"});
        */
        $(this).css({
            "background":"yellow"
        }).siblings().css({
            "background":"green"
        });
    });
    //链式语法【来源于OC语言：搞ios苹果开发语言】
    //为了方便（书写语句的时候）可以从左到右连续打点
    //看着比较舒服
    //链式语法执行顺序：从左到右依次执行
</script>
```

## 24.4children

概述：它也是jQuery函数库提供的一个节点关系函数，主要的作用是可以获取到某一个节点儿子元素

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/jQuery.min.js"></script>
    <style>
        *{
            margin:0px;
            padding: 0px;
        }
        div{
            width: 500px;
            height: 100px;
            border: 1px solid black;
            margin: 100px auto;
        }
        p{
            float: left;
            width: 100px;
            height: 100px;
            background: pink;
            margin-right:10px;
        }
    </style>
</head>
<body>
    <div>
        <p></p>
        <p></p>
        <p></p>
        <p></p>
    </div>
</body>
</html>
<script>
    //将四个p标签背景颜色为黑色
    //$("p").css({"background":"black"});
    $("div").children().css({
        "background":"black"
    });
</script>
```

## 24.5折叠卡片效果

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="../js/jQuery.min.js"></script>
    <style>
        *{
            margin: 0px;
            padding: 0px;
        }
        ul{
            width: 600px;
            border: 1px solid black;
            margin:0px auto;
            list-style: none;
        }
        li{
            border-bottom: 1px solid red;
        }
        p{
            background: black;
            color: white;
            display: none;
        }
        h4{
            text-align: center;
            /* 小手 */
            cursor: pointer;
        }
        .open{
            display: block;
        }
    </style>
</head>
<body>
    <ul>
        <li>
            <h4>时政新闻眼丨一场不同寻常的汇报会，习近平强调了什么？</h4>
            <p class="open">
                　　8月20日上午，正在安徽视察调研防汛救灾工作的习近平听取军队参与防汛
                救灾情况汇报，并发表重要讲话。今年防汛，不同往常。这场防汛救灾斗争战况
                如何？后续工作重点怎么干？下半年全军各项工作如何抓？总书记在这场汇报会
                上重点作了部署。△联播视频丨习近平听取军队参与防汛救灾情况汇报并发表重
                要讲话一次不同寻常的汇报会视察调研防汛救灾工作，是习近平这次安徽之行的
                重中之重。从淮河到长江，再到巢湖，都留下了总书记察看水情汛情、关注防汛
                救灾、筹划长远之策的足迹。
            </p>
        </li>
        <li>
            <h4>时政新闻眼丨一场不同寻常的汇报会，习近平强调了什么？</h4>
            <p>
                　　8月20日上午，正在安徽视察调研防汛救灾工作的习近平听取军队参与防汛
                救灾情况汇报，并发表重要讲话。今年防汛，不同往常。这场防汛救灾斗争战况
                如何？后续工作重点怎么干？下半年全军各项工作如何抓？总书记在这场汇报会
                上重点作了部署。△联播视频丨习近平听取军队参与防汛救灾情况汇报并发表重
                要讲话一次不同寻常的汇报会视察调研防汛救灾工作，是习近平这次安徽之行的
                重中之重。从淮河到长江，再到巢湖，都留下了总书记察看水情汛情、关注防汛
                救灾、筹划长远之策的足迹。
            </p>
        </li>
        <li>
            <h4>时政新闻眼丨一场不同寻常的汇报会，习近平强调了什么？</h4>
            <p>
                　　8月20日上午，正在安徽视察调研防汛救灾工作的习近平听取军队参与防汛
                救灾情况汇报，并发表重要讲话。今年防汛，不同往常。这场防汛救灾斗争战况
                如何？后续工作重点怎么干？下半年全军各项工作如何抓？总书记在这场汇报会
                上重点作了部署。△联播视频丨习近平听取军队参与防汛救灾情况汇报并发表重
                要讲话一次不同寻常的汇报会视察调研防汛救灾工作，是习近平这次安徽之行的
                重中之重。从淮河到长江，再到巢湖，都留下了总书记察看水情汛情、关注防汛
                救灾、筹划长远之策的足迹。
            </p>
        </li>
        <li>
            <h4>时政新闻眼丨一场不同寻常的汇报会，习近平强调了什么？</h4>
            <p>
                　　8月20日上午，正在安徽视察调研防汛救灾工作的习近平听取军队参与防汛
                救灾情况汇报，并发表重要讲话。今年防汛，不同往常。这场防汛救灾斗争战况
                如何？后续工作重点怎么干？下半年全军各项工作如何抓？总书记在这场汇报会
                上重点作了部署。△联播视频丨习近平听取军队参与防汛救灾情况汇报并发表重
                要讲话一次不同寻常的汇报会视察调研防汛救灾工作，是习近平这次安徽之行的
                重中之重。从淮河到长江，再到巢湖，都留下了总书记察看水情汛情、关注防汛
                救灾、筹划长远之策的足迹。
            </p>
        </li>
    </ul>
</body>
</html>
<script>
    $("h4").click(function(){
        $(this).siblings().slideDown(2000).parent().siblings().children("p").slideUp(2000);
    });
</script>
```

# 二十五、animate函数

概述：它也是JQ函数库提供的一个动画函数，主要的作用是可以让函数添加一些2D动画效果

语法格式：

$(selector).animate(JSON,TIME,CALLBACK);

* JSON:动画属性设置【left、width、top等等】
* TIME：动画时间设置（MS）
* CALLBACK：函数、这个函数会在动画结束的时候执行一次

## 25.1animate简单使用

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="../js/jQuery.min.js"></script>
    <style>
        *{
            margin: 0px;
            padding: 0px;
        }
        div{
            /* 相对定位 */
            position: relative;
            width: 100px;
            height: 100px;
            background: pink;
        }
    </style>
</head>
<body>
    <div>
        中国
    </div>
</body>
</html>
<script>
    $("div").animate({
        "left":1000,
        "top":100,
        "width":250,
        "heigth":50
    },5000,function(){
        //console.log("动画结束");
        $(this).css({
            "borderRadius":"50%",
            "textAlign":"center"
        })
    });
</script>
```

* Animate:是JQ封装的一个函数动画，并不是全部的样式都可以参与动画（涉及颜色的一般都不能参与动画）

## 25.2动画积累问题

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="../js/jQuery.min.js"></script>
    <style>
        *{
            margin:0px;
            padding: 0px;
        }
        div{
            position: relative;
            width: 100px;
            height: 100px;
            border-radius: 50%;
            background: red;
        }
    </style>
</head>
<body>
    <button class="btn1">去北京</button>
    <button class="btn2">去东京</button>
    <div></div>
</body>
</html>
<script>
    $(".btn1").click(function(){
        $("div").stop(true).animate({
            "left":1000
        },2000);
    });
    //第二个按钮
    $(".btn2").click(function(){
        $("div").stop(true).animate({
            "left":0
        },2000);
    })
</script>
```

* stop（true）：就是将匹配的元素全部动画清除

# 二十六、轮播图实战案例需求

1. 淘宝轮播图

* 自动轮播（每个一段时间，自动换一场图）
* 鼠标放上去（自动轮播停止），鼠标移出（自动轮播开始）
* 有左右按钮，单击左右按钮，可以切换图片
* 单击不同的分页器，可以显示不同的图片

2. 百度新闻导航

* 鼠标移上去，移下来

## 26.1三位轮播图

概述：轮播图（carousel）。类似于淘宝、京东首页的轮播图，前端工程师经常叫三位轮播图

样式css代码

```css
*{
    margin: 0px;
    padding: 0px;
}
div{
    position: relative;
    width: 520px;
    height: 280px;
    border: 1px solid black;
    margin: 50px auto;
    overflow: hidden;
}
ul{
    position: absolute;
    width: 520px;
    height: 280px;
    list-style: none;
}
img{
    width: 520px;
    height: 280px;
}
ul li{
    position: absolute;
    width: 520px;
    height: 280px;
    left: 520px;
}
.current{
    left: 0px;
}
.lbtn{
    position: absolute;
    left: 0px;
    top: 125px;
    width: 30px;
    height: 30px;
}
.rbtn{
    position: absolute;
    right: 0px;
    top: 125px;
    width: 30px;
    height: 30px;
}
ol{
    position: absolute;
    width: 150px;
    height: 25px;
    list-style: none;
    left: 180px;
    bottom: 5px;

}
ol li{
    float: left;
    width: 25px;
    height: 25px;
    border-radius: 50%;
    background: black;
    margin-right: 5px;
    color: white;
    text-align: center;
    line-height: 25px;
    cursor: pointer;
}
.l1{
        background: skyblue;
        /* 进行缩放 */
        transform: scale(1.2);
}
.l5{
    margin-right: 0px;
}
```

//javascript

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引入外部样式 -->
    <link rel="stylesheet" href="./css/default.css">
    <!-- 引包 -->
    <script src="../js/jQuery.min.js"></script>
</head>
<body>
    <div>
        <ul>
            <li class="current"><img src="../image/1.jpg" alt=""></li>
            <li><img src="../image/09.jpg" alt=""></li>
            <li><img src="../image/10.webp" alt=""></li>
            <li><img src="../image/07.jpg" alt=""></li>
            <li><img src="../image/08.jpg" alt=""></li>
        </ul>
        <!-- &lt;小于符号    &gt;大于符号 -->
        <button class="lbtn">&lt;</button>
        <button class="rbtn">&gt;</button>
        <ol>
            <li class="l1">1</li>
            <li>2</li>
            <li>3</li>
            <li>4</li>
            <li class="l5">5</li>
        </ol>
    </div>
</body>
</html>
<script>
    //rbtn按钮单击事件
    //信号量，全局变量，（控制某一个li的运动）
    var idx=0;
    //右侧按钮的代码进行封装
    function rhandle(){
         //当前显示的这张图片行left为0的位置运动到-600
        //eq():代表的是ul下面所有的li
        $("ul li").eq(idx).css({"left":0}).stop(true).animate({"left":-520},500);
        //全局变量需要累加1【下一张图片要进入到容器里面】
        idx++;
        if(idx>4){
            idx=0;
        }
        //下一张图片从容器的右侧动画进入
        $("ul li").eq(idx).css({"left":520}).stop(true).animate({"left":0},500);
        //底下的分页器页跟着变化
        //addClass代表给标签添加类型，removeClass代表给标签移除类名
        $("ol li").eq(idx).addClass("l1").siblings().removeClass();
    }
    $(".rbtn").click(rhandle);
    //开启定时器
    var timer=setInterval(rhandle,2000);
    //鼠标移上事件
    $("div").mouseenter(function(){
        clearInterval(timer);
    });
    //鼠标离开事件
    $("div").mouseleave(function(){
        timer=setInterval(rhandle,2000);
    })

    $(".lbtn").click(function(){
        //当前显示的这张图片行left为0的位置运动到520
        //eq():代表的是ul下面所有的li
        $("ul li").eq(idx).css({"left":0}).stop(true).animate({"left":520},500);
        //全局变量需要累加1【下一张图片要进入到容器里面】
        idx--;
        if(idx<0){
            idx=4;
        }
        //下一张图片从容器的右侧动画进入
        $("ul li").eq(idx).css({"left":-520}).stop(true).animate({"left":0},500);
        //底下的分页器页跟着变化
        //addClass代表给标签添加类型，removeClass代表给标签移除类名
        $("ol li").eq(idx).addClass("l1").siblings().removeClass();
    });
    /*****************************************/
    //底下分页器业务
    $("ol li").click(function(){
        //获取单击的那个li的索引值
        var index=$(this).index();
        //分两种情况讨论
        if(index>idx){
            //当前显示的这张图片动画
            $("ul li").eq(idx).css({"left":0}).stop(true).animate({"left":-520},500);
            $("ul li").eq(index).css({"left":520}).stop(true).animate({"left":0},500);
            //底下的分页器页跟着变化
            //addClass代表给标签添加类型，removeClass代表给标签移除类名
            idx=index;
            $("ol li").eq(idx).addClass("l1").siblings().removeClass();
        }
        if(index<idx){
            //当前显示的这张图片动画
            $("ul li").eq(idx).css({"left":0}).stop(true).animate({"left":520},500);
            $("ul li").eq(index).css({"left":-520}).stop(true).animate({"left":0},500);
            //底下的分页器页跟着变化
            //addClass代表给标签添加类型，removeClass代表给标签移除类名
            idx=index;
            $("ol li").eq(idx).addClass("l1").siblings().removeClass();
        }

    })
</script>
```

* addClass||removeClass:分别是给标签添加类名
* eq方法：可以获取到某一个索引值标签
* index：可以获取到某一个标签索引值

## 26.2百度导航图

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/jQuery.min.js"></script>
    <style>
        *{
            margin: 0px;
            padding: 0px;
        }
        div{
            position: relative;
            width: 100%;
            height: 40px;
            background: #01204f;
        }
        ul{
            position: absolute;
            width: 100%;
            height: 40px;
            list-style: none;
        }
        ul li{
            float: left;
            /* margin-right: 10px;
            text-align: center;
            line-height: 40px; */
            color:white;
            padding: 10px;
        }
        .slider{
            position: absolute;
            width: 52px;
            height: 41px;
            background: red;
            
        }
        .l1{
            background: red;
        }
    </style>
</head>
<body>
    <div>
        <div class="slider"></div>
        <ul>
            <li class="l1">首页</li>
            <li>国内</li>
            <li>国际</li>
            <li>军事</li>
            <li>财经</li>
            <li>娱乐</li>
            <li>体育</li>
            <li>互联网</li>
            <li>科技</li>
            <li>游戏</li>
            <li>女人</li>
            <li>汽车</li>
            <li>房产</li>
        </ul>
    </div>
</body>
</html>
<script>
    //全部的li添加鼠标移上事件
    $("ul li").mouseenter(function(){
        //红色滑块算法（要获取到鼠标进入的这个li，前面全部姊妹元素之和）
        //prevAll：代表的是获取某一个元素前面全部姊妹元素
        //累加器
        var sum=0;
        $(this).prevAll().each(function(){
            //获取每一个姊妹元素宽度
            sum+=$(this).innerWidth();
        });
        //让红色滑块动起来
        /*
        var width=$(this).width()+20;
        console.log(width);
        */
        $(".slider").stop(true).animate({
            "left":sum,
            width:$(this).innerWidth()
        },500);
    });
    //鼠标移除，红色滑块归还原始位置
    $("ul li").mouseleave(function(){
        $(".slider").stop(true).animate({
            "left":0,
            "width":$("ul li").eq(0).innerWidth()
        },500);

    });
</script>
```

* prevALL：可以获取到某一个节点前面全部姊妹元素
* Each：可以便利到每一个匹配节点
* InnerWidth：可以获取某一个标签宽度（也算上内边距数据）

# 二十七、AJAX

## 27.1认知服务器

* 什么是服务器

  答：服务器又称伺服器，只要是一台功能、性能差不多的电脑就可以作为服务器

* 服务器主要作用

  答：服务器主要的作用是可以提供数据来源

* 了解一些比较出名的服务器：Apache服务器、nginx

* 服务器可以做什么？

  答：你拥有自己的服务器，就可以创建属于自己的网站了

* 创建属于自己网站需要经历下面三步骤：

  1. 购买一个服务器
  2. 购买域名
  3. DNS解析【域名解析：目的是让服务器认识域名，让域名认识服务器】

* 当用户在地址栏中输入一个网址（url：网络资源定位符），按下回车到底会发生什么

  **答：当用户在地址栏中输入一个网址（url），按下回车，会向服务器端发起一次上行请求，服务器端接受到上行请求后做出下行响应。（经过浏览器渲染，就可以看到网站了）**
  
  注意：客户端可以向服务器发送上行请求，常见上行请求有GET、POST上行请求（其实有20多种上行请求）

## 27.2认知HTTP协议

概述：HTTP【超文本传输协议】，在网络中请求别人网络的时候，地址（url）必须是http||https开头

* http和https有什么不同？

  相同的，都是超文本传输协议，但需要注意https相对安全一些 http safe

* 一个网址URL由哪些部分组成？

  http：超文本传输协议

  www：别名

  taobao：域名

  .com：域名尾缀

  ：8080     ,端口号，端口号范围【0~65535】

| 域名尾缀 | 名称                 |
| -------- | -------------------- |
| .cn      | 中国国家顶级域名     |
| .gov     | 政府机构域名尾缀     |
| .com     | 盈利商业组织（公司） |
| .me      | 黑山共和国顶级域名   |

## 27.3区分前端语言和后台语言区别

* 工作面试的时候：前端语言和后台语言有什么区别？

  后台语言PHP在本地浏览器中没有运行，只是当作标签文本

  PHP后台语言是在服务器上面运行的

  前端语言：JS、CSS、标签是在客户端浏览器中运行的

## 27.4安装服务器Apache服务器

概述：为了学习PHP、将来AJAX技术，我们计算机需要安装一个Apache服务器软件

目的就是为了安装前面这两者知识点

# 二十八、了解PHP基本语法

## 28.1PHP简介

概述：PHP即“超文本预处理器”，是一种通用的开源脚本语言，PHP是在服务器端执行的脚本语言，与c语言类似，是常用的网站编程语言

## 28.2PHP壳子

注意：在学习PHP语法的时候一定要切记PHP是在服务器端运行的

注意：在学习PHP路径千万别出现汉字（倒置程序崩溃）

PHP语法务必放置在壳子中书写：

```php
<?php 书写代码 ?>
```

```php
<?php echo "PHP是世界上最好的语言" ?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>我非常喜欢华为，花了我<?php echo 5888+1 ?></h1>
</body>
</html>
<?php echo 5888+1 ?>
```

* PHP语法需要放置在壳子当中使用<?php 书写代码的地方 ?>
* php可以有多个，可以放置程序任意地方

## 28.3echo

概述：echo是php中一个关键字，主要作用是可以输出数据

一般输出的都是基本数据类型（字符串、数字、布尔等等）

```php
<meta http-equiv="Content-Type" content="text/html;charset=UTF-8">
<!-- php语法当中基本类型数据有数字、字符串、布尔值、空对象，没有未定义 -->
<?php
   echo 123;
   echo "<br>";
   echo "我爱你祖国";
   echo "<br>";
   echo true;

?>
```

## 28.4变量

```php
<?php 
//变量需要用关键字$进行声明
$a = 100;
$b = 200;
echo $a+$b;
//php也支持我们曾经学过的运算符
//数学运算符，+、-、*、/、%
//比较运算符 <、<=、>、>=、！=
//赋值运算符++、--、+=
//逻辑运算符：与、或、非
echo $a>$b?$a:$b;
?>
```

## 28.5流程控制语句

概述：php语言当中也有条件、循环语句

```php
<?php
  for($i =1;$i<=100;$i++){
      if($i %2 ==0){
          echo $i."<br>";
      }
  }
?>
```

* php中也有流程控制语句：条件+循环语句

## 28.6函数

```javascript
<?php
  //函数
  $c=1000;
  function sum($a,$b){
      //如果在函数体中使用全局变量
      //需要受用global关键字进行声明
      global $c;
      echo $a+$b+$c;
  }
  sum(100,200);
?>
```

* php当中函数使用类似于js，但是还是有区别

## 28.7数组

```php
<meta http-equiv="Content-Type" content="text/html;charset=UTF-8">
<?php
  //php当中数组需要通过php内置Array函数进行声明
  $arr =array("吃饭",1);
  echo $arr[0];
  echo $arr[1];
?>
```

# 二十九、AJAX

## 29.1AJAX简介

概述：AJAX【Asynchronous Javascript And XML】是一门技术（不是一门语言），在客户端可以悄悄的向服务器发起上行请求，服务器可以悄悄的做出相应的下行响应，<font color='red' size='5'>在页面没有重新加载的情况下可以实现页面的局部更新</font>

## 29.2AJAX技术的基本束用

概述：AJAX用户端可以向服务器端悄悄的发起上行请求，服务器端悄悄的做出相应的下行相应

在页面中没有重新加载的情况下实现页面的局部更新

注意：前端当中AJAX技术实现其实是有内置构造函数XMLHttpRequest构造函数实现的，但是在工作当中一般都是用JQ，因为JQ将原生AJAX技术进行封装

//JQ当中的AJAX技术------GET

```javascript
<script>
    //给按钮绑定单击事件
    $("button").click(function(){
        //向服务器端悄悄发起上行请求---get，拉取服务器端数据
        //第一个参数，向服务器端请求的path
        //第二个参数：客户端向服务器端额外传递一些数据（可有可无）
        //第三个参数：当服务器响应数据成功的时候会立即执行
        $.get(URL="./data.txt",{"name":"小明","ps":123},
        //data:就是服务器端响应的数据
        function(data){
            alert(data);
            //修改h1标签
            $("h1").html(data);
        });
    });
</script>
```

//JQ当中的AJAX技术------POST

```javascript
<script>
    //第二个按钮发起POST请求
    $("button:eq(1)").click(function(){
        //向服务器端悄悄发起上行请求---POST，拉取服务器端数据
        //第一个参数，向服务器端请求的path
        //第二个参数：客户端向服务器端额外传递一些数据（可有可无）
        //第三个参数：当服务器响应数据成功的时候会立即执行
        $.post(URL="./data.txt",{"color":"yellow"},
        //data:就是服务器端响应的数据
        function(data){
            alert(data);
            //修改h1标签
            $("h1").html(data);
        });
    });
</script>
```

//JQ当中的AJAX技术------get、post

```javascript
 <script>  
   //第三个按钮单击事件
    $("button:eq(2)").click(function () {
        //向服务器端悄悄发起上行请求---POST，拉取服务器端数据
        //当前这个方法可以发起GET、POST，请求参数配置务必是一个JSON数据格式
        $.ajax({
            //请求网站
            "url":"./data.txt",
            //请求方式
            "type":"post",
            "data":{
                "a":1
            },"success":function(data){
            //当服务器想用成功的时候会立即执行一次
            $("h1").html(data);
        }
        
        });
    });
</script>
```

## 29.3原生AJAX技术

概述：AJAX技术原生写法在工作当中不常用，但是面试的时候（前端）有时候会让你手写出来

问题：你了解前端AJAX技术吗，实现原理其实就是使用内置构造函数XMLHttpRequest构造函数使用

状态码：

200   请求成功

404   请求失败

500   服务器端错误

301是永久重定向   302是临时重定向

## 29.4GET和POST区别

概述：

相同地方：GET、POST都属于上行请求

不同地方：

| GET                              | POST                 |
| -------------------------------- | -------------------- |
| 相对而言不安全                   | 相对而言安全一些     |
| 给服务器额外传递的数据是有上限的 | 相对而言是没有上限的 |
| 便与分享                         | 不便于分享           |

# 三十、JSONP跨域问题

概述：跨域（前端当中术语）：当用户发起多次请求的时候，如果协议、域名、端口号不同的情况下，称之为跨域

比如：看下面的表格，问问自己是否跨域

|         第一次请求          |        第二次请求         |        是否跨域        |
| :-------------------------: | :-----------------------: | :--------------------: |
|    http://www.baidu.com     |    http://www.sina.com    |    跨域（域名不同）    |
|   http://www.baidu.com:80   | http://www.baidu.com:8080 | 跨域（因为端口号不同） |
| http://127.0.0.1/index.html |  http://127.0.0.1/01.php  |        没有跨域        |
|      http://127.0.0.1       |     http://127.0.0.2      |    跨域（域名不同）    |

注意：apche服务器可以同时模拟多个服务器

## 30.1JASX技术不能跨域请求数据

概述：AJAX技术不能实现跨域请求数据，因为AJAX技术遵守  ‘同源策略’

```javascript
<script>
    //AJAX技术不能跨域请求问题
    $("button").click(function(){
        //请求第二个服务器上面数据
        $.get("http://127.0.0.2/anli/AJAX/data.txt",function(){
            
        })
    })
</script>
```

## 30.2JSONP可以跨域请求数据

概述：AJAX技术确实不能实现跨域，但是JSONP可以实现

JSONP数据格式跨域so easy：实现原理是如下

* 利用Script标签src属性（本身就可以跨域请求数据）
* 利用的是将一个函数的执行部分放置另外一个服务器上

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="../js/jQuery.min.js"></script>
</head>
<body>
    <h1>我是来源于127.0.0.1服务器上面的页面------拉取127.0.0.2服务器上面的数据</h1>
</body>
</html>
<script>
    //声明一个同名函数
    function fetchV85(a,b,c,d,e){
        console.log(a,b,c,d,e)
    }
</script>
<!-- 将另外一个服务器函数调用部分引入 -->
<script src="http://127.0.0.2/anli/AJAX/fetchV85.txt"></script>
```

# 三十一、node平台**************

https://nodejs.org/en/官方地址

概述：node诞生于2009年，他是一款软件（并不是一门语言），这个软件有一个很牛的功能，可以让JS在这个软件上运行

node在设计的时候目的是想替代老牌Java、PHP后台语言

注意：node软件最开始的时候，想搞服务器端开发（最近已经停止更新了），一定要注意，前端工程师使用node软件目的不是为了开发服务器，它（node）相当于前端开发当中的  ’脚手架‘ ；

node可以跨平台使用

## 31.1安装

概述：安装非常简单，就是无脑下一步

注意：安装node.js四样东西

* 可以让JS运行的环境
* 安装npm工具
* 在线学习手册
* 将node添加环境变量

验证是否安装成功：

打开cmd命令行，输入node -v如果显示出版本号代表安装成功

## 31.2node的基本使用

概述：node是一个软件，这个软件可以让javascript脚本语言在这个软件上运行，使用方式如下：

注意：node软件可以运行JS语法，node软甲只能运行尾缀为.js文件（像静态页面、css、php等等运行不了）

```javascript
//node平台支持js全部核心语法
var a =100;
var b =200;
console.log(a+b);

//运算符【数学运算符、比较运算符、逻辑运算符】都支持
console.log(3>8?3:8);

console.log("------------------------------")

//流程控制语句
var sum=0;
for(var i=1;i<=100;i++){
    if(i%2==0){
        sum+=i; 
    }
}
console.log(sum);

//函数
function fun(a,b){
    console.log(a,b);
}
fun(100,200);

//数组
var arr=["吃饭","睡觉","打豆豆"];
for(var j=0;j<arr.length;j++){
    console.log(arr[j]);
}

//构造函数
var erha=new fun("erha","wangwang");
erha;
//没有BOM、DOM
```

* node软甲支持JS全部核心语法，（ES6、7、8、9、10）
* node平台没有DOM和BOM的概念

运行方式：node软件只能运行JS文件，运行JS文件是在CMD窗口里面运行的（没有浏览器的概念）

进入到JS文件的文件夹里面（shift+鼠标右键）使用CMD，运行方式：执行哪个JS文件，就node +JS文件

## 31.3node平台内置模块的使用

概述：传统JS使用，是在静态页面中通过Script标签引入，node软甲给js赋予一些‘超能力’

传统js是没有办法做到的：比如通过js向某一个文件里面写入一些数据，而这些所谓的超能力，即node给我们提供的内置模块

### 31.3.1fs模块

概述：fs是node软件给我们提供内置模块功能，可以向某一个文件里面写入数据

```javascript
// node软件给我们提供的模块（给js赋予的超能力），node本身就有的
//fs：可以通过JS向某一个文件写入数据
var fs=require("fs");
//向某一个文件写入数据
fs.writeFile("./ty.txt","老师是祖国的未来",function(){
    console.log("数据写入成功");
});
//读取数据
fs.readFile("./ty.txt",function(err,data){
    console.log("文件读取成功");
    console.log(data.toString());
});
```

### 31.3.2queryString模块

```javascript
//queryString模块：可以将JSON数据格式转化为queryString字符串
var queryString=require("querystring");
//将JSON转换为queryString字符串
console.log(queryString.stringify({"a":1,"b":2}));
```

## 31.4NPM工具使用

https://www.npmjs.com/社区网站，这个网站服务器位于美国，

可以利用npm工具去社区网站下载别人已经写好的插件使用（Vue、React）

概述：在安装node的时候，我们安装了一个npm工具，这个工具可以去社区下载其他人已经写好自定义模块，直接在程序中使用

### 31.4.1colors社区自定义模块

自定义：程序员自己写好了的一些模块，不是node平台提供的（需要我们去社区网站通过npm工具进行下载）

问题：CMD控制台打印的文字变颜色

安装：

第一步：去社区网站npm搜多

第二步：打开CMD命令行（路径：务必是当前案例文件夹路径）

第三步：安装通过npm install 自定义模块名字

```javascript
//引入社区自定义模块colors
//可以改变文字颜色
var colors =require("colors");
console.log("我喜欢你".green);
console.log("我很喜欢小红".rainbow);
```

### 31.4.2solarlunar社区自定义模块

概述：进行公历、农历的转换

上同

# 三十二、Vue框架

https://cn.vuejs.org/ Vue框架官网地址

概述：前段领域当中有三大框架（都是开发单页面应用的框架）

1. angular诞生于2009年，是有谷歌创建出来的框架

2. react诞生于2013年，是有Facebook创建出来的框架

3. Vue诞生于2014年，是有中国在校大学生尤雨溪创建出来的

   概述：Vue (读音 /vjuː/，类似于 **view**) 是一套用于构建用户界面的**渐进式框架**。与其它大型框架不同的是，Vue 被设计为可以自底向上逐层应用。Vue 的核心库只关注视图层，不仅易于上手，还便于与第三方库或既有项目整合。



## 32.1Vue框架基本使用

注意：Vue它是属于前端当中的Javascript框架，源码都封装到了一个尾缀为JS这样一个文件里面

因此我们需要获取到源码

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/vue.min.js"></script>
</head>
<body>
    <!-- 页面标签布局 -->
    <div id="app">
        <h1>我是小明，今年{{age}}岁了</h1>
    </div>
</body>
</html>
<script>
    //当程序中引入Vue框架的时候，这个框架对外暴露了一个Vue构造函数
    //通过Vue构造函数可以创建Vue类实例
    var vm=new Vue({
        //el:(element简写)挂载点：将Vue实例和架构层中标签进行联系
        el:"#app",
        //Vue实例数据来源
        data:{
            age:18
        }
    });
    //修改实例age属性值
    vm.age=20;
</script>
```

## 32.2Vue框架中常用的指令

概述：Vue框架给我们提供了很多的指令，都是以v-xxx开头（因为都是Vue提供的），Vue提供的这些指令其实都是作为标签的属性直接使用：

```javascript
<!-- id、class都是标签的属性 -->
<div id="box" class="cur">我是div</div>
```

指令：指令是有Vue提供的，主要的作用是可以操作标签（文本、样式、事件等等）

指令的理解：相当于长官给士兵下达命令

### 32.2.1v-text、v-html

概述：可以更新标签的文本内容   v-text就是{{}}的简写

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/vue.min.js"></script>
</head>
<body>
    <div id="app">
        <h1>下面的指令是操作文本</h1>
        <p v-text="msg"></p>
        <hr>
        <p>{{msg}}</p>
        <p v-html="msg"></p>
    </div>
</body>
</html>
<script>
    //创建Vue实例
    var vm=new Vue({
        "el":"#app",
        data:{
            msg:"Hello World"
        }
    });
</script>
```

* v-text:它可以更新标签文本内容【简写的方式是双大括号】
* v-html:它也可以更新标签文本内容【如果渲染数据为标签形式字符串，会真的渲染为标签】

### 32.2.2v-show

概述：v-show指令可以控制标签的显示与隐藏，底层原理其实是通过CSS中display属性进行控制

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="../js/vue.min.js"></script>
</head>
<body>
    <div id="app">
        <ul>
            <li>吃饭</li>
            <li v-show='false'>睡觉</li>
            <li>打豆豆</li>
        </ul>
    </div>
</body>
</html>
<script>
    var vm=new Vue({
        "el":"#app"
    });
</script>
```

#### 32.2.2.1选项卡小练习

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/vue.min.js"></script>
</head>
<body>
    <div id="app">
        <button @click="add('军事')">军事</button>
        <button @click="add('新闻')">新闻</button>
        <button @click="add('直播')">直播</button>
        <ul v-show="'军事'===info">
            <li>军事</li>
            <li>军事</li>
            <li>军事</li>
            <li>军事</li>
            <li>军事</li>
            <li>军事</li>
            <li>军事</li>
            <li>军事</li>
            <li>军事</li>
            <li>军事</li>
        </ul>
        <ul v-show="'直播'===info">
            <li>直播</li>
            <li>直播</li>
            <li>直播</li>
            <li>直播</li>
            <li>直播</li>
            <li>直播</li>
            <li>直播</li>
            <li>直播</li>
            <li>直播</li>
            <li>直播</li>
        </ul>
        <ul v-show="'新闻'===info">
            <li>新闻</li>
            <li>新闻</li>
            <li>新闻</li>
            <li>新闻</li>
            <li>新闻</li>
            <li>新闻</li>
            <li>新闻</li>
            <li>新闻</li>
            <li>新闻</li>
            <li>新闻</li>
        </ul>
    </div>
</body>
</html>
<script>
    var vm=new Vue({
        el:"#app",
        data:{
            info:"军事"
        },
        //书写标签事件处理函数的地方
        methods:{
            //事件处理函数add
            add(a){
                vm.info=a;
            }
        }
    });
    
</script>
```

### 32.2.3v-if

概述：v-if根据属性值为真假进行渲染标签

注：它和v-show区别：显示与隐藏的标签（在节点树上始终是有的）

​        v-if控制这标签在节点树上上树、下树操作

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/vue.min.js"></script>
</head>
<body>
    <div id="app">
        <h1>你的性别是什么呀</h1>
        <ul>
            <li v-if="'男'==sex">男</li>
            <li v-else-if="'女'==sex">女</li>
            <li v-else>未知</li>
        </ul>
    </div>
</body>
</html>
<script>
    var vm=new Vue({
        "el":"#app",
        data:{
            sex:"31"
        }
    });
</script>
```

### 32.2.4v-for**************

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="../js/vue.min.js"></script>
</head>
<body>
    <div id="app">
        <h1>非常常用的指令v-for</h1>
        <h1>循环语句遍历数字</h1>
        <h2 v-for="item in 10">我是二级标题{{item}}</h2>
        <h1>循环语句遍历数组</h1>
        <ul>
            <li v-for="(item,index) in arr">{{item}}---{{index}}</li>
        </ul>
        <!-- 九九乘法口诀 -->
        <table>
            <!-- 行 -->
            <tr v-for="row in 9">
                <!-- 列 -->
                <td v-for="col in 9" v-show="row>=col">{{col}}*{{row}}={{row*col}}　　</td>
            </tr>
        </table>
    </div>
</body>
</html>
<script>
    var vm=new Vue({
        "el":"#app",
        data:{
            arr:["吃饭","shuijiao","dadoudou"]
        }
    });
</script>
```

#### 32.2.4.1v-for小练习

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="../js/vue.min.js"></script>
</head>
<body>
    <div id="app">
        <p>
            <input type="text" v-model="hoddy">
            <button @click="add()">单机我添加爱好</button>
        </p>
        <ul>
            <li v-for="(item,index) in arr">{{item}}---{{index}}</li>
        </ul>
    </div>
</body>
</html>
<script>
    var vm=new Vue({
        "el":"#app",
        data:{
            arr:["吃饭","睡觉","打豆豆"],
            hoddy:'123'
        },methods:{
            add(){
                //向数组的尾处添加元素
                this.arr.push(this.hoddy),
                this.hoddy=''
            }
        }
    });
</script>
```

### 32.2.5v-on********

概述：这个指令可以给元素绑定事件。v-on简写方式即为@

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="../js/vue.min.js"></script>
</head>
<body>
    <div id="app">
        <h1>我是计数器小案例---{{count}}</h1>
        <!-- <button @click="count+=1">单击我+1</button> -->
        <button @click="add">单击我+1</button>
        <!-- <button v-on:click="count-=1">单击我-1</button> -->
        <button v-on:click="minus">单击我-1</button>
    </div>
</body>
</html>
<script>
    var vm=new Vue({
        "el":"#app",
        data:{
            count:1
        },methods:{
            //加上一的处理函数
            add(){
                this.count++,
                //设置上限
                this.count=this.count>=10?0:this.count
            },
            //减去一的处理函数
            minus(){
                this.count--,
                //设置下线
                this.count=this.count<=0?0:this.count
            }

        }
    });
</script>
```

* Methods这里是书写标签事件处理函数的地方，一定要注意函数名字务必要准确

### 32.2.6v-model**************

概述：v-model这个指令，只能给表单元素使用【给非表单元素使用也可以，但是没有任何效果】

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="../js/vue.min.js"></script>
</head>
<body>
    <div id="app">
        <h1>我是实例属性值{{msg}}</h1>
        <input type="text" v-model="msg">
    </div>
</body>
</html>
<script>
    var vm=new Vue({
        "el":"#app",
        data:{
            msg:"我是实例的数据"
        }
    });
</script>
```

# 三十三、Vue实现联系

复习一下指令：

v-text:简写为{{}}（渲染DOM文本）

v-html:可以渲染DOM文本（可以将标签形式的字符串转换为标签）

v-if:通过标签的上树、下树的形式控制节点的显示与隐藏

v-show：通过display这个属性，控制着标签的控制与隐藏

v-model：数据的双向绑定（表单元素使用）

v-for：遍历

v-on：简写为@，可以给元素绑定事件

v-bind：简写为：（冒号）动态绑定属性值

## 33.1调色板

HTML5中新增的一些表单元素：

HTML5【即为超文本标记语言第五次重大修改，这次修改的时间为2014】新增了很多的表单元素

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form>
        <p>
            <!-- placeholder：占位符属性 -->
            文本框：<input type="text" placeholder="请你输入用户名">
        </p>
        <p>
            单选按钮：
            <input type="radio" name="hobby">吃饭
            <input type="radio" name="hobby">睡觉
            <input type="radio" name="hobby">打豆豆
        </p>
        <p>
            复选按钮：
            <input type="checkbox">飞机
            <input type="checkbox">大炮
            <input type="checkbox">坦克
        </p>
        <hr>
        <h2>一下就是h5中新增的表单元素</h2>
        <p>
            范围条：<input type="range" min="0" max="255" value="0">
        </p>
        <p>
            颜色的表单元素：<input type="color">
        </p>
        <p>
            日历的表单元素：<input type="date">
        </p>
        <p>
            第几周的日历：<input type="week">
        </p>
        <p>
            搜索的表单元素：<input type="serch">
        </p>
        <p>
            网址格式表单元素：（表单元素输入文本务必符合URL格式）
            <input type="url">
        </p>
        <p>
            邮箱格式：（表单元素输入文本务必符合邮箱格式）
            <input type="email">
        </p>
        <p>
            密码框：<input type="password">
        </p>
        <button type="submit">提交</button>
    </form>
</body>
</html>
```

///调色板代码

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/vue.min.js"></script>
</head>
<body>
    <!-- 模板 -->
    <div id="app">
        <!-- 显示颜色变化的元素 -->
        <div :style="{width:'100px',height:'100px',background:`rgb(${R},${G},${B})`}"></div>
        <!-- 三个范围条 -->
        <p>
            R:<input type="range" min="0" max="255" value="0" v-model="R"><span>{{R}}</span>
        </p>
        <p>
            G:<input type="range" min="0" max="255" value="0" v-model="G"><span>{{G}}</span>
        </p>
        <p>
            B:<input type="range" min="0" max="255" value="0" v-model="B"><span>{{B}}</span>
        </p>
    </div>
</body>
</html>
<script>
    var vm=new Vue({
        "el":"#app",
        data:{
            R:0,
            G:0,
            B:0
        }
    });
</script>
```

## 33.2微博发布框

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/vue.min.js"></script>
</head>
<body>
    <!-- 模板 -->
    <div id="app">
        <!-- 多行文本框 -->
        <textarea cols="30" rows="10" v-model="info"></textarea><span>{{info.length}}/140</span>
        <p>
            <button :disabled='info.length==0||info.length>140'>发布</button>
            <button @click="clear">清除</button>
        </p>
    </div>
</body>
</html>
<script>
    //创建vm实例
    var vm=new Vue({
        //配置对象
        el:"#app",
        data:{
            info:''
        },methods:{
            //事件处理函数
            clear(){
                this.info=''
            }
        }
    });
    console.log(vm.info);
</script>
```

## 32.3animation*********

概述：animation是CSS3中新增的动画样式，它的使用类似于函数，分为两部分：声明和调用。

animation这个属性可以让程序员在样式当中完成动画效果

注意：以前让元素运动一般都是需要用过JS【比如：JQ】

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        div{
            position: relative;
            top: 50px;
            left: 50px;
            width: 100px;
            height: 100px;
            background: red;
            text-align: center;
            line-height: 100px;
            /* 第一个参数：动画名称
               第二个参数：每一次动画执行时间（S/MS）
               第三个参数：动画的速率
               第四个参数：第一次动画的延迟事件
               第五个参数：动画执行次数（infinite：执行无数次） */
            animation: donghua 2s linear 0s infinite;
        }
        /* animation动画生命部分 */
        /* webkit代表的是谷歌浏览器的私有前缀 */
        @-webkit-keyframes donghua{
            from{
                transform:rotate(0deg);
                background: red;
                border-radius: 0px 0px 0px 0px;
                font-size: 6px;
            }
            to{
                transform:rotate(360deg);
                background: cyan;
                border-radius: 50px 50px 50px 50px;
                font-size: 30px;
            }
        }
    </style>
</head>
<body>
    <div>我爱你</div>
</body>
</html>
```

## 32.4watch监听属性

概述：Vue框架当中给我们的配置对象当中，可以进行监听属性值变化。

```vue
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="../js/vue.min.js"></script>
</head>
<body>
    <div id="app">
        <h1>{{msg}}</h1>
        <input type="text" v-model="msg">
    </div>
</body>
</html>
<script>
    var vm=new Vue({
        el:"#app",
        data:{
            msg:''
        },
        //监听实例属性值变化的地方
        watch:{
            //watch可以监听实例的属性值的变化
            //watch这里书写函数名字务必和监听属性名字要统一
            msg(){
                console.log(123);
            }
        }
    });
</script>
```

### 32.4.1百度预搜索

```vue
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="./js/vue.min.js"></script>
</head>
<body>
    <div id="app">
        <h1>请你输入想搜索的内容</h1>
        <input type="text" v-model="url">
        <ul>
            <li v-for="item in arr">{{item.q}}</li>
        </ul>
    </div>
</body>
</html>
<script>
    var vm=new Vue({
        el:"#app",
        data:{
            url:"",
            arr:[]
        },
        //监听url属性值变化
        watch:{
            //函数名字务必和监听属性名字一致
            url(newValue){
                //这个函数在监听的属性值发生变化的时候会立即执行一次
                //会将最新的数值给我们作为实参注入
                //请求的网址的拼接
                var path="https://www.baidu.com/sugrec?pre=1&p=3&ie=utf-8&json=1&prod=pc&from=pc_web&sugsid=32667,32606,1469,32327,31254,32046,32270,32117,32090,26350,32497&wd="+newValue+"&req=2&csor=2&pwd=1&cb=jQuery11020035707657495287703_1598517939654&_=1598517939656";
                //JSONP跨域拉取数据
                //实现原理，利用Script标签src属性
                //利用函数的声明+调用放在两个不同的服务器上面
                //动态创建一个Script标签
                var script=document.createElement("script");
                //设置Script标签的src的属性值
                script.src=path;
                //标签上树，将请求发出去
                document.body.appendChild(script);
            }
        }
    });

    //声明一个同名函数
    function jQuery11020035707657495287703_1598517939654(obj){
        //修改vue实例的arr属性值
        console.log(obj);
        vm.arr=obj.g;
    }
</script>
```

# 三十四、框架的生命周期、组件使用

## 34.1Vue当中的声明周期函数

概述：在Vue实例和模板的DOM标签进行关联的时候，其实这个阶段经历很多种状态，

可以通过Vue框架提供的生命周期函数，可以在不同的状态下，书写自己的业务代码即可

注意：在特定的条件下，执行的函数而已（面试常问的：八个）

```vue
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="./js/vue.min.js"></script>
</head>
<body>
    <!-- 模板 -->
    <div id="app">
        <h1>声明周期函数-----{{msg}}</h1>
        <button @click="add">单机我加上一</button>
    </div>
</body>
</html>
<script>
    //创建Vue的实例
    var vm=new Vue({
        //配置对象
        //挂载点
        el:"#app",
        //数据
        data:{
            //msg:"我是vm属性值"
            msg:1
        },
        //事件处理函数
        methods:{
            //事件处理函数
            add(){
                this.msg++
            }
        },
        //监听属性的地方
        watch:{

        },
        //声明周期函数
        beforeCreate(){
            //在创建实例之前执行一次，这里访问不到实例data的数据
            console.log("在创建之前执行一次");
            //console.log(this.msg);
        },
        created(){
            //在实例创建完成之后执行一次
            console.log("在创建vm之后执行一次");
            //console.log(this.msg);
        },
        beforeMount(){
            //在实例创建完毕且和模板进行关联之前执行一次
            console.log("我是vm，即将和模板进行关联");
        },
        /*******************************************/
        mounted(){
            //实例在挂载后执行一次.
            //实际工作当中经常从这个生命周期函数拉取服务器数据
            console.log("我是vm，我已经挂载了");
            //console.log(this.msg);
        },
        beforeUpdate(){
            //数据更新时调用
            console.log("当数据发生变化的时候立即执行一次");
            if(this.msg%2==0)this.msg+=6;
        },
        updated(){
            //当数据发生变化之后
            console.log("当数据发生变化之后立即执行一次");
        }
    });
</script>
```

## 34.2Vue当中AJAX技术实现

概述：AJAX：它是前端当中的一门技术，客户端可以悄悄的向服务器端发起上行请求，服务器端接受到请求后，做出相应的下行响应

在页面没有重新加载的情况下，实现页面的局部更新

Vue2.0版本以后，但是Vue当中的AJAX技术，经常使用axios第三方实现AJAX技术（它的底层使用promise进行封装）

**axios**    exact match

Promise based HTTP client for the browser and node.js

axios：它是Vue当中经常使用的第三方JavaScript函数库，它主要作用是可以向服务器端发起请求

下载axios源码方式：

CDN：百度静态资源库（百度公司给提供的网站：各种常用的源码文件都有）

https://www.bootcdn.cn/

```vue
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="./js/vue.min.js"></script>
    <script src="./js/asios.js"></script>
</head>
<body>
    <div id="app">
        <h1>{{msg}}</h1>
        <button @click="fetchData">单机我发起get</button>
        <button @click="postData">单机我发起post</button>
    </div>
</body>
</html>
<script>
    var vm=new Vue({
        el:"#app",
        data:{
            msg:"默认文本"
        },methods:{
            //通过get请求拉取服务器数据
            fetchData(){
                //发起get请求，拉取服务器新闻数据
                axios.get("./data.txt").then((obj) =>{
                    this.msg=obj.data;
                })
            },
            postData(){
                axios.post("./data.txt").then((obj1)=>{
                    this.msg=obj1.data;
                })
            }
        }
    });
</script>
```

## 34.3生命周期函数结合axios一起使用

```vue
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <!-- 引包 -->
    <script src="./js/axios.js"></script>
    <script src="./js/vue.min.js"></script>
</head>

<body>
    <div id="app">
        <ul>
            <li v-for="item in postList">{{item.name}}</li>
        </ul>
    </div>
</body>

</html>
<script>
    //创建Vue实例
    var vm = new Vue({
        //挂载点
        el: "#app",
        data: {
            postList: []
        },
        //生命周期函数:实例已经和模板挂在完毕
        mounted() {
            //向服务器拉去数据
            axios.get("./jieyong.txt").then(obj => {
                //修改实例postList属性值
                this.postList = obj.data.postList;
            })
        },
    })
</script>

```

## 34.4组件开发

组件：component

![image-20200828164502407](D:/HTMLproject/image/image-20200828164502407.png)

概述：React、Vue框架开发离不开组件式开发

什么组件？

答：在程序当中经常出现功能类似的结构，就可以利用组件进行开发

//局部组件、全局组件

```vue
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="./js/vue.min.js"></script>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        p{
            width: 100px;
            height: 100px;
            background: cyan;
            float: left;
            margin-right: 20px;
        }
    </style>
</head>
<body>
    <!-- 模板 -->
    <div id="app">
        <!-- 用标签形式使用组件 -->
        <ty></ty>
        <gen></gen>
        <tao></tao>
    </div>
    <hr>
    <!-- 下面这里是组件模板 -->
    <template id="ty">
        <p @click="add">{{msg}}</p>
    </template>
    <template id="gen">
        <div>
            <ul>
                <li v-for="item in arr">吃饭-----{{item}}</li>
            </ul>
        </div>
    </template>
    <template id="tao">
        <div>
            <a href="https://www.baidu.com">百度</a>
        </div>
    </template>
</body>
</html>
<script>
    //全局组件，可以在任意地方使用
    //需要通过Vue构造函数的component属性进行创建
    //全局组件要写在局部组件之前
    Vue.component("tao",{
        template:"#tao"
    });
    //Vue当中的组件分为两种，局部组件、全局组件
    //局部组件务必需要在components里面进行注册
    //使用的时候当作一个自定义标签即可
    //注意组件名字不能瞎写，不能是已有标签的名字
    //局部组件名字如果是驼峰写法，在调用的时候要全部小写，中间加-
    //创建Vue实例
    var vm=new Vue({
        //挂载点
        el:"#app",
        //跟组件数据
        data:{},
        methods:{},
        watch:{},
        //局部组件需要注册
        components:{
            ty:{
                //ty组件模板的地方
                template:"#ty",
                //组件的数据
                data(){
                    //ty组件的数据务必要有返回值
                    return {
                        msg:1
                    }
                },
                //ty事件处理函数
                methods:{
                    add(){
                        this.msg++
                    }
                }
            },gen:{
                //gen组件模板
                template:"#gen",
                data(){
                    return{
                        arr:[1,2,3,4,5]
                    }
                }
            }
        }
    });

</script>
```

# 三十五、Vue的高阶使用

重点

* Vue框架当中组件传值方式
* Vue-CLI（脚手架使用：Vue框架提供的可以快速开发项目工具）
* 明星图集

## 35.1Vue框架中组件的通信

概述：在实际的工作当中，项目中一定会大量使用组件，组件和组件之间可以通信

Vue当中组件通信方式有三种：父子组件、子父组件、兄弟组件

### 35.1.1父组件给子组件传值

```vue
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="./js/vue.min.js"></script>
    <style>
        #app{
            width: 80%;
            height: 300px;
            background: red;
            border: 2px solid black;
            margin: 0 auto;
        }
        .cur{
            width: 400px;
            height: 200px;
            background: yellow;
        }
    </style>
</head>
<body>
    <!-- 模板 -->
    <div id="app">
        <h1>我是最大的跟组件---{{msg}},{{car}}</h1>
        <son class="cur" :msg="msg":car="car"></son>
    </div>
    <template id="son">
        <div>
            <h1>我是儿子组件~~~{{msg}},{{car}}</h1>
        </div>
    </template>
</body>
</html>
<script>
    //创建Vue实例
    var vm=new Vue({
        el:"#app",
        data:{
            msg:"我有一个亿",
            car:"奔驰"
        },components:{
            //局部组件
            son:{
                template:"#son",
                //组件当中的props，接受父组件传递数据
                props:["msg",'car']
            }
        }
    });
    //父组件给子组件传递数据，利用props
</script>
```

* 父组件可以通过v-bind（简写：），通过在子组件（标签）动态属性值的形式给子组件传递数值
* 子组件通过props【它的数值是一个数组】，接受父亲给的数据

### 35.1.2子组件给父组件传递数据

概述：在Vue框架当中，也可以实现子组件给父组件传递数据，利用的是自定义事件

```vue
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="./js/vue.min.js"></script>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        #app{
            width: 80%;
            height: 400px;
            background: skyblue;
            margin: 10px auto;
        }
        .cur{
            width: 400px;
            height: 200px;
            background: pink;
        }
    </style>
</head>
<body>
    <!-- 根组件的模板 -->
    <div id="app">
        <h1>我是王健林~~~{{liwu}}</h1>
        <wsc class="cur" @gift="show($event)"></wsc>
    </div>
    <!-- 子组件的模板 -->
    <template id="wsc">
        <div>
            <h1>我是王思聪---{{msg}}</h1>
            <button @click="send">单机我送礼物</button>
        </div>
    </template>
</body>
</html>
<script>
    var vm=new Vue({
        el:"#app",
        data:{
            liwu:''
        },
        methods:{
            show(liwu){
                this.liwu=liwu
            }
        },
        components:{
            //子组件
            wsc:{
                template:"#wsc",
                //组件的数据data，务必是一个函数，函数务必要有返回值
                data(){
                    return{
                        msg:"熊猫tv"
                    }
                },methods:{
                    //给父亲传递数据的方法
                    send(){
                        //触发自定义事件
                        this.$emit("gift",this.msg)
                    }
                }
            }
        }
    });
</script>
```

* 儿子组件需要通过$emit方法触发自定义事件：第一个参数自定义事件名字、第二个参数给父组件的数据
* 父组件接受子组件数据：在子组件的便牵上@自定义事件+父组件提供的函数即可

### 35.1.3兄弟组件传值

```vue
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- 引包 -->
    <script src="./js/vue.min.js"></script>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        #app{
            width: 80%;
            height: 300px;
            background: skyblue;
            border: 2px solid black;
            margin: 0 auto;
        }
        .son{
            width: 400px;
            height: 100px;
            background: pink;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <!-- 根组件的模板 -->
    <div id="app">
        <son class="son"></son>
        <son1 class="son"></son1>
    </div>
    <!-- 子组件的模板 -->
    <template id="son">
        <div>
            <h1>大儿子组件~~~{{msg}}</h1>
        </div>
    </template>
    <template id="son1">
        <div>
            <h1>小儿子组件---{{car}}</h1>
            <button @click="sendCar">单机我送奔驰</button>
        </div>
    </template>
</body>
</html>
<script>
    //前端工程师，叫做中央管道
    //就是将Vue实例作为原型对象属性值
    Vue.prototype.$bus=new Vue;
    //兄弟组件传递参数
    var vm=new Vue({
        el:"#app",
        data:{},
        components:{
            //第一个儿子组件
            son:{
                template:"#son",
                data(){
                    return{
                        msg:''
                    }
                },
                mounted(){
                    //哥哥组件接受兄弟的数据
                    // this.$bus.$on("sendCar",(car)=>{
                    //     this.msg=car;
                    // })
                    this.$bus.$on("sendCar",($event)=>{
                        this.msg=$event;
                    })
                }
            },
            son1:{
                template:"#son1",
                data(){
                    return{
                        car:"奔驰"
                    }
                },methods:{
                    //小儿子给哥哥送奔驰
                    sendCar(){
                        this.$bus.$emit("sendCar",this.car)
                    }
                }
            }
        }
    });
</script>
```

## 35.2Vue-CLI使用

概述：在公司创建Vue项目的时候一般都是脚手架【它是Vue框架提供的一个工具】，可以快速生成Vue项目

很多常用Vue项目依赖自动安装

1. 安装Vue-CLI脚手架工具(全局安装脚手架工具)

   npm install -g  vue-cli

   解释：-g（global）代表这个工具可以在cmd命令行任意目录下使用

因安装不成功，略过

























































