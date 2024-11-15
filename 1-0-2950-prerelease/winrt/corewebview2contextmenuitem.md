---
description: 
title: CoreWebView2ContextMenuItem
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2ContextMenuItem
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2ContextMenuItem
- CoreWebView2ContextMenuItem.Children
- CoreWebView2ContextMenuItem.CommandId
- CoreWebView2ContextMenuItem.Icon
- CoreWebView2ContextMenuItem.IsChecked
- CoreWebView2ContextMenuItem.IsEnabled
- CoreWebView2ContextMenuItem.Kind
- CoreWebView2ContextMenuItem.Label
- CoreWebView2ContextMenuItem.Name
- CoreWebView2ContextMenuItem.ShortcutKeyDescription
- CoreWebView2ContextMenuItem.CustomItemSelected
---

# CoreWebView2ContextMenuItem Class



## Summary

Members|Description
--|--
[Children](#children) | 
[CommandId](#commandid) | 
[Icon](#icon) | 
[IsChecked](#ischecked) | 
[IsEnabled](#isenabled) | 
[Kind](#kind) | 
[Label](#label) | 
[Name](#name) | 
[ShortcutKeyDescription](#shortcutkeydescription) | 
[CustomItemSelected](#customitemselected) | 

## Properties

### Children

> readonly  [`IVector`](/uwp/api/Windows.Foundation.Collections.IVector-1)&lt;CoreWebView2ContextMenuItem&gt; Children

### CommandId

> readonly  int CommandId

### Icon

> readonly  [IRandomAccessStream](/uwp/api/Windows.Storage.Streams.IRandomAccessStream) Icon

### IsChecked

>  bool IsChecked

### IsEnabled

>  bool IsEnabled

### Kind

> readonly  [CoreWebView2ContextMenuItemKind](corewebview2contextmenuitemkind.md) Kind

### Label

> readonly  string Label

### Name

> readonly  string Name

### ShortcutKeyDescription

> readonly  string ShortcutKeyDescription




## Events

### CustomItemSelected

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2ContextMenuItem, Object&gt;



## Referenced by

- [CoreWebView2Environment](corewebview2environment.md)
