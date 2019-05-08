# Summary

* [说明](README.md)

* [前言](introduction/README.md)
   * [术语说明](introduction/terminology.md)
   * [指南说明](introduction/guide-notes.md)

* [源文件基础](source-file-basics/README.md)
   * [文件名](source-file-basics/file-name.md)
   * [文件编码：UTF-8](source-file-basics/file-encoding.md)
   * [特殊字符](source-file-basics/special-characters.md)
       * [空白字符](source-file-basics/whitespace-characters.md)
       * [特殊转义序列](source-file-basics/special-escape-sequences.md)
       * [非ASCII字符](source-file-basics/non-ascii-characters.md)
* [源文件结构](source-file-structure/README.md)
   * [许可证或版权信息](source-file-structure/copyright-statement.md)
   * [package语句](source-file-structure/package-statement.md)
   * [import语句](source-file-structure/import-statements.md)
       * [import不要使用通配符](source-file-structure/wildcard-imports.md)
       * [不要换行](source-file-structure/import-line-wrapping.md)
       * [顺序和间距](source-file-structure/import-ordering-and-spacing.md)
   * [类声明](source-file-structure/class-declaration.md)
       * [只有一个顶级类声明](source-file-structure/one-top-level-class.md)
       * [类成员顺序](source-file-structure/class-member-ordering.md)
* [格式](formatting/README.md)
   * [大括号](formatting/braces.md)
       * [使用大括号(即使是可选的)](formatting/braces-always-used.md)
       * [非空块：K & R 风格](formatting/blocks-k-r-style.md)
       * [空块：可以用简洁版本](formatting/braces-empty-blocks.md)
   * [块缩进：2个空格](formatting/block-indentation.md)
   * [一行一个语句](formatting/one-statement-per-line.md)
   * [列限制：80或100](formatting/column-limit.md)
   * [自动换行](formatting/line-wrapping.md)
       * [从哪里断开](formatting/line-wrapping-where-to-break.md)
       * [自动换行时缩进至少+4个空格](formatting/line-wrapping-indent.md)
   * [空白](formatting/whitespace.md)
       * [垂直空白](formatting/vertical-whitespace.md)
       * [水平空白](formatting/horizontal-whitespace.md)
       * [水平对齐：不做要求](formatting/horizontal-alignment.md)
   * [用小括号来限定组：推荐](formatting/grouping-parentheses.md)
   * [枚举类](formatting/specific-constructs.md)
       * [枚举类](formatting/enum-classes.md)
       * [变量声明](formatting/variable-declarations.md)
       * [数组](formatting/arrays.md)
       * [switch语句](formatting/switch.md)
       * [注解(Annotations)](formatting/annotations.md)
       * [注释](formatting/comments.md)
       * [Modifiers](formatting/modifiers.md)
* [命名](naming/README.md)
   * [对所有标识符都通用的规则](naming/identifier-names.md)
   * [标识符类型的规则](naming/specific-identifier-names.md)
       * [包名](naming/package-names.md)
       * [类名](naming/class-names.md)
       * [方法名](naming/method-names.md)
       * [常量名](naming/constant-names.md)
       * [非常量字段名](naming/non-constant-field-names.md)
       * [参数名](naming/parameter-names.md)
       * [局部变量名](naming/local-variable-names.md)
       * [类型变量名](naming/type-variable-names.md)
   * [驼峰式命名法(CamelCase)](naming/camel-case.md)
* [编程实践](programming-practices/README.md)
   * [@Override：能用则用](programming-practices/override-annotation.md)
   * [捕获的异常：不能忽视](programming-practices/caught-exceptions.md)
   * [静态成员：使用类进行调用](programming-practices/static-members.md)
   * [Finalizers: 禁用](programming-practices/finalizers.md)
* [Javadoc](javadoc/README.md)
   * [格式](javadoc/javadoc-formatting.md)
       * [一般形式](javadoc/javadoc-multi-line.md)
       * [段落](javadoc/javadoc-paragraphs.md)
       * [Javadoc标记](javadoc/javadoc-at-clauses.md)
   * [摘要片段](javadoc/summary-fragment.md)
   * [哪里需要使用Javadoc](javadoc/javadoc-where-required.md)
       * [例外：不言自明的方法](javadoc/javadoc-exception-self-explanatory.md)
       * [例外：重载](javadoc/javadoc-exception-overrides.md)
       * [可选的Javadoc](javadoc/javadoc-optional.md)
