---
UID: NC:uart.UART_HARDWARE_READ_INDEXED_UCHAR
title: UART_HARDWARE_READ_INDEXED_UCHAR (uart.h)
description: Reads a byte from the port specified by index.
tech.root: serports
ms.date: 10/19/2018
keywords: ["UART_HARDWARE_READ_INDEXED_UCHAR callback function"]
req.header: uart.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: Windows 10, version 1803
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.lib: 
req.dll: 
req.irql: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
targetos: Windows
f1_keywords:
 - UART_HARDWARE_READ_INDEXED_UCHAR
 - uart/UART_HARDWARE_READ_INDEXED_UCHAR
topic_type:
 - apiref
api_type:
 - UserDefined
api_location:
 - uart.h
api_name:
 - UART_HARDWARE_READ_INDEXED_UCHAR
---

# UART_HARDWARE_READ_INDEXED_UCHAR callback function


## -description

Reads a byte from the specified port.

## -parameters

### -param Port [_In_]

A pointer to a [**_CPPORT**](ns-uart-_cpport.md) structure that was received during port initialization.

### -param Index

A zero-based index for the port.

## -returns

Returns the byte that is read from the specified port address.

## -prototype

```cpp
//Declaration

UART_HARDWARE_READ_INDEXED_UCHAR UartHardwareReadIndexedUchar;

// Definition

UCHAR UartHardwareReadIndexedUchar
(
	PCPPORT Port
	 const UCHAR Index
)
{...}

```

## -remarks

Register your implementation of this callback function by setting the appropriate member of the [**_CPPORT**](ns-uart-_cpport.md) structure.

## -see-also

