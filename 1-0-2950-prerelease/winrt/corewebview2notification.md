---
description: 
title: CoreWebView2Notification
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2Notification
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2Notification
- CoreWebView2Notification.BadgeUri
- CoreWebView2Notification.Body
- CoreWebView2Notification.BodyImageUri
- CoreWebView2Notification.Direction
- CoreWebView2Notification.IconUri
- CoreWebView2Notification.IsSilent
- CoreWebView2Notification.Language
- CoreWebView2Notification.RequiresInteraction
- CoreWebView2Notification.ShouldRenotify
- CoreWebView2Notification.Tag
- CoreWebView2Notification.Timestamp
- CoreWebView2Notification.Title
- CoreWebView2Notification.VibrationPattern
- CoreWebView2Notification.ReportClicked
- CoreWebView2Notification.ReportClosed
- CoreWebView2Notification.ReportShown
- CoreWebView2Notification.CloseRequested
---

# CoreWebView2Notification Class



## Summary

Members|Description
--|--
[BadgeUri](#badgeuri) | 
[Body](#body) | 
[BodyImageUri](#bodyimageuri) | 
[Direction](#direction) | 
[IconUri](#iconuri) | 
[IsSilent](#issilent) | 
[Language](#language) | 
[RequiresInteraction](#requiresinteraction) | 
[ShouldRenotify](#shouldrenotify) | 
[Tag](#tag) | 
[Timestamp](#timestamp) | 
[Title](#title) | 
[VibrationPattern](#vibrationpattern) | 
[ReportClicked](#reportclicked) | 
[ReportClosed](#reportclosed) | 
[ReportShown](#reportshown) | 
[CloseRequested](#closerequested) | 

## Properties

### BadgeUri

> readonly  string BadgeUri

### Body

> readonly  string Body

### BodyImageUri

> readonly  string BodyImageUri

### Direction

> readonly  [CoreWebView2TextDirectionKind](corewebview2textdirectionkind.md) Direction

### IconUri

> readonly  string IconUri

### IsSilent

> readonly  bool IsSilent

### Language

> readonly  string Language

### RequiresInteraction

> readonly  bool RequiresInteraction

### ShouldRenotify

> readonly  bool ShouldRenotify

### Tag

> readonly  string Tag

### Timestamp

> readonly  double Timestamp

### Title

> readonly  string Title

### VibrationPattern

> readonly  [`IVectorView`](/uwp/api/Windows.Foundation.Collections.IVectorView-1)&lt;uint64_t&gt; VibrationPattern



## Methods

### ReportClicked

> void ReportClicked()



### ReportClosed

> void ReportClosed()



### ReportShown

> void ReportShown()




## Events

### CloseRequested

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Notification, Object&gt;



## Referenced by

- [CoreWebView2NotificationReceivedEventArgs](corewebview2notificationreceivedeventargs.md)
