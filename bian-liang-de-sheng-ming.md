## 变量的声明

```js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>js的变量声明</title>
</head>
<body>
    <script type="text/javascript">
    /*
        变量声明
            必须以字母、下划线、$开头
            变量名字可以由$,_，字母和数字组成

        js的数据输出方式
            alert() 跳出消息
            console.log() console 一个对象 . 对象操作符 log 表示console对象的方法

        ;代表分隔符


        js的变量严格区分大小写
    */
        var a=1;
        // alert(a);
        var $a=2;
        var _a=4;
        // var 1a=3;

        bbb=333;

        console.log(a);
        console.log($a);
        console.log(_a);
        // console.log(1a);
        console.log(bbb);
        // console.log(A);
    </script>
</body>
</html>
```

## 变量的类型

```js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>js的变量类型</title>
</head>
<body>
    <!--浏览器没有开启javascript时候显示的提示信息-->
    <noscript>
        你的浏览器没有开启javascript
    </noscript>

    <script type="text/javascript">

    /*
        typeof 获得变量的数据类型 
        注意：typeof后面可以使用括号也可以忽略，原因typeof非系统函数属于操作符
    */
    /*
        布尔类型 boolean 值 2个 true false

        注意：true和false必须小写
    */
    var a=true;
    var b=false;

    // console.log(typeof a);
    // console.log(typeof(b));

    // var a=TRUE;
    // var a=True;
    // console.log(typeof a);

    /*
        字符串
            单双引号都可以，但是单双引号没有区别
    */
    var str='aaa';
    // console.log(typeof str);
    var str1='bbbstr';
    var str2="cccstr";
    // console.log(typeof str1);
    // console.log(typeof str2);
    // console.log(str1);
    // console.log(str2);
    /*
        数字        
    */
    var a=1;
    // console.log(typeof a);
    var b=1.1;
    // console.log(typeof b);
    var c=NaN;//not a  number
    // console.log(typeof c);
    // console.log(c);

    /*
        对象
    */
    var a=new Object();
    var a=new Object;//可以
    var a=new Array();
    var a=null;
    // var a={};

    /*
        函数

        注意：
            函数声明方式有两种
            1、a=function(){}
            2、function a(){}

        区别：
            第二种方式声明的函数在脚本解析的时候会预先加载处理,
            但是第一种方式表示变量的声明，只有运行的时候才回进行加载
    */
    // var a=function (){
    //     alert('i kiss you');
    // };

    // function a(){
    //     alert('i miss you');
    // }
    // console.log(typeof a);
    // a();
    // console.log(a);
    // xxoo();
    function xxoo(){
        console.log("this is function xxoo");
    }
    // xxoo();
    // demo();
    var demo=function(){
        console.log("this is function demo");
    }

    // demo();

    // console.log(typeof Object);
    // var aa=new xxoo();
    // console.log(typeof aa);

    /*
        undefined
    */
    console.log(typeof houjie);

    </script>

</body>
</html>
```

```js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>NaN,null,undefined</title>
</head>
<body>
    <p>
        NaN表示不是一个数字，类型为number
    </p>
    <p>
        null 表示空指针，类型为object
    </p>
    <p>
        undefined 表示不存在的变量， 类型为undefined （和php的null相同）
    </p>
    <p>
        三者之间有联系，也有区别
        联系：都表示一个空值
        区别：
            NaN表示一个数字的空值
            null区别于php的null，表示一个空对象的指针
            undefined 表示一个不存在的变量，一般不会进行显性赋值 
                var a=undefined 显性赋值 一点意义都没有
    </p>
</body>
</html>
```



