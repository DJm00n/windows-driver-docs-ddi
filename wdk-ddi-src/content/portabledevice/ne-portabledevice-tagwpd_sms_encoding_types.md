---
UID: NE:portabledevice.tagWPD_SMS_ENCODING_TYPES
title: WPD_SMS_ENCODING_TYPES (portabledevice.h)
description: The WPD_SMS_ENCODING_TYPES enumeration type describes the encoding type of a short message service (SMS) message.
old-location: wpddk\wpd_sms_encoding_types.htm
tech.root: wpd_dk
ms.assetid: 5062c220-c775-442b-af0a-48b9d3dcf79b
ms.date: 02/15/2018
keywords: ["tagWPD_SMS_ENCODING_TYPES enumeration"]
ms.keywords: SMS_ENCODING_7_BIT, SMS_ENCODING_8_BIT, SMS_ENCODING_UTF_16, WPD_SMS_ENCODING_TYPES, WPD_SMS_ENCODING_TYPES enumeration, enumeration, portabledevice/SMS_ENCODING_7_BIT, portabledevice/SMS_ENCODING_8_BIT, portabledevice/SMS_ENCODING_UTF_16, portabledevice/WPD_SMS_ENCODING_TYPES, tagWPD_SMS_ENCODING_TYPES, wpddk.wpd_sms_encoding_types
req.header: portabledevice.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
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
req.typenames: WPD_SMS_ENCODING_TYPES
ms.custom: RS5
f1_keywords:
 - tagWPD_SMS_ENCODING_TYPES
 - portabledevice/tagWPD_SMS_ENCODING_TYPES
 - WPD_SMS_ENCODING_TYPES
 - portabledevice/WPD_SMS_ENCODING_TYPES
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - PortableDevice.h
api_name:
 - WPD_SMS_ENCODING_TYPES
---

# tagWPD_SMS_ENCODING_TYPES enumeration


## -description

The <b>WPD_SMS_ENCODING_TYPES</b> enumeration type describes the encoding type of a short message service (SMS) message.

## -enum-fields

### -field SMS_ENCODING_7_BIT

Seven-bit encoding.

### -field SMS_ENCODING_8_BIT

Eight-bit encoding.

### -field SMS_ENCODING_UTF_16

Sixteen-bit encoding (UTF).

## -remarks

This enumeration is used by the <a href="/windows/desktop/wpd_sdk/sms-properties">WPD_SMS_ENCODING</a> property.

## -see-also

<a href="/previous-versions/windows/hardware/drivers/ff597672(v=vs.85)">Structures and Enumeration Types</a>