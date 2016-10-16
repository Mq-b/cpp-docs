---
title: "Types of Linkage"
ms.custom: na
ms.date: 10/03/2016
ms.devlang: 
  - C++
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - devlang-cpp
ms.tgt_pltfrm: na
ms.topic: language-reference
ms.assetid: 41326c7f-4602-4bad-a648-697604858ba0
caps.latest.revision: 7
manager: ghogen
translation.priority.ht: 
  - cs-cz
  - de-de
  - es-es
  - fr-fr
  - it-it
  - ja-jp
  - ko-kr
  - pl-pl
  - pt-br
  - ru-ru
  - tr-tr
  - zh-cn
  - zh-tw
---
# Types of Linkage
The way the names of objects and functions are shared between translation units is called linkage. These names can have:  
  
-   Internal linkage, in which case they refer only to program elements inside their own translation units; they are not shared with other translation units.  
  
     The same name in another translation unit may refer to a different object or a different class. Names with internal linkage are sometimes referred to as being local to their translation units.  
  
     An example declaration of a name with internal linkage is:  
  
    ```  
    static int i;   // The static keyword ensures internal linkage.  
    ```  
  
-   External linkage, in which case they can refer to program elements in any translation unit in the program — the program element is shared among the translation units.  
  
     The same name in another translation unit is guaranteed to refer to the same object or class. Names with external linkage are sometimes referred to as being global.  
  
     An example declaration of a name with external linkage is:  
  
    ```  
    extern int i;  
    ```  
  
-   No linkage, in which case they refer to unique entities. The same name in another scope may not refer to the same object. An example is an enumeration. (Note, however, that you can pass a pointer to an object with no linkage. This makes the object accessible in other translation units.)  
  
## See Also  
 [Program and Linkage](../VS_visualcpp/Program-and-Linkage---C---.md)