# Javascript简介

1、javascript的组成

```
核心 ECMASript
文档对象模型 DOM
浏览器对象  BOM
```

2、ECMA-262标准没有参照Web浏览器，它规定了这门语言的组成部分：

```
语法
类型
语句
关键字
保留字
操作符
对象
```

3、文档对象模型（DOM）

```
文档对象模型(DOM Document Object Model)是针对XML但经过扩展用于HTML的应用程序编程接口(API Application Programming Interface).
DOM把整个页面映射为一个多层节点结构。HTML或XML页面中的每个组成部分都是某种类型的阶段，这些节点又包含着不同类型的数据。
```

4、为什么使用BOM

```
通过DOM的API，开发人员可以在无需加载网页，就可以修改其外观和内容。
```

5、DOM的发展

```
DOM1于1998年10月成为W3C推荐的标准。
DOM1级由两个模块组成：DOM核心（DOM Core）和DOM HTML。
DOM核心规定的是如何映射基于XML的文档结构，以便简化对文档中任意部分的访问和操作。
DOM HTML则在DOM核心的基础上加以扩展，添加了针对HTML的对象和方法。

DOM1级的目标主要是映射文档的结构。

DOM2在DOM1的基础上又扩充了鼠标和用户界面事件、安慰、遍历（迭代DOM文档的方法）等细分模块，而且通过对象接口增加了对CSS的支持。
DOM1级中的DOM核心模块也经过扩展开始支持XML命名空间
```

6、DOM2级引入下列模块，也给出了众多新类型和新街口的定义

```
DOM视图 (DOM Views):定义了跟踪不同的文档（例如，应用CSS之前和之后的文档）视图接口

DOM事件 （DOM Events）：定义了事件和事件处理接口

DOM样式 （DOM Style）：定义了基于CSS为元素应用样式的接口

DOM遍历和范围 （DOM Traversal and Range）：定义了遍历和操作文档树的接口。
```

7、DOM3级则进一步扩展了DOM，引入了以统一方式加载和保存文档的方法---在DOM文档加载和保存（DOM Load和Save）模块中定义；新增了验证文档的方法---在DOM验证（DOM Validation）模块中定义。

8、浏览器对象模型\(BOM\)

```
BOM (Browser Object Model)开发人员可以使用BOM来控制浏览器显示的页面意外的部分。
BOM真正与众不同的地方（也是经常会导致问题的地方，还是它作为JavaScript实现的一部分但却没有相关的标准）

从根本上讲，BOM只处理浏览器窗口和框架；但人们习惯上也把所有针对浏览器的JavaScript扩展算作BOM的一部分。下面就是一些这样的扩展

    1、弹出新浏览器窗口后的功能
    2、移动、缩放和关闭浏览器窗口的功能
    3、提供浏览器详细信息的navigator对象
    4、提供浏览器所加载页面的详细信息的location对象
    5、对cookie的支持
    6、像XMLHttpRequest和IE的ActiveXObject这样的自定义对象
```

9、JavaScript是一种专为与网页交互而设计的脚本语言，由下列三个不同的部分组成

```
ECMAScript，由ECMA-262定义，提供核心语言功能
文档对象模型（DOM），提供访问和操作网页内容的方法和接口
浏览器对象模型（BOM），提供与浏览器交互的方法和接口
```



