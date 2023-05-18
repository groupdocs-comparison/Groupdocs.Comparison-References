---
title: PaperSize
second_title: GroupDocs.Comparison for Java API Reference
description: Represents the paper size options for document comparison.
type: docs
weight: 12
url: /java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

Represents the paper size options for document comparison.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [DEFAULT](#DEFAULT) | Default paper size. |
| [A0](#A0) | Standard paper size A0 (841mm x 1189mm). |
| [A1](#A1) | Standard paper size A1 (594mm x 841mm). |
| [A2](#A2) | Standard paper size A2 (420mm x 594mm). |
| [A3](#A3) | Standard paper size A3 (297mm x 420mm). |
| [A4](#A4) | Standard paper size A4 (210mm x 297mm). |
| [A5](#A5) | Standard paper size A5 (148mm x 210mm). |
| [A6](#A6) | Standard paper size A6 (105mm x 148mm). |
| [A7](#A7) | Standard paper size A7 (74mm x 105mm). |
| [A8](#A8) | Standard paper size A8 (52mm x 74mm). |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromString(String toStringValue)](#fromString-java.lang.String-) | Parses string representation of PaperSize to get the enum constant. |
| [toString()](#toString--) | String representation of PaperSize. |
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


Default paper size.

### A0 {#A0}
```
public static final PaperSize A0
```


Standard paper size A0 (841mm x 1189mm).

### A1 {#A1}
```
public static final PaperSize A1
```


Standard paper size A1 (594mm x 841mm).

### A2 {#A2}
```
public static final PaperSize A2
```


Standard paper size A2 (420mm x 594mm).

### A3 {#A3}
```
public static final PaperSize A3
```


Standard paper size A3 (297mm x 420mm).

### A4 {#A4}
```
public static final PaperSize A4
```


Standard paper size A4 (210mm x 297mm).

### A5 {#A5}
```
public static final PaperSize A5
```


Standard paper size A5 (148mm x 210mm).

### A6 {#A6}
```
public static final PaperSize A6
```


Standard paper size A6 (105mm x 148mm).

### A7 {#A7}
```
public static final PaperSize A7
```


Standard paper size A7 (74mm x 105mm).

### A8 {#A8}
```
public static final PaperSize A8
```


Standard paper size A8 (52mm x 74mm).

### values() {#values--}
```
public static PaperSize[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PaperSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PaperSize valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


Parses string representation of PaperSize to get the enum constant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String | The string representation of PaperSize |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string
### toString() {#toString--}
```
public String toString()
```


String representation of PaperSize.

**Returns:**
java.lang.String - string value of enum constant
