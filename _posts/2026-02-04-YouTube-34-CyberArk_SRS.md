---
title: "#34 - CyberArk SRS"
date: 2026-02-04 09:10:10 +1100
categories: [CyberArk SRS]
tags: [cyberark,privilegecloud,pamsaas,Identity,srs,sia]     # TAG names should always be lowercase
---
This video presents a comprehensive tutorial on setting up and using CyberArk - Secrets Rotation Service (SRS) within a newly created Privileged Access Management SaaS (PAM SaaS) tenant. 

I will walk you through configuring identity connectors for user authentication, establishing connector pools, deploying System and Secure Infrastructure Access (SIA) connectors, and demonstrating key features of the secrets rotation service. The explanation method balances detailed step-by-step lab deployment with conceptual clarifications, illustrating differences from previous systems and showcasing practical password rotation, verification, reconciliation, and target connection scenarios.

[![Video Preview](https://i.ytimg.com/vi/jHBXRjIn4QI/maxresdefault.jpg)](https://www.youtube.com/watch?v=jHBXRjIn4QI)

## Objectives

- Setting up a new CyberArk PAM SaaS tenant.
- Identity Configuration.
- Installing and configuring the Identity Connector.
- Create Connector Pools and deploying System + SIA Connectors.
- Exploring the new Secrets Rotation Service (SRS) interface and policies.
- Creating a Windows Reconcile Platform and configuring rotation/verification.
- Onboarding Reconcile Accounts.
- Onboarding Windows and Linux privileged accounts.
- Demonstrating password rotation, verification & reconciliation workflows.
- Using SIA to launch RDP/SSH sessions (HTML5, RDP and SSH methods).

# Lab Diagram

![alt text](/assets/img/acme-diagram.png)

# Reconcile Script

I've made a video on how to configure the Reconcile account [here.](https://cybrad.au/posts/YouTube-16-ISPSS-Widnows-Reconcile/)

# SIA - SSH Logon Sequernce

Here is the regex that was used for the SSH logon account fro SIA.

```
.*\@.*\$>exec su {Username}
Password:>{Password}
```
- 
## Timeline

- 00:00:00 — Intro
- 00:01:32 — CPM vs SRS Architecture Explained
- 00:07:39 — Entering the Lab & Identity Setup
- 00:12:54 — Installing the Identity Connector
- 00:17:28 — Connector Pools & SIA/System Connectors
- 00:21:23 — SRS Platform Management Overview
- 00:27:26 — Creating Safes & AD Reconcile Accounts
- 00:34:43 — Onboarding Windows Domain Accounts
- 00:38:47 — Secure Infrastructure Access (SIA) Demo
- 00:42:47 — Linux Platforms & SSH Access via SIA
- 00:47:46 — Final Recap

Brad McDowell LinkedIn: https://au.linkedin.com/in/bradmcdowell

#CyberArk #SRS #SIA #ISPSS #Identity #privilegeaccessmanagement