# !!!! WORK IN PROGRESS !!!
# Baidu.Android.PushService

Xamarin.Android Bindings for Baidu Push Notification Service

[![NuGet](https://img.shields.io/nuget/vpre/Baidu.Android.PushService.svg?label=NuGet)](https://www.nuget.org/packages/Baidu.Android.PushService)

## Introduction

[Baidu cloud push](http://push.baidu.com/) is a Chinese cloud service that you can use to send push notifications to mobile devices.

As Google Play and FCM (Firebase Cloud Messaging) are not available in China, it is necessary to use different app stores and push services. Baidu is one of them, and currently used by [Azure Notification Hub](https://azure.microsoft.com/en-us/services/notification-hubs/) & [Amazon Simple Notification Service](https://aws.amazon.com/sns/).

## Notes

As of 23 Feb 2019

* It will only work if we have it as part of the project.
* Doesn't work if pull from nuget directly. It will complain of missing libpush_*.so
* Working
 * Google emulator (Pie/API 28)
* Not working
 * Google emulator (Oreo/API 26)
 * Samsung S8 (Oreo/API 26)
