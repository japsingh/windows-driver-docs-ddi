---
UID: NE:d3dkmdt._D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY
title: D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY (d3dkmdt.h)
description: The D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY enumerated type indicates the type of connector a video output device (on the display adapter) uses to connect to an external display device.
old-location: display\d3dkmdt_video_output_technology.htm
tech.root: display
ms.date: 07/29/2022
keywords: ["D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY enumeration"]
ms.keywords: D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY, D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY enumeration [Display Devices], D3DKMDT_VOT_BNC, D3DKMDT_VOT_COMPONENT_VIDEO, D3DKMDT_VOT_COMPOSITE_VIDEO, D3DKMDT_VOT_DISPLAYPORT_EMBEDDED, D3DKMDT_VOT_DISPLAYPORT_EXTERNAL, D3DKMDT_VOT_DVI, D3DKMDT_VOT_D_JPN, D3DKMDT_VOT_HD15, D3DKMDT_VOT_HDMI, D3DKMDT_VOT_INTERNAL, D3DKMDT_VOT_LVDS, D3DKMDT_VOT_MIRACAST, D3DKMDT_VOT_OTHER, D3DKMDT_VOT_RCA_3COMPONENT, D3DKMDT_VOT_RF, D3DKMDT_VOT_SDI, D3DKMDT_VOT_SDTVDONGLE, D3DKMDT_VOT_SVIDEO, D3DKMDT_VOT_SVIDEO_4PIN, D3DKMDT_VOT_SVIDEO_7PIN, D3DKMDT_VOT_UDI_EMBEDDED, D3DKMDT_VOT_UDI_EXTERNAL, D3DKMDT_VOT_UNINITIALIZED, DmEnums_c4d89369-4b10-4033-9bb6-218904fc5c5a.xml, _D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY, d3dkmdt/D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY, d3dkmdt/D3DKMDT_VOT_BNC, d3dkmdt/D3DKMDT_VOT_COMPONENT_VIDEO, d3dkmdt/D3DKMDT_VOT_COMPOSITE_VIDEO, d3dkmdt/D3DKMDT_VOT_DISPLAYPORT_EMBEDDED, d3dkmdt/D3DKMDT_VOT_DISPLAYPORT_EXTERNAL, d3dkmdt/D3DKMDT_VOT_DVI, d3dkmdt/D3DKMDT_VOT_D_JPN, d3dkmdt/D3DKMDT_VOT_HD15, d3dkmdt/D3DKMDT_VOT_HDMI, d3dkmdt/D3DKMDT_VOT_INTERNAL, d3dkmdt/D3DKMDT_VOT_LVDS, d3dkmdt/D3DKMDT_VOT_MIRACAST, d3dkmdt/D3DKMDT_VOT_OTHER, d3dkmdt/D3DKMDT_VOT_RCA_3COMPONENT, d3dkmdt/D3DKMDT_VOT_RF, d3dkmdt/D3DKMDT_VOT_SDI, d3dkmdt/D3DKMDT_VOT_SDTVDONGLE, d3dkmdt/D3DKMDT_VOT_SVIDEO, d3dkmdt/D3DKMDT_VOT_SVIDEO_4PIN, d3dkmdt/D3DKMDT_VOT_SVIDEO_7PIN, d3dkmdt/D3DKMDT_VOT_UDI_EMBEDDED, d3dkmdt/D3DKMDT_VOT_UDI_EXTERNAL, d3dkmdt/D3DKMDT_VOT_UNINITIALIZED, display.d3dkmdt_video_output_technology
req.header: d3dkmdt.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista
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
req.typenames: D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY
f1_keywords:
 - _D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY
 - d3dkmdt/_D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY
 - D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY
 - d3dkmdt/D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - d3dkmdt.h
api_name:
 - _D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY
 - D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY
---

# D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY enumeration

## -description

A **D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY** enumeration value indicates the type of connector a video output device (on the display adapter) uses to connect to an external display device.

## -enum-fields

### -field D3DKMDT_VOT_UNINITIALIZED:-2

A variable of type **D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY** has not yet been assigned a meaningful value.

### -field D3DKMDT_VOT_OTHER:-1

The video output device connects to an external display device through a connector that is not one of the types that is indicated by the following values in this enumeration.

### -field D3DKMDT_VOT_HD15:0

The video output device connects to an external display device through an HD15 (VGA) connector.

### -field D3DKMDT_VOT_SVIDEO:1

