---
UID: NF:ntifs.FsRtlAcknowledgeEcp
title: FsRtlAcknowledgeEcp function (ntifs.h)
description: The FsRtlAcknowledgeEcp routine marks an extra create parameter (ECP) context structure as acknowledged.
old-location: ifsk\fsrtlacknowledgeecp.htm
tech.root: ifsk
ms.date: 04/16/2018
keywords: ["FsRtlAcknowledgeEcp function"]
ms.keywords: FsRtlAcknowledgeEcp, FsRtlAcknowledgeEcp routine [Installable File System Drivers], fsrtlref_2c3b8577-e61e-4ff3-9443-b3838077d762.xml, ifsk.fsrtlacknowledgeecp, ntifs/FsRtlAcknowledgeEcp
req.header: ntifs.h
req.include-header: Ntifs.h
req.target-type: Universal
req.target-min-winverclnt: Available starting with Windows Vista.
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
req.lib: NtosKrnl.lib
req.dll: NtosKrnl.exe
req.irql: <= APC_LEVEL
targetos: Windows
req.typenames: 
f1_keywords:
 - FsRtlAcknowledgeEcp
 - ntifs/FsRtlAcknowledgeEcp
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - DllExport
api_location:
 - NtosKrnl.exe
api_name:
 - FsRtlAcknowledgeEcp
---

# FsRtlAcknowledgeEcp function


## -description

The <b>FsRtlAcknowledgeEcp</b> routine marks an extra create parameter (ECP) context structure as acknowledged.

## -parameters

### -param EcpContext [in]


A pointer to the ECP to mark as acknowledged.

## -remarks

When <b>FsRtlAcknowledgeEcp</b> marks an ECP as acknowledged, it could indicate   whether the ECP has been looked at, used, processed, or any other condition of the ECP.  

You can use the <a href="/windows-hardware/drivers/ddi/fltkernel/nf-fltkernel-fltisecpacknowledged">FltIsEcpAcknowledged</a> routine to determine if a particular ECP has been marked as acknowledged.

## -see-also

<a href="/previous-versions/windows/hardware/drivers/ff540148(v=vs.85)">ECP_LIST</a>



<a href="/windows-hardware/drivers/ddi/fltkernel/nf-fltkernel-fltallocateextracreateparameterfromlookasidelist">FltAllocateExtraCreateParameterFromLookasideList</a>



<a href="/windows-hardware/drivers/ddi/fltkernel/nf-fltkernel-fltfreeextracreateparameter">FltFreeExtraCreateParameter</a>



<a href="/windows-hardware/drivers/ddi/fltkernel/nf-fltkernel-fltgetecplistfromcallbackdata">FltGetEcpListFromCallbackData</a>



<a href="/windows-hardware/drivers/ddi/fltkernel/nf-fltkernel-fltisecpacknowledged">FltIsEcpAcknowledged</a>



<a href="/windows-hardware/drivers/ddi/fltkernel/nf-fltkernel-fltisecpfromusermode">FltIsEcpFromUserMode</a>



<a href="/windows-hardware/drivers/ddi/fltkernel/nf-fltkernel-fltremoveextracreateparameter">FltRemoveExtraCreateParameter</a>



<a href="/windows-hardware/drivers/ddi/fltkernel/nf-fltkernel-fltsetecplistintocallbackdata">FltSetEcpListIntoCallbackData</a>
