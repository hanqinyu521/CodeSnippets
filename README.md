# CodeSnippets
### 1、为什么要使用代码块？

提高编码效率

### 2、自定义的代码片段存放在哪里?

Xcode中的自定义的代码片段一般存放在:
~/Library/Developer/Xcode/UserData/CodeSnippets

### 3、代码块包括

property

block

notification

delegate

UI控件（frame or Masonry）

其他一些常用

### 4、使用方法

可以直接运行工程中的ExportSnippets.command文件自动导入到代码块文件目录内。

### 5、代码块定义

Title 标题 - 块的名字（出现在代码补全和代码块库列表中）

Summary 简介 - 简单描述下它是干嘛的（只出现在代码块库列表中）

Platform 平台 - 限制可访问该代码块的平台。OS X，iOS，或者（“全部”）

Language 语言 - 限制可访问该代码块的语言。常见的有 C，Objective-C，C++，或 Objective-C++

Completion Shortcut 输入码 - 快捷输入码。常用块的输入码应该非常简练。Xcode 不会警告冲突 / 重复的输入码，所以一定要确保新添加的不要和已有的冲突。

Completion Scopes 有效范围 - 限制可访问该代码块的范围。if / else语句的自动补全应该只在方法或者函数的实现中有效。

下面这些选项可以任意组合：

1、All 全部

2、Class Implementation 类实现，范围为.m文件，@implementation - @end的范围

3、Class Interface Methods 类接口方法，范围为.h文件的方法，@interface - @end的范围，指的是定义的方法

4、Class Interface Variables 类接口变量，范围为.h文件的属性，@interface - @end的范围

5、Code Expression 代码表达式,Method方法的一部分

6、Function or Method 函数或方法，指的是调用的方法，区别于2和3（定义的方法）

7、Preprocessor Directive 预处理指令

8、String or Comment 字符串或注释

9、Top Level 最高层
