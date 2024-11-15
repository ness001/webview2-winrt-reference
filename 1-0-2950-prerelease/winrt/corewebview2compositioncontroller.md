---
description: 
title: CoreWebView2CompositionController
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2CompositionController
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2CompositionController
- CoreWebView2CompositionController.Cursor
- CoreWebView2CompositionController.RootVisualTarget
- CoreWebView2CompositionController.CreateCoreWebView2PointerInfoFromPointerId
- CoreWebView2CompositionController.DragEnter
- CoreWebView2CompositionController.DragLeave
- CoreWebView2CompositionController.DragOver
- CoreWebView2CompositionController.Drop
- CoreWebView2CompositionController.GetNonClientRegionAtPoint
- CoreWebView2CompositionController.QueryNonClientRegion
- CoreWebView2CompositionController.SendMouseInput
- CoreWebView2CompositionController.SendPointerInput
- CoreWebView2CompositionController.CursorChanged
- CoreWebView2CompositionController.NonClientRegionChanged
---

# CoreWebView2CompositionController Class

Extends: [CoreWebView2Controller](corewebview2controller.md)



## Summary

Members|Description
--|--
[Cursor](#cursor) | 
[RootVisualTarget](#rootvisualtarget) | 
[CreateCoreWebView2PointerInfoFromPointerId](#createcorewebview2pointerinfofrompointerid) | 
[DragEnter](#dragenter) | 
[DragLeave](#dragleave) | 
[DragOver](#dragover) | 
[Drop](#drop) | 
[GetNonClientRegionAtPoint](#getnonclientregionatpoint) | 
[QueryNonClientRegion](#querynonclientregion) | 
[SendMouseInput](#sendmouseinput) | 
[SendPointerInput](#sendpointerinput) | 
[CursorChanged](#cursorchanged) | 
[NonClientRegionChanged](#nonclientregionchanged) | 

## Properties

### Cursor

> readonly  [CoreCursor](/uwp/api/Windows.UI.Core.CoreCursor) Cursor

### RootVisualTarget

>  Object RootVisualTarget



## Methods

### CreateCoreWebView2PointerInfoFromPointerId

> [CoreWebView2PointerInfo](corewebview2pointerinfo.md) CreateCoreWebView2PointerInfoFromPointerId(uint32_t PointerId, [CoreWebView2ControllerWindowReference](corewebview2controllerwindowreference.md) ParentWindow, [Matrix4x4](/uwp/api/Windows.Foundation.Numerics.Matrix4x4) transform)



### DragEnter

> [DataPackageOperation](/uwp/api/Windows.ApplicationModel.DataTransfer.DataPackageOperation) DragEnter([CoreDragInfo](/uwp/api/Windows.ApplicationModel.DataTransfer.DragDrop.Core.CoreDragInfo) dragInfo, [CoreDragUIOverride](/uwp/api/Windows.ApplicationModel.DataTransfer.DragDrop.Core.CoreDragUIOverride) dragUIOverride)



### DragLeave

> void DragLeave()



### DragOver

> [DataPackageOperation](/uwp/api/Windows.ApplicationModel.DataTransfer.DataPackageOperation) DragOver([CoreDragInfo](/uwp/api/Windows.ApplicationModel.DataTransfer.DragDrop.Core.CoreDragInfo) dragInfo, [CoreDragUIOverride](/uwp/api/Windows.ApplicationModel.DataTransfer.DragDrop.Core.CoreDragUIOverride) dragUIOverride)



### Drop

> [DataPackageOperation](/uwp/api/Windows.ApplicationModel.DataTransfer.DataPackageOperation) Drop([CoreDragInfo](/uwp/api/Windows.ApplicationModel.DataTransfer.DragDrop.Core.CoreDragInfo) dragInfo)



### GetNonClientRegionAtPoint

> [CoreWebView2NonClientRegionKind](corewebview2nonclientregionkind.md) GetNonClientRegionAtPoint([Point](/uwp/api/Windows.Foundation.Point) point)



### QueryNonClientRegion

> [`IVectorView`](/uwp/api/Windows.Foundation.Collections.IVectorView-1)&lt;[Rect](/uwp/api/Windows.Foundation.Rect)&gt; QueryNonClientRegion([CoreWebView2NonClientRegionKind](corewebview2nonclientregionkind.md) Kind)



### SendMouseInput

> void SendMouseInput([CoreWebView2MouseEventKind](corewebview2mouseeventkind.md) eventKind, [CoreWebView2MouseEventVirtualKeys](corewebview2mouseeventvirtualkeys.md) virtualKeys, uint32_t mouseData, [Point](/uwp/api/Windows.Foundation.Point) point)



### SendPointerInput

> void SendPointerInput([CoreWebView2PointerEventKind](corewebview2pointereventkind.md) eventKind, [CoreWebView2PointerInfo](corewebview2pointerinfo.md) pointerInfo)




## Events

### CursorChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2CompositionController, Object&gt;

### NonClientRegionChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2CompositionController, [CoreWebView2NonClientRegionChangedEventArgs](corewebview2nonclientregionchangedeventargs.md)&gt;

