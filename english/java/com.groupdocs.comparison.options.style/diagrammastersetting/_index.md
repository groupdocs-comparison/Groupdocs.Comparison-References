---
title: DiagramMasterSetting
second_title: GroupDocs.Comparison for Java API Reference
description: Represents the settings for diagram master comparison.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

Represents the settings for diagram master comparison.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final DiagramMasterSetting diagramMasterSetting = new DiagramMasterSetting();
    diagramMasterSetting.setMasterPath(masterFilePath);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDiagramMasterSetting(diagramMasterSetting);

    comparer.compare(resultFile, compareOptions);
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DiagramMasterSetting()](#DiagramMasterSetting--) | Initializes a new instance of the DiagramMasterSetting class. |
## Methods

| Method | Description |
| --- | --- |
| [isUseSourceMaster()](#isUseSourceMaster--) | Gets a flag that indicates whether source master path will be used. |
| [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | Gets a flag that indicates whether source master path should be used. |
| [getMasterPath()](#getMasterPath--) | Gets a master path that will be used to render documents. |
| [setMasterPath(String value)](#setMasterPath-java.lang.String-) | Sets a master path that should be used to render documents. |
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


Initializes a new instance of the DiagramMasterSetting class.

### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


Gets a flag that indicates whether source master path will be used.

**Returns:**
boolean - true if source master path will be shown, otherwise false
### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


Gets a flag that indicates whether source master path should be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true if source master path should be shown, otherwise false |

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


Gets a master path that will be used to render documents. MasterPath is needed to create a result document from a set of default shapes.

**Returns:**
java.lang.String - path of master document if it is set, otherwise default master path
### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


Sets a master path that should be used to render documents. MasterPath is needed to create a result document from a set of default shapes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Path of master document if it is set, otherwise default master path |

