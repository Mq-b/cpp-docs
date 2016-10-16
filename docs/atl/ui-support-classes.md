---
title: "UI Support Classes"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "article"
f1_keywords: 
  - "vc.atl.ui"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "user interfaces, support classes"
  - "user interfaces, ATL classes"
ms.assetid: 313dfc95-308a-4118-b919-5a3c3673b865
caps.latest.revision: 8
ms.author: "mblome"
manager: "ghogen"
translation.priority.ht: 
  - "cs-cz"
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "pl-pl"
  - "pt-br"
  - "ru-ru"
  - "tr-tr"
  - "zh-cn"
  - "zh-tw"
---
# UI Support Classes
The following classes provide general UI support:  
  
-   [IDocHostUIHandlerDispatch](../atl/idochostuihandlerdispatch-interface.md) An interface to the Microsoft HTML parsing and rendering engine.  
  
-   [IOleObjectImpl](../atl/ioleobjectimpl-class.md) Provides the principal methods through which a container communicates with a control. Manages the activation and deactivation of in-place controls.  
  
-   [IOleInPlaceObjectWindowlessImpl](../atl/ioleinplaceobjectwindowlessimpl-class.md) Manages the reactivation of in-place controls. Enables a windowless control to receive messages, as well as to participate in drag-and-drop operations.  
  
-   [IOleInPlaceActiveObjectImpl](../atl/ioleinplaceactiveobjectimpl-class.md) Assists communication between an in-place control and its container.  
  
-   [IViewObjectExImpl](../atl/iviewobjecteximpl-class.md) Enables a control to display itself directly and to notify the container of changes in its display. Provides support for flicker-free drawing, non-rectangular and transparent controls, and hit testing.  
  
## Related Articles  
 [ATL Tutorial](../atl/active-template-library--atl--tutorial.md)  
  
## See Also  
 [Class Overview](../atl/atl-class-overview.md)