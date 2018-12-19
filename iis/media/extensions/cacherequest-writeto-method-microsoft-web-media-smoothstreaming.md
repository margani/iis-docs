﻿---
title: CacheRequest.WriteTo Method  (Microsoft.Web.Media.SmoothStreaming)
TOCTitle: WriteTo Method
ms:assetid: M:Microsoft.Web.Media.SmoothStreaming.CacheRequest.WriteTo(System.IO.Stream)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.smoothstreaming.cacherequest.writeto(v=VS.90)
ms:contentKeyID: 31469202
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.SmoothStreaming.CacheRequest.WriteTo
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Media.SmoothStreaming.dll
api_name:
- Microsoft.Web.Media.SmoothStreaming.CacheRequest.WriteTo
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# WriteTo Method

Writes the request to a [Stream](https://msdn.microsoft.com/en-us/library/8f86tw9e\(v=vs.90\)) object.

**Namespace:**  [Microsoft.Web.Media.SmoothStreaming](microsoft-web-media-smoothstreaming-namespace_1.md)  
**Assembly:**  Microsoft.Web.Media.SmoothStreaming (in Microsoft.Web.Media.SmoothStreaming.dll)

## Syntax

``` vb
'Declaration
PublicOverridableSubWriteTo ( _
    streamAsStream _
)
'Usage
DiminstanceAsCacheRequestDimstreamAsStream

instance.WriteTo(stream)
```

``` csharp
publicvirtualvoidWriteTo(
    Streamstream
)
```

``` c++
public:
virtualvoidWriteTo(
    Stream^ stream
)
```

``` jscript
publicfunctionWriteTo(
    stream : Stream
)
```

#### Parameters

  - stream  
    Type: [System.IO. . :: . .Stream](https://msdn.microsoft.com/en-us/library/8f86tw9e\(v=vs.90\))  
    A [Stream](https://msdn.microsoft.com/en-us/library/8f86tw9e\(v=vs.90\)) object.  

## Version Information

#### Silverlight

Supported in: 4  

#### Silverlight for Windows Phone

Supported in: Windows Phone OS 7.0  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[CacheRequest Class](cacherequest-class-microsoft-web-media-smoothstreaming_1.md)

[Microsoft.Web.Media.SmoothStreaming Namespace](microsoft-web-media-smoothstreaming-namespace_1.md)
