---
description: 
title: CoreWebView2ContextMenuRequestedEventArgs
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2ContextMenuRequestedEventArgs
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2ContextMenuRequestedEventArgs
- CoreWebView2ContextMenuRequestedEventArgs.ContextMenuTarget
- CoreWebView2ContextMenuRequestedEventArgs.Handled
- CoreWebView2ContextMenuRequestedEventArgs.Location
- CoreWebView2ContextMenuRequestedEventArgs.MenuItems
- CoreWebView2ContextMenuRequestedEventArgs.SelectedCommandId
- CoreWebView2ContextMenuRequestedEventArgs.GetDeferral
---

# CoreWebView2ContextMenuRequestedEventArgs Class



## Summary

Members|Description
--|--
[ContextMenuTarget](#contextmenutarget) | 
[Handled](#handled) | 
[Location](#location) | 
[MenuItems](#menuitems) | 
[SelectedCommandId](#selectedcommandid) | 
[GetDeferral](#getdeferral) | 

## Properties

### ContextMenuTarget

> readonly  [CoreWebView2ContextMenuTarget](corewebview2contextmenutarget.md) ContextMenuTarget

### Handled

>  bool Handled

### Location

> readonly  [Point](/uwp/api/Windows.Foundation.Point) Location

### MenuItems

> readonly  [`IVector`](/uwp/api/Windows.Foundation.Collections.IVector-1)&lt;[CoreWebView2ContextMenuItem](corewebview2contextmenuitem.md)&gt; MenuItems

### SelectedCommandId

>  int SelectedCommandId



## Methods

### GetDeferral

> [Deferral](/uwp/api/Windows.Foundation.Deferral) GetDeferral()






## Referenced by

- [CoreWebView2](corewebview2.md)
