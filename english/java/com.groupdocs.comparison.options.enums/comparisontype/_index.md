---
title: ComparisonType
second_title: GroupDocs.Comparison for Java API Reference
description: Represents the type of comparison to be performed.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

Represents the type of comparison to be performed.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [TEXT](#TEXT) | Files must be compared as text documents. |
| [SLIDES](#SLIDES) | Files must be compared as presentation documents. |
| [WORDS](#WORDS) | Files must be compared as words documents. |
| [CELLS](#CELLS) | Files must be compared as excel documents. |
| [PDF](#PDF) | Files must be compared as pdf documents. |
| [IMAGING](#IMAGING) | Files must be compared as image documents. |
| [EMAIL](#EMAIL) | Files must be compared as email documents. |
| [NOTE](#NOTE) | Files must be compared as note documents. |
| [HTML](#HTML) | Files must be compared as html documents. |
| [DIAGRAM](#DIAGRAM) | Files must be compared as diagram documents. |
| [DIFFERENT](#DIFFERENT) | Files must be compared as documents in different formats. |
| [SVG](#SVG) | Files must be compared as svg documents. |
| [UNDEFINED](#UNDEFINED) | For internal use. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromString(String toStringValue)](#fromString-java.lang.String-) | Parses string representation of ComparisonType to get the enum constant. |
| [toString()](#toString--) | String representation of ComparisonType. |
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


Files must be compared as text documents.

### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


Files must be compared as presentation documents.

### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


Files must be compared as words documents.

### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


Files must be compared as excel documents.

### PDF {#PDF}
```
public static final ComparisonType PDF
```


Files must be compared as pdf documents.

### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


Files must be compared as image documents.

### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


Files must be compared as email documents.

### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


Files must be compared as note documents.

### HTML {#HTML}
```
public static final ComparisonType HTML
```


Files must be compared as html documents.

### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


Files must be compared as diagram documents.

### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


Files must be compared as documents in different formats.

### SVG {#SVG}
```
public static final ComparisonType SVG
```


Files must be compared as svg documents.

### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


For internal use.

### values() {#values--}
```
public static ComparisonType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.ComparisonType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


Parses string representation of ComparisonType to get the enum constant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String | The string representation of ComparisonType |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string
### toString() {#toString--}
```
public String toString()
```


String representation of ComparisonType.

**Returns:**
java.lang.String - string value of enum constant
