---
title: "DiagramMasterSetting"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Diagram ana karşılaştırması için ayarları temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

Diagram ana karşılaştırması için ayarları temsil eder.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final DiagramMasterSetting diagramMasterSetting = new DiagramMasterSetting();
    diagramMasterSetting.setMasterPath(masterFilePath);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDiagramMasterSetting(diagramMasterSetting);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | DiagramMasterSetting sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | Kaynak ana yolun kullanılacağını gösteren bir bayrak alır. |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | Kaynak ana yolun kullanılmalı olduğunu gösteren bir bayrak alır. |
|
|  | [getMasterPath()](#getMasterPath--) | Belgeleri renderlemek için kullanılacak bir ana yol alır. |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | Belgeleri renderlemek için kullanılacak bir ana yol ayarlar. |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


DiagramMasterSetting sınıfının yeni bir örneğini başlatır.


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


Kaynak ana yolun kullanılacağını gösteren bir bayrak alır.


**Returns:**
boolean - true ise kaynak ana yol gösterilecek, aksi takdirde false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


Kaynak ana yolun kullanılmalı olduğunu gösteren bir bayrak alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true ise kaynak ana yol gösterilmeli, aksi takdirde false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


Belgeleri renderlemek için kullanılacak bir ana yol alır. MasterPath, varsayılan şekiller kümesinden bir sonuç belgesi oluşturmak için gereklidir.


**Returns:**
java.lang.String - ayarlanmışsa ana belgenin yolu, aksi takdirde varsayılan ana yol

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


Belgeleri renderlemek için kullanılacak bir ana yol ayarlar. MasterPath, varsayılan şekiller kümesinden bir sonuç belgesi oluşturmak için gereklidir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Ayarlanmışsa ana belgenin yolu, aksi takdirde varsayılan ana yol |
|

