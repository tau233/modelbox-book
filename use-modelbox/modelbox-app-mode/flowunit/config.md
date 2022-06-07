# 配置类功能单元

本章节介绍推配置类功能单元的开发流程。在AI应用开发时，存在较多处理过程完全一样，但输入参数存在差异的处理，如yolo检测的后处理。为了减少开发者开发工作，Modelbox提供了配置类功能单元，完成特定功能。用户只需填写配置文件即可完成功能单元开发。下面以yolo功能单元为例介绍配置类功能单元开发流程。

## 创建配置类功能单元

Modelbox提供了多种方式进行功能单元的创建，以yolo为例:

* 通过UI创建
  
  xxx

* 通过命令行创建

ModelBox提供了模板创建工具，可以通过**ModelBox Tool**工具产生python功能单元的模板，具体的命令为

```shell
modelbox-tool template -flowunit -lang python -name [name]  
```

创建完成的C++功能单元目录结构如下：

```shell
[flowunit-name]
     |---CMakeList.txt           # 用于CPACK 打包 
     |---[flowunit-name].toml    # 功能单元属性配置文件
```

## 配置功能单元属性

每种配置类功能单元是完成特定功能，所以他们的配置参数各不相同，具体参数配置可参考预置功能单元中[配置类](../../../flowunits/flowunits-virtual.md)章节。

## 打包运行

配置内功能单元只需要配置文
