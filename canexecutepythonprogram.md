可执行的Python程序
=======================
这部分内容只对Linux/Unix用户适用，不过Windows用户可能也对程序的第一行比较好奇。首先我们需要通过chmod命令，给程序可执行的许可，然后 运行 程序。

	$ chmod a+x helloworld.py
	$ ./helloworld.py
	Hello World
	
chmod命令用来 改变 文件的 模式 ，给系统中所有用户这个源文件的执行许可。然后我们可以直接通过指定源文件的位置来执行程序。我们使用./来指示程序位于当前目录。

为了更加有趣一些，你可以把你的文件名改成仅仅helloworld，然后运行./helloworld。这样，这个程序仍然可以工作，因为系统知道它必须用源文件第一行指定的那个解释器来运行程序。

只要知道程序的确切位置，你现在就可以运行程序了——但是如果你希望你的程序能够从各个位置运行呢？那样的话，你可以把你的程序保存在PATH环境变量中的目录之一。每当你运行任何程序，系统会查找列在PATH环境变量中的各个目录。然后运行那个程序。你只要简单地把这个源文件复制到PATH所列目录之一就可以使你的程序在任何位置都可用了


	$ echo $PATH
	/opt/mono/bin/:/usr/local/bin:/usr/bin:/bin:/usr/X11R6/bin:/home/swaroop/bin
	$ cp helloworld.py /home/swaroop/bin/helloworld
	$ helloworld
	Hello World
	
Tpis:
----------------
对于Python来说，程序、脚本或者软件都是指同一个东西。