oC-DroidBOT
DroidBot Google Summer of Code 2016 HoneyNet Project
*****************************************************
Table of content
================
1. **Abstract**
2. **Schedule and milestones**
3. **About me** 

1. Abstract
===========
Android users are free to download and install 3rd party applications. The rapid development of smart terminal also brings a variety of malicious software, mobile Internet is also facing a growing number of security issues. Android has more than 60% of the market share and it is in the initial stage. The mobile phone security industry analysis reports in year 2012, that they have found 26850 of malware infections on Android. Stealing confidential information (i.e IMEI numbers, mobile numbers or Contact details) and send SMS messages without user permission are the most damaging attacks done by the malware in the past. Now it is not like that, the smart terminals perform the same functionality like computers. Data transmission, online shopping using credit cards are few examples, today we perform using smart terminals. Therefore the cost of the vulnerability is very high than the past couple of years. Android device shipments are expected to top 1 billion this year and there are currently more than 1.100.000 apps available in the Play Store, which generated 50 billion downloads in 2013 alone, therefore, it is reasonable to assume that there is plenty of potential malware and other security threats designed to take advantage of careless Android users. Considering cost, there is a huge requirement to protect Android system from the malware infection. 
In 2016, one of the [HoneyNet](https://honeynet.org) project proposal is 
[DroidBot] (https://honeynet.org/node/1317) to enhace it's features to identifying malware by statistically as well as dynamically analysing the mobile apps. [DroidBot](https://honeynet.org/node/1317) uses 
[DroidBox] (http://www.honeynet.org/project/droidbox) to works like a robot interacting with the target app and tries to trigger as many malicious behaviors as possible. (This is more over to dynamic analysis).
[DroidBox] (http://www.honeynet.org/project/droidbox) is built in Dalvik Runtime environment and currently it become obsolete since there is a new Android [ART](https://en.wikipedia.org/wiki/Android_Runtime) is in the market. With Android 4.4, a new Android runtime, [ART](https://en.wikipedia.org/wiki/Android_Runtime). This runtime offers a number of new features that improve performance and smoothness of the Android platform and apps. Currently, [ART](https://en.wikipedia.org/wiki/Android_Runtime) is available on a number of Android 4.4 devices, such as the Nexus 4, Nexus 5, Nexus 7, and Google Play edition devices. At this time, all devices still use Dalvik as the default runtime. Android runtime ([ART](https://en.wikipedia.org/wiki/Android_Runtime)) is the managed runtime used by applications and some system services on Android. [ART](https://en.wikipedia.org/wiki/Android_Runtime) and its predecessor Dalvik were originally created specifically for the Android project. [ART](https://en.wikipedia.org/wiki/Android_Runtime) as the runtime executes the Dalvik Executable format and Dex bytecode specification. [ART](https://en.wikipedia.org/wiki/Android_Runtime) and Dalvik are compatible runtimes running Dex bytecode, so apps developed for Dalvik should work when running with [ART](https://en.wikipedia.org/wiki/Android_Runtime). However, some techniques that work on Dalvik do not work on [ART](https://en.wikipedia.org/wiki/Android_Runtime).

1.2 Goals
---------
[DroidBot] (https://honeynet.org/node/1317) is developed to offer dynamic analysis and static analysis of Android applications. It uses Droitbox for dynamic analysis. Since [DroidBox] (http://www.honeynet.org/project/droidbox) is not compatible with [ART](https://en.wikipedia.org/wiki/Android_Runtime), the goal of this project is to enhance the [DroidBot] (https://honeynet.org/node/1317) features and enabling the [DroidBox] (http://www.honeynet.org/project/droidbox) to work on [ART](https://en.wikipedia.org/wiki/Android_Runtime). This includes the following sub-goals:

 + Monitoring function calls
 + Modifying parameters/return value before/after function's execution
 + Dumping objects' contents
 + Reporting layer that is compatible with existing systems
 
2. Schedule and milestones
==========================
+ I'm new to Android application development, therefore need to fulfil the knowlege gap, Therefore I will following the [Udaciy Android Development CoursSetup environment] (https://www.udacity.com/course/viewer#!/c-ud853) for 1st month (Jan 2016).
+ The second milestone is to setup Android and Drodbot application and Analysing the features of existing project. This will take another 1 month (Feb 2016)
1. Setup environment - 1 week (legend : medium)
2. Identifying existing features (working on obsolete Dalvik system) - 2 weeks (legend : medium)
3. Create Test Cases and Test Plan -1 week (legend : medium)
4. Test Execution  - 1 week (legend : medium)
+ Then I will work with the Coding and start work with the Development. The Development effort will be approximately 3 months starting from March 2016.
1. Upgrade runtime environment to ART - 2 week (legend : medium)
2. Compiling and fixing compilation errors on ART - 4 weeks (legend : hard)
3. Execute Test Cases and identifying issues - 2 weeks (legend : medium)
4. Fixing broken features - 4 weeks (legend : hard)
+ Finally preparing the project report will take another 1 month approximately.
1. Preparing Draf 3 weeks (legend : medium)
2. Proof Reading 1 week

3. About me
============
I am work as QA tech lead working for a reputed international company, and having more than 10 years industrial experience. Having Java development skills when automating the test scripts is my strong point. Currently following Cyber Security MSC course in [SLITT](http://www.sliit.lk/) university. This is my final year of the MSC and I already submitted my proposal to campus and have started working on the this project.

Professional Qualifications
===========================
Linkedin profile [here](http://lk.linkedin.com/in/rukmalhewawasam)

Master of Science (MSc), Specializing in Cyber Security

Successfully Completed Udacity [Course introuduction to Computer Science building a search engine using Python](https://github.com/rukmalhe/GSoC-DroidBOT/blob/master/certificate.pdf)

Professional Graduate Diploma in IT, [British Computer Society](https://www.bcs.org/)

Skills
======
Java, Test Automation, Oracle, Python,

Projects
========
1st year research project - A GUI for the Volatility Framework
