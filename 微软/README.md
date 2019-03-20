# Windows微软电脑设备SS/ShadowsocksR使用教程

<hr>

前言：需要安装 .NET Framework 4.6.2 和 Microsoft Visual C++ 2015 Redistributable (x86)（一般电脑已经安装，不需要再次安装）。

## 第一步，下载用于Windows设备的Shadowsocks-Windows软件

点击此处下载任意一个软件压缩包，下载后解压至任意目录

1、[Shadowsocks-4.0.10点击下载](https://github.com/shadowsocks/shadowsocks-windows/releases/download/4.0.10/Shadowsocks-4.0.10.zip)  【若高版本有问题，可试试此版本下载。】

2、下载【shadowsocks-windows】软件 [微软点击下载](https://raw.githubusercontent.com/ss-ssr/download/master/shadowsocks-windows.zip)

3、[Shadowsocks-4.1.3点击下载](https://github.com/shadowsocks/shadowsocks-windows/releases/download/4.1.3/Shadowsocks-4.1.3.zip)

4、[Shadowsocks-4.1.4点击下载](https://github.com/shadowsocks/shadowsocks-windows/releases/download/4.1.4/Shadowsocks-4.1.4.zip)

5、[Shadowsocks-3.2点击下载](https://github.com/shadowsocks/shadowsocks-windows/releases/download/3.2/Shadowsocks-3.2.zip)  【XP系统，请下载此版本】

## 第二步，打开程序文件SHADOWSOCKS.EXE，鼠标右键单击配置节点信息

![](https://raw.githubusercontent.com/ss-ssr/Help/master/%E7%85%A7%E7%89%87/w1.png)

下载后解压文件，打开EXE文件，右键单击左下角的飞机图标进行配置

![](https://raw.githubusercontent.com/ss-ssr/Help/master/%E7%85%A7%E7%89%87/w2.png)

目前主要有三种配置节点信息的方法，可以根据你的习惯和需要选择

1、从剪切板导入URL【推荐】每次复制SS链接，点击从剪切板导入URL即可配置服务器

2、扫二维码配置【推荐】	通过扫描屏幕上的二维码，自动配置，推荐

3、手动编辑服务器配置	添加服务器，并逐一配置相关节点信息

### 方法一，从剪切板导入URL 【推荐】

首先复制SS地址

![](https://raw.githubusercontent.com/ss-ssr/Help/master/%E7%85%A7%E7%89%87/w10.jpg)

然后右键单击右下角的软件，点击“服务器”－“从剪切板导入URL”

![](https://raw.githubusercontent.com/ss-ssr/Help/master/%E7%85%A7%E7%89%87/w11.jpg)

### 方法二，扫二维码配置

首先网页上或者是聊天窗口打开节点的二维码图片

然后右键单击右下角的软件，点击“服务器”－“扫描屏幕上的二维码”

程序自动识别二维码并导入服务器节点信息

最后启用系统代理即可使用

![](https://raw.githubusercontent.com/ss-ssr/Help/master/%E7%85%A7%E7%89%87/w3.png)

### 方法三，手动编辑服务器配置

右键单击右下角的软件，点击“服务器”－“编辑服务器”

## 最后

若有一些网站你打不开，这个试试你可以试试全局模式。但也可能需要更新PAC文件，或者你可以编辑本地pac文件。

![](https://raw.githubusercontent.com/ss-ssr/Help/master/%E7%85%A7%E7%89%87/w12.jpg)

需要更新PAC：依次操作：PAC ->从GFW List更新PAC （等待更新完毕后）->使用本地PAC->启动系统代理

### 若提示.NET framework过低

则需要下载.NET framework软件[点击下载](https://www.microsoft.com/zh-CN/download/details.aspx?id=53344)，重新打开运行即可。

完成，可打开游览器访问网站google.com进行测试

