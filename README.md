# GSoC-DroidBOT
DroidBot Google Summer of Code 2016 HoneyNet Project
*****************************************************
Table of content
================

1. **Abstract** 
2. **
3. ****
4. **
5. **About me**
6. 

1. Abstract
===========
Android users are free to download and install 3rd party applications. The rapid development of smart terminal also brings a variety of malicious software, mobile Internet is also facing a growing number of security issues. Android has more than 60% of the market share and it is in the initial stage. The mobile phone security industry analysis reports in year 2012, that they have found 26850 of malware infections on Android. Stealing confidential information (i.e IMEI numbers, mobile numbers or Contact details) and send SMS messages without user permission are the most damaging attacks done by the malware in the past. Now it is not like that, the smart terminals perform the same functionality like computers. Data transmission, online shopping using credit cards are few examples, today we perform using smart terminals. Therefore the cost of the vulnerability is very high than the past couple of years. Android device shipments are expected to top 1 billion this year and there are currently more than 1.100.000 apps available in the Play Store, which generated 50 billion downloads in 2013 alone, therefore, it is reasonable to assume that there is plenty of potential malware and other security threats designed to take advantage of careless Android users. Considering cost, there is a huge requirement to protect Android system from the malware infection. 
In 2016, one of the [HoneyNet](https://honeynet.org) project proposal is 
[DroidBot] (https://honeynet.org/node/1317) to enhace it's features to identifying malware by statistically as well as dynamically analysing the mobile apps. [DroidBot](https://honeynet.org/node/1317) uses 
[DroidBox] (http://www.honeynet.org/project/droidbox) to works like a robot interacting with the target app and tries to trigger as many malicious behaviors as possible. (This is more over to dynamic analysis).
[DroidBox] (http://www.honeynet.org/project/droidbox) is built in Dalvik Runtime environment and currently it become obsolete since there is a new Android [ART](https://en.wikipedia.org/wiki/Android_Runtime) is in the market. With Android 4.4, a new Android runtime, [ART](https://en.wikipedia.org/wiki/Android_Runtime). This runtime offers a number of new features that improve performance and smoothness of the Android platform and apps. Currently, [ART](https://en.wikipedia.org/wiki/Android_Runtime) is available on a number of Android 4.4 devices, such as the Nexus 4, Nexus 5, Nexus 7, and Google Play edition devices. At this time, all devices still use Dalvik as the default runtime. Android runtime ([ART](https://en.wikipedia.org/wiki/Android_Runtime)) is the managed runtime used by applications and some system services on Android. [ART](https://en.wikipedia.org/wiki/Android_Runtime) and its predecessor Dalvik were originally created specifically for the Android project. [ART](https://en.wikipedia.org/wiki/Android_Runtime) as the runtime executes the Dalvik Executable format and Dex bytecode specification. [ART](https://en.wikipedia.org/wiki/Android_Runtime) and Dalvik are compatible runtimes running Dex bytecode, so apps developed for Dalvik should work when running with [ART](https://en.wikipedia.org/wiki/Android_Runtime). However, some techniques that work on Dalvik do not work on [ART](https://en.wikipedia.org/wiki/Android_Runtime).

1.2 Goals
---------
DroidBox is developed to offer dynamic analysis of Android applications. Already developed open source project has to work on new Android ART (Android Runtime). The goal of this project is to build a dynamic malware analysis system on ART, which allows users to monitor the execution of potentially malicious apps. This includes the following sub-goals:

 + Monitoring function calls
 + Modifying parameters/return value before/after function's execution
 + Dumping objects' contents
 + Reporting layer that is compatible with existing systems
