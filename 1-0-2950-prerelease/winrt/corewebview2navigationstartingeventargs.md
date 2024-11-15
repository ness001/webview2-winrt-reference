---
description: 
title: CoreWebView2NavigationStartingEventArgs
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2NavigationStartingEventArgs
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2NavigationStartingEventArgs
- CoreWebView2NavigationStartingEventArgs.AdditionalAllowedFrameAncestors
- CoreWebView2NavigationStartingEventArgs.Cancel
- CoreWebView2NavigationStartingEventArgs.IsRedirected
- CoreWebView2NavigationStartingEventArgs.IsUserInitiated
- CoreWebView2NavigationStartingEventArgs.NavigationId
- CoreWebView2NavigationStartingEventArgs.NavigationKind
- CoreWebView2NavigationStartingEventArgs.RequestHeaders
- CoreWebView2NavigationStartingEventArgs.Uri
---

# CoreWebView2NavigationStartingEventArgs Class



## Summary

Members|Description
--|--
[AdditionalAllowedFrameAncestors](#additionalallowedframeancestors) | 
[Cancel](#cancel) | 
[IsRedirected](#isredirected) | 
[IsUserInitiated](#isuserinitiated) | 
[NavigationId](#navigationid) | 
[NavigationKind](#navigationkind) | 
[RequestHeaders](#requestheaders) | 
[Uri](#uri) | 

## Properties

### AdditionalAllowedFrameAncestors

>  string AdditionalAllowedFrameAncestors

### Cancel

>  bool Cancel

### IsRedirected

> readonly  bool IsRedirected

### IsUserInitiated

> readonly  bool IsUserInitiated

### NavigationId

> readonly  uint64_t NavigationId

### NavigationKind

> readonly  [CoreWebView2NavigationKind](corewebview2navigationkind.md) NavigationKind

### RequestHeaders

> readonly  [CoreWebView2HttpRequestHeaders](corewebview2httprequestheaders.md) RequestHeaders

### Uri

> readonly  string Uri






## Referenced by

- [CoreWebView2](corewebview2.md)
- [CoreWebView2Frame](corewebview2frame.md)
