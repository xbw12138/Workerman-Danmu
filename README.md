workerman-danmu
=======
基于workerman的GatewayWorker框架开发的一款高性能支持分布式部署的弹幕系统。

GatewayWorker框架文档：http://www.workerman.net/gatewaydoc/

 特性
======
 * 使用websocket协议
 * 多浏览器支持（浏览器支持html5或者flash任意一种即可）
 * 掉线自动重连
 * 支持多服务器部署
 * 业务逻辑全部在一个文件中，快速入门可以参考这个文件[Applications/Danmu/Event.php](https://github.com/xbw12138/Workerman-Danmu/blob/master/Applications/Danmu/Events.php)   
  
下载安装
=====
1、git clone https://github.com/xbw12138/Workerman-Danmu

2、composer install

启动停止(Linux系统)
=====
以debug方式启动  
```php start.php start  ```

以daemon方式启动  
```php start.php start -d ```

测试
=======
浏览器访问 http://服务器ip或域:55151,例如http://127.0.0.1:55151

![image](https://github.com/xbw12138/Workerman-Danmu/blob/master/shortscreen.png)
