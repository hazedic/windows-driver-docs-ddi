---
UID: NS:d3dukmdt._D3DKMDT_3X4_COLORSPACE_TRANSFORM
title: _D3DKMDT_3X4_COLORSPACE_TRANSFORM
author: windows-driver-content
description: Structure to describe the three programmable sub-stages of the 3 by 4 matrix colorspace transform.
ms.assetid: 2797701a-8924-4292-ad6f-d015993d86a3
ms.author: windowsdriverdev
ms.date: 
ms.topic: struct
ms.prod: windows-hardware
ms.technology: windows-devices
ms.keywords: _D3DKMDT_3X4_COLORSPACE_TRANSFORM, D3DKMDT_3x4_COLORSPACE_TRANSFORM, *PD3DDDI_3x4_COLORSPACE_TRANSFORM, 
req.header: d3dukmdt.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.ddi-compliance:
req.unicode-ansi:
req.max-support:
req.typenames: D3DKMDT_3x4_COLORSPACE_TRANSFORM, *PD3DDDI_3x4_COLORSPACE_TRANSFORM
topic_type: 
-	apiref
api_type: 
-	HeaderDef
api_location: 
-	d3dukmdt.h
api_name: 
-	_D3DKMDT_3X4_COLORSPACE_TRANSFORM
product: Windows
targetos: Windows
---

# _D3DKMDT_3X4_COLORSPACE_TRANSFORM structure

## -description

Structure to describe the three programmable sub-stages of the 3 by 4 matrix colorspace transform.

## -struct-fields

### -field ColorMatrix3x4

[in] A 3x3 matrix and 3x1 addition to be applied to each pixel, stored in row-major order. Transforms colors within CIEXYZ.

### -field ScalarMultiplier

[in] A scalar to be multiplied into each element of ColorMatrix3x4.

### -field LookupTable1D

[in] 1D look-up table. Transforms colors within the colorspace specified by [DXGK_SET_TIMING_PATH_INFO](../d3dkmddi/ns-d3dkmddi-_dxgk_set_timing_path_info.md).

## -remarks

## -see-also