# 后台管理的前端

##### 1. 前言

这是后台管理的前端部分

##### 2. 修改一些配置

需要根据你的实际情况修改一些配置。图片看不了请复制下面给的https链接到浏览器查看

![image-20200111160035731](https://leyou-oss-quark.oss-cn-shenzhen.aliyuncs.com/image-20200111160035731.png)

https://leyou-oss-quark.oss-cn-shenzhen.aliyuncs.com/image-20200111160035731.png

##### 3. 运行打包

当前目录下的cmd运行以下命令

``` bash
# install dependencies
npm install

npm run build

```

然后把dist文件夹下的index.html和static文件夹上传到服务器nginx的html文件夹下。我用的是SmarTTY SSH客户端。注意不要传错了位置。

![image-20200111161004193.png](https://leyou-oss-quark.oss-cn-shenzhen.aliyuncs.com/image-20200111161004193.png)

https://leyou-oss-quark.oss-cn-shenzhen.aliyuncs.com/image-20200111161004193.png

![image-20200111161222548.png](https://leyou-oss-quark.oss-cn-shenzhen.aliyuncs.com/image-20200111161222548.png)

https://leyou-oss-quark.oss-cn-shenzhen.aliyuncs.com/image-20200111161222548.png

##### 4. 访问后台管理

浏览器访问 http://106.52.114.205 ，自动跳转到登录页面。注意，这个登录页面只是装饰的，密码对或不对都会跳转进去。一开始设置的时候，后台经常不稳定，即使密码都对了，都不一定跳转，所以这里一律设置点击登录后直接进入后台。



![image-20200111161621982.png](https://leyou-oss-quark.oss-cn-shenzhen.aliyuncs.com/image-20200111161621982.png)

各项功能测试，基本都正常

![image-20200111162057349.png](https://leyou-oss-quark.oss-cn-shenzhen.aliyuncs.com/image-20200111162057349.png)
