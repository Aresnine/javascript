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



