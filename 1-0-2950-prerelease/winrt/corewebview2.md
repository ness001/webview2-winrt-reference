---
description: 
title: CoreWebView2
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2
- CoreWebView2.BrowserProcessId
- CoreWebView2.CanGoBack
- CoreWebView2.CanGoForward
- CoreWebView2.ContainsFullScreenElement
- CoreWebView2.CookieManager
- CoreWebView2.CustomDataPartitionId
- CoreWebView2.DefaultDownloadDialogCornerAlignment
- CoreWebView2.DefaultDownloadDialogMargin
- CoreWebView2.DocumentTitle
- CoreWebView2.Environment
- CoreWebView2.FaviconUri
- CoreWebView2.FrameId
- CoreWebView2.IsDefaultDownloadDialogOpen
- CoreWebView2.IsDocumentPlayingAudio
- CoreWebView2.IsMuted
- CoreWebView2.IsSuspended
- CoreWebView2.MemoryUsageTargetLevel
- CoreWebView2.Profile
- CoreWebView2.Settings
- CoreWebView2.Source
- CoreWebView2.StatusBarText
- CoreWebView2.AddHostObjectToScript
- CoreWebView2.AddScriptToExecuteOnDocumentCreatedAsync
- CoreWebView2.AddWebResourceRequestedFilter
- CoreWebView2.AddWebResourceRequestedFilter
- CoreWebView2.CallDevToolsProtocolMethodAsync
- CoreWebView2.CallDevToolsProtocolMethodForSessionAsync
- CoreWebView2.CapturePreviewAsync
- CoreWebView2.ClearServerCertificateErrorActionsAsync
- CoreWebView2.ClearVirtualHostNameToFolderMapping
- CoreWebView2.CloseDefaultDownloadDialog
- CoreWebView2.ExecuteScriptAsync
- CoreWebView2.ExecuteScriptWithResultAsync
- CoreWebView2.GetDevToolsProtocolEventReceiver
- CoreWebView2.GetFaviconAsync
- CoreWebView2.GoBack
- CoreWebView2.GoForward
- CoreWebView2.Navigate
- CoreWebView2.NavigateToString
- CoreWebView2.NavigateWithWebResourceRequest
- CoreWebView2.OpenDefaultDownloadDialog
- CoreWebView2.OpenDevToolsWindow
- CoreWebView2.OpenTaskManagerWindow
- CoreWebView2.PostSharedBufferToScript
- CoreWebView2.PostWebMessageAsJson
- CoreWebView2.PostWebMessageAsJson
- CoreWebView2.PostWebMessageAsString
- CoreWebView2.PrintAsync
- CoreWebView2.PrintToPdfAsync
- CoreWebView2.PrintToPdfStreamAsync
- CoreWebView2.Reload
- CoreWebView2.RemoveHostObjectFromScript
- CoreWebView2.RemoveScriptToExecuteOnDocumentCreated
- CoreWebView2.RemoveWebResourceRequestedFilter
- CoreWebView2.RemoveWebResourceRequestedFilter
- CoreWebView2.Resume
- CoreWebView2.SetVirtualHostNameToFolderMapping
- CoreWebView2.ShowPrintUI
- CoreWebView2.ShowSaveAsUIAsync
- CoreWebView2.Stop
- CoreWebView2.TrySuspendAsync
- CoreWebView2.BasicAuthenticationRequested
- CoreWebView2.ClientCertificateRequested
- CoreWebView2.ContainsFullScreenElementChanged
- CoreWebView2.ContentLoading
- CoreWebView2.ContextMenuRequested
- CoreWebView2.DOMContentLoaded
- CoreWebView2.DocumentTitleChanged
- CoreWebView2.DownloadStarting
- CoreWebView2.FaviconChanged
- CoreWebView2.FrameCreated
- CoreWebView2.FrameNavigationCompleted
- CoreWebView2.FrameNavigationStarting
- CoreWebView2.HistoryChanged
- CoreWebView2.IsDefaultDownloadDialogOpenChanged
- CoreWebView2.IsDocumentPlayingAudioChanged
- CoreWebView2.IsMutedChanged
- CoreWebView2.LaunchingExternalUriScheme
- CoreWebView2.NavigationCompleted
- CoreWebView2.NavigationStarting
- CoreWebView2.NewWindowRequested
- CoreWebView2.NotificationReceived
- CoreWebView2.PermissionRequested
- CoreWebView2.ProcessFailed
- CoreWebView2.SaveAsUIShowing
- CoreWebView2.SaveFileSecurityCheckStarting
- CoreWebView2.ScreenCaptureStarting
- CoreWebView2.ScriptDialogOpening
- CoreWebView2.ServerCertificateErrorDetected
- CoreWebView2.SourceChanged
- CoreWebView2.StatusBarTextChanged
- CoreWebView2.WebMessageReceived
- CoreWebView2.WebResourceRequested
- CoreWebView2.WebResourceResponseReceived
- CoreWebView2.WindowCloseRequested
---

