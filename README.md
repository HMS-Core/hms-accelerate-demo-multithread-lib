# HMS Accelerate Kit Demo


## Table of Contents

 * [Introduction](#introduction)
 * [Preparation](#preparation)
 * [Installation](#installation)
 * [Experience Different Functions](#function-use)
 * [Supported Environments](#supported-environments)
 * [Result](#result)
 * [License](#license)


## Introduction
The sample code describes how to use the HMS AccelerateKit SDK, including dispatch queues create, push work items into queues, release queues.
    
Main APIs in sample code:
1. Queues Create
dispatch_queue_create(): creates queues.
2. Push Work Items(blocks) into queues:
dispatch_async(): pushes work items into queue asynchronously.
dispatch_barrier_sync(): push work items into queue synchronously and make sure that all of work items, which has been pushed in the queue, should be finished.
3. Queues Release
dispatch_release(): releases queues.

## Preparation
### 1. Register as a developer.
Before you get started, you must register as a HUAWEI developer and complete identity verification on [HUAWEI Developers](https://developer.huawei.com/consumer/en/). For details, please refer to [Registration and Verification](https://developer.huawei.com/consumer/en/doc/start/10104).
### 2. Create an app and apply for a agconnect-services.json.
Create an app and set package type to APK (android app). Apply for the agconnect-services.json file on HUAWEI Developers. For details, please refer to [Adding the AppGallery Connect Configuration File].
See details: [HUAWEI Accelerate Development Preparation](hhttps://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides/introduction-0000001050980807)
### 3. Build
To build this sample, import the sample to Android Studio (3.x +), download agconnect-services.json from AppGallery Connect, and add the file to the app's root directory app of the demo app.

## Installation
Download the sample code and open it in Android Studio. Ensure that your device has been connected to the internet and obtain the APK by building a project.

## Function Use
You can tap buttons in your app to experience rich services of HUAWEI Accelerate Kit.

## Supported Environments
Devices with Android 7.0 or later are recommended.

## Result
After the four tasks are executed concurrently, the other four tasks are executed in serial mode.

## Question or issues
If you want to evaluate more about HMS Core, [r/HMSCore on Reddit](https://www.reddit.com/r/HMSCore/) is for you to keep up with latest news about HMS Core, and to exchange insights with other developers.

If you have questions about how to use HMS samples, try the following options:
- [Stack Overflow](https://stackoverflow.com/questions/tagged/huawei-mobile-services) is the best place for any programming questions. Be sure to tag your question with 
**huawei-mobile-services**.
- [Huawei Developer Forum](https://forums.developer.huawei.com/forumPortal/en/home?fid=0101187876626530001) HMS Core Module is great for general questions, or seeking recommendations and opinions.

If you run into a bug in our samples, please submit an [issue](https://github.com/HMS-Core/hms-accelerate-demo/issues) to the Repository. Even better you can submit a [Pull Request](https://github.com/HMS-Core/hms-accelerate-demo/pulls) with a fix.

## License
The sample of HUAWEI Accelerate Kit has obtained the [Apache 2.0 license.](http://www.apache.org/licenses/LICENSE-2.0).
