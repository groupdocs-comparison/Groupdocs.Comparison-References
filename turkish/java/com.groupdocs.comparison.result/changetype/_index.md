---
title: "ChangeType"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "ChangeType enum'ı, belge karşılaştırma sürecinde meydana gelebilecek değişiklik türlerini temsil eder."
type: docs
weight: 14
url: /tr/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

ChangeType enum'ı, belge karşılaştırma sürecinde meydana gelebilecek değişiklik türlerini temsil eder.


Bu enum'daki her sabit, belirli bir değişiklik türünü temsil eder ve insan tarafından okunabilir bir açıklama ile sayısal bir değer sağlar.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [NONE](#NONE) | Değişiklik olmadığını temsil eder. |
|
|  | [MODIFIED](#MODIFIED) | Değiştirilen bir değişikliği temsil eder. |
|
|  | [INSERTED](#INSERTED) | Eklenmiş bir değişikliği temsil eder. |
|
|  | [DELETED](#DELETED) | Silinmiş bir değişikliği temsil eder. |
|
|  | [ADDED](#ADDED) | Eklenen bir değişikliği temsil eder. |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | Değiştirilmemiş bir değişikliği temsil eder. |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | Stil değişikliğine uğramış bir değişikliği temsil eder. |
|
|  | [RESIZED](#RESIZED) | Yeniden boyutlandırılmış bir değişikliği temsil eder. |
|
|  | [MOVED](#MOVED) | Taşınmış bir değişikliği temsil eder. |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | Taşınmış ve yeniden boyutlandırılmış bir değişikliği temsil eder. |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | Kaydırılmış ve yeniden boyutlandırılmış bir değişikliği temsil eder. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | ChangeType'ın dize temsili çözümlenerek enum sabiti elde edilir. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Sağlanan sayısal değer kullanılarak ChangeType enum'ının yeni sabiti oluşturulur. |
|
|  | [toString()](#toString--) | ChangeType'ın dize temsili. |
|
|  | [toInt()](#toInt--) | ChangeType'ın sayısal temsili. |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


Değişiklik olmadığını temsil eder.


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


Değiştirilen bir değişikliği temsil eder.


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


Eklenmiş bir değişikliği temsil eder.


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


Silinmiş bir değişikliği temsil eder.


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


Eklenen bir değişikliği temsil eder.


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


Değiştirilmemiş bir değişikliği temsil eder.


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


Stil değişikliğine uğramış bir değişikliği temsil eder.


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


Yeniden boyutlandırılmış bir değişikliği temsil eder.


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


Taşınmış bir değişikliği temsil eder.


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


Taşınmış ve yeniden boyutlandırılmış bir değişikliği temsil eder.


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


Kaydırılmış ve yeniden boyutlandırılmış bir değişikliği temsil eder.


### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


ChangeType'ın dize temsili çözümlenerek enum sabiti elde edilir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ChangeType'ın dize temsili |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


Sağlanan sayısal değer kullanılarak ChangeType enum'ının yeni sabiti oluşturulur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | intValue | int | ChangeType'ın sayısal temsili |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


ChangeType'ın dize temsili.


**Returns:**
java.lang.String - enum sabitinin dize değeri

### toInt() {#toInt--}
```
public int toInt()
```


ChangeType'ın sayısal temsili.


**Returns:**
int - enum sabitinin sayısal değeri

