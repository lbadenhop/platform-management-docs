---
title: Platform Management 7.4.0 release notes
linkTitle: Platform Management 7.4.0 release notes
description: New features, improvements, and bug fixes for the release.
weight: 2
date: 2021-08-12
Hide_readingtime: true
---

## Platform Management 7.4.0 \- 25 June 2020

Platform Management 7.4.0 is a minor release, which includes one new feature, one changed behavior, improvements, and several bug fixes.

## New features

* Added support for configuring a corporate Identity Provider for authenticating to Amplify Platform services and automatically provisioning members within their Platform organization. This feature is available to organizations with Enterprise subscriptions. See the [Configuring and Managing Identity Providers documentation](/docs/management_guide/configuring_and_managing_identity_providers) for more information.

## Changed Behavior

* Claimed Indie Seats for Application Development will now be shown with a subscription end date of Dec 31, 2099. Previously, no subscription end date was shown.

Improvements

* Members' names will now be shown in the confirmation dialog prior to removal from the organization from the _Members_ table view.
* Assigned Members' and Assigned Apps' names (if singular) or counts (if plural) will now be shown in a confirmation dialog prior to removal from a team.

Fixed issues

* Fixed an issue where the _All Apps_ table view may not have shown values in the Creator column.
* Fixed an issue where the Amplify Crash Analytics _Crash Details_ view may omit "tags" in crash stacks.
* Fixed an issue where an organization member's Platform role may not have displayed if no seats remained.
* Fixed an issue where the Password Last Updated date on the _Account Credentials_ view may not update when the password is changed.
* Fixed an issue where some Analytics view will not render properly when Demo Data is enabled.
* Fixed an issue where users may not be shown error messages when errors are encountered during device authorization.
