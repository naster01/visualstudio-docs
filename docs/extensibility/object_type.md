---
title: "OBJECT_TYPE"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: na
ms.topic: "article"
f1_keywords: 
  - "OBJECT_TYPE"
helpviewer_keywords: 
  - "OBJECT_TYPE enumeration"
ms.assetid: c4d246f9-8a98-44ec-b2bb-ff5c684f668e
caps.latest.revision: 9
ms.author: "gregvanl"
manager: "ghogen"
translation.priority.mt: 
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
# OBJECT_TYPE
Specifies the type of an object from the expression evaluator.  
  
## Syntax  
  
```cpp#  
enum enum_OBJECT_TYPE {   
   OBJECT_TYPE_BOOLEAN = 0x0,  
   OBJECT_TYPE_CHAR    = 0x1,  
   OBJECT_TYPE_I1      = 0x2,  
   OBJECT_TYPE_U1      = 0x3,  
   OBJECT_TYPE_I2      = 0x4,  
   OBJECT_TYPE_U2      = 0x5,  
   OBJECT_TYPE_I4      = 0x6,  
   OBJECT_TYPE_U4      = 0x7,  
   OBJECT_TYPE_I8      = 0x8,  
   OBJECT_TYPE_U8      = 0x9,  
   OBJECT_TYPE_R4      = 0xa,  
   OBJECT_TYPE_R8      = 0xb,  
   OBJECT_TYPE_OBJECT  = 0xc,  
   OBJECT_TYPE_NULL    = 0xd,  
   OBJECT_TYPE_CLASS   = 0xe  
};  
typedef DWORD OBJECT_TYPE;  
```  
  
```c#  
public enum enum_OBJECT_TYPE {   
   OBJECT_TYPE_BOOLEAN = 0x0,  
   OBJECT_TYPE_CHAR    = 0x1,  
   OBJECT_TYPE_I1      = 0x2,  
   OBJECT_TYPE_U1      = 0x3,  
   OBJECT_TYPE_I2      = 0x4,  
   OBJECT_TYPE_U2      = 0x5,  
   OBJECT_TYPE_I4      = 0x6,  
   OBJECT_TYPE_U4      = 0x7,  
   OBJECT_TYPE_I8      = 0x8,  
   OBJECT_TYPE_U8      = 0x9,  
   OBJECT_TYPE_R4      = 0xa,  
   OBJECT_TYPE_R8      = 0xb,  
   OBJECT_TYPE_OBJECT  = 0xc,  
   OBJECT_TYPE_NULL    = 0xd,  
   OBJECT_TYPE_CLASS   = 0xe  
};  
```  
  
## Members  
 OBJECT_TYPE_BOOLEAN  
 Indicates that the object is a Boolean.  
  
 OBJECT_TYPE_CHAR  
 Indicates that the object is a character.  
  
 OBJECT_TYPE_I1  
 Indicates that the object is a one-byte signed integer.  
  
 OBJECT_TYPE_U1  
 Indicates that the object is a one-byte unsigned integer.  
  
 OBJECT_TYPE_I2  
 Indicates that the object is a two-byte signed integer.  
  
 OBJECT_TYPE_U2  
 Indicates that the object is a two-byte unsigned integer.  
  
 OBJECT_TYPE_I4  
 Indicates that the object is a four-byte signed integer.  
  
 OBJECT_TYPE_U4  
 Indicates that the object is a four-byte unsigned integer.  
  
 OBJECT_TYPE_I8  
 Indicates that the object is an eight-byte signed integer.  
  
 OBJECT_TYPE_U8  
 Indicates that the object is an eight-byte unsigned integer.  
  
 OBJECT_TYPE_R4  
 Indicates that the object is a four-byte floating-point number.  
  
 OBJECT_TYPE_R8  
 Indicates that the object is an eight-byte floating-point number.  
  
 OBJECT_TYPE_OBJECT  
 Indicates that the object is an object.  
  
 OBJECT_TYPE_NULL  
 Indicates that the object is NULL.  
  
 OBJECT_TYPE_CLASS  
 Indicates that the object is a class.  
  
## Remarks  
 Passed as an argument to the [CreatePrimitiveObject](../extensibility/idebugfunctionobject--createprimitiveobject.md) and [CreateArrayObject](../extensibility/idebugfunctionobject--createarrayobject.md) methods.  
  
## Requirements  
 Header: ee.h  
  
 Namespace: Microsoft.VisualStudio.Debugger.Interop  
  
 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll  
  
## See Also  
 [Enumerations](../extensibility/enumerations--visual-studio-debugging-.md)   
 [CreatePrimitiveObject](../extensibility/idebugfunctionobject--createprimitiveobject.md)   
 [CreateArrayObject](../extensibility/idebugfunctionobject--createarrayobject.md)