---
description: Representation of a DOM FileSystemHandle object.
title: CoreWebView2FileSystemHandle
ms.date: 11/19/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2FileSystemHandle
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2FileSystemHandle
- CoreWebView2FileSystemHandle.Kind
- CoreWebView2FileSystemHandle.Path
- CoreWebView2FileSystemHandle.Permission
---

# CoreWebView2FileSystemHandle Class



Representation of a DOM [FileSystemHandle](https://developer.mozilla.org/docs/Web/API/FileSystemHandle) object.

## Summary

Members|Description
--|--
[Kind](#kind) | The kind of the FileSystemHandle. It can either be a file or a directory.
[Path](#path) | The path to the FileSystemHandle.
[Permission](#permission) | The permissions granted to the FileSystemHandle.

## Properties

### Kind

> readonly  [CoreWebView2FileSystemHandleKind](corewebview2filesystemhandlekind.md) Kind

The kind of the FileSystemHandle. It can either be a file or a directory.

### Path

> readonly  string Path

The path to the FileSystemHandle.

### Permission

> readonly  [CoreWebView2FileSystemHandlePermission](corewebview2filesystemhandlepermission.md) Permission

The permissions granted to the FileSystemHandle.






## Referenced by

- [CoreWebView2Environment](corewebview2environment.md)
