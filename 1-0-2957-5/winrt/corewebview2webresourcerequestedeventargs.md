---
description: Event args for the CoreWebView2.WebResourceRequested event.
title: CoreWebView2WebResourceRequestedEventArgs
ms.date: 11/19/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2WebResourceRequestedEventArgs
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2WebResourceRequestedEventArgs
- CoreWebView2WebResourceRequestedEventArgs.Request
- CoreWebView2WebResourceRequestedEventArgs.RequestedSourceKind
- CoreWebView2WebResourceRequestedEventArgs.ResourceContext
- CoreWebView2WebResourceRequestedEventArgs.Response
- CoreWebView2WebResourceRequestedEventArgs.GetDeferral
---

# CoreWebView2WebResourceRequestedEventArgs Class



Event args for the [CoreWebView2.WebResourceRequested](corewebview2.md#webresourcerequested) event.

## Summary

Members|Description
--|--
[Request](#request) | Gets the web resource request.
[RequestedSourceKind](#requestedsourcekind) | Gets the source of web resource request.
[ResourceContext](#resourcecontext) | Gets the web resource request context.
[Response](#response) | Gets or sets the [CoreWebView2WebResourceResponse](corewebview2webresourceresponse.md) object.
[GetDeferral](#getdeferral) | Gets a Deferral object and put the event into a deferred state.

## Properties

### Request

> readonly  [CoreWebView2WebResourceRequest](corewebview2webresourcerequest.md) Request

Gets the web resource request.
The request object may be missing some headers that are added by network stack at a later time.

### RequestedSourceKind

> readonly  [CoreWebView2WebResourceRequestSourceKinds](corewebview2webresourcerequestsourcekinds.md) RequestedSourceKind

Gets the source of web resource request.

### ResourceContext

> readonly  [CoreWebView2WebResourceContext](corewebview2webresourcecontext.md) ResourceContext

Gets the web resource request context.

### Response

>  [CoreWebView2WebResourceResponse](corewebview2webresourceresponse.md) Response

Gets or sets the [CoreWebView2WebResourceResponse](corewebview2webresourceresponse.md) object.
If this object is set, the [CoreWebView2.WebResourceRequested](corewebview2.md#webresourcerequested) event will be completed with this Response.
An empty [CoreWebView2WebResourceResponse](corewebview2webresourceresponse.md) object can be created with [CoreWebView2Environment.CreateWebResourceResponse](corewebview2environment.md#createwebresourceresponse) and then modified to construct the Response.



## Methods

### GetDeferral

> [Deferral](/uwp/api/Windows.Foundation.Deferral) GetDeferral()

Gets a Deferral object and put the event into a deferred state.
Use this to Complete the event at a later time.






## Referenced by

- [CoreWebView2](corewebview2.md)
