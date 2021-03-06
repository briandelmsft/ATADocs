---
# required metadata
title: Microsoft Defender for Identity unmonitored domain controllers assessments
description: This article provides an overview of Microsoft Defender for Identity's unmonitored domain controllers identity security posture assessment report.
keywords:
author: shsagir
ms.author: shsagir
manager: shsagir
ms.date: 10/26/2020
ms.topic: how-to
ms.collection: M365-security-compliance
ms.service: azure-advanced-threat-protection

# optional metadata
ms.reviewer: itargoet
ms.suite: ems
---

# Security assessment: Unmonitored domain controllers

[!INCLUDE [Rebranding notice](includes/rebranding.md)]

## What are unmonitored domain controllers?

An essential part of the [!INCLUDE [Product long](includes/product-long.md)] solution requires that its sensors are deployed on all organizational domain controllers, providing a comprehensive view for all user activities from every device.

For this reason, [!INCLUDE [Product short](includes/product-short.md)] continuously monitors your environment to identify domain controllers without an installed [!INCLUDE [Product short](includes/product-short.md)] sensor, and reports on these unmonitored servers to assist you in managing full coverage of your environment.

## What risk do unmonitored domain controllers pose to an organization?

In order to operate at maximum efficiency, all domain controllers must be monitored with [!INCLUDE [Product short](includes/product-short.md)] sensors. Organizations that fail to remediate unmonitored domain controllers, reduce visibility into their environment and potentially expose their assets to malicious actors.

## How do I use this security assessment?

1. Use the report table to discover which of your domain controllers are unmonitored.
    ![Remediate unmonitored domain controllers](media/cas-isp-unmonitored-domain-controller-1.png)
1. Take appropriate action on those domain controllers by [installing and configuring monitoring sensors](sensor-monitoring.md#domain-controller-status).

> [!NOTE]
> This assessment is updated in near real time.

## See Also

- [Monitoring your domain controller coverage](sensor-monitoring.md)
- [Check out the [!INCLUDE [Product short](includes/product-short.md)] forum!](https://aka.ms/MDIcommunity)
