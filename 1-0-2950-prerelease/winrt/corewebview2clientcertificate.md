---
description: 
title: CoreWebView2ClientCertificate
ms.date: 11/15/2024
keywords: webview2, webview, winrt, win32, edge, CoreWebView2, CoreWebView2Controller, browser control, edge html, CoreWebView2ClientCertificate
topic_type:
- APIRef
api_type:
- Assembly
api_location:
- Microsoft.Web.WebView2.Core.dll
api_name:
- CoreWebView2ClientCertificate
- CoreWebView2ClientCertificate.DerEncodedSerialNumber
- CoreWebView2ClientCertificate.DisplayName
- CoreWebView2ClientCertificate.Issuer
- CoreWebView2ClientCertificate.Kind
- CoreWebView2ClientCertificate.PemEncodedIssuerCertificateChain
- CoreWebView2ClientCertificate.Subject
- CoreWebView2ClientCertificate.ValidFrom
- CoreWebView2ClientCertificate.ValidTo
- CoreWebView2ClientCertificate.ToCertificate
- CoreWebView2ClientCertificate.ToPemEncoding
---

# CoreWebView2ClientCertificate Class



## Summary

Members|Description
--|--
[DerEncodedSerialNumber](#derencodedserialnumber) | 
[DisplayName](#displayname) | 
[Issuer](#issuer) | 
[Kind](#kind) | 
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

### Kind

> readonly  [CoreWebView2ClientCertificateKind](corewebview2clientcertificatekind.md) Kind

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

- [CoreWebView2ClientCertificateRequestedEventArgs](corewebview2clientcertificaterequestedeventargs.md)
