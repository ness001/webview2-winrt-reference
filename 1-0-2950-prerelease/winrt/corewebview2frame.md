---
description: 
title: CoreWebView2Frame
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2Frame
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2Frame
- CoreWebView2Frame.FrameId
- CoreWebView2Frame.Name
- CoreWebView2Frame.UseOverrideTimerWakeInterval
- CoreWebView2Frame.ExecuteScriptAsync
- CoreWebView2Frame.IsDestroyed
- CoreWebView2Frame.PostSharedBufferToScript
- CoreWebView2Frame.PostWebMessageAsJson
- CoreWebView2Frame.PostWebMessageAsString
- CoreWebView2Frame.RemoveHostObjectFromScript
- CoreWebView2Frame.ContentLoading
- CoreWebView2Frame.DOMContentLoaded
- CoreWebView2Frame.Destroyed
- CoreWebView2Frame.NameChanged
- CoreWebView2Frame.NavigationCompleted
- CoreWebView2Frame.NavigationStarting
- CoreWebView2Frame.PermissionRequested
- CoreWebView2Frame.ScreenCaptureStarting
- CoreWebView2Frame.WebMessageReceived
---

# CoreWebView2Frame Class



## Summary

Members|Description
--|--
[FrameId](#frameid) | 
[Name](#name) | 
[UseOverrideTimerWakeInterval](#useoverridetimerwakeinterval) | 
[ExecuteScriptAsync](#executescriptasync) | 
[IsDestroyed](#isdestroyed) | 
[PostSharedBufferToScript](#postsharedbuffertoscript) | 
[PostWebMessageAsJson](#postwebmessageasjson) | 
[PostWebMessageAsString](#postwebmessageasstring) | 
[RemoveHostObjectFromScript](#removehostobjectfromscript) | 
[ContentLoading](#contentloading) | 
[DOMContentLoaded](#domcontentloaded) | 
[Destroyed](#destroyed) | 
[NameChanged](#namechanged) | 
[NavigationCompleted](#navigationcompleted) | 
[NavigationStarting](#navigationstarting) | 
[PermissionRequested](#permissionrequested) | 
[ScreenCaptureStarting](#screencapturestarting) | 
[WebMessageReceived](#webmessagereceived) | 

## Properties

### FrameId

> readonly  uint32_t FrameId

### Name

> readonly  string Name

### UseOverrideTimerWakeInterval

>  bool UseOverrideTimerWakeInterval



## Methods

### ExecuteScriptAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;string&gt; ExecuteScriptAsync(string javaScript)



### IsDestroyed

> int IsDestroyed()



### PostSharedBufferToScript

> void PostSharedBufferToScript([CoreWebView2SharedBuffer](corewebview2sharedbuffer.md) sharedBuffer, [CoreWebView2SharedBufferAccess](corewebview2sharedbufferaccess.md) access, string additionalDataAsJson)



### PostWebMessageAsJson

> void PostWebMessageAsJson(string webMessageAsJson)



### PostWebMessageAsString

> void PostWebMessageAsString(string webMessageAsString)



### RemoveHostObjectFromScript

> void RemoveHostObjectFromScript(string name)




## Events

### ContentLoading

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Frame, [CoreWebView2ContentLoadingEventArgs](corewebview2contentloadingeventargs.md)&gt;

### DOMContentLoaded

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Frame, [CoreWebView2DOMContentLoadedEventArgs](corewebview2domcontentloadedeventargs.md)&gt;

### Destroyed

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Frame, Object&gt;

### NameChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Frame, Object&gt;

### NavigationCompleted

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Frame, [CoreWebView2NavigationCompletedEventArgs](corewebview2navigationcompletedeventargs.md)&gt;

### NavigationStarting

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Frame, [CoreWebView2NavigationStartingEventArgs](corewebview2navigationstartingeventargs.md)&gt;

### PermissionRequested

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Frame, [CoreWebView2PermissionRequestedEventArgs](corewebview2permissionrequestedeventargs.md)&gt;

### ScreenCaptureStarting

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Frame, [CoreWebView2ScreenCaptureStartingEventArgs](corewebview2screencapturestartingeventargs.md)&gt;

### WebMessageReceived

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Frame, [CoreWebView2WebMessageReceivedEventArgs](corewebview2webmessagereceivedeventargs.md)&gt;



## Referenced by

- [CoreWebView2FrameCreatedEventArgs](corewebview2framecreatedeventargs.md)
