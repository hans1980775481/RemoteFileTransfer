# RemoteFileTransfer
远程文件传输程序，以知网为例  

## 原理  
  1. **服务端**运行在校园网环境，**客户端**为用户使用。双方建立连接后，客户端上报知网文章URL，服务端获取文章后，即可下发到客户端。  
  2. 目前只获取pdf格式，若知网页面不提供pdf下载，则无法获取。  
  3. 引入排队下载机制，当有多个用户同时请求下载时，将按照先进先出的原则依次运行。  
  4. 同时使用sqlite3数据库对用户进行管理。  


.  
.  
.  
* 演示视频如下
  http://ncurobot.club/Share/
  
* 体验链接：https://pan.baidu.com/s/1f6XY7dNNdX0ZH-OIMDMVpQ   提取码：lfku 
  
  
