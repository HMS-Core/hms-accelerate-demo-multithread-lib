# 华为计算加速服务示例代码

## 目录

 * [简介](#简介)
 * [开发准备](#开发准备)
 * [环境要求](#环境要求)
 * [技术支持](#技术支持)
 * [授权许可](#授权许可)


## 简介
本示例代码介绍华为计算加速服务（HUAWEI Accelerate Kit）SDK的使用方法，包括创建队列、提交任务到队列、释放队列等。
    
主要示例接口：
1. 创建队列
dispatch_queue_create(): 创建队列。
2. 提交任务到队列
dispatch_async(): 提交任务到队列，并立即返回。 
dispatch_barrier_sync(): 提交一个barrier任务到队列，barrier任务完成后返回。前面的任务完成后，才会开始执行barrier任务（及在它之后提交的任务）。
3. 释放队列
dispatch_release(): 释放队列。

## 开发准备
1.	在Android Studio（3.0及以上版本）中打开示例代码工程。
2.	从[SDK下载](https://developer.huawei.com/consumer/cn/doc/development/HMSCore-Library-V5/sdk-download-0000001051060752-V5)获取SDK包。
3.	复制头文件和.so库到工程中。具体操作请参见[复制库和头文件](https://developer.huawei.com/consumer/cn/doc/development/HMSCore-Guides-V5/integrating-sdk-0000001050166844-V5)。
4.	在Android设备或虚拟机上编译运行demo。

## 环境要求
推荐使用Android 5.0及以上版本的设备。

## 技术支持
如果您对HMS Core还处于评估阶段，可在[Reddit社区](https://www.reddit.com/r/HuaweiDevelopers/)获取关于HMS Core的最新讯息，并与其他开发者交流见解。

如果您对使用HMS示例代码有疑问，请尝试：
- 开发过程遇到问题上[Stack Overflow](https://stackoverflow.com/questions/tagged/huawei-mobile-services)，在`huawei-mobile-services`标签下提问，有华为研发专家在线一对一解决您的问题。
- 到[华为开发者论坛](https://developer.huawei.com/consumer/cn/forum/blockdisplay?fid=18) HMS Core板块与其他开发者进行交流。

如果您在尝试示例代码中遇到问题，请向仓库提交[issue](https://github.com/HMS-Core/hms-accelerate-demo-multithread-lib/issues)，也欢迎您提交[Pull Request](https://github.com/HMS-Core/hms-accelerate-demo-multithread-lib/pulls)。

## 授权许可
计算加速服务示例代码已获得[Apache 2.0 license.](http://www.apache.org/licenses/LICENSE-2.0)授权许可。
