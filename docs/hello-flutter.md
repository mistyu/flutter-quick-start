# 初识 Flutter
> 一款多端构建的 UI 框架，目前主要用于移动端（Android, IOS）

他是基于图像渲染引擎去直接绘制UI

## [Flutter 架构](https://juejin.cn/post/6890951845729009671?searchId=202309200141079EC4185B0D2FB9450474)
![Flutter](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/6f2c698b00734ac7ae0e9647e4636560~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

从结构上看，Flutter 主要分为三个层次：

* Dart 框架层（Framework）
上层框架，主要包括 dart 侧 Widget 管理、绘制、动画、手势等接口

* C++ 引擎层（Engine）
虚拟机、线程模型、与平台的通信、绘制流程、系统事件、文字布局、帧渲染管线等

* 平台相关的嵌入层（Embeder）
渲染图层、平台线程和事件循环管理，Native Plugin 等
