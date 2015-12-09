#WTL vs2013/2015安装

1)首先,去[http://sourceforge.net/projects/wtl/](http://sourceforge.net/projects/wtl/ "http://sourceforge.net/projects/wtl/")下WTL90_4140_Final.zip,解压.

2)然后在 **..\WTL90_4140_Final\AppWiz** 文件夹下找到**Setup.js**,用记事本把里面的**11.0**都改成**14.0**,然后运行(对应vs**2015**)；

3)把文件夹**..\WTL90_4140_Final\include** 里所有的 .h 文件拷到 vs2015安装文件夹**..\Program Files\Microsoft Visual Studio 14.0\VC\include**里.

4)大功告成了,以后建立 vs 项目使就有 Wtl 向导了,当然使用 Win32 工程也能从零建一个 Wtl 程序.