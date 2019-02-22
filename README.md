# Baidu.Android.PushService

**WORK IN PROGRESS**

Xamarin.Android Bindings for Baidu Push Notification Service

[![NuGet](https://img.shields.io/nuget/vpre/Baidu.Android.PushService.svg?label=NuGet)](https://www.nuget.org/packages/Baidu.Android.PushService)

## Introduction

Baidu cloud push is a Chinese cloud service that you can use to send push notifications to mobile devices.

As Google Play and FCM (Firebase Cloud Messaging) are not available in China, it is necessary to use different app stores and push services. Baidu is one of them, and currently used by Azure Notification Hub &Amazon Simple Notification Service.

## Tested OS/Device

As of 22 Feb 2019

* Marshmallow - API 23
  * :x: Google emulator
* Oreo - API 26
  * :white_check_mark: Google emulator
  * :white_check_mark: Samsung Galaxy S8
* Pie - API 27
  * :white_check_mark: Google emulator
  * :x: Huawei Mate 10
