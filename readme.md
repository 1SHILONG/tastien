# 塔斯汀小程序模仿项目

- 本项目归塔斯汀所有， 只做学习所用， 请尊重原厂版权

- fiddler 抓包工具抓取图片

- 界面模仿采用markman做标记
  1. 我们没有设计搞， 如何1:1 还原小程序？
  2. 拍屏得到小程序截图
  3. 使用在线大小[转换工具](https://www.gaitubao.com/)，讲图片改成750
    以后在写wxss的时候，直接量像素就可以写进去， 因为小程序以750rpx作为
    设计稿标准大小帮我们自动适配，很好用。
  4. 使用[markman](http://www.getmarkman.com/) 先标注，在写样式
    以后呢，上了班就不用了， 有设计师给你标好
    现在， 还是自己来LOL 吧

- 项目配置在根目录app.json
  - 隐藏并定制navigationBar
    "navigationStyle": "custom"
  - 启动定位功能
    
- 使用了BEM 国际css命名规范
  tst_banners  广告位 Block
  tst_banners__img  Element

- css 技巧
  1. 能不用定位就不要用定位
    脱离文档流
  2. 移动端多用弹性布局
    
- git 提交
  1. 第一次git 命令行
  全局配置 git config --global user.name
    
