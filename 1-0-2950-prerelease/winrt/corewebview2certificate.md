---
description: 
title: CoreWebView2Certificate
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2Certificate
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2Certificate
- CoreWebView2Certificate.DerEncodedSerialNumber
- CoreWebView2Certificate.DisplayName
- CoreWebView2Certificate.Issuer
- CoreWebView2Certificate.PemEncodedIssuerCertificateChain
- CoreWebView2Certificate.Subject
- CoreWebView2Certificate.ValidFrom
- CoreWebView2Certificate.ValidTo
- CoreWebView2Certificate.ToCertificate
- CoreWebView2Certificate.ToPemEncoding
---

# CoreWebView2Certificate Class



## Summary

Members|Description
--|--
[DerEncodedSerialNumber](#derencodedserialnumber) | 
[DisplayName](#displayname) | 
[Issuer](#issuer) | 
[PemEncodedIssuerCertificateChain](#pemencodedissuercertificatechain) | 
[Subject](#subject) | 
[ValidFrom](#validfrom) | 
[ValidTo](#validto) | 
[ToCertificate](#tocertificate) | 
[ToPemEncoding](#topemencoding) | 

## Properties

### DerEncodedSerialNumber

> readonly  string DerEncodedSerialNumber

### DisplayName

> readonly  string DisplayName

### Issuer

> readonly  string Issuer

### PemEncodedIssuerCertificateChain

> readonly  [`IVectorView`](/uwp/api/Windows.Foundation.Collections.IVectorView-1)&lt;string&gt; PemEncodedIssuerCertificateChain

### Subject

> readonly  string Subject

### ValidFrom

> readonly  double ValidFrom

### ValidTo

> readonly  double ValidTo



## Methods

### ToCertificate

> [Certificate](/uwp/api/Windows.Security.Cryptography.Certificates.Certificate) ToCertificate()



### ToPemEncoding

> string ToPemEncoding()






## Referenced by

- [CoreWebView2ServerCertificateErrorDetectedEventArgs](corewebview2servercertificateerrordetectedeventargs.md)
