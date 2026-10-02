---
title: "PageInfo"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "PageInfo sınıfı, bir belgedeki belirli bir sayfa hakkında bilgi temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

PageInfo sınıfı, bir belgedeki belirli bir sayfa hakkında bilgi temsil eder.


Sayfa numarası, genişlik, yükseklik ve diğer ilgili özellikler gibi ayrıntılar sağlar.
Karşılaştırma sürecinde bir belgedeki ayrı ayrı sayfalar hakkında bilgi almak için bu sınıfı kullanın.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final PageInfo pageInfo = change.getPageInfo();
         // Print the page information
         System.out.println("Page Number: " + pageInfo.getPageNumber());
         System.out.println("Page Width: " + pageInfo.getWidth());
         System.out.println("Page Height: " + pageInfo.getHeight());
     }
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | PageInfo sınıfının yeni bir örneğini pageNumber, genişlik ve yükseklik ayarlarıyla başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWidth()](#getWidth--) | Sayfanın genişliğini alır |
|
|  | [setWidth(int value)](#setWidth-int-) | Sayfanın genişliğini ayarlar |
|
|  | [getHeight()](#getHeight--) | Sayfanın yüksekliğini alır |
|
|  | [setHeight(int value)](#setHeight-int-) | Sayfanın yüksekliğini ayarlar |
|
|  | [getPageNumber()](#getPageNumber--) | Sayfanın numarasını alır |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Sayfanın numarasını ayarlar |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


PageInfo sınıfının yeni bir örneğini pageNumber, genişlik ve yükseklik ayarlarıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageNumber | int | Sayfanın numarası |
|
|  | genişlik | int | Sayfanın genişliği |
|
|  | yükseklik | int | Sayfanın yüksekliği |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Sayfanın genişliğini alır


**Returns:**
int - sayfanın genişliği

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Sayfanın genişliğini ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Sayfanın genişliği |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Sayfanın yüksekliğini alır


**Returns:**
int - sayfanın yüksekliği

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Sayfanın yüksekliğini ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Sayfanın yüksekliği |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Sayfanın numarasını alır


**Returns:**
int - sayfanın numarası

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


Sayfanın numarasını ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Sayfanın numarası |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
