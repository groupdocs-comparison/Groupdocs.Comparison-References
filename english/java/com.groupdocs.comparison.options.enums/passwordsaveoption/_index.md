---
title: PasswordSaveOption
second_title: GroupDocs.Comparison for Java API Reference
description: Enumerates the options for saving password information in a document during the comparison process.
type: docs
weight: 14
url: /java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

Enumerates the options for saving password information in a document during the comparison process.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [NONE](#NONE) | Do not save the password. |
| [SOURCE](#SOURCE) | Use password from source document. |
| [TARGET](#TARGET) | Use password from target document. |
| [USER](#USER) | \* Use password provided by user. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromString(String toStringValue)](#fromString-java.lang.String-) | Parses string representation of PasswordSaveOption to get the enum constant. |
| [toString()](#toString--) | String representation of PasswordSaveOption. |
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


Do not save the password.

### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


Use password from source document.

### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


Use password from target document.

### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* Use password provided by user.

### values() {#values--}
```
public static PasswordSaveOption[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PasswordSaveOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PasswordSaveOption valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


Parses string representation of PasswordSaveOption to get the enum constant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String | The string representation of PasswordSaveOption |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string
### toString() {#toString--}
```
public String toString()
```


String representation of PasswordSaveOption.

**Returns:**
java.lang.String - string value of enum constant
