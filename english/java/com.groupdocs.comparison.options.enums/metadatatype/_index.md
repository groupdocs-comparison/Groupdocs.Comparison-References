---
title: MetadataType
second_title: GroupDocs.Comparison for Java API Reference
description: Determines from where the result document will take metadata information.
type: docs
weight: 11
url: /java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

Determines from where the result document will take metadata information.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [DEFAULT](#DEFAULT) | Metadata will be left as is. |
| [SOURCE](#SOURCE) | Metedata will be taken from source document. |
| [TARGET](#TARGET) | Metedata will be taken from target document. |
| [FILE_AUTHOR](#FILE-AUTHOR) | Metedata will be set by user. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromString(String toStringValue)](#fromString-java.lang.String-) | Parses string representation of MetadataType to get the enum constant. |
| [toString()](#toString--) | String representation of MetadataType. |
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


Metadata will be left as is.

### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Metedata will be taken from source document.

### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Metedata will be taken from target document.

### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Metedata will be set by user.

### values() {#values--}
```
public static MetadataType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.MetadataType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MetadataType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


Parses string representation of MetadataType to get the enum constant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String | The string representation of MetadataType |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string
### toString() {#toString--}
```
public String toString()
```


String representation of MetadataType.

**Returns:**
java.lang.String - string value of enum constant
