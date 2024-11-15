---
description: 
title: CoreWebView2Controller
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2Controller
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2Controller
- CoreWebView2Controller.AllowExternalDrop
- CoreWebView2Controller.Bounds
- CoreWebView2Controller.BoundsMode
- CoreWebView2Controller.CoreWebView2
- CoreWebView2Controller.DefaultBackgroundColor
- CoreWebView2Controller.IsBrowserHitTransparent
- CoreWebView2Controller.IsVisible
- CoreWebView2Controller.ParentWindow
- CoreWebView2Controller.RasterizationScale
- CoreWebView2Controller.ShouldDetectMonitorScaleChanges
- CoreWebView2Controller.ZoomFactor
- CoreWebView2Controller.Close
- CoreWebView2Controller.MoveFocus
- CoreWebView2Controller.NotifyParentWindowPositionChanged
- CoreWebView2Controller.SetBoundsAndZoomFactor
- CoreWebView2Controller.AcceleratorKeyPressed
- CoreWebView2Controller.GotFocus
- CoreWebView2Controller.LostFocus
- CoreWebView2Controller.MoveFocusRequested
- CoreWebView2Controller.RasterizationScaleChanged
- CoreWebView2Controller.ZoomFactorChanged
---

# CoreWebView2Controller Class



## Summary

Members|Description
--|--
[AllowExternalDrop](#allowexternaldrop) | 
[Bounds](#bounds) | 
[BoundsMode](#boundsmode) | 
[CoreWebView2](#corewebview2) | 
[DefaultBackgroundColor](#defaultbackgroundcolor) | 
[IsBrowserHitTransparent](#isbrowserhittransparent) | 
[IsVisible](#isvisible) | 
[ParentWindow](#parentwindow) | 
[RasterizationScale](#rasterizationscale) | 
[ShouldDetectMonitorScaleChanges](#shoulddetectmonitorscalechanges) | 
[ZoomFactor](#zoomfactor) | 
[Close](#close) | 
[MoveFocus](#movefocus) | 
[NotifyParentWindowPositionChanged](#notifyparentwindowpositionchanged) | 
[SetBoundsAndZoomFactor](#setboundsandzoomfactor) | 
[AcceleratorKeyPressed](#acceleratorkeypressed) | 
[GotFocus](#gotfocus) | 
[LostFocus](#lostfocus) | 
[MoveFocusRequested](#movefocusrequested) | 
[RasterizationScaleChanged](#rasterizationscalechanged) | 
[ZoomFactorChanged](#zoomfactorchanged) | 

## Properties

### AllowExternalDrop

>  bool AllowExternalDrop

### Bounds

>  [Rect](/uwp/api/Windows.Foundation.Rect) Bounds

### BoundsMode

>  [CoreWebView2BoundsMode](corewebview2boundsmode.md) BoundsMode

### CoreWebView2

> readonly  [CoreWebView2](corewebview2.md) CoreWebView2

### DefaultBackgroundColor

>  [Color](/uwp/api/Windows.UI.Color) DefaultBackgroundColor

### IsBrowserHitTransparent

> readonly  bool IsBrowserHitTransparent

### IsVisible

>  bool IsVisible

### ParentWindow

>  [CoreWebView2ControllerWindowReference](corewebview2controllerwindowreference.md) ParentWindow

### RasterizationScale

>  double RasterizationScale

### ShouldDetectMonitorScaleChanges

>  bool ShouldDetectMonitorScaleChanges

### ZoomFactor

>  double ZoomFactor



## Methods

### Close

> void Close()



### MoveFocus

> void MoveFocus([CoreWebView2MoveFocusReason](corewebview2movefocusreason.md) reason)



### NotifyParentWindowPositionChanged

> void NotifyParentWindowPositionChanged()



### SetBoundsAndZoomFactor

> void SetBoundsAndZoomFactor([Rect](/uwp/api/Windows.Foundation.Rect) Bounds, double ZoomFactor)




## Events

### AcceleratorKeyPressed

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Controller, [CoreWebView2AcceleratorKeyPressedEventArgs](corewebview2acceleratorkeypressedeventargs.md)&gt;

### GotFocus

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Controller, Object&gt;

### LostFocus

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Controller, Object&gt;

### MoveFocusRequested

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Controller, [CoreWebView2MoveFocusRequestedEventArgs](corewebview2movefocusrequestedeventargs.md)&gt;

### RasterizationScaleChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Controller, Object&gt;

### ZoomFactorChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Controller, Object&gt;

