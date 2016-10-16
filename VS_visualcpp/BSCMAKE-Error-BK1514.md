---
title: "BSCMAKE Error BK1514"
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
ms.topic: error-reference
ms.assetid: 7c7e2504-a490-44ab-bb1f-47385ee2f4b0
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
# BSCMAKE Error BK1514
all .SBR files truncated, none found in filename  
  
 None of the .sbr files specified for an update were part of the original browse information (.bsc) file. To find the names of the .sbr files that caused this error, read the [BK4502](../VS_visualcpp/BSCMAKE-Warning-BK4502.md) warnings that precede it.  
  
### To fix by checking the following possible causes  
  
1.  Wrong filename specified for .sbr or .bsc.  
  
2.  Corrupted .bsc file required BSCMAKE to rebuild it.