---
title: GetChangeOptions
second_title: GroupDocs.Comparison for Java API Reference
description: Allows configuring filtering for retrieving specific change types from the comparison result.
type: docs
weight: 13
url: /java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

Allows configuring filtering for retrieving specific change types from the comparison result.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [GetChangeOptions()](#GetChangeOptions--) | Initializes a new instance of the GetChangeOptions class. |
| [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | Initializes a new instance of the GetChangeOptions class for specified filter type. |
## Methods

| Method | Description |
| --- | --- |
| [getFilter()](#getFilter--) | Gets the filter for retrieving specific change types from the comparison result. |
| [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | Sets the filter for retrieving specific change types from the comparison result. |
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


Initializes a new instance of the GetChangeOptions class.

### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


Initializes a new instance of the GetChangeOptions class for specified filter type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


Gets the filter for retrieving specific change types from the comparison result.

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.
### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


Sets the filter for retrieving specific change types from the comparison result.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | The filter specifying the types of changes to be retrieved. |

