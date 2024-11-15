---
description: 
title: CoreWebView2DownloadOperation
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2DownloadOperation
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2DownloadOperation
- CoreWebView2DownloadOperation.BytesReceived
- CoreWebView2DownloadOperation.CanResume
- CoreWebView2DownloadOperation.ContentDisposition
- CoreWebView2DownloadOperation.EstimatedEndTime
- CoreWebView2DownloadOperation.InterruptReason
- CoreWebView2DownloadOperation.MimeType
- CoreWebView2DownloadOperation.ResultFilePath
- CoreWebView2DownloadOperation.State
- CoreWebView2DownloadOperation.TotalBytesToReceive
- CoreWebView2DownloadOperation.Uri
- CoreWebView2DownloadOperation.Cancel
- CoreWebView2DownloadOperation.Pause
- CoreWebView2DownloadOperation.Resume
- CoreWebView2DownloadOperation.BytesReceivedChanged
- CoreWebView2DownloadOperation.EstimatedEndTimeChanged
- CoreWebView2DownloadOperation.StateChanged
---

# CoreWebView2DownloadOperation Class



## Summary

Members|Description
--|--
[BytesReceived](#bytesreceived) | 
[CanResume](#canresume) | 
[ContentDisposition](#contentdisposition) | 
[EstimatedEndTime](#estimatedendtime) | 
[InterruptReason](#interruptreason) | 
[MimeType](#mimetype) | 
[ResultFilePath](#resultfilepath) | 
[State](#state) | 
[TotalBytesToReceive](#totalbytestoreceive) | 
[Uri](#uri) | 
[Cancel](#cancel) | 
[Pause](#pause) | 
[Resume](#resume) | 
[BytesReceivedChanged](#bytesreceivedchanged) | 
[EstimatedEndTimeChanged](#estimatedendtimechanged) | 
[StateChanged](#statechanged) | 

## Properties

### BytesReceived

> readonly  int64_t BytesReceived

### CanResume

> readonly  bool CanResume

### ContentDisposition

> readonly  string ContentDisposition

### EstimatedEndTime

> readonly  string EstimatedEndTime

### InterruptReason

> readonly  [CoreWebView2DownloadInterruptReason](corewebview2downloadinterruptreason.md) InterruptReason

### MimeType

> readonly  string MimeType

### ResultFilePath

> readonly  string ResultFilePath

### State

> readonly  [CoreWebView2DownloadState](corewebview2downloadstate.md) State

### TotalBytesToReceive

> readonly  int64_t TotalBytesToReceive

### Uri

> readonly  string Uri



## Methods

### Cancel

> void Cancel()



### Pause

> void Pause()



### Resume

> void Resume()




## Events

### BytesReceivedChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2DownloadOperation, Object&gt;

### EstimatedEndTimeChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2DownloadOperation, Object&gt;

### StateChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2DownloadOperation, Object&gt;



## Referenced by

- [CoreWebView2DownloadStartingEventArgs](corewebview2downloadstartingeventargs.md)
