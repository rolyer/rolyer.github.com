---
layout: post
title: ��Windows�´React Native Android��������
categories: [general, Android]
tags: [React Native, Android]
description: ���Ľ����������Windows�´React Native Android��������
comments: true
---

# ��װJDK

��[Java����֮JDK�����б�](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)����JDK����װ����ע��ѡ��x86����x64�汾����JDK��binĿ¼���뵽��ϵͳPATH����������ע�⣺�������Ӳ���ֱ��ʹ�ã���Ҫ�Ƚ���Э�飨�����д���cookies��������ͨ��[Java����֮JDK�����б�](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)����JDK��

���û�������PATH��jdk��λ�á����磺��PATH => C:\Program Files\Java\jdk1.8.0_11��

# ��װAndroid SDK

������װAndroid SDK����ǽ�Ļ����£�Ϊ���ٶ���ѡ����ʹ��[AndroidDevTools](http://androiddevtools.cn/)��

���û�������ANDROID_HOME��Android SDK Manager��λ�� ���磺��PATH => C:\Program Files\Android SDK Tools��

���û�������PATH�����磺��PATH => %ANDROID_HOME%\tools;%ANDROID_HOME%\platform-tools��

# ��װReact-native-cli

{% highlight bash %}
npm install -g react-native-cli
{% endhighlight bash %}

# ��ʼ����Ŀ

{% highlight bash %}
react-native init reactNative
{% endhighlight bash %}
> ���
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