The video output device connects to an external display device through an S-video connector.

### -field D3DKMDT_VOT_COMPOSITE_VIDEO:2

The video output device connects to an external display device through composite video connectors.

### -field D3DKMDT_VOT_COMPONENT_VIDEO:3

The video output device connects to an external display device through component video connectors.

### -field D3DKMDT_VOT_DVI:4

The video output device connects to an external display device through a Digital Video Interface (DVI) connector.

### -field D3DKMDT_VOT_HDMI:5

The video output device connects to an external display device through an High-Definition Multimedia Interface (HDMI) connector.

### -field D3DKMDT_VOT_LVDS:6

The video output device connects to an external display device through an Low Voltage Differential Swing (LVDS) or Mobile Industry Processor Interface (MIPI) Digital Serial Interface (DSI) connector.

### -field D3DKMDT_VOT_D_JPN:8

The video output device connects to an external display device through a D-Jpn connector.

### -field D3DKMDT_VOT_SDI:9

The video output device connects to an external display device through an SDI connector.

### -field D3DKMDT_VOT_DISPLAYPORT_EXTERNAL:10

The connector type is an external display port.

### -field D3DKMDT_VOT_DISPLAYPORT_EMBEDDED:11

The connector type is an embedded display port.

### -field D3DKMDT_VOT_UDI_EXTERNAL:12

The connector type is an external Unified Display Interface (UDI).

### -field D3DKMDT_VOT_UDI_EMBEDDED:13

The connector type is an embedded UDI.

### -field D3DKMDT_VOT_SDTVDONGLE:14

The video output device connects to an external display device through a dongle cable that supports SDTV.

### -field D3DKMDT_VOT_MIRACAST:15

The video output device connects to an external display device wirelessly through a Miracast connected session. For more info, see [Wireless displays (Miracast)](/windows-hardware/drivers/display/wireless-displays--miracast-). Supported starting with Windows 8.1 (WDDM 1.3)

### -field D3DKMDT_VOT_INDIRECT_WIRED:16

The video output device connects to a wired indirect display device. Supported starting with Windows 10 version 1607 (WDDM 2.1).

### -field D3DKMDT_VOT_INDIRECT_VIRTUAL:17

The video output device connects to a virtual indirect display device. Supported starting with Windows 10 version 1809 (WDDM 2.5).

### -field D3DKMDT_VOT_INTERNAL:0x80000000

The video output device connects internally to a display device (for example, the internal connection in a laptop computer). This constant value is not a bit-field value. Instead, it's a standalone video output type.

### -field D3DKMDT_VOT_SVIDEO_4PIN:D3DKMDT_VOT_SVIDEO

The video output device connects to an external display device through a 4-pin S-video connector.

### -field D3DKMDT_VOT_SVIDEO_7PIN:D3DKMDT_VOT_SVIDEO

The video output device connects to an external display device through a 7-pin S-video connector.

### -field D3DKMDT_VOT_RF:D3DKMDT_VOT_COMPOSITE_VIDEO

The video output device connects to an external display device through an RF connector.

### -field D3DKMDT_VOT_RCA_3COMPONENT:D3DKMDT_VOT_COMPOSITE_VIDEO

The video output device connects to an external display device through a set of three RCA connectors.

### -field D3DKMDT_VOT_BNC:D3DKMDT_VOT_COMPOSITE_VIDEO

The video output device connects to an external display device through a BNC connector.

## -remarks

The **ChildCapabilities** member of a [**DXGK_CHILD_DESCRIPTOR**](../dispmprt/ns-dispmprt-_dxgk_child_descriptor.md) structure is a [**DXGK_CHILD_CAPABILITIES**](../dispmprt/ns-dispmprt-_dxgk_child_capabilities.md) structure whose **Type.VideoOutput** member is a [**DXGK_VIDEO_OUTPUT_CAPABILITIES**](../dispmprt/ns-dispmprt-_dxgk_video_output_capabilities.md) structure. The **InterfaceTechnology** member of a DXGK_VIDEO_OUTPUT_CAPABILITIES structure is a single **D3DKMDT_VIDEO_OUTPUT_TECHNOLOGY** value.

## -see-also

[**DXGK_VIDEO_OUTPUT_CAPABILITIES**](../dispmprt/ns-dispmprt-_dxgk_video_output_capabilities.md)

[**DxgkDdiQueryChildRelations**](../dispmprt/nc-dispmprt-dxgkddi_query_child_relations.md)
