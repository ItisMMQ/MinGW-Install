# MinGW-Install
MinGW，是Minimalist GNUfor Windows的缩写。它是一个可自由使用和自由发布的Windows特定头文件和使用GNU工具集导入库的集合，允许你在GNU/Linux和Windows平台生成本地的Windows程序而不需要第三方C运行时（C Runtime）库。MinGW 是一组包含文件和端口库，其功能是允许控制台模式的程序使用微软的标准C运行时（C Runtime）库（MSVCRT.DLL）,该库在所有的 NT OS 上有效，在所有的 Windows 95发行版以上的 Windows OS 有效，使用基本运行时，你可以使用 GCC 写控制台模式的符合美国标准化组织（ANSI）程序，可以使用微软提供的 C 运行时（C Runtime）扩展，与基本运行时相结合，就可以有充分的权利既使用 CRT（C Runtime）又使用 WindowsAPI功能。摘自百度百科
一、进入网站
![image](https://github.com/ItisMMQ/Images/blob/master/MinGW_website.jpg)
二、点击右上角的下载。进入页面：
![image](https://github.com/ItisMMQ/Images/blob/master/MinGW2.jpg）
或者:
![image](https://github.com/ItisMMQ/Images/blob/master/MinGW2-2.jpg)
三、选择对应操作系统的安装包，下载。建议安装到C盘根目录下或其他不杂乱的地方。
安装界面如下：
![image]（https://github.com/ItisMMQ/Images/blob/master/MinGW3.png）
选择安装，出现对话框时选择continue：
![image](https://github.com/ItisMMQ/Images/blob/master/MinGW4.png)
四、之后选择需要的包，可以点击界面左边打开All packages进行选择。我当时是直接点外面的选项把相关的包全装了，呃呵呵。
![image](https://github.com/ItisMMQ/Images/blob/master/MinGW5.png)
五、耐心等一下就可以安装完毕，然后就要检验一下安装是否成功。
   打开cmd，输入“cmd”；
   输入“gcc -v”;
若出现以下界面则说明安装成功啦！
六、添加环境变量
   右键单击“计算机”或“我的电脑”——>属性——>高级系统设置——>环境变量——>系统变量列表中选“path”，编辑——>将路径加入。
![image](https://github.com/ItisMMQ/Images/blob/master/MinGW7.png)
然后就OK啦~
