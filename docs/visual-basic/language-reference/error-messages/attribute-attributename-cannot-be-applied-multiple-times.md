---
title: 特性“<attributename>”不能应用多次
ms.date: 07/20/2015
f1_keywords:
- bc30663
- vbc30663
helpviewer_keywords:
- BC30663
ms.assetid: 3760e7ff-7238-40a1-8676-77d858a64fc0
ms.openlocfilehash: 62e84d174e4e218472eda9b7c08ed677e0140438
ms.sourcegitcommit: 14355b4b2fe5bcf874cac96d0a9e6376b567e4c7
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/30/2019
ms.locfileid: "55278702"
---
# <a name="attribute-attributename-cannot-be-applied-multiple-times"></a>属性 '\<attributename > 不能应用多次
该特性仅应用一次。 `AttributeUsage`属性确定是否可以多次应用属性。  
  
 **错误 ID:** BC30663  
  
## <a name="to-correct-this-error"></a>更正此错误  
  
1.  请确保该属性只应用一次。  
  
2.  如果使用的您开发的自定义特性，请考虑更改其`AttributeUsage`属性以允许多个特性用法，与下面的示例一样。  
  
```vb  
<AttributeUsage(AllowMultiple := True)>  
```  
  
## <a name="see-also"></a>请参阅
- <xref:System.AttributeUsageAttribute>
- [创建自定义特性](../../../visual-basic/programming-guide/concepts/attributes/creating-custom-attributes.md)
- [AttributeUsage](../../../visual-basic/programming-guide/concepts/attributes/attributeusage.md)
