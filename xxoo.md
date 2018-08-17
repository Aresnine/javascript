## NaN

* 任何一个数值跟NaN进行运算得到的值都是NaN
* 任何数跟NaN进行比较\(除了 != 和 !==\)的时候返回的结果都是false
* 检测一个值是否为NaN的时候使用isNaN

```js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>NaN</title>
</head>
<body>
    <script type="text/javascript">
    /*
        任何值和NaN计算返回值都为NaN
    */
    var res=100+NaN;
    var res=100-NaN;
    var res=100*NaN;
    var res=100/NaN;
    var res=100%NaN;
    console.log(res);
    /*
        任何值和NaN进行比较运算返回的结果都为false除了!= 和 !==

        NaN和任何值都不相等，包括他本身
    */
    var res=1>NaN;
    var res=1==NaN;
    var res=1<NaN;
    var res=NaN==NaN;
    var res=1 != NaN;
    var res=1 !== NaN;
    var res=NaN !=NaN;
    console.log(res);
    /*
        检测一个值是否为NaN使用isNaN
    */
    var res=1;
    var res=NaN;
    console.log(isNaN(res));
    </script>
</body>
</html>
```



