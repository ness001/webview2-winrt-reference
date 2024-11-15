---
description: 
title: CoreWebView2ControllerWindowReference
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2ControllerWindowReference
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2ControllerWindowReference
- CoreWebView2ControllerWindowReference.CoreWindow
- CoreWebView2ControllerWindowReference.WindowHandle
- CoreWebView2ControllerWindowReference.CreateFromCoreWindow
- CoreWebView2ControllerWindowReference.CreateFromWindowHandle
---

# CoreWebView2ControllerWindowReference Class



## Summary

Members|Description
--|--
[CoreWindow](#corewindow) | 
[WindowHandle](#windowhandle) | 
[CreateFromCoreWindow](#createfromcorewindow) | 
[CreateFromWindowHandle](#createfromwindowhandle) | 

## Properties

### CoreWindow

> readonly  [CoreWindow](/uwp/api/Windows.UI.Core.CoreWindow) CoreWindow

### WindowHandle

> readonly  uint64_t WindowHandle



## Methods

### CreateFromCoreWindow

> static CoreWebView2ControllerWindowReference CreateFromCoreWindow([CoreWindow](/uwp/api/Windows.UI.Core.CoreWindow) coreWindow)



### CreateFromWindowHandle

> static CoreWebView2ControllerWindowReference CreateFromWindowHandle(uint64_t windowHandle)






## Referenced by

- [CoreWebView2CompositionController](corewebview2compositioncontroller.md)
- [CoreWebView2Controller](corewebview2controller.md)
- [CoreWebView2Environment](corewebview2environment.md)
