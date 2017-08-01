# hosts
抛弃VPN使用host越过长城防火墙
## 前言 ##
> 最近国内VPN限制的严厉的多，一不小心就会被抓去签保证书，为了能和小伙伴联系，也为了能查到相关资讯，了解国内动态，关注权利的猎物老郭
> 特此写博，然而这一切都是免费的！免费的！免费的！（重要的事情讲三遍）

## 正文开始 ##

- 1.亲测可访问网站
更新最新Google、谷歌学术、维基百科、ccFox.info、ProjectH、Battle.NET 、WordPress、Microsoft Live、GitHub、Amazon、Archive、Box.com、Disqus、SoundCloud、inoreader、Feedly、FlipBoard、Twitter、Tumblr、Facebook、Flickr、imgur、Instagram、DuckDuckGo、Ixquick、Yahoo、Google Services、Google apis、Android
、Youtube、Google Drive、UpLoad、Appspot、Googl eusercontent、Gstatic、Gmail、Google other、Google Play等hosts。
- 2.感谢[老D博客](https://laod.cn/hosts/2017-google-hosts.html)提供的资源
- 3.hosts所在目录

 - Windows 系统hosts位于 C:\Windows\System32\drivers\etc\hosts
 - Android（安卓）系统hosts位于 /etc/hosts
 - Mac（苹果电脑）系统hosts位于 /etc/hosts
 - iPhone（iOS）系统hosts位于 /etc/hosts
 - Linux系统hosts位于 /etc/hosts
 - 绝大多数Unix系统都是在 /etc/hosts
 
## 修改hosts文件具体步骤
1. Windows环境
 开始 -> 运行 -> 输入cmd -> 在CMD窗口输入
 ``` 	
 ipconfig /flushdns
 ```
2. Linux终端输入
 ```
 sudo rcnscd restart
 ```
3. Mac OS X终端输入
 ```
 sudo killall -HUP mDNSResponder
 ```
4.Android
开启飞行模式 -> 关闭飞行模式
5.实在不行通用方法
拔网线(断网) -> 插网线(重新连接网络)
> 下载地址：[hosts](https：//github.com/xkloveme/hosts/archive/master.zip)
## 写在最后
请低调使用。
