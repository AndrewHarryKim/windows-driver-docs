---
title: Installing IEEE 1394 Device Drivers
author: windows-driver-content
description: Installing IEEE 1394 Device Drivers
MS-HAID:
- '1394-design\_7fceb873-a7f2-4e00-8345-623bf233a6ed.xml'
- 'IEEE.installing\_ieee\_1394\_device\_drivers'
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 3f99bec7-e657-4de7-bce4-36a779cc0442
keywords: ["IEEE 1394 WDK buses , driver installations", "1394 WDK buses , driver installations"]
---

# Installing IEEE 1394 Device Drivers


## <a href="" id="ddk-installing-ieee-1394-device-drivers-kg"></a>


This section provides installation information, specific to IEEE 1394 device drivers in Microsoft Windows 2000 and later operating systems.

Vendors supplying their own IEEE 1394 device driver should make that driver a member of the Base setup class in the [**INF Version Section**](https://msdn.microsoft.com/library/windows/hardware/ff547502) of the driver's INF file. For example:

```
[Version]
Signature="$WINDOWS NT$"
Class = Base
```

There are no other special requirements associated with installing IEEE 1394 device drivers.

For general information about device installation in Windows 2000 and later operating systems, see [Device Installation Overview](https://msdn.microsoft.com/library/windows/hardware/ff549455).

 

 


--------------------


