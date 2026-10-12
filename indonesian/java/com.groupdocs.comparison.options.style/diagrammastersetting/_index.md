---
title: "DiagramMasterSetting"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Mewakili pengaturan untuk perbandingan master diagram."
type: docs
weight: 10
url: /id/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

Mewakili pengaturan untuk perbandingan master diagram.


Contoh penggunaan:

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


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | Menginisialisasi instance baru dari kelas DiagramMasterSetting. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | Mendapatkan flag yang menunjukkan apakah jalur master sumber akan digunakan. |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | Mendapatkan flag yang menunjukkan apakah jalur master sumber harus digunakan. |
|
|  | [getMasterPath()](#getMasterPath--) | Mendapatkan master path yang akan digunakan untuk merender dokumen. |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | Menetapkan master path yang harus digunakan untuk merender dokumen. |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


Menginisialisasi instance baru dari kelas DiagramMasterSetting.


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


Mendapatkan flag yang menunjukkan apakah jalur master sumber akan digunakan.


**Returns:**
boolean - true jika source master path akan ditampilkan, jika tidak false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


Mendapatkan flag yang menunjukkan apakah jalur master sumber harus digunakan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true jika source master path harus ditampilkan, jika tidak false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


Mendapatkan master path yang akan digunakan untuk merender dokumen. MasterPath diperlukan untuk membuat dokumen hasil dari sekumpulan bentuk default.


**Returns:**
java.lang.String - path dokumen master jika telah disetel, jika tidak default master path

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


Menetapkan master path yang harus digunakan untuk merender dokumen. MasterPath diperlukan untuk membuat dokumen hasil dari sekumpulan bentuk default.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Path dokumen master jika telah disetel, jika tidak default master path |
|

