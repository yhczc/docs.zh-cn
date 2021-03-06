---
title: 使用 Glyphs 绘制文本
ms.date: 03/30/2017
helpviewer_keywords:
- text [WPF], drawing with Glyphs objects
- Glyphs objects [WPF], drawing text
- typography [WPF], Glyphs objects
ms.assetid: 587ab17e-a419-4ad5-b6da-8933a8e83d97
ms.openlocfilehash: 155f0b756b43ad8cfd0ddde63a5e86854f5f1624
ms.sourcegitcommit: 0c48191d6d641ce88d7510e319cf38c0e35697d0
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/05/2019
ms.locfileid: "57363002"
---
# <a name="draw-text-using-glyphs"></a>使用 Glyphs 绘制文本
本主题说明如何使用低级<xref:System.Windows.Documents.Glyphs>对象中显示的文本[!INCLUDE[TLA#tla_xaml](../../../../includes/tlasharptla-xaml-md.md)]。  
  
## <a name="example"></a>示例  
 以下示例演示如何定义的属性<xref:System.Windows.Documents.Glyphs>对象中[!INCLUDE[TLA#tla_xaml](../../../../includes/tlasharptla-xaml-md.md)]。 <xref:System.Windows.Documents.Glyphs>对象表示的输出<xref:System.Windows.Media.GlyphRun>中[!INCLUDE[TLA2#tla_xaml](../../../../includes/tla2sharptla-xaml-md.md)]。 示例假定本地计算机上的 C:\WINDOWS\Fonts 文件夹中安装了 Arial、Courier New 和 Times New Roman 字体。  
  
 [!code-xaml[GlyphsOvwSample1#1](~/samples/snippets/csharp/VS_Snippets_Wpf/GlyphsOvwSample1/CS/default.xaml#1)]  
  
 此示例演示如何定义的其他属性<xref:System.Windows.Documents.Glyphs>中的对象[!INCLUDE[TLA2#tla_xaml](../../../../includes/tla2sharptla-xaml-md.md)]。  
  
 [!code-xaml[GlyphsOvwSamp2#1](~/samples/snippets/csharp/VS_Snippets_Wpf/GlyphsOvwSamp2/CS/default.xaml#1)]  
  
## <a name="see-also"></a>请参阅
- [WPF 中的版式](typography-in-wpf.md)
