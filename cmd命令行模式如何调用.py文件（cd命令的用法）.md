# 命令行模式和交互式模式

- Windows+R+cmd进入命令行模式
- 在命令行模式下输入python进入Python交互模式
- 交互模式下输入exit（）并且回车，退出交互模式，进入命令行模式

*命令行模式可以直接运行一个.py文件（一次性执行该文件内所有代码），Python交互模式的代码是输入一行执行一行，会把每一行的Python代码结果自动打印出来*

# cd命令的使用

- 我们要在cmd窗口调用main.py文件，只需要将cmd路径目录转入main.py所在的文件夹，然后输入命令即可
- 先将当前盘由C盘转到F盘，输入f:回车即可
- 再通过cd命令，进入F:\jiaqi\py\demo目录下，此时再输入调用语句*python* main.py，就可以就可以成功运行此命令

*cd命令只能在同一个盘符下的不同文件夹之间跳转*

cd命令的格式：**cd(空格)（完整路径，不能少了某个盘,也不能在这个命令行直接直接输入.py的调用语句）**

.py文件调用语句：**python(空格)（文件名）.py**

![](F:\jiaqi\py\Snipaste_2023-06-21_17-18-13.png)