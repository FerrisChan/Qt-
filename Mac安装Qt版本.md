# mac 安装qt的简单笔记

因为最近学习的是桌面开发，主要是v对mfc，win32+duilib，mfc 实现有点扭曲，一堆宏定义绕来绕去的，对于消息响应有点懵逼；

所以打算打算看一下跨平台的qt是如何实现的v

记录一下安装的坑

环境是mac10.13.4 ，需要安装xcode并且跑过一次程序；
这里qt 指的是qmake 和 qt creater，Ubuntu 下apt-get install qt 就可以了

mac 安装qt的几个方法基本是：

- brew 安装(不推荐，坑贼多)

   * 安装qmake 版本和 qtcreater，根据这个教程（https://web.stanford.edu/class/archive/cs/cs106b/cs106b.1164/handouts/qt-creator-mac.html）
   * qt版本需要安装 5.5
  brew install qt@5.5；
  不要安装最新版，brew install qt


- 直接下载qt对应的dmg安装(https://download.qt.io/official_releases/qt/5.8/5.8.0/)
  - 选择自己的需要的版本就可以了，我选择的是5.8
 

 qt笔记比较好的网站是这个
 https://www.devbean.net/2012/08/qt-study-road-2-catelog/