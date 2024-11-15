---
description: 
title: CoreWebView2ClientCertificateRequestedEventArgs
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2ClientCertificateRequestedEventArgs
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2ClientCertificateRequestedEventArgs
- CoreWebView2ClientCertificateRequestedEventArgs.AllowedCertificateAuthorities
- CoreWebView2ClientCertificateRequestedEventArgs.Cancel
- CoreWebView2ClientCertificateRequestedEventArgs.Handled
- CoreWebView2ClientCertificateRequestedEventArgs.Host
- CoreWebView2ClientCertificateRequestedEventArgs.IsProxy
- CoreWebView2ClientCertificateRequestedEventArgs.MutuallyTrustedCertificates
- CoreWebView2ClientCertificateRequestedEventArgs.Port
- CoreWebView2ClientCertificateRequestedEventArgs.SelectedCertificate
- CoreWebView2ClientCertificateRequestedEventArgs.GetDeferral
---

# CoreWebView2ClientCertificateRequestedEventArgs Class



## Summary

Members|Description
--|--
[AllowedCertificateAuthorities](#allowedcertificateauthorities) | 
[Cancel](#cancel) | 
[Handled](#handled) | 
[Host](#host) | 
[IsProxy](#isproxy) | 
[MutuallyTrustedCertificates](#mutuallytrustedcertificates) | 
[Port](#port) | 
[SelectedCertificate](#selectedcertificate) | 
[GetDeferral](#getdeferral) | 

## Properties

### AllowedCertificateAuthorities

> readonly  [`IVectorView`](/uwp/api/Windows.Foundation.Collections.IVectorView-1)&lt;string&gt; AllowedCertificateAuthorities

### Cancel

>  bool Cancel

### Handled

>  bool Handled

### Host

> readonly  string Host

### IsProxy

> readonly  bool IsProxy

### MutuallyTrustedCertificates

> readonly  [`IVectorView`](/uwp/api/Windows.Foundation.Collections.IVectorView-1)&lt;[CoreWebView2ClientCertificate](corewebview2clientcertificate.md)&gt; MutuallyTrustedCertificates

### Port

> readonly  int Port

### SelectedCertificate

>  [CoreWebView2ClientCertificate](corewebview2clientcertificate.md) SelectedCertificate



## Methods

### GetDeferral

> [Deferral](/uwp/api/Windows.Foundation.Deferral) GetDeferral()






## Referenced by

- [CoreWebView2](corewebview2.md)
