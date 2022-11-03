---
title: DetalisationLevel
second_title: GroupDocs.Comparison for Java API Reference
description: Specifies the level of comparison details.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DetalisationLevel extends System.Enum
```

Specifies the level of comparison details.
## Fields

| Field | Description |
| --- | --- |
| [Low](#Low) | Low level. |
| [Middle](#Middle) | Middle level. |
| [High](#High) | High level. |
## Methods

| Method | Description |
| --- | --- |
| [getName(int type)](#getName-int-) |  |
### Low {#Low}
```
public static final int Low
```


Low level. Provides the best speed comparison sacrificing comparison quality. Comparison is perfromed per-word.

### Middle {#Middle}
```
public static final int Middle
```


Middle level. A reasonable compromise between comparison speed and quality. Comparison is perfromed per-character, but ignoring character case and spaces count.

### High {#High}
```
public static final int High
```


High level. The best comparison quality, but the lowest speed. Comparison is perfromed per-character considering character case and spaces count.

### getName(int type) {#getName-int-}
```
public static String getName(int type)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int |  |

**Returns:**
java.lang.String
