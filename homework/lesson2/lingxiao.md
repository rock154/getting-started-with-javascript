# 编程中为什么会有丰富化的数据格式-JavaScript第二次作业
## 作业
【作业要求】
1. 熟读getting-started-with-javascript/study/lesson2/smaple_code.js代码。用node环境和浏览器环境运行一下代码（注意：浏览器运行请使用my_personal_info_page.html）
2. 写一遍课程总结，题目为：编程中为什么会有丰富化的数据格式？
3. 如果有问题，在总结中把你的问题罗列出来，我会做解答。
  【附加作业要求】
4. 在github上部署自己的静态网页，把网页地址放在总结文档里。
  【提交方式】
5. 请向getting-started-with-javascript项目发起pull request。
  https://github.com/xugy0926/getting-started-with-javascript

## 答案
1. **Demo代码运行结果**

|                Node环境运行结果                |                浏览器环境运行结果                 |
| :--------------------------------------: | :--------------------------------------: |
| ![Node环境运行结果](https://github.com/LydiaLing/MyPostImage/blob/master/Js_Homework/Lesson2/Node%E7%8E%AF%E5%A2%83%E8%BF%90%E8%A1%8C%E7%BB%93%E6%9E%9C.PNG?raw=true) | ![浏览器环境运行结果](https://github.com/LydiaLing/MyPostImage/blob/master/Js_Homework/Lesson2/%E6%B5%8F%E8%A7%88%E5%99%A8%E7%8E%AF%E5%A2%83%E8%BF%90%E8%A1%8C%E7%BB%93%E6%9E%9C.PNG?raw=true) |

2. **编程中为什么会有丰富化的数据格式？**

为了描述这个世界，人类发明了计算机，而我们现在讨论的数据格式，也即是**数据类型**，其实更直接的是计算机里的数据类型。
> 数据类型(Data type)是用来约束数据的解释。在编程语言中，常见的数据类型包括原始类型（如：整数、浮点数或字元）、多元组、记录单元、代数数据类型、抽象数据类型、参考类型、类以及函式类型。数据类型描述了数值的表示法、解释和结构，并以算法操作，或是物件在内存中的储存区，或者其它储存装置。-- [wiki百科](https://zh.wikipedia.org/wiki/%E8%B3%87%E6%96%99%E9%A1%9E%E5%9E%8B)

大家知道，目前我们用的均是冯氏体系架构的计算机，其核心思想是存储程序，执行程序。而程序本身，也只是一种数据代码。即，数据从外在来看，可能就纯的数据本身，也可能是代表一段执行代码，也可能代表一定格式的程序或是文件。现代计算机，由于硬件设计上的限制，均采用的是二进制体系。那么在二进制的编码下，就产生了各种各样的数据类型。

尽管有各种各样的数据类型，但人们总是在想方设法的去追求一个目标，即，用尽可能少的空间，存储尽可能多的信息；就尽可能少的运算，呈现尽可能多的信息变换。而通过数据类型限定数据的范围，相当于加了范围约束，这种约束有如下好处：1）使用优化的存储格式，比如INT类型是四字节，存储格式为32位二进制字符，而varchar表示 “9999999999”则需要10字节（甚至更多，取决于DBMS类型）；2）在对该类约束数据实现某些操作就不再会报错，比如日期类型 ‘2017-3-28 00：00：00’就可以无障碍的通过内置函数转换为任何等价形式，比如"28/3/2017" 或者"2017年3月28日 0点"；3）通过数据类型约束可以减少非正常数据的存入，比如INT类型的列不应该存入字符串。一句话概括，有了数据类型,才能更好的分配管理内存,节省不必要的开支，可以处理一些非法输入。[^1]

在实际编程中，我们知道，任何编程语言（除了汇编，汇编只规定数据的字长），都会有自己的数据类型，而对一个程序员来讲，写代码的第一件事情就是定义数据类型。在数据类型背后，隐藏的是编译器或者解释器对数据处理方式的定义。知道了这个以后，我们在定义数据类型的时候，就应该知道，我们定义的这种数据类型，可以进行哪些操作，这些操作的规则是什么，这样我们才算真正掌握了这个数据类型。[^2]

3. 木有...

4. **我的静态网页：** https://lydialing.github.io/MyStaticWebpage/



[^1]: https://www.zhihu.com/question/54104439

[^2]: http://5412097.blog.51cto.com/5402097/1626125