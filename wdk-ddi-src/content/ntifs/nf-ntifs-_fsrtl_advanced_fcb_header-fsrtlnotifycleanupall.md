---
UID: NF:ntifs.FsRtlNotifyCleanupAll
title: FsRtlNotifyCleanupAll function (ntifs.h)
description: The FsRtlNotifyCleanupAll routine removes all members of the specified notification list.
old-location: ifsk\fsrtlnotifycleanupall.htm
tech.root: ifsk
ms.date: 04/16/2018
keywords: ["FsRtlNotifyCleanupAll function"]
ms.keywords: FsRtlNotifyCleanupAll, FsRtlNotifyCleanupAll routine [Installable File System Drivers], fsrtlref_f0eea2f1-9bc9-41e1-843c-a69b3e63f452.xml, ifsk.fsrtlnotifycleanupall, ntifs/FsRtlNotifyCleanupAll
req.header: ntifs.h
req.include-header: FltKernel.h, Ntifs.h
req.target-type: Universal
req.target-min-winverclnt: Available in Windows Vista and later version of the Windows operating system.
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
req.irql: <=APC_LEVEL
targetos: Windows
req.typenames: 
ms.custom: RS5
f1_keywords:
 - FsRtlNotifyCleanupAll
 - ntifs/FsRtlNotifyCleanupAll
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - DllExport
api_location:
 - NtosKrnl.exe
api_name:
 - FsRtlNotifyCleanupAll
dev_langs:
 - c++
---

# FsRtlNotifyCleanupAll function


## -description

The <b>FsRtlNotifyCleanupAll</b> routine removes all members of the specified notification list.

## -parameters

### -param NotifySync [in]


A pointer to the opaque synchronization object for <i>NotifyList</i>.

### -param NotifyList [in]


A pointer to the head of the notify list to be cleaned up. Each element in the list is an opaque notify structure.

## -remarks

For each entry in the <i>NotifyList</i> list, <b>FsRtlNotifyCleanupAll</b> completes all pending IRPs. Then the routine removes the entry from the list and deallocates the entry.

Because a notify list is typically associated with a volume, the <b>FsRtlNotifyCleanupAll</b> routine can be used to complete all the IRP requests for the volume.

## -see-also

<a href="/windows-hardware/drivers/ddi/ntifs/nf-ntifs-_fsrtl_advanced_fcb_header-fsrtlnotifycleanup">FsRtlNotifyCleanup</a>



<a href="/windows-hardware/drivers/ddi/ntifs/nf-ntifs-_fsrtl_advanced_fcb_header-fsrtlnotifyfilterchangedirectory">FsRtlNotifyFilterChangeDirectory</a>



<a href="/windows-hardware/drivers/ddi/ntifs/nf-ntifs-_fsrtl_advanced_fcb_header-fsrtlnotifyfilterreportchange">FsRtlNotifyFilterReportChange</a>



<a href="/windows-hardware/drivers/ddi/ntifs/nf-ntifs-_fsrtl_advanced_fcb_header-fsrtlnotifyfullchangedirectory">FsRtlNotifyFullChangeDirectory</a>



<a href="/windows-hardware/drivers/ddi/ntifs/nf-ntifs-_fsrtl_advanced_fcb_header-fsrtlnotifyfullreportchange">FsRtlNotifyFullReportChange</a>
