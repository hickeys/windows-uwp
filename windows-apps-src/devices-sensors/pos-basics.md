﻿---
author: TerryWarwick
title: Getting started with Point of Service
description: This article contains information about getting started with the PointOfService UWP APIs.
ms.author: jken
ms.date: 06/13/2018
ms.topic: article
ms.prod: windows
ms.technology: uwp
keywords: windows 10, uwp, point of service, pos
ms.localizationpriority: medium
---

# Getting started with Point of Service

## PointOfService basics

This section contains topics that are common across all Point of Service device categories.

|Topic |Description |
|------|------------|
| [Capability declaration](pos-basics-capability.md)      | Learn how to add the **pointOfService** capability to your application manifest.  This capability is required for use of Windows.Devices.PointOfService namespace.  |
| [Enumerating devices](pos-basics-enumerating.md)        | Learn how to define a device selector that is used to query devices available to the system and use this selector to enumerate Point of Service devices.  |
| [Creating a device object](pos-basics-deviceobject.md)  | Learn how to create a PointOfService device object that will give you access to read-only properties of the peripheral and claim the peripheral for exclusive use. |
| [Claiming a device for exclusive use ](pos-basics-claim.md)  | Learn how to reserve a PointOfService peripheral for exclusive use with the PointOfService claim model while allowing other applications on the same computer access to the PointOfService peripheral when they need exclusive use.  |
| [PointOfService end-to-end](pos-get-started.md)  | This is an end to end example of how to interact with PointOfService peripherals utilizing the examples above. |
|

## See also

| Topic   | Description |
|:--------|:------------|
| [Application distribution](../publish/distribute-lob-apps-to-enterprises.md) | Learn about the options for distributing your app to enterprise customers. |
| [Application lifecycle](../launch-resume/app-lifecycle.md) | Learn about the life cycle of a UWP application and what happens when Windows launches, suspends, and resumes your app. |
| [Application resources](../app-resources/index.md) | Learn how to author, package, and consume your app's string, image, and file resources. |
| [Data binding](../data-binding/index.md) | Learn how to use data binding to display data in your app's UI. |
| [Device enumeration](enumerate-devices.md) | Learn use advanced enumeration techniques to find your peripherals.|
| [Version adaptive applications](../debug-test-perf/version-adaptive-apps.md) | Lean how to design your app so that it runs on multiple versions of Windows 10.|
|


## Sample code
+ [Barcode scanner sample](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/BarcodeScanner)
+ [Cash drawer sample]( https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/CashDrawer)
+ [Line display sample](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/LineDisplay)
+ [Magnetic stripe reader sample](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/MagneticStripeReader)
+ [POSPrinter sample](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/PosPrinter)
