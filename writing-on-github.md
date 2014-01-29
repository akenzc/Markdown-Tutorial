# 在GitHub上用Markdown写作

Issue、评论、pull request描述均可以使用GFM（GitHub flavored markdown）语法来写，并且还有一些额外的特性使得在GitHub上写作更容易。

## 标示符

### 换行符

标准Markdown语法的换行需要两个换行符。

GFM只需要一个即可，以下例子中两个短语只用了一个换行符分割即实现了换行。

	Roses are red
	Violets are blue

### 任务列表

列表变成任务列表只需要在列表前加入 `[]` 或 `[X]`。

	- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
	- [x] list syntax required (any unordered or ordered list supported)
	- [x] this is a complete item
	- [ ] this is an incomplete item

任务列表也可以在Gist评论以及Gist Markdown文件中使用。在这些情况下，任务列表显示为复选框，你可以点击打开或关闭。

### 引用

某些引用可以自动添加链接，比如：

	* SHA: 17bb13a686306dd0e95428d89311e45342532db0
	* User@SHA: mojombo@17bb13a686306dd0e95428d89311e45342532db0
	* User/Repository@SHA: mojombo/	jekyll@17bb13a686306dd0e95428d89311e45342532db0
	* #Num: #1
	* User#Num: mojombo#1
	* User/Repository#Num: mojombo/jekyll#1

----------------------

## 功能

### 快速引用

键入 `r` 可以回复当前问题或pull request的评论。任何被选中的文本

### 人名或团队名称自动补全

当你寻找某个人或团队时，键入`@`即可列出过滤后的清单，可以方便选择。

### 表情自动补全

键入 `:` 即可显示表情建议列表。

### Issue自动补全

键入 `#` 将列出Issue和Pull Request的建议，输入数字或文本来过滤列表，点击完成补全。

### Zen Mode(全屏)写作

Zen Mode允许你全屏写作，你可以在comment、issue、和pull request表单中找到Zen Mode按钮。

Zen Mode提供亮、暗两种主题。

--------------------

原文： <https://help.github.com/articles/writing-on-github>
