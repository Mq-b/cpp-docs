---
title: "int_4::int_4 Constructor"
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
ms.topic: article
ms.assetid: 27ec1a04-9e4b-4fde-8c27-9d5b0a8805a5
caps.latest.revision: 4
manager: ghogen
translation.priority.ht: 
  - de-de
  - es-es
  - fr-fr
  - it-it
  - ja-jp
  - ko-kr
  - ru-ru
  - zh-cn
  - zh-tw
translation.priority.mt: 
  - cs-cz
  - pl-pl
  - pt-br
  - tr-tr
---
# int_4::int_4 Constructor
Default constructor, initializes all elements with 0.  
  
## Syntax  
  
```  
int_4() restrict(amp,cpu);  
int_4(  
   int _V0,  
   int _V1,  
   int _V2,  
   int _V3  
) restrict(amp,cpu);  
int_4(  
   int _V  
) restrict(amp,cpu);  
int_4(  
   const int_4& _Other  
) restrict(amp,cpu);  
explicit inline int_4(  
   const uint_4& _Other  
) restrict(amp,cpu);  
explicit inline int_4(  
   const float_4& _Other  
) restrict(amp,cpu);  
explicit inline int_4(  
   const unorm_4& _Other  
) restrict(amp,cpu);  
explicit inline int_4(  
   const norm_4& _Other  
) restrict(amp,cpu);  
explicit inline int_4(  
   const double_4& _Other  
) restrict(amp,cpu);  
```  
  
#### Parameters  
 `_V0`  
 The value to initialize element 0.  
  
 `_V1`  
 The value to initialize element 1.  
  
 `_V2`  
 The value to initialize element 2.  
  
 `_V3`  
 The value to initialize element 3.  
  
 `_V`  
 The value for initialization.  
  
 `_Other`  
 The object used to initialize.  
  
## Requirements  
 **Header:** amp_short_vectors.h  
  
 **Namespace:** Concurrency::graphics  
  
## See Also  
 [int_4 Class](../VS_visualcpp/int_4-Class.md)