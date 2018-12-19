﻿---
title: DeploymentLinkExtension.Enabled Property  (Microsoft.Web.Deployment)
TOCTitle: Enabled Property
ms:assetid: P:Microsoft.Web.Deployment.DeploymentLinkExtension.Enabled
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.deployment.deploymentlinkextension.enabled(v=VS.90)
ms:contentKeyID: 20209296
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Deployment.DeploymentLinkExtension.Enabled
- Microsoft.Web.Deployment.DeploymentLinkExtension.get_Enabled
- Microsoft.Web.Deployment.DeploymentLinkExtension.set_Enabled
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Deployment.dll
api_name:
- Microsoft.Web.Deployment.DeploymentLinkExtension.Enabled
- Microsoft.Web.Deployment.DeploymentLinkExtension.get_Enabled
- Microsoft.Web.Deployment.DeploymentLinkExtension.set_Enabled
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# Enabled Property

Gets or sets a value that determines if the link extension is enabled or disabled.

**Namespace:**  [Microsoft.Web.Deployment](microsoft-web-deployment-namespace.md)  
**Assembly:**  Microsoft.Web.Deployment (in Microsoft.Web.Deployment.dll)

## Syntax

``` vb
'Declaration
PublicPropertyEnabledAsBoolean
'Usage
DiminstanceAsDeploymentLinkExtensionDimvalueAsBooleanvalue = instance.Enabled

instance.Enabled = value
```

``` csharp
publicboolEnabled { get; set; }
```

``` c++
public:
propertyboolEnabled {
    boolget ();
    voidset (boolvalue);
}
```

``` jscript
function getEnabled () : booleanfunction setEnabled (value : boolean)
```

#### Property Value

Type: [System. . :: . .Boolean](https://msdn.microsoft.com/en-us/library/a28wyd50\(v=vs.90\))  
true if the link extension is enabled, otherwise false.  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[DeploymentLinkExtension Class](deploymentlinkextension-class-microsoft-web-deployment.md)

[Microsoft.Web.Deployment Namespace](microsoft-web-deployment-namespace.md)
