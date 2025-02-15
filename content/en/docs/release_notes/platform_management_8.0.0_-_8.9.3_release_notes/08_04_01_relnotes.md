---
title: Platform Management 8.4.1 release notes
linkTitle: Platform Management 8.4.1 release notes
description: New features, improvements, and bug fixes for the release.
weight: 210
date: 2021-08-12
Hide_readingtime: true
---

## Platform Management 8.4.1 - 5 February 2021

Platform Management 8.4.1 is a patch release, which includes new features, improvements, and bug fixes.

## New features

* Organizations using their company's Identity Provider to authenticate to **Amplify Platform** can now select the default roles and teams to which members are assigned when initially signing in. User attributes from their Identity Provider can also be used to manage assigned roles and teams. See the [Identity Provider Configuration documentation](https://docs.axway.com/csh?context=62555476) for more information.

## Improvements

* Added an option to the organization _Usage_ view to show usage for all environments or production environments only.
* Updated organization _Usage_ view to no longer show entitlements for which the organization has no quota or usage.
* Updated the _Usage Report History_ view to show the user who performed usage upload or manual entry and includes entries for both Axway-managed and customer-managed environments.

## Fixed issues

* Fixed an issue where **Amplify Crash Analytics** views permitted selection of a date range more than the allowed 30 day retention for crash events.
* Fixed an issue where organizations with one or more available VPC environments may not be able to deselect environments during **Mobile Backend Services** app creation.
* Fixed an issue on the _Usage Report History_ view where filtering report history by selected date range may not function as expected.
* Fixed an issue where the **Mobile Backend Services** Friends object type form view may not render properly.
