---
title: Documents.DataRecordsetChanged Event (Visio)
keywords: vis_sdr.chm10662025
f1_keywords:
- vis_sdr.chm10662025
ms.prod: visio
api_name:
- Visio.Documents.DataRecordsetChanged
ms.assetid: 39febf24-a586-f56d-285f-9e36794db28d
ms.date: 06/08/2017
---


# Documents.DataRecordsetChanged Event (Visio)

Occurs when a data recordset changes as a result of being refreshed.


 **Note**  This Visio object or member is available only to licensed users of Visio Professional 2013.


## Syntax

Private Sub  _expression_ _**DataRecordsetChanged**( **_ByVal DataRecordsetChanged As IVDATARECORDSETCHANGEDEVENT_** )

 _expression_ An expression that returns a **Documents** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _DataRecordsetChanged_|Required| **[IVDATARECORDSETCHANGEDEVENT]**|The data recordset that changed.|

## Remarks

When the  **DataRecordsetChanged** event fires, the **[DataRecordsetChangedEvent](datarecordsetchangedevent-object-visio.md)** object is passed to the **[IVisEventProc.VisEventProc](iviseventproc-viseventproc-method-visio.md)** method as the pSubjectObj parameter, which represents he subject of the event?the object to which the event occurs.

If you're using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own  **Event** objects, use the **Add** or **AddAdvise** method. To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. To create an **Event** object that receives notification, use the **AddAdvise** method. To find an event code for the event you want to create, see[Event codes](http://msdn.microsoft.com/library/de8f5c7a-421d-ebcf-22b6-4310a202ef64%28Office.15%29.aspx).


