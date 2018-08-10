## 1、使用方式

* script标签
* 外部引入
* 元素的事件属性
* a标签的href属性

> 注意：在使用外部引入的时候，在有src的script标签内不能写js代码

```js
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>js的使用方式---四种</title>
</head>
<body>
	<!--标签元素-->
	<script type="text/javascript">
		// alert("i love you!!!");
	</script>
	<!--导入外部的js文件-->
	<script src="./1.js" type="text/javascript">
		alert("测试该处代码是否可以运行");//此处的js代码不可运行
	</script>
	<!--通过元素的事件-->
	<!--
		on     when 当什么时候
		click       点击
	-->
	<button onclick="alert('小样继续！');alert('是男人你就再点');alert('精彩马上呈现');alert('再点我就给你看大宝的果照');alert('对不起，我不跟重口味的人做朋友');">点我</button>

	<!--a链接-->
	<a href="javascript:alert('i can see you');">百度一下</a>

	<!--
		js 在html中的使用方式公有4种
			1、a链接 href属性
			2、元素的事件属性（用-测试)
			3、<script>js代码</script> 平时我经常用 些项目不建议使用
			4、<script src="js文件路径"></script> 项目
				易维护、易扩展、可缓存
	-->

</body>
</html>
```

## 2、script元素

script定义了下列6个属性

```
async：可选。表示应该立即下载脚本，但不应妨碍页面中的其他操作，比如下载其他资源或等待加载其他脚本。只对外部脚本有效

charset：可选。表示通过src属性指定的代码的字符集。由于大多数浏览器都会忽略这个值，因此这个属性也很少有人会用

defer：可选。表示脚本可以延迟到文档被解析和显示之后再执行

language：已废弃。原指编写代码使用的脚本语言

src：可选。表示包含要执行代码的外部文件

type：可选。可以看成是language的替代属性；表示编写代码使用的脚本语言的类型（也称为MIME类型）。虽然text/javascript和text/ecmascript
都已经不推荐使用，但是人们还是经常使用text/javascript.实际上，服务器在传送javascript问件事使用的MIME类型通常是application/x-javascript
但在type中设置这个值缺可能导致脚本被忽略。
```



