﻿---
title: SmoothStreamingMediaElement.MarkerReached Event (Microsoft.Web.Media.SmoothStreaming)
TOCTitle: MarkerReached Event
ms:assetid: E:Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.MarkerReached
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.smoothstreaming.smoothstreamingmediaelement.markerreached(v=VS.90)
ms:contentKeyID: 23960986
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.MarkerReached
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Media.SmoothStreaming.dll
api_name:
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.add_MarkerReached
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.MarkerReached
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.remove_MarkerReached
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# MarkerReached Event

Occurs when media playback reaches a timeline marker.

**Namespace:**  [Microsoft.Web.Media.SmoothStreaming](microsoft-web-media-smoothstreaming-namespace_1.md)  
**Assembly:**  Microsoft.Web.Media.SmoothStreaming (in Microsoft.Web.Media.SmoothStreaming.dll)

## Syntax

``` vb
'Declaration
Public Event MarkerReachedAsTimelineMarkerRoutedEventHandler
'Usage
DiminstanceAsSmoothStreamingMediaElementDimhandlerAsTimelineMarkerRoutedEventHandlerAddHandler instance.MarkerReached, handler
```

``` csharp
public event TimelineMarkerRoutedEventHandlerMarkerReached
```

``` c++
public:
 eventTimelineMarkerRoutedEventHandler^ MarkerReached {
    voidadd (TimelineMarkerRoutedEventHandler^ value);
    voidremove (TimelineMarkerRoutedEventHandler^ value);
}
```

``` jscript
JScript does not support events.
```

## Remarks

For more information, see [Timeline Markers and Events (IIS Smooth Streaming)](timeline-markers-and-events.md).

## Version Information

#### Silverlight

Supported in: 4  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[SmoothStreamingMediaElement Class](smoothstreamingmediaelement-class-microsoft-web-media-smoothstreaming_1.md)

[Microsoft.Web.Media.SmoothStreaming Namespace](microsoft-web-media-smoothstreaming-namespace_1.md)
