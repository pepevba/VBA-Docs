---
title: EmptyCell.GridlineTint property (Access)
keywords: vbaac10.chm14636
f1_keywords:
- vbaac10.chm14636
ms.prod: access
api_name:
- Access.EmptyCell.GridlineTint
ms.assetid: a8749810-6ec0-d10b-2ea8-71531e2dac0a
ms.date: 06/08/2017
---


# EmptyCell.GridlineTint property (Access)

Gets or sets the tint applied to the theme color in the  **GridlineColor** property of the specified object. Read/write **Single**.


## Syntax

_expression_. `GridlineTint`

_expression_ A variable that represents an [EmptyCell](Access.EmptyCell.md) object.


## Remarks

The  **GridlineTint** property contains a numeric expression that can be used to lighten the theme color in the **GridlineColor** property. The default value of the **GridlineTint** property is 100, which is neutral, and does not change the theme color. To lighten the color, first determine the percentage by which to lighten from 1 to 100, then subtract that value as a whole number from 100 and use the remainder. For example, to lighten the theme color tint by 75%, subtract 75 from 100 and use the remainder, which is 25.

This property is not surfaced in the property sheet.


## See also


[EmptyCell Object](Access.EmptyCell.md)

