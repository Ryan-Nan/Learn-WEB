#学习HTML5笔记
##HTML5深受欢迎的理由
1、解决之前版本兼容问题，使各个主流浏览器规范统一；

2、HTML4及以前版本文档结构不明确，如过多使用div，无法判断其含义；

3、解决了web应用程序功能的限制，比如不能上传过多文件，只能上传一个文件。无法实现富web应用。

## HTML5与HTML4的区别
###1.语法的改变
这种的改变目的是使各个浏览器符合一个通用的标准，减低兼容性问题。在现有的基础语法修改，废弃不符合标准规范的语法。
* 可以省略标记的元素
* 具有boolean值的属性

        <!--只写属性不写属性值代码属性为true-->
        <input type="checkbox" checked>

* 省略引号

        <!--省略属性值两边的双引号-->
        <input type=text>

### 2.新增的结构元素
在HTML5中，新增了以下与结构相关的元素

***section元素***，它表示页面中的一个内容区块，比如章节、页眉、页脚或页面中的其他部分。它可以与h1、h2、h3等元素结合起来使用，标示文档结构。

HTML5中代码示例

        <section...</section>
        
    
***article元素***

article元素表示页面中的一块与上下文不相关的独立内容，比如博客中的一遍文章。

***aside元素***

aside元素表示article元素内容之外的、与article元素的内容相关的辅助信息。

***header元素***

header元素表示页面中一个内容区块或整个页面的标题。

        <header>..</header>
        
html4中代码示例

       <div>...</div>
       <!--以上都是 -->
       

***hgroup元素***

hgroup元素 标签用于对网页或区段（section）的标题进行组合。这个语义就是组合网页或区段的标题，修改hgroup样式后，被他包围的h1、h4之类的标题元素就会同时继承他设置的样式。

        <hgroup>
            <h1>Welcome to my WWF</h1>
            <h2>For a living planet</h2>
        </hgroup>

        <p>The rest of the content...</p>

***footer元素***

footer元素表示整个页面或页面中一个内容区块的脚注。一般来说，它包含作者姓名、创作日期、地址等。

        HTML5中代码示例
        <footer>..</footer>

        HTML4中代码示例
        <div>..</div>
        
***nav***，
nav元素表示页面中导航链接的部分。

HTML4中代码示例

        <ul>..</ul>
        
*** figure元素***，表示一段独立的流内容，文档主体流内容中的一个独立单元。使用figcaption元素为figure元素组添加标题。
HTML5中代码示例

        <figure>
            <figcaption>黄浦江上的的卢浦大桥</figcaption>
            <p>拍摄者：W3School 项目组，拍摄时间：2010 年 10 月</p>
            <img src="/i/shanghai_lupu_bridge.jpg" width="350" height="234" />
        </figure>
        
运行效果：

[figure]!()
