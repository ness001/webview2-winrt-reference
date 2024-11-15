---
description: 
title: CoreWebView2TextureStream
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2TextureStream
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2TextureStream
- CoreWebView2TextureStream.Id
- CoreWebView2TextureStream.AddAllowedOrigin
- CoreWebView2TextureStream.CloseTexture
- CoreWebView2TextureStream.CreateTexture
- CoreWebView2TextureStream.GetAvailableTexture
- CoreWebView2TextureStream.PresentTexture
- CoreWebView2TextureStream.RemoveAllowedOrigin
- CoreWebView2TextureStream.SetD3DDevice
- CoreWebView2TextureStream.Stop
- CoreWebView2TextureStream.ErrorReceived
- CoreWebView2TextureStream.StartRequested
- CoreWebView2TextureStream.Stopped
- CoreWebView2TextureStream.WebTextureReceived
- CoreWebView2TextureStream.WebTextureStreamStopped
---

# CoreWebView2TextureStream Class



## Summary

Members|Description
--|--
[Id](#id) | 
[AddAllowedOrigin](#addallowedorigin) | 
[CloseTexture](#closetexture) | 
[CreateTexture](#createtexture) | 
[GetAvailableTexture](#getavailabletexture) | 
[PresentTexture](#presenttexture) | 
[RemoveAllowedOrigin](#removeallowedorigin) | 
[SetD3DDevice](#setd3ddevice) | 
[Stop](#stop) | 
[ErrorReceived](#errorreceived) | 
[StartRequested](#startrequested) | 
[Stopped](#stopped) | 
[WebTextureReceived](#webtexturereceived) | 
[WebTextureStreamStopped](#webtexturestreamstopped) | 

## Properties

### Id

> readonly  string Id



## Methods

### AddAllowedOrigin

> void AddAllowedOrigin(string origin, int value)



### CloseTexture

> void CloseTexture([CoreWebView2Texture](corewebview2texture.md) texture)



### CreateTexture

> [CoreWebView2Texture](corewebview2texture.md) CreateTexture(uint32_t widthInTexels, uint32_t heightInTexels)



### GetAvailableTexture

> [CoreWebView2Texture](corewebview2texture.md) GetAvailableTexture()



### PresentTexture

> void PresentTexture([CoreWebView2Texture](corewebview2texture.md) texture)



### RemoveAllowedOrigin

> void RemoveAllowedOrigin(string origin)



### SetD3DDevice

> void SetD3DDevice(Object d3dDevice)



### Stop

> void Stop()




## Events

### ErrorReceived

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2TextureStream, [CoreWebView2TextureStreamErrorReceivedEventArgs](corewebview2texturestreamerrorreceivedeventargs.md)&gt;

### StartRequested

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2TextureStream, Object&gt;

### Stopped

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2TextureStream, Object&gt;

### WebTextureReceived

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2TextureStream, [CoreWebView2TextureStreamWebTextureReceivedEventArgs](corewebview2texturestreamwebtexturereceivedeventargs.md)&gt;

### WebTextureStreamStopped

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2TextureStream, Object&gt;



## Referenced by

- [CoreWebView2Environment](corewebview2environment.md)
