---
UID: NS:d3dkmddi._DXGKARG_QUERYCURRENTFENCE
title: _DXGKARG_QUERYCURRENTFENCE (d3dkmddi.h)
description: The DXGKARG_QUERYCURRENTFENCE structure describes the latest completed submission fence.
old-location: display\dxgkarg_querycurrentfence.htm
ms.date: 05/10/2018
keywords: ["DXGKARG_QUERYCURRENTFENCE structure"]
ms.keywords: "*INOUT_PDXGKARG_QUERYCURRENTFENCE, DXGKARG_QUERYCURRENTFENCE, DXGKARG_QUERYCURRENTFENCE structure [Display Devices], DmStructs_799a15e5-b780-43c4-a0c2-d97e3c91caec.xml, _DXGKARG_QUERYCURRENTFENCE, d3dkmddi/DXGKARG_QUERYCURRENTFENCE, display.dxgkarg_querycurrentfence"
req.header: d3dkmddi.h
req.include-header: D3dkmddi.h
req.target-type: Windows
req.target-min-winverclnt: Available in Windows Vista and later versions of the Windows operating systems.
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
tech.root: display
req.typenames: DXGKARG_QUERYCURRENTFENCE
f1_keywords:
 - _DXGKARG_QUERYCURRENTFENCE
 - d3dkmddi/_DXGKARG_QUERYCURRENTFENCE
 - DXGKARG_QUERYCURRENTFENCE
 - d3dkmddi/DXGKARG_QUERYCURRENTFENCE
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - d3dkmddi.h
api_name:
 - _DXGKARG_QUERYCURRENTFENCE
 - DXGKARG_QUERYCURRENTFENCE
---

# _DXGKARG_QUERYCURRENTFENCE structure


## -description

The DXGKARG_QUERYCURRENTFENCE structure describes the latest completed submission fence.

## -struct-fields

### -field CurrentFence [out]

The current fence data.

### -field NodeOrdinal [in]

The zero-based index of the node for the current fence.

### -field EngineOrdinal [in]

The zero-based index of the engine, within the node that <b>NodeOrdinal</b> specifies, for the current fence.

## -see-also

<a href="/windows-hardware/drivers/ddi/d3dkmddi/nc-d3dkmddi-dxgkddi_querycurrentfence">DxgkDdiQueryCurrentFence</a>

