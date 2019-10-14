---
layout : post
title : "Android 中NDK的使用详解第一篇:环境"
category : Android
duoshuo: true
date : 2014-10-28
tags : [AndroidNDK , NDK , JNI]
SyntaxHihglighter: true
shTheme: shThemeMidnight # shThemeDefault  shThemeDjango  shThemeEclipse  shThemeEmacs  shThemeFadeToGrey  shThemeMidnight  shThemeRDark
---

<style>
h3 {
    line-height: 1;
    letter-spacing: 2px;
    margin-top: 5px;
}
h6 {
    line-height: 1;
    letter-spacing: 2px;
    margin-top: 5px;
}
</style>

* ### 1.下载集成开发环境
* ### 2.安装配置环境
* ### 3.常用功能配置
	* ###### 3.1自动生成头文件(配置javah)
	* ###### 3.2生成Sign签名(配置Javap)
	* ###### 3.3配置C/C++库


#### 2.10. 打开Android SDK Manager下载SDK
	
> 如果速度慢可按照如下设置代理:

	Android SDK在线更新镜像服务器

	中国科学院开源协会镜像站地址:

	IPV4/IPV6: http://mirrors.opencas.cn 端口：80

	IPV4/IPV6: http://mirrors.opencas.org 端口：80

	IPV4/IPV6: http://mirrors.opencas.ac.cn 端口：80

	上海GDG镜像服务器地址:

	http://sdk.gdgshanghai.com 端口：8000

	北京化工大学镜像服务器地址:

	IPv4: http://ubuntu.buct.edu.cn/ 端口：80

	IPv4: http://ubuntu.buct.cn/ 端口：80

	IPv6: http://ubuntu.buct6.edu.cn/ 端口：80

	大连东软信息学院镜像服务器地址:

	http://mirrors.neusoft.edu.cn 端口：80

	使用方法：

	启动 Android SDK Manager ，打开主界面，依次选择『Tools』、『Options...』，
	弹出『Android SDK Manager - Settings』窗口；

	在『Android SDK Manager - Settings』窗口中，在『HTTP Proxy Server」和
	「HTTP Proxy Port』输入框内填入上面镜像服务器地址(不包含http:// )和端口，
	并且选中『Force https://... sources to be fetched using http://...』复选框。
	设置完成后单击『Close』按钮关闭『Android SDK Manager - Settings』窗口返回到主界面；

	依次选择『Packages』、『Reload』。

---



---

End
