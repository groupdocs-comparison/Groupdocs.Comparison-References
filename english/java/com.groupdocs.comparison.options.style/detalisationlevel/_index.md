---
title: DetalisationLevel
second_title: GroupDocs.Comparison for Java API Reference
description: Specifies the level of comparison details.
type: docs
weight: 13
url: /java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

Specifies the level of comparison details.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [LOW](#LOW) | Represents the Low comparison level. |
| [MIDDLE](#MIDDLE) | Represents the Middle comparison level. |
| [HIGH](#HIGH) | Represents the High comparison level. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromString(String toStringValue)](#fromString-java.lang.String-) | Parses string representation of DetalisationLevel to get the enum constant. |
| [toString()](#toString--) | String representation of DetalisationLevel. |
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Represents the Low comparison level.

The "Low" level provides the best speed for comparisons but sacrifices comparison quality. Comparison is performed per-word.

### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Represents the Middle comparison level.

The "Middle" level is a reasonable compromise between comparison speed and quality. Comparison is performed per-character, but ignoring character case and spaces count.

### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


Represents the High comparison level.

The "High" level is the best comparison quality, but the lowest speed. Comparison is performed per-character considering character case and spaces count.

### values() {#values--}
```
public static DetalisationLevel[] values()
```




**Returns:**
com.groupdocs.comparison.options.style.DetalisationLevel[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DetalisationLevel valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


Parses string representation of DetalisationLevel to get the enum constant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String | The string representation of DetalisationLevel |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string
### toString() {#toString--}
```
public String toString()
```


String representation of DetalisationLevel.

**Returns:**
java.lang.String - string value of enum constant
