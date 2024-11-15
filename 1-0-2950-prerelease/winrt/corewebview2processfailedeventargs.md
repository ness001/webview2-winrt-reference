---
description: 
title: CoreWebView2ProcessFailedEventArgs
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2ProcessFailedEventArgs
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2ProcessFailedEventArgs
- CoreWebView2ProcessFailedEventArgs.ExitCode
- CoreWebView2ProcessFailedEventArgs.FailureSourceModulePath
- CoreWebView2ProcessFailedEventArgs.FrameInfosForFailedProcess
- CoreWebView2ProcessFailedEventArgs.ProcessDescription
- CoreWebView2ProcessFailedEventArgs.ProcessFailedKind
- CoreWebView2ProcessFailedEventArgs.Reason
---

# CoreWebView2ProcessFailedEventArgs Class



## Summary

Members|Description
--|--
[ExitCode](#exitcode) | 
[FailureSourceModulePath](#failuresourcemodulepath) | 
[FrameInfosForFailedProcess](#frameinfosforfailedprocess) | 
[ProcessDescription](#processdescription) | 
[ProcessFailedKind](#processfailedkind) | 
[Reason](#reason) | 

## Properties

### ExitCode

> readonly  int ExitCode

### FailureSourceModulePath

> readonly  string FailureSourceModulePath

### FrameInfosForFailedProcess

> readonly  [`IVectorView`](/uwp/api/Windows.Foundation.Collections.IVectorView-1)&lt;[CoreWebView2FrameInfo](corewebview2frameinfo.md)&gt; FrameInfosForFailedProcess

### ProcessDescription

> readonly  string ProcessDescription

### ProcessFailedKind

> readonly  [CoreWebView2ProcessFailedKind](corewebview2processfailedkind.md) ProcessFailedKind

### Reason

> readonly  [CoreWebView2ProcessFailedReason](corewebview2processfailedreason.md) Reason






## Referenced by

- [CoreWebView2](corewebview2.md)
