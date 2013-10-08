使用带提示符的解释器
===================
在命令行的shell提示符下键入python，启动解释器。现在输入print 'Hello World'，然后按Enter键。你应该可以看到输出的单词Hello World。

对于Windows用户，只要你正确的设置了PATH变量，你应该可以从命令行启动解释器。或者你可以选择使用IDLE程序。IDLE是集成开发环境的缩写。点击开始->程序->Python 2.3->IDLE(Python GUI)。Linux用户也可以使用IDLE。

注意，>>>是你键入Python语句的提示符。


	$ python
	Python 2.3.4 (#1, Oct 26 2004, 16:42:40)
	[GCC 3.4.2 20041017 (Red Hat 3.4.2-6.fc3)] on linux2
	Type "help", "copyright", "credits" or "license" for more information.
	>>> print 'hello world'
	hello world
	>>>
	
注意，Python会在下一行立即给出你输出！你刚才键入的是一句Python 语句 。我们使用print（不要惊讶）来打印你提供给它的值。这里，我们提供的是文本Hello World，它被迅速地打印在屏幕上。

如何退出
-------
如果你使用的是Linux/BSD shell，那么按Ctrl-d退出提示符。如果是在Windows命令行中，则按Ctrl-z再按Enter。