---
title: "#25 - Migrate CyberArk PSM to SIA ZSP for Windows RDP Access"
date: 2025-06-26 08:10:10 +1100
categories: [CyberArk Privilege Cloud]
tags: [cyberark,privilegecloud,Identity,SIA,ZSP,PSM,CPM]     # TAG names should always be lowercase
---
TBC

[![Video Preview](https://i.ytimg.com/vi/TDqr6yvKIS4/maxresdefault.jpg)](https://www.youtube.com/watch?v=TDqr6yvKIS4)

## CyberArk Doc
CyberArk docs [Privilege Cloud Architecture](https://docs.cyberark.com/privilege-cloud-shared-services/latest/en/content/privilege%20cloud/privcloud-detailed-architecture.htm) has a detailed description of all the components.

## High-Level Architecture Diagram
The below diagram is a high level overview on how a typical environment will connecto to CyberArk Privilege Cloud ISPSS.

![image](/assets/img/CyberArk-High-Level.png)

## Low-Level Architecture Diagram
This low-level diagram is an example scenario where Active-Directory is the source for identities.

![image](/assets/img/CyberArk-Low-Level-Identity-AD.png)

This low-level diagram is an example scenario where an external IdP is the source for identities.
![image](/assets/img/CyberArk-Low-Level-External-IdP.png)

## Objectives

- High-level deployment overview
- Low-level architecture components

## Timeline

- Intro 0:00
- PSM vs SIA ZSP  1:30
- PSM Connection Example 7:10
- SIA Roles 7:53
- SIA Connector Pools 8:43
- SIA Connector Install 9:40
- SIA Settings 11:00
- TLS Certiificates 12:45
- Test SIA with vaulted acccount 13:35
- SIA Strong Account 14:30
- SIA Policy 20:38
- SIA Local Ephemeral Test 20:25
- SIA Domain Ephemeral Test 24:25
- Disable Vaulted Accounts 26:05

LinkedIn: https://au.linkedin.com/in/bradmcdowell