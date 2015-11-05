# tencentyun-cos-js-sdk
js sdk for [腾讯云对象存储服务](http://wiki.qcloud.com/wiki/COS%E4%BA%A7%E5%93%81%E4%BB%8B%E7%BB%8D)

##前期准备
SDK需要浏览器支持HTML 5。<br>
SDK需要浏览器支持Flash。<br>
获取项目ID(appid)，bucket，secret_id和secret_key。

## 安装（直接下载源码集成）

### 直接下载源码集成
从github下载源码，将SDK中sdk文件夹包含到您的项目中。

## 加载相关文件
在您使用SDK之前，加载相关支持的Javascript文件即可。<br>
&lt;script type="text/javascript" src="sdk/jquery1x.min.js"&gt;&lt;/script&gt;<br>
&lt;script type="text/javascript" src="sdk/qcloud_sdk.js"&gt;&lt;/script&gt;<br>
&lt;script type="text/javascript" src="sdk/swfobject.js"&gt;&lt;/script&gt;<br>
本SDK需要jQuery的支持，如果您的项目已经引入jQuery，那么可以省略jquery1x.min.js的引入。<br>
修改Sign.php中的APPID、SECRET_ID、SECRET_KEY，换成您相应的值。

## 上传、查询、删除程序示例
参见index.html内的调用实例。
