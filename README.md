日本AV元数据抓取工具  
========================
**关于本软件**

目前，我下的AV越来越多，也意味着AV要集中地管理，形成媒体库。现在有两款主流的AV元数据获取器，"EverAver"和"Javhelper"。前者的优点是元数据获取比较全，缺点是不能批量处理；后者优点是可以批量处理，但是元数据不够全。

为此，我写出了本软件，为了方便的管理本地AV，和更好的手冲体验。

**如何使用**
1. 请安装requests,pyquery,lxml,Beautifulsoup,pillow模块,可在CMD逐条输入以下命令安装
  `pip install requests`
  `pip install pyquery`
  `pip install lxml`
  `pip install beautifulsoup4`
  `pip install pillow`
2. 你的AV在被软件管理前最好命名为番号:**COSQ-004.mp4**
文件名中间要有减号"-"，没有多余元数据只有番号为最佳，可以让软件更好获取元数据

![](readme1.PNG)

3. 把软件拷贝到AV的所在目录下，运行程序（中国大陆用户必须挂VPN，Shsadowsocks开全局代理）
4. 运行AV_Data_capture.exe 如果使用源码请运行py文件
5. 软件会自动把元数据获取成功的电影移动到JAV_output文件夹中，根据女优分类，失败的电影移动到failed文件夹中。
6. ！！下载kodi管理器，把Jav_output导入到kodi，好好享受吧，骚年。

![](readme2.PNG)
![](readme3.PNG)
![](readme4.PNG)
  