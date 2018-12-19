﻿---
title: TraceEntry.ThreadId Property  (Microsoft.Web.Media.Diagnostics)
TOCTitle: ThreadId Property
ms:assetid: P:Microsoft.Web.Media.Diagnostics.TraceEntry.ThreadId
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.diagnostics.traceentry.threadid(v=VS.90)
ms:contentKeyID: 23961187
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.Diagnostics.TraceEntry.ThreadId
- Microsoft.Web.Media.Diagnostics.TraceEntry.get_ThreadId
- Microsoft.Web.Media.Diagnostics.TraceEntry.set_ThreadId
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Media.SmoothStreaming.dll
api_name:
- Microsoft.Web.Media.Diagnostics.TraceEntry.get_ThreadId
- Microsoft.Web.Media.Diagnostics.TraceEntry.set_ThreadId
- Microsoft.Web.Media.Diagnostics.TraceEntry.ThreadId
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# ThreadId Property

Gets or sets the ThreadId property.

**Namespace:**  [Microsoft.Web.Media.Diagnostics](microsoft-web-media-diagnostics-namespace_1.md)  
**Assembly:**  Microsoft.Web.Media.SmoothStreaming (in Microsoft.Web.Media.SmoothStreaming.dll)

## Syntax

``` vb
'Declaration
PublicPropertyThreadIdAsInteger
'Usage
DiminstanceAsTraceEntryDimvalueAsIntegervalue = instance.ThreadId

instance.ThreadId = value
```

``` csharp
publicintThreadId { get; set; }
```

``` c++
public:
propertyintThreadId {
    intget ();
    voidset (intvalue);
}
```

``` jscript
function getThreadId () : intfunction setThreadId (value : int)
```

#### Property Value

Type: [System. . :: . .Int32](https://msdn.microsoft.com/en-us/library/td2s409d\(v=vs.90\))  
An integer value that specifies the numeric ID of the thread that invoked the trace.  

## Version Information

#### Silverlight

Supported in: 4  

#### Silverlight for Windows Phone

Supported in: Windows Phone OS 7.0  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[TraceEntry Class](traceentry-class-microsoft-web-media-diagnostics_1.md)

[Microsoft.Web.Media.Diagnostics Namespace](microsoft-web-media-diagnostics-namespace_1.md)
