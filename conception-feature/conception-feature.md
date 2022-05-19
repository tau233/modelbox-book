# 概念特性

## 基础概念

通过ModelBox开发应用时，开发者需要将应用程序的逻辑表达为流程图，应用功能被拆分为多个功能单元。采用这种方式的目的是：对数据流(如视频)处理可以利用多段流水线并行提供吞吐量；通用的功能单元可以复用；通用的流程图可以复用。  
使用流程图表达应用程序时，还需要关心的一点是数据的表示。在ModelBox中，定义功能单元端口之间传递的均是数据流，Buffer则是数据流中数据的承载者。  
阅读如下章节，以对ModelBox基础概念有更深入了解。

* [图](basic-conception/graph.md)
* [功能单元](basic-conception/flowunit.md)
* [数据流](basic-conception/stream.md)
* [Buffer](basic-conception/buffer.md)

## 高级特性

AI应用开发中，可能还会使用到如下特性，可按需进行相关内容的阅读。

* [多设备开发](advanced-features/device/device.md)
* [异常](advanced-features/exception.md)