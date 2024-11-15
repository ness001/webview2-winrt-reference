---
description: 
title: CoreWebView2NewWindowRequestedEventArgs
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2NewWindowRequestedEventArgs
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2NewWindowRequestedEventArgs
- CoreWebView2NewWindowRequestedEventArgs.Handled
- CoreWebView2NewWindowRequestedEventArgs.IsUserInitiated
- CoreWebView2NewWindowRequestedEventArgs.Name
- CoreWebView2NewWindowRequestedEventArgs.NewWindow
- CoreWebView2NewWindowRequestedEventArgs.OriginalSourceFrameInfo
- CoreWebView2NewWindowRequestedEventArgs.Uri
- CoreWebView2NewWindowRequestedEventArgs.WindowFeatures
- CoreWebView2NewWindowRequestedEventArgs.GetDeferral
---

# CoreWebView2NewWindowRequestedEventArgs Class



## Summary

Members|Description
--|--
[Handled](#handled) | 
[IsUserInitiated](#isuserinitiated) | 
[Name](#name) | 
[NewWindow](#newwindow) | 
[OriginalSourceFrameInfo](#originalsourceframeinfo) | 
[Uri](#uri) | 
[WindowFeatures](#windowfeatures) | 
[GetDeferral](#getdeferral) | 

## Properties

### Handled

>  bool Handled

### IsUserInitiated

> readonly  bool IsUserInitiated

### Name

> readonly  string Name

### NewWindow

>  [CoreWebView2](corewebview2.md) NewWindow

### OriginalSourceFrameInfo

> readonly  [CoreWebView2FrameInfo](corewebview2frameinfo.md) OriginalSourceFrameInfo

### Uri

> readonly  string Uri

### WindowFeatures

> readonly  [CoreWebView2WindowFeatures](corewebview2windowfeatures.md) WindowFeatures



## Methods

### GetDeferral

> [Deferral](/uwp/api/Windows.Foundation.Deferral) GetDeferral()






## Referenced by

- [CoreWebView2](corewebview2.md)
