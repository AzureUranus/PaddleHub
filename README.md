# PaddleHub


[![Build Status](https://travis-ci.org/PaddlePaddle/PaddleHub.svg?branch=develop)](https://travis-ci.org/PaddlePaddle/PaddleHub)
[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](LICENSE)

PaddleHub是基于PaddlePaddle框架开发的预训练模型管理工具，可以借助预训练模型更便捷的完成迁移学习工作。

## 特性

通过PaddleHub，您可以：

1. 通过hub download命令，快速地获取PaddlePaddle生态下的所有预训练模型；
2. 使用PaddleHub Finetune API对通过少量代码完成迁移学习；
3. 通过hub run命令或者Python编程的方式，快速使用预训练模型进行预测；

除此之外，我们还提供了预训练模型的本地管理机制（类似于pip），用户可以通过命令行来管理本地的预训练模型
![图片](https://paddlehub.bj.bcebos.com/resources/cmd_demo.JPG)

想了解PaddleHub已经发布的模型，请查看[模型列表](https://github.com/PaddlePaddle/PaddleHub/tree/develop/docs/released_module_list.md)

## 安装
Paddle Hub可直接通过pip进行安装（python3+），请使用如下命令来安装Paddle Hub

```
pip install paddlehub
```

## 快速体验
通过下面的命令，来体验下paddle hub的魅力
```
#使用lac进行分词
hub run lac --input_text "今天是个好日子"
#使用senta进行情感分析
hub run senta --input_text "今天是个好日子"
```

## 深入了解Paddle Hub
* [命令行功能](https://github.com/PaddlePaddle/PaddleHub/tree/develop/docs/command_line_introduction.md)
* [Transfer Learning](https://github.com/PaddlePaddle/PaddleHub/tree/develop/docs/transfer_learning_turtorial.md)
* API

## 答疑

欢迎您将问题和bug报告以[Github Issues](https://github.com/PaddlePaddle/PaddleHub/issues)的形式提交

## 版权和许可证
PaddleHub由[Apache-2.0 license](LICENSE)提供
