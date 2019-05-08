#### 4.8.6 注释

##### 4.8.6.1 块注释风格

块注释与其周围的代码在同一缩进级别。它们可以是`/* ... */`风格，也可以是`// ...`风格。对于多行的`/* ... */`注释，后续行必须从`*`开始， 并且与前一行的`*`对齐。以下示例注释都是OK的。

    /*
     * This is          // And so           /* Or you can
     * okay.            // is this.          * even do this. */
     */

注释不要封闭在由星号或其它字符绘制的框架里。

> > Tip：在写多行注释时，如果你希望在必要时能重新换行(即注释像段落风格一样)，那么使用`/* ... */`。

