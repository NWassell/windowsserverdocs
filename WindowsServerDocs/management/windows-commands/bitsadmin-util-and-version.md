---
title: bitsadmin util and version
description: "Windows Commands topic for **bitsadmin util and version** - Displays the version of BITS service."
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 98f17328-dfbd-4cbb-93c1-b8d424bc3f0a
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# bitsadmin util and version

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Displays the version of BITS service.
## Syntax
```
bitsadmin /Util /version [/verbose]
```
## remarks
The **verbose** command performs the following:
-   Displays the file version for each BITS related DLL
-   verifies the BITS Service can be started
-   Displays BITS Group Policy values (Windows Vista only)
## <a name="BKMK_examples"></a>Examples
The following example the version of the BITS Service.
```
C:\>bitsadmin /Util /version
```
## additional references
[Command-Line Syntax Key](command-line-syntax-key.md)