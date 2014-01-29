# Markdown指导

## 什么是Markdown?

Markdown 是一种轻量级标记语言，创始人为约翰·格鲁伯（John Gruber）和亚伦·斯沃茨（Aaron Swartz）。它允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML(或者HTML)文档”。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。

Markdown同时还是一个由Gruber编写的Perl脚本：Markdown.pl。它把用markdown语法编写的内容转换成有效的、结构良好的XHTML或HTML内容，并将左尖括号('<')和&号替换成它们各自的字符实体引用。它可以用作单独的脚本，Blosxom和Movable Type的插件又或者BBEdit的文本过滤器。

Markdown也已经被其他人用Perl和别的编程语言重新实现，其中一个Perl模块放在了CPAN(Text::Markdown)上。它基于一个BSD风格的许可证分发并可以作为几个内容管理系统的插件。

--------------------

## Markdown语法

### 标准Markdown语法 (Standard Markdown)

标准Markdown语法包括了标题、强调、引用、列表、链接、图片、代码、分割线和转义反斜杠。

详细的标准语法请见[这里](http://github.com/)

### 扩展markdown语法

#### 1. GFM (GitHub Flavored Markdown)语法

GFM是SM的一个超集，对标准Markdown进行了一些扩展.

包括了代码、链接、标题的优化，Issue和request的自动识别、自动@系统用户，以及自动引用。

详细的GFM语法请见[这里](http://github.com/)

#### 2. Pandoc's markdown语法
注脚、引用表格、上下标、删除线、行区块、定义清单、Raw TeX、数学等均有扩展。

http://pages.tzengyuxio.me/pandoc/

---------------------


## 在GitHub上用Markdown写作
GitHub上提供一些特有的符号、快捷键以及功能方便使用Markdown来写作。

具体请看：