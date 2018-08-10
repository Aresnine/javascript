## 1、使用方式

* script标签
* 外部引入
* 元素的事件属性
* a标签的href属性

> 注意：在使用外部引入的时候，在有src的script标签内不能写js代码

1、script元素

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



