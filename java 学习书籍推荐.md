# 工作十年，分享看过的优质 Java 书籍

> [原文](http://www.itwanger.com/java/2019/12/13/java-book.html)


## Table of contents
- 第一本《Head First Java》
- 第二本《Java 核心技术卷一》
- 第三本《Java 编程思想》
- 第四本《Effective Java》
- 第五本《Java网络编程》
- 第六本《Java 并发编程实战》
- 第七本《深入理解Java虚拟机》
- 第八本《Java性能权威指南》
- 第九本《代码整洁之道》
- 第十本《设计模式之禅》
- 第十一本《Java开发手册》
- 第十二本《重构——改善既有的代码设计》
- 第十三本《算法》



## New words



## Content
不知不觉, 我已经接触 Java 11 年了——从 2008 年北京奥运会那年开始，到现在；未来还会更久。这期间我读了不少 Java 方面的书籍，纸质版的少说有三十来本吧，更何况还有不少的电子书。万事都有好坏，书也一样。有的是精神粮食，有的纯粹是浪费时间。这里就分享一些我精挑细选后的优质书籍，希望能帮大家少走点弯路。

<img src="./images-java-study-notes/java-book-1.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

在读这些书的过程中，我还写下了不少博文，这些文章也帮助过不少年轻人，他们经常发私信感谢我，这让我感觉自己的分享很有意义。

### 第一本《[Head First Java](http://www.itwanger.com/java/2019/12/04/java-head-first-advise.html)》

<img src="./images-java-study-notes/java-book-2.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

在我遇到《Head First Java》之前，如果你要我推荐 Java 技术书，我会毫不犹豫地推荐《[Java 编程思想](http://www.itwanger.com/java/2019/10/30/think-java-book-read-jianyi.html)》和《[Java 核心技术卷](http://www.itwanger.com/java/2019/11/14/java-core-advise.html)》，因为大家都说好嘛，我只能“同流合污”了（强颜欢笑）；但换成是现在的话，我会优先推荐《Head First Java》。

尽管《Head First Java》也非常的厚，至少比我的脸皮后，但趣味性就要甩前面两本好几条街了。这年头，大家都没时间读枯燥的技术书，尤其是厚的。上一张图大家感受一下《Head First Java》的调皮吧。

<img src="./images-java-study-notes/java-book-3.png"
     style="border-radius:4px; width:60%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

就冲着这张图，我觉得《[Head First Java](http://www.itwanger.com/java/2019/12/04/java-head-first-advise.html)》的作者就足够的大胆。作者挑选的图片可以说张张经典，真正实现了“图文并茂”的需求，搞得你感觉有点不好意思，仿佛不是在读一本 Java 技术书，而是在读一本《知音》。

不止是图片，还有游戏、拼图、解谜题以及意想不到的内容。真的是一点都不“正经”，正因为如此，阅读起来才感觉兴趣盎然。

第一章主要介绍了 Java 的工作原理、发展简史、程序结构。

第二章主要介绍了 Java 的面向对象，包括继承、覆盖等内容。

[什么是面向对象编程（OOP）？](http://www.itwanger.com/java/2019/11/01/oop.html)

第三章主要介绍了 Java 的变量。关键点：引用变量存储的是对象的地址（储存方式）、数组也是对象。

[为什么要将局部变量的作用域最小化？](http://www.itwanger.com/java/2019/12/04/java-variable-zuixiaohua.html)

第四章主要介绍了 Java 的方法。关键点：实参和形参、值传递和引用传递、== 和 equals()。

[Java到底是值传递还是引用传递？](http://www.itwanger.com/java/2019/11/26/java-yinyong-value.html)

[如何比较 Java 的字符串？](http://www.itwanger.com/java/2019/12/03/java-string-compare.html)

第五章主要介绍了程序设计与实现的步骤。

第六章主要介绍了 Java 的 API。关键点：ArrayList。

第七章主要介绍了继承和多态。关键点：覆盖和重载。

第八章主要介绍了接口和抽象类。关键点：超类 Object。

[再谈 Java 的继承和超类 Object](http://www.itwanger.com/java/2019/11/14/java-extends.html)

第九章主要介绍了构造器与垃圾收集器。关键点：对象存储在堆中，对象引用在栈中；当对象失去最后一个引用变量时，它会被回收。

第十章主要介绍了静态类、静态方法、静态变量。关键点：final、常量、数字格式化、日期表示法。

第十一章主要介绍了异常处理。

第十二章和第十三章，主要介绍了 GUI 和 Swing。关键点：事件处理机制。

第十四章主要介绍了序列化和文件输入/输出。关键点：Serializable接口。

[Java Serializable：明明就一个空的接口嘛](http://www.itwanger.com/java/2019/11/14/java-serializable.html)

第十五章主要介绍了网络 Socket 和多线程。

[Java Socket：飞鸽传书的网络套接字](http://www.itwanger.com/java/2019/12/04/java-socket.html)

[Java 网络编程：必知必会的 URL 和 URLConnection](http://www.itwanger.com/java/2019/08/27/java-url-urlconnection.html)

第十六章主要介绍了集合和泛型。

第十七章主要介绍了程序的打包和发布。

第十八章主要介绍了远程服务调用。

### 第二本《[Java 核心技术卷一](http://www.itwanger.com/java/2019/11/14/java-core-advise.html)》

《Java核心技术卷一》是唯一可以和《[Java编程思想](http://www.itwanger.com/java/2019/10/30/think-java-book-read-jianyi.html)》媲美的一本 Java 入门书。单从技术的角度来看，前者更好一些。但上升到思想层面嘛，自然后者更好，两者的偏重点不同。

思想不会变，所以《Java编程思想》还停留在第 4 版（2007 年）；而技术是要更新迭代的，所以《Java核心技术卷一》来到了第十版（2016 年）。

我们来看一下《Java核心技术卷一》第十版的大纲。

<img src="./images-java-study-notes/java-book-4.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

前九章：包括 “Java 程序设计概述”、“Java 程序设计环境”、“Java 的基本程序设计结构”、“对象与类”、“继承”、“接口”、“lambda 表达式与内部类”、“异常”、“断言和日志”、“泛型程序设计”、“集合”。这九章讲述的是 Java 基础知识点，是 Java 程序员必须要掌握的内容，所以必看。

第十到第十二章：讲的是 AWT 和 Swing，个人感觉这部分内容属于[不需要再学的 Java 知识点](http://www.itwanger.com/java/2019/10/28/java-no-learn.html)。当然了，窗口编程涉及到的“事件驱动-监听-方法回调”的机制蛮重要的，需要掌握，但和 AWT 和 Swing 的关联度不大。就好像，我们取钱直接去招商银行，没必要把招商银行的钱转到工商银行再取出来。

第十三章：讲的是应用部署和 Applet，显然 Applet 也没必要学了。出版社没有把这部分内容删掉，纯粹是为了让这本书变得更笨重（定价就高了）。

第十四章：并发编程。这也是 Java 学习过程中最难的一块之一，另外一难是 Java 虚拟机。但这是初级程序员迈向高手的必经之路。

整体上来讲，《Java核心技术卷一》非常值得一读，广度和深度都恰到好处。强烈推荐。

我知道，有些同学因为工作时间的原因，一直没有时间读书。像《Java核心技术卷一》这样厚得像特朗普的脸皮一样的书，更是没有时间读了。不过，不要担心，二哥替大家解决了这个烦恼，我用了一个月的时间把这本书完整地读了一遍，并写了 9 篇高质量且通俗易懂的文章，供大家作为参考。

先来通过思维导图看一下这 9 篇 Java 核心技术博文涉及到的内容。

<img src="./images-java-study-notes/java-book-5.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

下面是这 9 篇 Java 核心技术博文对应的链接。

[Java面试官：兄弟，你确定double精度比float低吗？](http://www.itwanger.com/java/2019/11/14/java-double-float.html)

[请用面向对象的思想，谈一谈这次面试的过程](http://www.itwanger.com/java/2019/11/14/java-oo-po.html)

[再谈 Java 的继承和超类 Object](http://www.itwanger.com/java/2019/11/14/java-extends.html)

[Java：接口和抽象类，傻傻分不清楚？](http://www.itwanger.com/java/2019/11/14/java-interface-abstract.html)

[Java生成二维码分享海报](http://www.itwanger.com/java/2019/11/14/java-qrcode-poster.html)

[Java：优雅地处理异常真是一门学问啊！](http://www.itwanger.com/java/2019/11/14/java-exception.html)

[教妹学 Java：晦涩难懂的泛型](http://www.itwanger.com/java/2019/11/14/java-fanxing.html)

[教妹学Java：大有可为的集合](http://www.itwanger.com/java/2019/11/14/java-jihe.html)

[教妹学 Java：难以驾驭的多线程](http://www.itwanger.com/java/2019/11/14/java-duoxiancheng.html)

### 第三本《[Java 编程思想](http://www.itwanger.com/java/2019/10/30/think-java-book-read-jianyi.html)》

<img src="./images-java-study-notes/java-book-6.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

这本书在豆瓣的评分高达 9.1 分，但我总觉得有点虚高。

记得刚上大学那会，就在某宝上买了一本影印版的《Java 编程思想》，但由于初学 Java，对编程极度缺乏信心，导致看这本书有一种看天书的感觉。后来，去苏州参加工作的时候把它作为最宝贵的纪念品带了过去。

2014 年回洛阳的时候把它送给了一位关系还不错的同事，权当是分别的礼物吧。2016 年的时候，我又重新买了一本希望自己能够夯实一下基础。但事与愿违，它被我束之高阁了，读起来无比的枯燥。2018 年的时候，我重新捧起它读了一遍，总觉得有一种莫名的负罪感。

《Java 编程思想》是个大部头，足足 880 页，文字更是密密麻麻。我不建议大家一个字一个字的读，知晓其中的精华就可以了。如果你觉得这本书读起来很痛苦，不妨来读一读我加工润色后分享博文，足足 25 篇，每一篇都很精彩。

先来通过思维导图看一下这 25 篇 Java 博文涉及到的知识点。

<img src="./images-java-study-notes/java-book-7.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

下面是这 25 篇 Java 技术博文对应的链接。

[Java 的核心目的和并发编程](http://www.itwanger.com/java/2019/10/30/think-java-book-read-1.html)

[Java：程序不过是几行代码的集合](http://www.itwanger.com/java/2019/11/01/java-mian-class.html)

[什么是面向对象编程（OOP）？](http://www.itwanger.com/java/2019/11/01/oop.html)

[如何理解 Java 中的继承？](http://www.itwanger.com/java/2019/11/01/java-extends.html)

[吃人的那些 Java 名词：对象、引用、堆、栈](http://www.itwanger.com/java/2019/11/05/java-eat-human-words.html)

[Java 的操作符——“=”号](http://www.itwanger.com/java/2019/11/06/java-caozuofu-denghao.html)

[害死人的自动递增，不偿命的自动递减](http://www.itwanger.com/java/2019/11/06/java-caozuofu-++.html)

[Java 流程控制语句](http://www.itwanger.com/java/2019/11/06/java-liuchengkongzhi.html)

[Java是通过什么机制来确保对象初始化呢？](http://www.itwanger.com/java/2019/11/06/java-chushihua.html)

[Java 访问权限控制：public、private、protected](http://www.itwanger.com/java/2019/11/07/java-public-private-protected.html)

[Java代码复用的三种常用方式：继承、组合和代理](http://www.itwanger.com/java/2019/11/06/java-code-fuyong.html)

[Java：多态乃幸福本源](http://www.itwanger.com/java/2019/11/06/java-duotai.html)

[Java 抽象类和接口，看这一篇就够了](http://www.itwanger.com/java/2019/11/06/java-abstract-interface.html)

[Java内部类](http://www.itwanger.com/java/2019/11/07/java-inner-class.html)

[Java String，看这篇就够了](http://www.itwanger.com/java/2019/11/08/java-string.html)

[Java 数组，看这一篇就够了](http://www.itwanger.com/java/2019/11/08/java-array.html)

[Java 集合类入门篇](http://www.itwanger.com/java/2019/11/08/java-jihe-rumen.html)

[HashMap，难的不在Map，而在Hash](http://www.itwanger.com/java/2019/11/08/java-hashmap.html)

[Java泛型的重要目的：别让猫别站在狗队里](http://www.itwanger.com/java/2019/11/08/java-fanxing.html)

[Java异常处理：给程序罩一层保险](http://www.itwanger.com/java/2019/11/08/java-exception.html)

[如果有人再问你 Java 的反射，把这篇文章扔给他](http://www.itwanger.com/java/2019/11/08/java-fanshe.html)

[Java枚举：小小enum，优雅而干净](http://www.itwanger.com/java/2019/11/09/java-enum.html)

[Java注解（Annotation）：请不要小看我！](http://www.itwanger.com/java/2019/11/08/java-annotation.html)

[Java I/O 入门篇](http://www.itwanger.com/java/2019/11/09/java-io.html)

[Java：并发不易，先学会用](http://www.itwanger.com/java/2019/11/09/java-bingfa.html)

《Java编程思想》无疑一直都会被大力推荐，可是第四版的出版时间竟然早在 2007 年，全书大部分的代码是基于 JDK 1.5 完成的。如今什么年代了？

告诉你一个好消息，《Java编程思想》的作者 Bruce Eckel 在 2017 年的时候发布了第五版，没想到吧？为什么在网上都看不到这本书的消息呢？因为改名了，而且只有电子版。

<img src="./images-java-study-notes/java-book-8.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

这本书的所有源代码已经开源在 GitHub，传送门：

https://github.com/BruceEckel/OnJava8-Examples

如果英语水平像我一样菜，看英文版比较费劲，可以在 GitHub 上查看大婶们的译本传送门：

https://github.com/LingCoder/OnJava8

如果英语水平还不错，可以自行购买电子版的《On Java 8》，虽然比较贵。

### 第四本《[Effective Java](http://www.itwanger.com/java/2019/12/06/java-effective-advise.html)》

《Effective Java》除了翻译让众多 Java 程序员诟病之外，再没有任何缺点了（有读者戏称：“这本书为翻译们作出了杰出的表率”）。其目标是帮助 Java 程序员更加有效地使用 Java 编程语言及其基本类库，主要涉及到 `java.lang`、`java.util`、 `java.io` 包下面的类。

<img src="./images-java-study-notes/java-book-9.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

《Effective Java》第三版一共包含了 90 条极具实用价值的经验规则，每条规则都值得 Java 程序员在实战中去参照。这本书不需要按部就班地从头到尾读，可以随意挑选任意小节进行阅读，因为每条规则相对都是独立的，尽管它们之间会交叉引用，但并不妨碍我们随心所欲地阅读。

作者 Josh Bloch 非常的牛逼，曾是 Google 的首席 Java 架构师，《Java开发者杂志》将他列为世界上最顶尖的四十名软件人物之一。Java 之父詹姆斯·高斯林对《Effective Java》的评价也非常的高。

我这里整理了一份第三版的中文在线翻译文档，大家可以参照一下。

- [01. 考虑使用静态工厂方法替代构造方法.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/01. 考虑使用静态工厂方法替代构造方法.md)
- [02. 当构造方法参数过多时使用builder模式.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/02. 当构造方法参数过多时使用builder模式.md)
- [03. 使用私有构造方法或枚类实现Singleton属性.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/03. 使用私有构造方法或枚类实现Singleton属性.md)
- [04. 使用私有构造方法执行非实例化.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/04. 使用私有构造方法执行非实例化.md)
- [05. 使用依赖注入取代硬连接资源(hardwiring resources).md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/05. 使用依赖注入取代硬连接资源(hardwiring resources).md)
- [06. 避免创建不必要的对象.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/06. 避免创建不必要的对象.md)
- [07. 消除过期的对象引用.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/07. 消除过期的对象引用.md)
- [08. 避免使用Finalizer和Cleaner机制.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/08. 避免使用Finalizer和Cleaner机制.md)
- [09. 使用try-with-resources语句替代try-finally语句.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/09. 使用try-with-resources语句替代try-finally语句.md)
- [10. 重写equals方法时遵守通用约定.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/10. 重写equals方法时遵守通用约定.md)
- [11. 重写equals方法时同时也要重写hashcode方法.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/11. 重写equals方法时同时也要重写hashcode方法.md)
- [12. 始终重写 toString 方法.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/12. 始终重写 toString 方法.md)
- [13. 谨慎地重写 clone 方法.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/13. 谨慎地重写 clone 方法.md)
- [14. 考虑实现Comparable接口.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/14. 考虑实现Comparable接口.md)
- [15. 使类和成员的可访问性最小化.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/15. 使类和成员的可访问性最小化.md)
- [16. 在公共类中使用访问方法而不是公共属性.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/16. 在公共类中使用访问方法而不是公共属性.md)
- [17. 最小化可变性.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/17. 最小化可变性.md)
- [18. 组合优于继承.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/18. 组合优于继承.md)
- [19. 如使用继承则设计，应当文档说明，否则不该使用.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/19. 如使用继承则设计，应当文档说明，否则不该使用.md)
- [20. 接口优于抽象类.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/20. 接口优于抽象类.md)
- [21. 为后代设计接口.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/21. 为后代设计接口.md)
- [22. 接口仅用来定义类型.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/22. 接口仅用来定义类型.md)
- [23. 优先使用类层次而不是标签类.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/23. 优先使用类层次而不是标签类.md)
- [24. 优先考虑静态成员类.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/24. 优先考虑静态成员类.md)
- [25. 将源文件限制为单个顶级类.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/25. 将源文件限制为单个顶级类.md)
- [26. 不要使用原始类型.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/26. 不要使用原始类型.md)
- [27. 消除非检查警告.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/27. 消除非检查警告.md)
- [28. 列表优于数组.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/28. 列表优于数组.md)
- [29. 优先考虑泛型.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/29. 优先考虑泛型.md)
- [30. 优先使用泛型方法.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/30. 优先使用泛型方法.md)
- [31. 使用限定通配符来增加API的灵活性.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/31. 使用限定通配符来增加API的灵活性.md)
- [32. 合理地结合泛型和可变参数.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/32. 合理地结合泛型和可变参数.md)
- [33. 优先考虑类型安全的异构容器.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/33. 优先考虑类型安全的异构容器.md)
- [34. 使用枚举类型替代整型常量.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/34. 使用枚举类型替代整型常量.md)
- [35. 使用实例属性替代序数.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/35. 使用实例属性替代序数.md)
- [36. 使用EnumSet替代位属性.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/36. 使用EnumSet替代位属性.md)
- [37. 使用EnumMap替代序数索引.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/37. 使用EnumMap替代序数索引.md)
- [38. 使用接口模拟可扩展的枚举.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/38. 使用接口模拟可扩展的枚举.md)
- [39. 注解优于命名模式.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/39. 注解优于命名模式.md)
- [40. 始终使用Override注解.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/40. 始终使用Override注解.md)
- [41. 使用标记接口定义类型.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/41. 使用标记接口定义类型.md)
- [42. lambda表达式优于匿名类.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/42. lambda表达式优于匿名类.md)
- [43. 方法引用优于lambda表达式.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/43. 方法引用优于lambda表达式.md)
- [44. 优先使用标准的函数式接口.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/44. 优先使用标准的函数式接口.md)
- [45. 明智审慎地使用Stream.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/45. 明智审慎地使用Stream.md)
- [46. 优先考虑流中无副作用的函数.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/46. 优先考虑流中无副作用的函数.md)
- [47. 优先使用Collection而不是Stream来作为方法的返回类型.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/47. 优先使用Collection而不是Stream来作为方法的返回类型.md)
- [48. 谨慎使用流并行.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/48. 谨慎使用流并行.md)
- [49. 检查参数有效性.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/49. 检查参数有效性.md)
- [50. 必要时进行防御性拷贝.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/50. 必要时进行防御性拷贝.md)
- [51. 仔细设计方法签名.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/51. 仔细设计方法签名.md)
- [52. 明智审慎地使用重载.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/52. 明智审慎地使用重载.md)
- [53. 明智审慎地使用可变参数.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/53. 明智审慎地使用可变参数.md)
- [54. 返回空的数组或集合，不要返回 null.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/54. 返回空的数组或集合，不要返回 null.md)
- [55. 明智审慎地返回 Optional.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/55. 明智审慎地返回 Optional.md)
- [56. 为所有已公开的 API 元素编写文档注释.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/56. 为所有已公开的 API 元素编写文档注释.md)
- [57. 最小化局部变量的作用域.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/57. 最小化局部变量的作用域.md)
- [58. for-each 循环优于传统 for 循环.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/58. for-each 循环优于传统 for 循环.md)
- [59. 了解并使用库.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/59. 了解并使用库.md)
- [60. 若需要精确答案就应避免使用 float 和 double 类型.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/60. 若需要精确答案就应避免使用 float 和 double 类型.md)
- [61. 基本数据类型优于包装类.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/61. 基本数据类型优于包装类.md)
- [62. 当使用其他类型更合适时应避免使用字符串.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/62. 当使用其他类型更合适时应避免使用字符串.md)
- [63. 当心字符串连接引起的性能问题.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/63. 当心字符串连接引起的性能问题.md)
- [64. 通过接口引用对象.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/64. 通过接口引用对象.md)
- [65. 接口优于反射.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/65. 接口优于反射.md)
- [66. 明智审慎地本地方法.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/66. 明智审慎地本地方法.md)
- [67. 明智审慎地进行优化.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/67. 明智审慎地进行优化.md)
- [68. 遵守被广泛认可的命名约定.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/68. 遵守被广泛认可的命名约定.md)
- [69. 只针对异常的情况下才使用异常.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/69. 只针对异常的情况下才使用异常.md)
- [70. 对可恢复的情况使用受检异常，对编程错误使用运行时异常.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/70. 对可恢复的情况使用受检异常，对编程错误使用运行时异常.md)
- [71. 避免不必要的使用受检异常.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/71. 避免不必要的使用受检异常.md)
- [72. 优先使用标准的异常.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/72. 优先使用标准的异常.md)
- [73. 抛出与抽象对应的异常.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/73. 抛出与抽象对应的异常.md)
- [74. 每个方法抛出的异常都需要创建文档.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/74. 每个方法抛出的异常都需要创建文档.md)
- [75. 在细节消息中包含失败一捕获信息.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/75. 在细节消息中包含失败一捕获信息.md)
- [76. 保持失败原子性.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/76. 保持失败原子性.md)
- [77. 不要忽略异常.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/77. 不要忽略异常.md)
- [78. 同步访问共享的可变数据.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/78. 同步访问共享的可变数据.md)
- [79. 避免过度同步.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/79. 避免过度同步.md)
- [80. executor 、task 和 stream 优先于线程.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/80. executor 、task 和 stream 优先于线程.md)
- [81. 相比 wait 和 notify 优先使用并发工具.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/81. 相比 wait 和 notify 优先使用并发工具.md)
- [82. 文档应包含线程安全属性.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/82. 文档应包含线程安全属性.md)
- [83. 明智审慎的使用延迟初始化.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/83. 明智审慎的使用延迟初始化.md)
- [84. 不要依赖线程调度器.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/84. 不要依赖线程调度器.md)
- [85. 优先选择 Java 序列化的替代方案.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/85. 优先选择 Java 序列化的替代方案.md)
- [86. 非常谨慎地实现 Serializable.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/86. 非常谨慎地实现 Serializable.md)
- [87. 考虑使用自定义的序列化形式.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/87. 考虑使用自定义的序列化形式.md)
- [88. 保护性的编写 readObject 方法.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/88. 保护性的编写 readObject 方法.md)
- [89. 对于实例控制，枚举类型优于 readResolve.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/89. 对于实例控制，枚举类型优于 readResolve.md)
- [90. 考虑用序列化代理代替序列化实例.md](https://github.com/sjsdfg/effective-java-3rd-chinese/blob/master/docs/notes/90. 考虑用序列化代理代替序列化实例.md)

我在读这本书的时候，曾写过两篇文章，大家也可以阅读一下。
+ [为什么要将局部变量的作用域最小化？](http://www.itwanger.com/java/2019/12/04/java-variable-zuixiaohua.html)
+ [面试官：兄弟，说说基本类型和包装类型的区别吧](http://www.itwanger.com/java/2019/11/01/java-int-integer.html)

### 第五本《[Java网络编程](http://www.itwanger.com/java/2019/12/06/java-effective-advise.html)》

《Java网络编程》全面介绍了如何使用 Java 开发网络程序。网络编程是指编写运行在多个设备（计算机）上的程序，这些设备可以通过网络连接起来。这也是 Java 基础学习完后必须要学习的一大块内容，包括：Internet 底层协议（TCP/IP 和 UDP/IP）、网络输入和输出、DNS 交互、定位、识别和下载网络资源、HTTP 协议（REST、HTTP 头部和 Cookie）、Socket 通信等等。

<img src="./images-java-study-notes/java-book-10.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

这本书的整体评价并不算高，吐槽的反而更多。但是，对于学习 Java 网络编程的基础知识非常的有用。

### 第六本《[Java 并发编程实战](http://www.itwanger.com/java/2019/12/11/java-bingfa-biancheng-shizhan.html)》

《Java并发编程实战》深入浅出地介绍了 Java 线程和并发编程，是一本还算不错的 Java 并发编程参考手册。本书从并发和线程安全性的基本概念出发，介绍了如何使用类库来提供基本的并发方案，包括如何利用线程来提高并发应用程序的吞吐量、如何识别可并发执行的任务、如何提高单线程子系统的响应性、如何确保并发程序执行预期的任务，如何提高并发代码的性能和可伸缩性等等内容。

<img src="./images-java-study-notes/java-book-11.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

但我必须要说的是，《Java并发编程实战》这本书并没有摆脱翻译枯燥的老毛病，读起来很需要耐住性子，不然就很难把这本书吃透。当然了，并发编程本身就很难，大家要做好心理准备。

我之前写了四篇这本书的读书心得，大家可以参照一下。
+ [Java 并发编程(一)：简介](http://www.itwanger.com/java/2019/11/09/java-bingfa-1.html)
+ [Java 并发编程(二)：如何保证共享变量的原子性？](http://www.itwanger.com/java/2019/11/09/java-bingfa-2.html)
+ [Java 并发编程(三)：如何保证共享变量的可见性？](http://www.itwanger.com/java/2019/11/09/java-bingfa-3.html)
+ [Java 并发编程(四)：如何保证对象的线程安全性](http://www.itwanger.com/java/2019/11/09/java-bingfa-4.html)

### 第七本《[深入理解Java虚拟机](http://www.itwanger.com/java/2019/12/11/java-jvm.html)》

《深入理解 Java 虚拟机：JVM 高级特性与最佳实践(第 2 版)》是唯一一本我们国内程序员写的经典书，可以媲美《Java 编程思想》。

<img src="./images-java-study-notes/java-book-12.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

这本书牛逼到什么程度，几乎所有写 Java 虚拟机方面的文章，没有一个不在文章最后注明：本文参考字周志明老师的《深入理解 Java 虚拟机》。假如这篇文章最后没有注明的话，那保不准是不尊重版权。

第 1 版两年内印刷近 10 次，好评（五星）如潮，是整个 Java 图书领域公认的经典著作和畅销书。

第 2 版共分为 5 大部分，围绕内存管理、执行子系统、程序编译与优化、高效并发等核心主题对 JVM 进行了全面深入的分析，深刻揭示了 JVM 的工作原理。

第一部分主要介绍了 Java 的技术体系、Java 和 JVM 的发展历程。

第二部分主要介绍了 JVM 的自动内存管理，包括虚拟机的内存区域划分原理，内存溢出产生的原因、常见的垃圾收集算法、垃圾收集器的工作原理等等。

第三部分主要介绍了类文件结构、虚拟机类加载机制、虚拟机字节码执行引擎。

第四部分主要介绍了程序的编译和代码的优化，阐述了泛型、自动装箱拆箱、条件编译等语法糖的原理；还有 HotSpot 的即时编译器。

第五部分主要介绍了 Java 实现高效并发的原理，包括 JVM 内存模型等。

作者周志明更成为了广大 Java 程序员心目中的大神级人物，厉害厉害了！有读者曾这样感叹道：“**国内程序员很难再写出这么经典的书了**！”

如果大家想要成为一名优秀的 Java 程序员，本书不得不读啊！并且是细细品味的那种。

### 第八本《[Java性能权威指南](http://www.itwanger.com/java/2019/12/11/java-xingneng-zhinan.html)》

市面上专注于 Java 性能的书不多，《Java性能权威指南》算是一本很不错的。通过阅读本书，我们可以运用 4 个基本原则最大程度地提升性能测试的效果、使用 JDK 自带的工具收集程序的性能数据、理解 JIT（即时编译器）编译器的优缺点、调优 JVM 垃圾收集器、最大程度优化多线程等等。

<img src="./images-java-study-notes/java-book-13.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

### 第九本《[代码整洁之道](http://www.itwanger.com/java/2019/12/11/java-clean-code.html)》

我可以这么肯定地说：《代码整洁之道》值得所有的程序员读一读。软件的质量，不仅依赖于架构，更与代码质量息息相关。而代码的质量与其整洁度成正比关系，越整洁的代码，其质量毫无疑问的就会越高。由于本书中的例子是由 Java 实现的，因此 Java 程序员在读这本书的时候有着天然的优势。

<img src="./images-java-study-notes/java-book-14.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

如何写出整洁的代码呢？Keep It Simple Stupid：代码简单直接，不仅能够提高代码的效率，还能够让阅读代码的人赏心悦目。

本书的第一章，对整洁代码下了一个定义，每个程序员都应该铭记在心。

> 1、整洁的代码力求专注，每个方法、每个类都应该全神贯注于一件事；命名更要给人一种“顾名思义”的感觉。 2、整洁的代码简单直接，从不隐藏设计者的意图。 3、整洁的代码应当有单元测试。 4、整洁的代码拒绝重复，其表达力直击人的心灵。

### 第十本《[设计模式之禅](http://www.itwanger.com/java/2019/12/11/java-sheji-moshi.html)》

《设计模式之禅（第 2 版）》是设计模式领域公认的 3 本经典著作之一，也是我们国内程序员写的一本书，趣味化十足，读起来也非常容易理解。这本书值得所有的程序员读一读，但 Java 程序员读起来更容易上手，因为源码是 Java 完成的。作者名叫秦小波，和我最喜欢的作家王小波同名。

<img src="./images-java-study-notes/java-book-15.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

本书可以分为五个部分：

第一部分（第 1～6 章），包含有单一职责原则、里氏替换原则、依赖倒置原则、接口隔离原则、迪米特法则、开闭原则等内容，对面向对象程序员设计的 6 大原则进行了深刻解读。

第二部分（第 7～29 章）通过大量生动的案例讲解了 23 种最常用的设计模式。包含单例模式、工厂方法模式、抽象工厂模式、模板方法模式、建造者模式、代理模式、原型模式、中介者模式、命令模式、责任链模式、装饰模式、策略模式、适配器模式、迭代器模式、组合模式、观察者模式、门面模式、备忘录模式、访问者模式、状态模式、解释器模式、享元模式、桥梁模式。

我在《Java极客技术》星球上解读过几篇模式，这里推荐给大家读一读。
+ [备忘录模式](https://t.zsxq.com/MJEeubM)
+ [解释器模式](https://t.zsxq.com/uZb2Bi6)
+ [组合模式](https://t.zsxq.com/6qnmyzj)

第三部分（第 30～33 章）对同类型和相关联的模式进行了比较，旨在说明它们之间的差别。

第四部分（第 34～36 章）探讨了如何在实际开发中将各种设计模式混合起来使用的可能性，以发挥设计模式的最大功效。

第五部分（第 37～38 章）主要讲解了 5 种新的设计模式的原理、意图和最佳实践。

大家都听说过，学习设计模式非常的重要，那么为什么这么重要呢，设计模式到底是什么？打个比喻学编程就像学武功一样。

武功要练得很牛逼，有两样东西不能丢。第一，是内功；第二，是武功秘籍。内功对应到编程就是我们编程基础能力，那编程的设计模式就可以想象成武术中的武功秘籍。

设计模式就是根据不同类型场景，设计优雅的（编码）解决方案。学好设计模式有很多好处，比如，容易看懂经典代码中的逻辑（很多优秀的开源框架大量使用了设计模式）；应对面试时对答如流（设计模是面试重点）；可以编写出优雅的解决方案（或者代码）。

### 第十一本《[Java开发手册](http://www.itwanger.com/java/2019/12/11/java-kaifa-shouce.html)》

《Java开发手册》是每个 Java 程序员都值得拥有的一本参考指南。该手册涵盖了编程规约、异常日志、单元测试、安全规约、MySQL 数据库、工程结构、设计规约等 7 个部分，参考价值极大。

<img src="./images-java-study-notes/java-book-16.png"
     style="border-radius:4px; width:32%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

《Java 开发手册》作为阿里官方的 Java 代码规范标准，是行业内领先的开发规范文档。如果能够认真践行该手册中提到的规约，绝壁能够帮助 Java 程序员养成良好的编程习惯，并且提高代码的质量和降低项目维护的难度。

据说，这本手册在阿里内部打磨了很久很久才对外开放的，所以倾注了很多大佬们的心血。况且，阿里作为一个大厂，拿出来一份有瑕疵的手册，多少会丢脸，所以这本手册绝对值得读一读。

本手册的作者孤尽曾说：

> 代码规范这事情，它是一个吃力不讨好，短期没结果，费心又费力的事情。唯有自己内心的技术情怀。

### 第十二本《重构——改善既有的代码设计》

<img src="./images-java-study-notes/java-book-17.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

这本书在业界的名声也非常的响，只不过看起来就需要一些精力和耐力，上面这些书看完后，可以看这一本，对于重新审视现有代码有极大的帮助。

### 第十三本《算法》

<img src="./images-java-study-notes/java-book-18.png"
     style="border-radius:4px; width:90%; margin:0 auto; box-shadow:1px 1px 3px 2px #e5e5e5">

说起数据结构和算法，我就觉得不好意思，脸上泛起难为情的红晕。但为什么我还要说呢？

因为我深受其苦。

我是一个农村走出来的娃，体会过其中的酸甜苦辣，所以我会奉劝各位，以后碰上什么知识分子上山下乡的活动，千万不要去。那不叫体验生活，那叫体验“艰苦”生活。

那在敲代码的过程中，我就经常遇到一些实际的问题，由于无法充分利用数据结构，将数据之间的关系通过合适的算法策略进行有效地存储转换，就导致程序的性能很低。

所以我劝各位新人，趁有大把的时间和精力，多投入一点到数据结构和算法上面去。基础知识就像是一座大楼的地基，它决定了我们的技术高度。数据结构和算法就是最重要的基础知识，学习它们的过程就像是在打地基。

上面这张思维导图提到的数据结构在工作当中太经常使用了，频率高得就像隔三差五会看到隔壁老王这个词一样。

对于算法，如果觉得《算法》这本鸿篇巨制太过枯燥的话，可以选择《趣学算法》、《啊哈算法》等一些非译作的，相对趣味化的入门书。

可能很多人会存在这样一个误区：算法在工作当中很少会用到，需要的时候面向搜索引擎解决一下就行了。

但我想说的是，跳槽的时候很有用，因为一些大厂就喜欢考算法。除此之外，算法对阅读源码也很有帮助；况且，谁不想做一名编程的艺术家呢？长期来看，大脑思考能力是一个人最重要的核心竞争力，而算法是为数不多的能够有效训练大脑思考能力的途径之一。

------

以上提到的这些书籍，如果大家需要 PDF 版, 见 github 仓库: https://github.com/itwanger/JavaBooks
