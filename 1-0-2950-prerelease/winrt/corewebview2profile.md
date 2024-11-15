---
description: 
title: CoreWebView2Profile
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2Profile
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2Profile
- CoreWebView2Profile.CookieManager
- CoreWebView2Profile.DefaultDownloadFolderPath
- CoreWebView2Profile.IsGeneralAutofillEnabled
- CoreWebView2Profile.IsInPrivateModeEnabled
- CoreWebView2Profile.IsPasswordAutosaveEnabled
- CoreWebView2Profile.PreferredColorScheme
- CoreWebView2Profile.PreferredTrackingPreventionLevel
- CoreWebView2Profile.ProfileName
- CoreWebView2Profile.ProfilePath
- CoreWebView2Profile.AddBrowserExtensionAsync
- CoreWebView2Profile.ClearBrowsingDataAsync
- CoreWebView2Profile.ClearBrowsingDataAsync
- CoreWebView2Profile.ClearBrowsingDataAsync
- CoreWebView2Profile.ClearCustomDataPartitionAsync
- CoreWebView2Profile.Delete
- CoreWebView2Profile.GetBrowserExtensionsAsync
- CoreWebView2Profile.GetNonDefaultPermissionSettingsAsync
- CoreWebView2Profile.SetPermissionStateAsync
- CoreWebView2Profile.Deleted
---

# CoreWebView2Profile Class



## Summary

Members|Description
--|--
[CookieManager](#cookiemanager) | 
[DefaultDownloadFolderPath](#defaultdownloadfolderpath) | 
[IsGeneralAutofillEnabled](#isgeneralautofillenabled) | 
[IsInPrivateModeEnabled](#isinprivatemodeenabled) | 
[IsPasswordAutosaveEnabled](#ispasswordautosaveenabled) | 
[PreferredColorScheme](#preferredcolorscheme) | 
[PreferredTrackingPreventionLevel](#preferredtrackingpreventionlevel) | 
[ProfileName](#profilename) | 
[ProfilePath](#profilepath) | 
[AddBrowserExtensionAsync](#addbrowserextensionasync) | 
[ClearBrowsingDataAsync](#clearbrowsingdataasync) | 
[ClearBrowsingDataAsync](#clearbrowsingdataasync) | 
[ClearBrowsingDataAsync](#clearbrowsingdataasync) | 
[ClearCustomDataPartitionAsync](#clearcustomdatapartitionasync) | 
[Delete](#delete) | 
[GetBrowserExtensionsAsync](#getbrowserextensionsasync) | 
[GetNonDefaultPermissionSettingsAsync](#getnondefaultpermissionsettingsasync) | 
[SetPermissionStateAsync](#setpermissionstateasync) | 
[Deleted](#deleted) | 

## Properties

### CookieManager

> readonly  [CoreWebView2CookieManager](corewebview2cookiemanager.md) CookieManager

### DefaultDownloadFolderPath

>  string DefaultDownloadFolderPath

### IsGeneralAutofillEnabled

>  bool IsGeneralAutofillEnabled

### IsInPrivateModeEnabled

> readonly  bool IsInPrivateModeEnabled

### IsPasswordAutosaveEnabled

>  bool IsPasswordAutosaveEnabled

### PreferredColorScheme

>  [CoreWebView2PreferredColorScheme](corewebview2preferredcolorscheme.md) PreferredColorScheme

### PreferredTrackingPreventionLevel

>  [CoreWebView2TrackingPreventionLevel](corewebview2trackingpreventionlevel.md) PreferredTrackingPreventionLevel

### ProfileName

> readonly  string ProfileName

### ProfilePath

> readonly  string ProfilePath



## Methods

### AddBrowserExtensionAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;[CoreWebView2BrowserExtension](corewebview2browserextension.md)&gt; AddBrowserExtensionAsync(string extensionFolderPath)



### ClearBrowsingDataAsync

> [IAsyncAction](/uwp/api/Windows.Foundation.IAsyncAction) ClearBrowsingDataAsync([CoreWebView2BrowsingDataKinds](corewebview2browsingdatakinds.md) dataKinds, [DateTime](/uwp/api/Windows.Foundation.DateTime) startTime, [DateTime](/uwp/api/Windows.Foundation.DateTime) endTime)



### ClearBrowsingDataAsync

> [IAsyncAction](/uwp/api/Windows.Foundation.IAsyncAction) ClearBrowsingDataAsync()



### ClearBrowsingDataAsync

> [IAsyncAction](/uwp/api/Windows.Foundation.IAsyncAction) ClearBrowsingDataAsync([CoreWebView2BrowsingDataKinds](corewebview2browsingdatakinds.md) dataKinds)



### ClearCustomDataPartitionAsync

> [IAsyncAction](/uwp/api/Windows.Foundation.IAsyncAction) ClearCustomDataPartitionAsync(string CustomDataPartitionId)



### Delete

> void Delete()



### GetBrowserExtensionsAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;[`IVectorView`](/uwp/api/Windows.Foundation.Collections.IVectorView-1)&lt;[CoreWebView2BrowserExtension](corewebview2browserextension.md)&gt;&gt; GetBrowserExtensionsAsync()



### GetNonDefaultPermissionSettingsAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;[`IVectorView`](/uwp/api/Windows.Foundation.Collections.IVectorView-1)&lt;[CoreWebView2PermissionSetting](corewebview2permissionsetting.md)&gt;&gt; GetNonDefaultPermissionSettingsAsync()



### SetPermissionStateAsync

> [IAsyncAction](/uwp/api/Windows.Foundation.IAsyncAction) SetPermissionStateAsync([CoreWebView2PermissionKind](corewebview2permissionkind.md) PermissionKind, string origin, [CoreWebView2PermissionState](corewebview2permissionstate.md) State)




## Events

### Deleted

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2Profile, Object&gt;



## Referenced by

- [CoreWebView2](corewebview2.md)