# CoreWebView2 Class



## Summary

Members|Description
--|--
[BrowserProcessId](#browserprocessid) | 
[CanGoBack](#cangoback) | 
[CanGoForward](#cangoforward) | 
[ContainsFullScreenElement](#containsfullscreenelement) | 
[CookieManager](#cookiemanager) | 
[CustomDataPartitionId](#customdatapartitionid) | 
[DefaultDownloadDialogCornerAlignment](#defaultdownloaddialogcorneralignment) | 
[DefaultDownloadDialogMargin](#defaultdownloaddialogmargin) | 
[DocumentTitle](#documenttitle) | 
[Environment](#environment) | 
[FaviconUri](#faviconuri) | 
[FrameId](#frameid) | 
[IsDefaultDownloadDialogOpen](#isdefaultdownloaddialogopen) | 
[IsDocumentPlayingAudio](#isdocumentplayingaudio) | 
[IsMuted](#ismuted) | 
[IsSuspended](#issuspended) | 
[MemoryUsageTargetLevel](#memoryusagetargetlevel) | 
[Profile](#profile) | 
[Settings](#settings) | 
[Source](#source) | 
[StatusBarText](#statusbartext) | 
[AddHostObjectToScript](#addhostobjecttoscript) | 
[AddScriptToExecuteOnDocumentCreatedAsync](#addscripttoexecuteondocumentcreatedasync) | 
[AddWebResourceRequestedFilter](#addwebresourcerequestedfilter) | 
[AddWebResourceRequestedFilter](#addwebresourcerequestedfilter) | 
[CallDevToolsProtocolMethodAsync](#calldevtoolsprotocolmethodasync) | 
[CallDevToolsProtocolMethodForSessionAsync](#calldevtoolsprotocolmethodforsessionasync) | 
[CapturePreviewAsync](#capturepreviewasync) | 
[ClearServerCertificateErrorActionsAsync](#clearservercertificateerroractionsasync) | 
[ClearVirtualHostNameToFolderMapping](#clearvirtualhostnametofoldermapping) | 
[CloseDefaultDownloadDialog](#closedefaultdownloaddialog) | 
[ExecuteScriptAsync](#executescriptasync) | 
[ExecuteScriptWithResultAsync](#executescriptwithresultasync) | 
[GetDevToolsProtocolEventReceiver](#getdevtoolsprotocoleventreceiver) | 
[GetFaviconAsync](#getfaviconasync) | 
[GoBack](#goback) | 
[GoForward](#goforward) | 
[Navigate](#navigate) | 
[NavigateToString](#navigatetostring) | 
[NavigateWithWebResourceRequest](#navigatewithwebresourcerequest) | 
[OpenDefaultDownloadDialog](#opendefaultdownloaddialog) | 
[OpenDevToolsWindow](#opendevtoolswindow) | 
[OpenTaskManagerWindow](#opentaskmanagerwindow) | 
[PostSharedBufferToScript](#postsharedbuffertoscript) | 
[PostWebMessageAsJson](#postwebmessageasjson) | 
[PostWebMessageAsJson](#postwebmessageasjson) | 
[PostWebMessageAsString](#postwebmessageasstring) | 
[PrintAsync](#printasync) | 
[PrintToPdfAsync](#printtopdfasync) | 
[PrintToPdfStreamAsync](#printtopdfstreamasync) | 
[Reload](#reload) | 
[RemoveHostObjectFromScript](#removehostobjectfromscript) | 
[RemoveScriptToExecuteOnDocumentCreated](#removescripttoexecuteondocumentcreated) | 
[RemoveWebResourceRequestedFilter](#removewebresourcerequestedfilter) | 
[RemoveWebResourceRequestedFilter](#removewebresourcerequestedfilter) | 
[Resume](#resume) | 
[SetVirtualHostNameToFolderMapping](#setvirtualhostnametofoldermapping) | 
[ShowPrintUI](#showprintui) | 
[ShowSaveAsUIAsync](#showsaveasuiasync) | 
[Stop](#stop) | 
[TrySuspendAsync](#trysuspendasync) | 
[BasicAuthenticationRequested](#basicauthenticationrequested) | 
[ClientCertificateRequested](#clientcertificaterequested) | 
[ContainsFullScreenElementChanged](#containsfullscreenelementchanged) | 
[ContentLoading](#contentloading) | 
[ContextMenuRequested](#contextmenurequested) | 
[DOMContentLoaded](#domcontentloaded) | 
[DocumentTitleChanged](#documenttitlechanged) | 
[DownloadStarting](#downloadstarting) | 
[FaviconChanged](#faviconchanged) | 
[FrameCreated](#framecreated) | 
[FrameNavigationCompleted](#framenavigationcompleted) | 
[FrameNavigationStarting](#framenavigationstarting) | 
[HistoryChanged](#historychanged) | 
[IsDefaultDownloadDialogOpenChanged](#isdefaultdownloaddialogopenchanged) | 
[IsDocumentPlayingAudioChanged](#isdocumentplayingaudiochanged) | 
[IsMutedChanged](#ismutedchanged) | 
[LaunchingExternalUriScheme](#launchingexternalurischeme) | 
[NavigationCompleted](#navigationcompleted) | 
[NavigationStarting](#navigationstarting) | 
[NewWindowRequested](#newwindowrequested) | 
[NotificationReceived](#notificationreceived) | 
[PermissionRequested](#permissionrequested) | 
[ProcessFailed](#processfailed) | 
[SaveAsUIShowing](#saveasuishowing) | 
[SaveFileSecurityCheckStarting](#savefilesecuritycheckstarting) | 
[ScreenCaptureStarting](#screencapturestarting) | 
[ScriptDialogOpening](#scriptdialogopening) | 
[ServerCertificateErrorDetected](#servercertificateerrordetected) | 
[SourceChanged](#sourcechanged) | 
[StatusBarTextChanged](#statusbartextchanged) | 
[WebMessageReceived](#webmessagereceived) | 
[WebResourceRequested](#webresourcerequested) | 
[WebResourceResponseReceived](#webresourceresponsereceived) | 
[WindowCloseRequested](#windowcloserequested) | 

## Properties

### BrowserProcessId

> readonly  uint32_t BrowserProcessId

### CanGoBack

> readonly  bool CanGoBack

### CanGoForward

> readonly  bool CanGoForward

### ContainsFullScreenElement

> readonly  bool ContainsFullScreenElement

### CookieManager

> readonly  [CoreWebView2CookieManager](corewebview2cookiemanager.md) CookieManager

### CustomDataPartitionId

>  string CustomDataPartitionId

### DefaultDownloadDialogCornerAlignment

>  [CoreWebView2DefaultDownloadDialogCornerAlignment](corewebview2defaultdownloaddialogcorneralignment.md) DefaultDownloadDialogCornerAlignment

### DefaultDownloadDialogMargin

>  [Point](/uwp/api/Windows.Foundation.Point) DefaultDownloadDialogMargin

### DocumentTitle

> readonly  string DocumentTitle

### Environment

> readonly  [CoreWebView2Environment](corewebview2environment.md) Environment

### FaviconUri

> readonly  string FaviconUri

### FrameId

> readonly  uint32_t FrameId

### IsDefaultDownloadDialogOpen

> readonly  bool IsDefaultDownloadDialogOpen

### IsDocumentPlayingAudio

> readonly  bool IsDocumentPlayingAudio

### IsMuted

>  bool IsMuted

### IsSuspended

> readonly  bool IsSuspended

### MemoryUsageTargetLevel

>  [CoreWebView2MemoryUsageTargetLevel](corewebview2memoryusagetargetlevel.md) MemoryUsageTargetLevel

### Profile

> readonly  [CoreWebView2Profile](corewebview2profile.md) Profile

### Settings

> readonly  [CoreWebView2Settings](corewebview2settings.md) Settings

### Source

> readonly  string Source

### StatusBarText

> readonly  string StatusBarText



## Methods

### AddHostObjectToScript

> void AddHostObjectToScript(string name, Object rawObject)



### AddScriptToExecuteOnDocumentCreatedAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;string&gt; AddScriptToExecuteOnDocumentCreatedAsync(string javaScript)



### AddWebResourceRequestedFilter

> void AddWebResourceRequestedFilter(string uri, [CoreWebView2WebResourceContext](corewebview2webresourcecontext.md) resourceContext, [CoreWebView2WebResourceRequestSourceKinds](corewebview2webresourcerequestsourcekinds.md) requestSourceKinds)



### AddWebResourceRequestedFilter

> void AddWebResourceRequestedFilter(string uri, [CoreWebView2WebResourceContext](corewebview2webresourcecontext.md) ResourceContext)



### CallDevToolsProtocolMethodAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;string&gt; CallDevToolsProtocolMethodAsync(string methodName, string parametersAsJson)



### CallDevToolsProtocolMethodForSessionAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;string&gt; CallDevToolsProtocolMethodForSessionAsync(string sessionId, string methodName, string parametersAsJson)



### CapturePreviewAsync

> [IAsyncAction](/uwp/api/Windows.Foundation.IAsyncAction) CapturePreviewAsync([CoreWebView2CapturePreviewImageFormat](corewebview2capturepreviewimageformat.md) imageFormat, [IRandomAccessStream](/uwp/api/Windows.Storage.Streams.IRandomAccessStream) imageStream)



### ClearServerCertificateErrorActionsAsync

> [IAsyncAction](/uwp/api/Windows.Foundation.IAsyncAction) ClearServerCertificateErrorActionsAsync()



### ClearVirtualHostNameToFolderMapping

> void ClearVirtualHostNameToFolderMapping(string hostName)



### CloseDefaultDownloadDialog

> void CloseDefaultDownloadDialog()



### ExecuteScriptAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;string&gt; ExecuteScriptAsync(string javaScript)



### ExecuteScriptWithResultAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;[CoreWebView2ExecuteScriptResult](corewebview2executescriptresult.md)&gt; ExecuteScriptWithResultAsync(string javaScript)



### GetDevToolsProtocolEventReceiver

> [CoreWebView2DevToolsProtocolEventReceiver](corewebview2devtoolsprotocoleventreceiver.md) GetDevToolsProtocolEventReceiver(string eventName)



### GetFaviconAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;[IRandomAccessStream](/uwp/api/Windows.Storage.Streams.IRandomAccessStream)&gt; GetFaviconAsync([CoreWebView2FaviconImageFormat](corewebview2faviconimageformat.md) format)



### GoBack

> void GoBack()



### GoForward

> void GoForward()



### Navigate

> void Navigate(string uri)



### NavigateToString

> void NavigateToString(string htmlContent)



### NavigateWithWebResourceRequest

> void NavigateWithWebResourceRequest([CoreWebView2WebResourceRequest](corewebview2webresourcerequest.md) Request)



### OpenDefaultDownloadDialog

> void OpenDefaultDownloadDialog()



### OpenDevToolsWindow

> void OpenDevToolsWindow()



### OpenTaskManagerWindow

> void OpenTaskManagerWindow()



### PostSharedBufferToScript

> void PostSharedBufferToScript([CoreWebView2SharedBuffer](corewebview2sharedbuffer.md) sharedBuffer, [CoreWebView2SharedBufferAccess](corewebview2sharedbufferaccess.md) access, string additionalDataAsJson)



### PostWebMessageAsJson

> void PostWebMessageAsJson(string webMessageAsJson, [`IVectorView`](/uwp/api/Windows.Foundation.Collections.IVectorView-1)&lt;Object&gt; additionalObjects)



### PostWebMessageAsJson

> void PostWebMessageAsJson(string webMessageAsJson)



### PostWebMessageAsString

> void PostWebMessageAsString(string webMessageAsString)



### PrintAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;[CoreWebView2PrintStatus](corewebview2printstatus.md)&gt; PrintAsync([CoreWebView2PrintSettings](corewebview2printsettings.md) printSettings)



### PrintToPdfAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;bool&gt; PrintToPdfAsync(string ResultFilePath, [CoreWebView2PrintSettings](corewebview2printsettings.md) printSettings)



### PrintToPdfStreamAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;[IRandomAccessStream](/uwp/api/Windows.Storage.Streams.IRandomAccessStream)&gt; PrintToPdfStreamAsync([CoreWebView2PrintSettings](corewebview2printsettings.md) printSettings)



### Reload

> void Reload()



### RemoveHostObjectFromScript

> void RemoveHostObjectFromScript(string name)



### RemoveScriptToExecuteOnDocumentCreated

> void RemoveScriptToExecuteOnDocumentCreated(string id)



### RemoveWebResourceRequestedFilter

> void RemoveWebResourceRequestedFilter(string uri, [CoreWebView2WebResourceContext](corewebview2webresourcecontext.md) resourceContext, [CoreWebView2WebResourceRequestSourceKinds](corewebview2webresourcerequestsourcekinds.md) requestSourceKinds)



### RemoveWebResourceRequestedFilter

> void RemoveWebResourceRequestedFilter(string uri, [CoreWebView2WebResourceContext](corewebview2webresourcecontext.md) ResourceContext)



### Resume

> void Resume()



### SetVirtualHostNameToFolderMapping

> void SetVirtualHostNameToFolderMapping(string hostName, string folderPath, [CoreWebView2HostResourceAccessKind](corewebview2hostresourceaccesskind.md) accessKind)



### ShowPrintUI

> void ShowPrintUI([CoreWebView2PrintDialogKind](corewebview2printdialogkind.md) printDialogKind)



### ShowSaveAsUIAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;[CoreWebView2SaveAsUIResult](corewebview2saveasuiresult.md)&gt; ShowSaveAsUIAsync()



### Stop

> void Stop()



### TrySuspendAsync

> [`IAsyncOperation`](/uwp/api/Windows.Foundation.IAsyncOperation-1)&lt;bool&gt; TrySuspendAsync()




## Events

### BasicAuthenticationRequested

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2BasicAuthenticationRequestedEventArgs](corewebview2basicauthenticationrequestedeventargs.md)&gt;

### ClientCertificateRequested

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2ClientCertificateRequestedEventArgs](corewebview2clientcertificaterequestedeventargs.md)&gt;

### ContainsFullScreenElementChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, Object&gt;

### ContentLoading

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2ContentLoadingEventArgs](corewebview2contentloadingeventargs.md)&gt;

### ContextMenuRequested

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2ContextMenuRequestedEventArgs](corewebview2contextmenurequestedeventargs.md)&gt;

### DOMContentLoaded

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2DOMContentLoadedEventArgs](corewebview2domcontentloadedeventargs.md)&gt;

### DocumentTitleChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, Object&gt;

### DownloadStarting

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2DownloadStartingEventArgs](corewebview2downloadstartingeventargs.md)&gt;

### FaviconChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, Object&gt;

### FrameCreated

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2FrameCreatedEventArgs](corewebview2framecreatedeventargs.md)&gt;

### FrameNavigationCompleted

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2NavigationCompletedEventArgs](corewebview2navigationcompletedeventargs.md)&gt;

### FrameNavigationStarting

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2NavigationStartingEventArgs](corewebview2navigationstartingeventargs.md)&gt;

### HistoryChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, Object&gt;

### IsDefaultDownloadDialogOpenChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, Object&gt;

### IsDocumentPlayingAudioChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, Object&gt;

### IsMutedChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, Object&gt;

### LaunchingExternalUriScheme

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2LaunchingExternalUriSchemeEventArgs](corewebview2launchingexternalurischemeeventargs.md)&gt;

### NavigationCompleted

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2NavigationCompletedEventArgs](corewebview2navigationcompletedeventargs.md)&gt;

### NavigationStarting

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2NavigationStartingEventArgs](corewebview2navigationstartingeventargs.md)&gt;

### NewWindowRequested

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2NewWindowRequestedEventArgs](corewebview2newwindowrequestedeventargs.md)&gt;

### NotificationReceived

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2NotificationReceivedEventArgs](corewebview2notificationreceivedeventargs.md)&gt;

### PermissionRequested

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2PermissionRequestedEventArgs](corewebview2permissionrequestedeventargs.md)&gt;

### ProcessFailed

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2ProcessFailedEventArgs](corewebview2processfailedeventargs.md)&gt;

### SaveAsUIShowing

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2SaveAsUIShowingEventArgs](corewebview2saveasuishowingeventargs.md)&gt;

### SaveFileSecurityCheckStarting

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2SaveFileSecurityCheckStartingEventArgs](corewebview2savefilesecuritycheckstartingeventargs.md)&gt;

### ScreenCaptureStarting

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2ScreenCaptureStartingEventArgs](corewebview2screencapturestartingeventargs.md)&gt;

### ScriptDialogOpening

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2ScriptDialogOpeningEventArgs](corewebview2scriptdialogopeningeventargs.md)&gt;

### ServerCertificateErrorDetected

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2ServerCertificateErrorDetectedEventArgs](corewebview2servercertificateerrordetectedeventargs.md)&gt;

### SourceChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2SourceChangedEventArgs](corewebview2sourcechangedeventargs.md)&gt;

### StatusBarTextChanged

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, Object&gt;

### WebMessageReceived

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2WebMessageReceivedEventArgs](corewebview2webmessagereceivedeventargs.md)&gt;

### WebResourceRequested

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2WebResourceRequestedEventArgs](corewebview2webresourcerequestedeventargs.md)&gt;

### WebResourceResponseReceived

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, [CoreWebView2WebResourceResponseReceivedEventArgs](corewebview2webresourceresponsereceivedeventargs.md)&gt;

### WindowCloseRequested

Type: [TypedEventHandler](/uwp/api/Windows.Foundation.TypedEventHandler-2)&lt;CoreWebView2, Object&gt;



## Referenced by

- [CoreWebView2Controller](corewebview2controller.md)
- [CoreWebView2DevToolsProtocolEventReceiver](corewebview2devtoolsprotocoleventreceiver.md)
- [CoreWebView2NewWindowRequestedEventArgs](corewebview2newwindowrequestedeventargs.md)
