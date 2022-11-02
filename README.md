# 花卉识别微信小程序(Flowers Identify Wechat Program)
## 本项目是一款实用的AI智能识物小程序，基于ResNet50模型并结合Paddle.js将模型部署在微信小程序中，可以通过拍照或上传本地图像进行智能识别花卉，支持识别共102类花卉。
*小程序代码中itemMap.js文件的识别标签不全
#
### 运行项目步骤：
#### 1.下载模型文件压缩包102flowersModel.zip
#### 2.使用python -m http.server 3300命令将模型挂载到3300端口(也可以是其他空端口)
#### 3.进入127.0.0.1:3300地址检查是否已经挂载
#### 4.下载代码压缩包flowerIdentifyWechatProgram.zip
#### 5.打开微信开发者工具导入代码
#### 6.点击操作界面按钮即可进行识别
*identifyFlowers文件夹列出了一些可供识别的花卉，但结果不一定准确
#
#### 可替换模型：
##### 1.identifyItems1.zip
##### 该压缩包包含识物标签、模型地址和可供识别的图片
##### 识物标签可替换小程序代码中的itemMap.js文件内容；模型地址可替换identify/index.js里Paddle.js注册代码中的modelPath属性
*模型地址来自Paddle.js官方示例“寻物大作战”
#
##### 2.identifyItems2.zip
##### 该压缩包包含识物标签和模型文件
##### 识物标签可替换小程序代码中的itemMap.js文件内容；模型文件的挂载参考上述“运行项目步骤”
