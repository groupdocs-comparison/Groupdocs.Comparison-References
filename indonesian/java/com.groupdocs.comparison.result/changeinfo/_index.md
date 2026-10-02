---
title: "ChangeInfo"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Kelas ChangeInfo mewakili informasi tentang perubahan spesifik dalam perbandingan dokumen."
type: docs
weight: 10
url: /id/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

Kelas ChangeInfo mewakili informasi tentang perubahan spesifik dalam perbandingan dokumen.


Ini menyediakan detail seperti tipe perubahan, area yang terpengaruh, dan konten sebelum serta sesudah perubahan.
Gunakan kelas ini untuk mengambil informasi tentang perubahan individual dalam hasil perbandingan.


Contoh penggunaan:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     // Get a list of changes from the comparison result
     ChangeInfo[] changes = comparer.getChanges();
     // Iterate through the changes and retrieve information
     for (ChangeInfo change : changes) {
         ChangeType changeType = change.getType();
         String componentType = change.getComponentType();
         PageInfo pageInfo = change.getPageInfo();
         // Process the change information as needed
         // ...
     }
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | Mengambil id unik dari perubahan. |
|
|  | [setId(int value)](#setId-int-) | Menetapkan id unik untuk perubahan. |
|
|  | [getComparisonAction()](#getComparisonAction--) | Mengambil aksi yang akan diterapkan pada perubahan. |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | Menetapkan aksi yang harus diterapkan pada perubahan. |
|
|  | [getPageInfo()](#getPageInfo--) | Mengambil informasi tentang halaman, di mana perubahan saat ini ditemukan. |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | Menetapkan informasi tentang halaman, di mana perubahan saat ini ditemukan. |
|
|  | [getBox()](#getBox--) | Mengambil koordinat elemen yang diubah pada halaman. |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | Menetapkan koordinat elemen yang diubah pada halaman. |
|
|  | [getText()](#getText--) | Mengambil nilai teks dari perubahan. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Menetapkan nilai teks dari perubahan. |
|
|  | [getStyleChanges()](#getStyleChanges--) | Mengambil daftar perubahan gaya. |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | Menetapkan daftar perubahan gaya. |
|
|  | [getAuthors()](#getAuthors--) | Mengambil daftar penulis. |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | Menetapkan daftar penulis. |
|
|  | [getType()](#getType--) | Mengambil tipe perubahan yang diwakili oleh enum [ChangeType](../../com.groupdocs.comparison.result/changetype). |
|
|  | [getTargetText()](#getTargetText--) | Mengambil teks yang diubah dari dokumen target. |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | Menetapkan teks yang diubah dari dokumen target. |
|
|  | [getSourceText()](#getSourceText--) | Mengambil teks yang diubah dari dokumen sumber. |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | Mengatur teks yang diubah dari dokumen sumber. |
|
|  | [getComponentType()](#getComponentType--) | Mendapatkan tipe komponen yang diubah. |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | Mengatur tipe komponen yang diubah. |
|
| [toString()](#toString--) |  |
### ChangeInfo() {#ChangeInfo--}
```
public ChangeInfo()
```


### getRow() {#getRow--}
```
public Integer getRow()
```




**Returns:**
java.lang.Integer
### setRow(Integer row) {#setRow-java.lang.Integer-}
```
public void setRow(Integer row)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baris | java.lang.Integer |  |

### getColumn() {#getColumn--}
```
public Integer getColumn()
```




**Returns:**
java.lang.Integer
### setColumn(Integer column) {#setColumn-java.lang.Integer-}
```
public void setColumn(Integer column)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kolom | java.lang.Integer |  |

### getColumnHeader() {#getColumnHeader--}
```
public String getColumnHeader()
```




**Returns:**
java.lang.String
### setColumnHeader(String columnHeader) {#setColumnHeader-java.lang.String-}
```
public void setColumnHeader(String columnHeader)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnHeader | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


Mengambil id unik dari perubahan.


**Returns:**
int - id perubahan

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Menetapkan id unik untuk perubahan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Id perubahan |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


Mengambil aksi yang akan diterapkan pada perubahan.
Aksi ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) atau [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) memberi tahu perbandingan apa yang harus dilakukan dengan perubahan ini.


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


Menetapkan aksi yang harus diterapkan pada perubahan.
Aksi ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) atau [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) memberi tahu perbandingan apa yang harus dilakukan dengan perubahan ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | Aksi yang harus diterapkan pada perubahan |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


Mengambil informasi tentang halaman, di mana perubahan saat ini ditemukan.


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


Menetapkan informasi tentang halaman, di mana perubahan saat ini ditemukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | Informasi tentang halaman |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Mengambil koordinat elemen yang diubah pada halaman.


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


Menetapkan koordinat elemen yang diubah pada halaman.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Koordinat elemen yang diubah, tidak null |
|

### getText() {#getText--}
```
public final String getText()
```


Mengambil nilai teks dari perubahan.


**Returns:**
java.lang.String - nilai teks perubahan

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Menetapkan nilai teks dari perubahan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Nilai teks perubahan |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


Mengambil daftar perubahan gaya.


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - daftar perubahan gaya

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


Menetapkan daftar perubahan gaya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | Daftar perubahan gaya |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


Mengambil daftar penulis.


**Returns:**
java.util.List<java.lang.String> - daftar penulis

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


Menetapkan daftar penulis.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.util.List<java.lang.String> | Daftar penulis |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


Mengambil tipe perubahan yang diwakili oleh enum [ChangeType](../../com.groupdocs.comparison.result/changetype).


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


Mengambil teks yang diubah dari dokumen target.


**Returns:**
java.lang.String - teks yang diubah

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


Menetapkan teks yang diubah dari dokumen target.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Teks yang diubah |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


Mengambil teks yang diubah dari dokumen sumber.


**Returns:**
java.lang.String - teks yang diubah

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


Mengatur teks yang diubah dari dokumen sumber.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Teks yang diubah |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


Mendapatkan tipe komponen yang diubah.


**Returns:**
java.lang.String - tipe komponen yang diubah

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


Mengatur tipe komponen yang diubah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Tipe komponen yang diubah |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
