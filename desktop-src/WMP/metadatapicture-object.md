---
title: MetadataPicture Object
description: The MetadataPicture object provides a way to retrieve the values of the WM/Picture metadata attribute. This attribute corresponds to album art contained in a digital media file, not to album art downloaded over the Internet.
ms.assetid: 522f6491-e84a-4cde-98db-e55742ed50a2
keywords:
- MetadataPicture Object Windows Media Player
topic_type:
- apiref
api_name:
- MetadataPicture Object
api_type:
- NA
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# MetadataPicture Object

The **MetadataPicture** object provides a way to retrieve the values of the [**WM/Picture**](https://msdn.microsoft.com/library/windows/desktop/dd757977) metadata attribute. This attribute corresponds to album art contained in a digital media file, not to album art downloaded over the Internet.

The **MetadataPicture** object supports the following properties.



| Property                                           | Description                                       |
|----------------------------------------------------|---------------------------------------------------|
| [**description**](metadatapicture-description.md) | Retrieves a description of the metadata image.    |
| [**mimeType**](metadatapicture-mimetype.md)       | Retrieves the MIME type of the metadata image.    |
| [**pictureType**](metadatapicture-picturetype.md) | Retrieves the picture type of the metadata image. |
| [**URL**](metadatapicture-url.md)                 | Internal use only.                                |



 

The **MetadataPicture** object is accessed through the following method.



| Object                        | Method                                               |
|-------------------------------|------------------------------------------------------|
| [**Media**](media-object.md) | [**getItemInfoByType**](media-getiteminfobytype.md) |



 

For purposes of illustration, `player.currentMedia.getItemInfoByType(name, language, index)` is used in the reference syntax sections.

## See also

<dl> <dt>

[**Object Model Reference for Scripting**](object-model-reference-for-scripting.md)
</dt> </dl>

 

 



