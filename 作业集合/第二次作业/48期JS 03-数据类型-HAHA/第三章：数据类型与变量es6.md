# 第三章：          数据类型与变量es6



### 一：定义变量 ： let goudan = document.getElmentById("")  var dachui = document.getElmentById("")

​	ECMA script   es      es5持续很久的版本，功能比较完善， ES2015 --- Es6	ES2016 ---Es7

#### Es5 : var  function Es6: let  const function class 以后使用Es6开发代码  不用担心兼容性问题 有一个叫Babel的网站可以用打包工具，可以将Es6代码转换为兼容所以浏览器的Es5代码。		

####  定义变量名不能使用：关键词，保留词，js里有意义的变量名，组成名字的字符最好是 数字 字母 下划线 $ 四种。定义变量要见名知意  ， 用驼峰命名法。



### 数据类型：

1.  **number**  数字

2. **string**      字符串 es6 新的字符串定义方式   ``;

3. **bool**   布尔值

4. **null**   空

5. **undefined**  未定义的    const不允许初始不赋值

6. **object**  对象    [ ]  数组，可以在数组里面存储任何类型的数据包括本身也可以是变量名，用下标取值从0开始，二维数组 三维数组 四维 五维数组 --- 等等，{ }对象 也叫  json  是以键值对的形式出现，一般是以后和后台传输数据来使用 。严格来说json是个字符串，对象它和数组不同的地方是它取值直接 .  点 (的) 什么什么的 Name  ，age，并且对象的表现数据信息更加丰富，明确一些对象里可以存数组同样数组里也能存对象。

7. **Es6新增数据类型  symbol**  定义的这个值 和以前的值完全不同。

   ****

