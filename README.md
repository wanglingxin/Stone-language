<p align = "center">
  <a href = "https://github.com/mathors/Stone-language">
    <img height="60%" width = "70%" src = "https://s1.ax1x.com/2018/12/15/FaQuNt.png">
  </a>
</p>
<p align = "center">
  <a href = "https://github.com/mathors/Stone-language">
    <img src="https://img.shields.io/badge/language-Java-brightgreen.svg">
  </a>
  <a href = "https://github.com/mathors/Stone-language">
    <img src = "https://img.shields.io/badge/Compiler-Eclipse-blue.svg">
  </a>
  <a href = "https://wmathor.com/" target = "_blank">
    <img src = "https://img.shields.io/badge/Blog-wmathor-orange.svg">
  </a>
</p>
  
或许你也刚学完编译原理，或者没有，但是你想自制一个属于自己的编程语言，那么看这个项目就对了，我将用14天设计一个简单的脚本语言

## 目录说明 
### 第1部分 基础篇
- [First Day](https://github.com/mathors/Stone-language/tree/master/First%20Day)

机器语言、汇编语言简介，语言处理器概述
- [Second Day](https://github.com/mathors/Stone-language/tree/master/Second%20Day)

设计Stone语言，决定Stone语言需要具备哪些语法功能
- [Third Day](https://github.com/mathors/Stone-language/tree/master/Third%20Day)

设计词法分析器，介绍通过正则表达式实现词法分析的方法
- [Fourth Day](https://github.com/mathors/Stone-language/tree/master/Fourth%20Day)

讲解抽象语法树，并通过BNF表达Stone语言的语法
- [Fifth Day](https://github.com/mathors/Stone-language/tree/master/Fifth%20Day)

利用非常简单的解析器组合子库创建语法解释器
- [Sixth Day](https://github.com/mathors/Stone-language/tree/master/Sixth%20Day)

设计一种极为基本的解释器。解释器将能够实际执行Stone语言写成的程序
- [Seventh Day](https://github.com/mathors/Stone-language/tree/master/Seventh%20Day)

增强解释器的功能，使它能够执行程序中的函数，并且支持闭包语法
- [Eighth Day](https://github.com/mathors/Stone-language/tree/master/Eighth%20Day)

为解释器增加static方法的调用支持，使Stone语言能像Java语言那样调用静态方法
- [Ninth Day](https://github.com/mathors/Stone-language/tree/master/Ninth%20Day)

为Stone语言新增类与对象的语法
- [Tenth Day](https://github.com/mathors/Stone-language/tree/master/Tenth%20Day)

为Stone语言增加数组功能
### 第2部分 性能优化
- [Eleventh Day](https://github.com/mathors/Stone-language/tree/master/Eleventh%20Day)

程序不应在访问变量时每次都搜索变量名，而应首先搜索事先分配好的编号，提高访问性能
- [Twelfth Day](https://github.com/mathors/Stone-language/tree/master/Twelfth%20Day)

同样地，程序在调用对象的方法或引用其中的字段时，也不应直接搜索其名称，而应搜索编号。此外，还为Stone语言的解释器增加内联缓存，进一步优化性能
- [Thirteenth Day](https://github.com/mathors/Stone-language/tree/master/Thirteenth%20Day)

Stone语言的解释器也采用了中间代码解释（或虚拟机）的机制。Stone语言写成的程序将首先被转换为中间代码（二进制代码），解释器执行的其实是转换后的中间代码
- [Fourteenth Day](https://github.com/mathors/Stone-language/tree/master/Fourteenth%20Day)

最后，为了提高性能，Stone语言有必要支持静态数据类型，并根据数据类型的不同进一步优化性能。在执行具有静态数据类型的Stone语言程序时，编译器可以先将其转换为Java二进制代码，再直接由Java虚拟机执行该程序。同时还会为编译器增加类型检查功能，在执行程序前检查是否存在类型错误，并同时提供类型预判功能。这样一来，即使程序没有显式地声明数据类型，Stone语言的解释器也能推测并指定合适的类型
### 第3部分 进阶篇（自习）
- [Fifteenth Day](https://github.com/mathors/Stone-language/tree/master/Fifteenth%20Day)

Stone语言的词法分析器由Java的正则表达式库实现，自此将不再使用这种方式，手工设计词法分析器。具体来讲，这里将介绍给予正则表达式的字符串匹配程序设计
- [Sixteenth Day](https://github.com/mathors/Stone-language/tree/master/Sixteenth%20Day)

之前采用了解析器组合子库这一简单的库来实现语法分析器，自此将介绍一些语法分析的基本算法，并以LL语法分析为基础，手工设计一个简单的语法分析器
- [Seventeenth Day](https://github.com/mathors/Stone-language/tree/master/Seventh%20Day)

简单介绍解析器组合子库的内部结构，并分析该库的源代码
- [Eighteenth Day](https://github.com/mathors/Stone-language/tree/master/Eighteenth%20Day)

Stone语言的解释器采用了GluonJ系统来实现，该系统允许Java语言执行类似于Ruby语言中open class的功能。这里将总结使用GluonJ时的一些琐碎的注意事项
- [Nineteenth Day](https://github.com/mathors/Stone-language/tree/master/Nineteenth%20Day)

介绍使用设计模式来实现抽象语法树的优缺点，并与使用GluonJ的方式做比较

### 最终效果
暂无

### TODO
暂无
