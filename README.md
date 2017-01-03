# WeChatSmallApp
微信小程序

[官方开发工具及文档](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/download.html?t=1474644089359)

后台管理:  
[微信公众平台](https://mp.weixin.qq.com)

开发资源:  
[微信小程序开发资源汇总](https://github.com/justjavac/awesome-wechat-weapp)



#### 删除项目部分文件后, Mac打开一直卡死, 卸载重装无法解决
原因:  
在微信web开发者工具上调试项目时，误删了该项目某个文件，导致缓存中一直会有这个错误导致编译不过。

解决办法:  
1.右键将“微信web开发者工具”  ---移到废纸篓  
2.删除以下几个配置和缓存文件

    ~/Library/Application Support/微信web开发者工具
    ~/Library/Preferences/com.tencent.wechat.devtools.plist
    ~/Library/Caches/微信web开发者工具
3.重新安装 “微信web开发者工具”  ，一直卡在加载项目界面的问题就解决了.
