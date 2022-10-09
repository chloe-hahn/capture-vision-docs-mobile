---
layout: default-layout
title: EnumPresetTemplate of Dynamsoft Capture Vision Cordova Edition
description: The enumeration of preset template
keywords: Preset template, API reference
needAutoGenerateSidebar: false
needGenerateH3Content: false
noTitleIndex: true
breadcrumbText: EnumPresetTemplate
---

# EnumDBRPresetTemplate

`EnumDBRPresetTemplate` is the enumeration of preset barcode setting templates.

```js
export enum EnumDBRPresetTemplate {
    DEFAULT,
    VIDEO_SINGLE_BARCODE,
    VIDEO_SPEED_FIRST,
    VIDEO_READ_RATE_FIRST,
    IMAGE_SPEED_FIRST,
    IMAGE_READ_RATE_FIRST,
    IMAGE_DEFAULT
}
```

## Related API(s)

- [`DCVBarcodeReader.updateRuntimeSettings`](barcode-reader.md#updateruntimesettings)