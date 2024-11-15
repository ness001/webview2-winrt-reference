---
description: 
title: CoreWebView2HttpRequestHeaders
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2HttpRequestHeaders
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2HttpRequestHeaders
- CoreWebView2HttpRequestHeaders.Contains
- CoreWebView2HttpRequestHeaders.First
- CoreWebView2HttpRequestHeaders.GetHeader
- CoreWebView2HttpRequestHeaders.GetHeaders
- CoreWebView2HttpRequestHeaders.RemoveHeader
- CoreWebView2HttpRequestHeaders.SetHeader
---

# CoreWebView2HttpRequestHeaders Class

Implements: [IIterable](/uwp/api/Windows.Foundation.Collections.IIterable-1)&lt;[`IKeyValuePair`](/uwp/api/Windows.Foundation.Collections.IKeyValuePair-2)&lt;string, string&gt;&gt;

## Summary

Members|Description
--|--
[Contains](#contains) | 
[First](#first) | 
[GetHeader](#getheader) | 
[GetHeaders](#getheaders) | 
[RemoveHeader](#removeheader) | 
[SetHeader](#setheader) | 



## Methods

### Contains

> bool Contains(string name)



### First

> [`IIterator`](/uwp/api/Windows.Foundation.Collections.IIterator-1)&lt;[`IKeyValuePair`](/uwp/api/Windows.Foundation.Collections.IKeyValuePair-2)&lt;string, string&gt;&gt; First()



### GetHeader

> string GetHeader(string name)



### GetHeaders

> [CoreWebView2HttpHeadersCollectionIterator](corewebview2httpheaderscollectioniterator.md) GetHeaders(string name)



### RemoveHeader

> void RemoveHeader(string name)



### SetHeader

> void SetHeader(string name, string value)






## Referenced by

- [CoreWebView2NavigationStartingEventArgs](corewebview2navigationstartingeventargs.md)
- [CoreWebView2WebResourceRequest](corewebview2webresourcerequest.md)
