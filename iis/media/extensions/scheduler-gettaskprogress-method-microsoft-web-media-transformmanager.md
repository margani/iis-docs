﻿---
title: Scheduler.GetTaskProgress Method  (Microsoft.Web.Media.TransformManager)
TOCTitle: GetTaskProgress Method
ms:assetid: M:Microsoft.Web.Media.TransformManager.Scheduler.GetTaskProgress(System.String)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.scheduler.gettaskprogress(v=VS.90)
ms:contentKeyID: 35520595
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.Scheduler.GetTaskProgress
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.Common.dll
api_name:
- Microsoft.Web.Media.TransformManager.Scheduler.GetTaskProgress
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# GetTaskProgress Method

Returns task progress for the specified job.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.Common (in Microsoft.Web.Media.TransformManager.Common.dll)

## Syntax

``` vb
'Declaration
PublicMustOverrideFunctionGetTaskProgress ( _
    jobInstanceIdAsString _
) AsTaskDetails
'Usage
DiminstanceAsSchedulerDimjobInstanceIdAsStringDimreturnValueAsTaskDetailsreturnValue = instance.GetTaskProgress(jobInstanceId)
```

``` csharp
publicabstractTaskDetailsGetTaskProgress(
    stringjobInstanceId
)
```

``` c++
public:
virtualTaskDetailsGetTaskProgress(
    String^ jobInstanceId
) abstract
```

``` fsharp
abstractGetTaskProgress : 
        jobInstanceId:string->TaskDetails
```

``` jscript
publicabstractfunctionGetTaskProgress(
    jobInstanceId : String
) : TaskDetails
```

#### Parameters

  - jobInstanceId  
    Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
    The ID of the job.  

#### Return Value

Type: [Microsoft.Web.Media.TransformManager. . :: . .TaskDetails](taskdetails-structure-microsoft-web-media-transformmanager.md)  
The task progress.  

## See Also

#### Reference

[Scheduler Class](scheduler-class-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)
