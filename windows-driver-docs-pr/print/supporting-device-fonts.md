---
title: Supporting Device Fonts
author: windows-driver-content
description: Supporting Device Fonts
MS-HAID:
- 'drvarch\_09c2d828-68d3-4a9f-b82b-ba79ca7b126b.xml'
- 'print.supporting\_device\_fonts'
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 9ca3269d-3f87-4d8a-a897-7305ac172227
keywords: ["printer graphics DLL WDK , device fonts", "graphics DLL WDK printer , device fonts", "device fonts WDK printer graphics", "fonts WDK printer graphics"]
---

# Supporting Device Fonts


## <a href="" id="ddk-supporting-device-fonts-gg"></a>


If a printer provides device fonts, the printer graphics DLL must define a [**DrvTextOut**](https://msdn.microsoft.com/library/windows/hardware/ff557277) function to generate text output commands. The graphics DLL must also define the following functions:

[**DrvQueryAdvanceWidths**](https://msdn.microsoft.com/library/windows/hardware/ff556259)
[**DrvQueryFont**](https://msdn.microsoft.com/library/windows/hardware/ff556262)
[**DrvQueryFontData**](https://msdn.microsoft.com/library/windows/hardware/ff556264)
[**DrvQueryFontTree**](https://msdn.microsoft.com/library/windows/hardware/ff556266)
For more information about supporting device fonts, see [Supporting Graphics DDI Font and Text Functions](https://msdn.microsoft.com/library/windows/hardware/ff569868).

 

 


--------------------
[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bprint\print%5D:%20Supporting%20Device%20Fonts%20%20RELEASE:%20%289/1/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")


