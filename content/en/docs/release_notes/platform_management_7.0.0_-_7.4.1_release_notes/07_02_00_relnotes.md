---
title: Platform Management 7.2.0 release notes
linkTitle: Platform Management 7.2.0 release notes
description: New features, improvements, and bug fixes for the release.
weight: 14
date: 2021-08-12
Hide_readingtime: true
---

## Platform Management 7.2.0 - 26 November 2019

Platform Management 7.2.0 is a minor release, which includes an improvement and a bug fix.

As of the 7.2.0 release, the Appcelerator Performance Management (APM) module and integration with Apteligent Crittercism are now discontinued.

Applications previously using the APM module may transition to use the Amplify Crash Analytics (ACA) module available from [https://platform.axway.com/#/download](https://platform.axway.com/#/download). For more details, please refer to the [Amplify Crash Analytics](https://docs.axway.com/bundle/Amplify_Appcelerator_Services_allOS_en/page/amplify_crash_analytics.html) documentation.

Attempts to build applications with the `com.appcelerator.apm` module will receive an error message regarding its discontinuation.

## Improvement

* Updated role select list on organization _Members_ and _Teams_ views to indicate the services to which roles are associated.

## Fixed issue

* Resolved issue where counts on _Unique Devices_ analytics views may have been incorrectly calculated.
