---
title: "Compiler Error C2624"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "error-reference"
f1_keywords: 
  - "C2624"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "C2624"
ms.assetid: 32f2ec15-a7cd-4049-a64b-131746d3152b
caps.latest.revision: 7
ms.author: "corob"
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
# Compiler Error C2624
local classes cannot be used to declare 'extern' variables  
  
 A local class or structure cannot be used to declare `extern` variables.  
  
 The following sample generates C2624:  
  
```  
// C2624.cpp  
int main() {  
   struct C {};  
   extern C ac;   // C2624  
}  
```