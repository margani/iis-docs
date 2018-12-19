﻿---
title: ConfigurationBase.ConfigurationDirectory Property  (Microsoft.Web.Media.TransformManager)
TOCTitle: ConfigurationDirectory Property
ms:assetid: P:Microsoft.Web.Media.TransformManager.ConfigurationBase.ConfigurationDirectory
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.configurationbase.configurationdirectory(v=VS.90)
ms:contentKeyID: 35520680
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.ConfigurationBase.get_ConfigurationDirectory
- Microsoft.Web.Media.TransformManager.ConfigurationBase.ConfigurationDirectory
- Microsoft.Web.Media.TransformManager.ConfigurationBase.set_ConfigurationDirectory
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.Common.dll
api_name:
- Microsoft.Web.Media.TransformManager.ConfigurationBase.ConfigurationDirectory
- Microsoft.Web.Media.TransformManager.ConfigurationBase.get_ConfigurationDirectory
- Microsoft.Web.Media.TransformManager.ConfigurationBase.set_ConfigurationDirectory
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# ConfigurationDirectory Property

Gets or sets the configuration directory path for the IIS Transform Manager configuration.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.Common (in Microsoft.Web.Media.TransformManager.Common.dll)

## Syntax

``` vb
'Declaration
PublicSharedPropertyConfigurationDirectoryAsStringGetSet
'Usage
DimvalueAsStringvalue = ConfigurationBase.ConfigurationDirectoryConfigurationBase.ConfigurationDirectory = value
```

``` csharp
publicstaticstringConfigurationDirectory { get; set; }
```

``` c++
public:
staticpropertyString^ ConfigurationDirectory {
    String^ get ();
    voidset (String^ value);
}
```

``` fsharp
staticmemberConfigurationDirectory : stringwithget, set
```

``` jscript
staticfunction getConfigurationDirectory () : Stringstaticfunction setConfigurationDirectory (value : String)
```

#### Property Value

Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
The configuration directory path.  

## See Also

#### Reference

[ConfigurationBase Class](configurationbase-class-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)
