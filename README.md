# 花卉识别微信小程序(flowers Identify WechatProgram)
## 本项目是一款实用的AI智能识物小程序，基于ResNet50模型并结合Paddle.js将模型部署在微信小程序中，可以通过拍照或上传本地图像进行智能识别花卉，支持识别共102类花卉。
*小程序代码中itemMap.js文件的识别标签不全

### 运行项目步骤：
#### 1.下载模型文件压缩包102flowersModel.zip
#### 2.使用python -m http.server 3300命令将模型挂载到3300端口(也可以是其他空端口)
#### 3.进入127.0.0.1:3300地址检查是否已经挂载
#### 4.下载代码压缩包flowerIdentifyWechatProgram.zip
#### 5.打开微信开发者工具导入代码
#### 6.点击操作界面按钮即可进行识别
