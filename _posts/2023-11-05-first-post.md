---
title: Hello Code-Log
date: 2023-11-05 12:00:00
categories: [code-log, misc]
tags: [random]
---

# Hello! Code-Log

## AZ-204 Lets kick this off by installing PS7

Grab PowerShell 7 MSI package from GitHub > 

```powershell
Get-ExecutionPolicy -List

Install-Module -Name Az -Repository PSGallery -Force

Get-Module -Name Az -ListAvailable

Update-Module -Name Ax

Connect-AzAccount
```
