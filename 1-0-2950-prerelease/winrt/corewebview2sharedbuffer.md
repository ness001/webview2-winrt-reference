---
description: 
title: CoreWebView2SharedBuffer
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2SharedBuffer
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2SharedBuffer
- CoreWebView2SharedBuffer.Buffer
- CoreWebView2SharedBuffer.Size
- CoreWebView2SharedBuffer.Close
- CoreWebView2SharedBuffer.OpenStream
---

# CoreWebView2SharedBuffer Class

Implements: [IClosable](/uwp/api/Windows.Foundation.IClosable)

## Summary

Members|Description
--|--
[Buffer](#buffer) | 
[Size](#size) | 
[Close](#close) | 
[OpenStream](#openstream) | 

## Properties

### Buffer

> readonly  [IMemoryBufferReference](/uwp/api/Windows.Foundation.IMemoryBufferReference) Buffer

### Size

> readonly  uint64_t Size



## Methods

### Close

> void Close()



### OpenStream

> [IRandomAccessStream](/uwp/api/Windows.Storage.Streams.IRandomAccessStream) OpenStream()






## Referenced by

- [CoreWebView2](corewebview2.md)
- [CoreWebView2Environment](corewebview2environment.md)
- [CoreWebView2Frame](corewebview2frame.md)
