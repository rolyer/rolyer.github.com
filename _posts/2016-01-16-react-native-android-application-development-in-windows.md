---
layout: post
title: 在Windows下搭建React Native Android开发环境
categories: [general, Android]
tags: [React Native, Android]
description: 本文将讲述如何在Windows下搭建React Native Android开发环境
comments: true
---

# 安装JDK

从[Java官网之JDK下载列表](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)下载JDK并安装。请注意选择x86还是x64版本。将JDK的bin目录加入到了系统PATH环境变量。注意：下载链接不能直接使用，需要先接受协议（这里有存入cookies），可以通过[Java官网之JDK下载列表](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)下载JDK。

设置环境变量PATH：jdk的位置。例如：（PATH => C:\Program Files\Java\jdk1.8.0_11）

# 安装Android SDK

单独安装Android SDK，在墙的环境下，为了速度我选择了使用[AndroidDevTools](http://androiddevtools.cn/)。

设置环境变量ANDROID_HOME：Android SDK Manager的位置 例如：（PATH => C:\Program Files\Android SDK Tools）

设置环境变量PATH：例如：（PATH => %ANDROID_HOME%\tools;%ANDROID_HOME%\platform-tools）

# 安装React-native-cli

{% highlight bash %}
npm install -g react-native-cli
{% endhighlight bash %}

# 初始化项目

{% highlight bash %}
react-native init reactNative
{% endhighlight bash %}
> 输出
{% highlight bash %}
This will walk you through creating a new React Native project in C:\dev\react
Installing react-native package from npm...
Setting up new React Native app in C:\dev\react
To run your app on iOS:
   Open C:\dev\react\ios\react.xcodeproj in Xcode
   Hit the Run button
To run your app on Android:
   Have an Android emulator running (quickest way to get started), or a device connected
   cd C:\dev\react
   react-native run-android
{% endhighlight bash %}
