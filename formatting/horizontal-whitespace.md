#### 4.6.2 水平空白

除了语言需求和其它规则，并且除了文字，注释和Javadoc用到单个空格，单个ASCII空格也出现在以下几个地方：

1.  分隔任何保留字与紧随其后的左括号(`(`)(如`if, for catch`等)。
2.  分隔任何保留字与其前面的右大括号(`}`)(如`else, catch`)。
3.  在任何左大括号前(`{`)，两个例外：
    *   `@SomeAnnotation({a, b})`(不使用空格)。
    *   `String[][] x = foo;`(大括号间没有空格，见下面的Note)。
4.  在任何二元或三元运算符的两侧。这也适用于以下“类运算符”符号：
    *   类型界限中的&(`<T extends Foo & Bar>`)。
    *   catch块中的管道符号(`catch (FooException | BarException e`)。
    *   `foreach`语句中的分号。
5.  在`, : ;`及右括号(`)`)后
6.  如果在一条语句后做注释，则双斜杠(//)两边都要空格。这里可以允许多个空格，但没有必要。
7.  类型和变量之间：List <string>list。</string>
8.  数组初始化中，大括号内的空格是可选的，即`new int[] {5, 6}`和`new int[] { 5, 6 }`都是可以的。

> > Note：这个规则并不要求或禁止一行的开关或结尾需要额外的空格，只对内部空格做要求。
