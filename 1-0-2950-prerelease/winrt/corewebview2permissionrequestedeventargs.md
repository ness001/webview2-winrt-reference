---
description: 
title: CoreWebView2PermissionRequestedEventArgs
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2PermissionRequestedEventArgs
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2PermissionRequestedEventArgs
- CoreWebView2PermissionRequestedEventArgs.Handled
- CoreWebView2PermissionRequestedEventArgs.IsUserInitiated
- CoreWebView2PermissionRequestedEventArgs.PermissionKind
- CoreWebView2PermissionRequestedEventArgs.SavesInProfile
- CoreWebView2PermissionRequestedEventArgs.State
- CoreWebView2PermissionRequestedEventArgs.Uri
- CoreWebView2PermissionRequestedEventArgs.GetDeferral
---

# CoreWebView2PermissionRequestedEventArgs Class



## Summary

Members|Description
--|--
[Handled](#handled) | 
[IsUserInitiated](#isuserinitiated) | 
[PermissionKind](#permissionkind) | 
[SavesInProfile](#savesinprofile) | 
[State](#state) | 
[Uri](#uri) | 
[GetDeferral](#getdeferral) | 

## Properties

### Handled

>  bool Handled

### IsUserInitiated

> readonly  bool IsUserInitiated

### PermissionKind

> readonly  [CoreWebView2PermissionKind](corewebview2permissionkind.md) PermissionKind

### SavesInProfile

>  bool SavesInProfile

### State

>  [CoreWebView2PermissionState](corewebview2permissionstate.md) State

### Uri

> readonly  string Uri



## Methods

### GetDeferral

> [Deferral](/uwp/api/Windows.Foundation.Deferral) GetDeferral()






## Referenced by

- [CoreWebView2](corewebview2.md)
- [CoreWebView2Frame](corewebview2frame.md)
