---
title: LVM\_GETVIEWRECT message
description: Retrieves the bounding rectangle of all items in the list-view control. The list view must be in icon or small icon view. You can send this message explicitly or by using the ListView\_GetViewRect macro.
ms.assetid: '69b96f86-8b7e-42c1-ad73-f9b2732ab9f9'
keywords: ["LVM_GETVIEWRECT message Windows Controls"]
topic_type:
- apiref
api_name:
- LVM_GETVIEWRECT
api_location:
- Commctrl.h
api_type:
- HeaderDef
---

# LVM\_GETVIEWRECT message

Retrieves the bounding rectangle of all items in the list-view control. The list view must be in icon or small icon view. You can send this message explicitly or by using the [**ListView\_GetViewRect**](listview-getviewrect.md) macro.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>Must be zero.</dd> <dt>

*lParam* 
</dt> <dd>

Pointer to a [**RECT**](https://msdn.microsoft.com/library/windows/desktop/dd162897) structure that receives the bounding rectangle. All coordinates are relative to the visible area of the list-view control.

</dd> </dl>

## Return value

Returns **TRUE** if successful, or **FALSE** otherwise.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server�2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Commctrl.h</dt> </dl> |



�

�




