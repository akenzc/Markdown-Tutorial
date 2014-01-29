# GitHub Flavored Markdown

GFM在标准Markdown语法的基础上有了一些优化，并且增加了一些额外的功能。

## 与标准Markdown的不同

### 多下划线的单词

代码和文件名中经常出现多个下划线的情况，而这些被标准Markdown处理为斜体字的一段，其实只是一个词的一部分。

因此，GFM忽略了多个下划线的单词，比如：

	perform_complicated_task

	do_this_and_do_that_and_another_thing

### URL自动链接

GFM将为文本中的标准的URL建立链接，如果你不用设置链接文本，而只是显示一个URL。可以简单的输入一个URL，就会自动变成一个URL链接。

	http://example.com
	
### 删除线

GFM增加了删除线的语法，在文本的前后环绕两个`~`符号，即可在文本上增加删除线。

	~~删除文本~~
	
### 代码块

标准Markdown语法，将每段开始空四格的文本视为代码块。

GFM支持 ` ``` ` 前后三个引号围起来的文本为代码块，而不需要缩进四格空格。尽管不需要缩进，但推荐在代码块的前面放置一个空行，使其更易于阅读。

	Here's an example:

	```
	function test() {
  	console.log("notice the blank line before this 	function?");
	}
	```

### 语法高亮

如果需要语法高亮，只要在代码块的最前添加一个可选的语言标示符，GFM即可高亮显示该代码块。

例如`Ruby`的代码语法高亮显示：

	```ruby
	require 'redcarpet'
	markdown = Redcarpet.new("Hello World!")
	puts markdown.to_html
	```
	
### 表格

可以简单的通过符号(`-`)和(`|`)来创建表格。

```
	First Header  | Second Header
	------------- | -------------
	Content Cell  | Content Cell
	Content Cell  | Content Cell
```

如果希望源文件更美观，可以在前后增加(`|`)。

	| First Header  | Second Header |
	| ------------- | ------------- |
	| Content Cell  | Content Cell  |
	| Content Cell  | Content Cell  |
	
顶部的小破折号不需要完全覆盖下面的文本：

	| Name | Description          |
	| ------------- | ----------- |
	| Help      | Display the help window.|
	| Close     | Closes a window     |
	
还可以在表格内加入链接、粗体、斜体和删除线：

	| Name | Description          |
	| ------------- | ----------- |
	| Help      | ~~Display the~~ help window.|
	| Close     | _Closes_ a window     |
	
最后，可以通过在标题行中增加一个冒号(`:`)，来定义文本的左对齐，右对齐或居中显示。

冒号在最左端为左对齐，最右端为右对齐，两端均有则为居中。

	| Left-Aligned  | Center Aligned  | Right Aligned |
	| :------------ |:---------------:| -----:|
	| col 3 is      | some wordy text | $1600 |
	| col 2 is      | centered        |   $12 |
	| zebra stripes | are neat        |    $1 |
	
------------------------

原文：<https://help.github.com/articles/github-flavored-markdown>
