---
title: "ODBC and MFC"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "ODBC [C++], MFC"
  - "connections [C++], databases"
  - "connections [C++], data source"
  - "databases [C++], connecting to"
  - "data sources [C++], connecting to"
  - "MFC [C++], ODBC and"
  - "database connections [C++], MFC ODBC classes"
ms.assetid: 98f02fd7-1235-437b-89a9-edfd0fc797f7
caps.latest.revision: 10
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
# ODBC and MFC
> [!NOTE]
>  To use the MFC database classes for targeting a Win32 platform (such as Windows NT), you must have the appropriate ODBC driver for your data source. Some drivers are included with Visual C++; others can be obtained from Microsoft and other vendors. For more information, see [ODBC Driver List](../data/odbc-driver-list.md).  
  
 This topic introduces the main concepts of the Microsoft Foundation Classes (MFC) library's ODBC-based database classes and provides an overview of how the classes work together. For more information about ODBC and MFC, see the following topics:  
  
-   [Connecting to a Data Source](../data/connecting-to-a-data-source.md)  
  
-   [Selecting and Manipulating Records](../data/selecting-and-manipulating-records.md)  
  
-   [Displaying and Manipulating Data in a Form](../data/displaying-and-manipulating-data-in-a-form.md)  
  
-   [Working with Documents and views](../data/working-with-documents-and-views.md)  
  
-   [Access to ODBC and SQL](../data/access-to-odbc-and-sql.md)  
  
-   [Further Reading About the MFC ODBC Classes](../data/further-reading-about-the-mfc-odbc-classes.md)  
  
 The MFC database classes based on ODBC are designed to provide access to any database for which an ODBC driver is available. Because the classes use ODBC, your application can access data in many different data formats and different local/remote configurations. You do not have to write special-case code to handle different database management systems (DBMSs). As long as your users have an appropriate ODBC driver for the data they want to access, they can use your program to manipulate data in tables stored there.  
  
## See Also  
 [Open Database Connectivity (ODBC)](../data/open-database-connectivity--odbc-.md)