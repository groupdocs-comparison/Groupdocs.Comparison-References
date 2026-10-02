---
title: "ComparisonAction"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "ComparisonAction enum'ı, belge karşılaştırma sürecinde bir değişikliğe uygulanabilecek eylemleri temsil eder."
type: docs
weight: 15
url: /tr/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

ComparisonAction enum'ı, belge karşılaştırma sürecinde bir değişikliğe uygulanabilecek eylemleri temsil eder.


Bu enumdaki her sabit belirli bir eylemi temsil eder ve insan tarafından okunabilir bir açıklama ile sayısal bir değer sağlar.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         if (changeInfo.getId() % 2 == 0) {
             changeInfo.setComparisonAction(ComparisonAction.REJECT);
         }
     }
     comparer.applyChanges(resultFile, changes);
 }
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [NONE](#NONE) | Herhangi bir eylemi temsil etmez. |
|
|  | [ACCEPT](#ACCEPT) | Kabul eylemini temsil eder. |
|
|  | [REJECT](#REJECT) | Reddetme eylemini temsil eder. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | ComparisonAction'ın dize temsilini ayrıştırarak enum sabitini alır. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Sağlanan sayısal değeri kullanarak ComparisonAction enum'ının yeni sabitini oluşturur. |
|
|  | [toString()](#toString--) | ComparisonAction'ın dize temsili. |
|
|  | [toInt()](#toInt--) | ComparisonAction'ın sayısal temsili. |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


Herhangi bir eylemi temsil etmez. Değişiklik hiçbir etki yapmayacaktır.


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


Kabul eylemini temsil eder. Değişiklik sonuç dosyasında görünecek.


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


Reddetme eylemini temsil eder. Değişiklik sonuç dosyasında görünmez olacak.


### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


ComparisonAction'ın dize temsilini ayrıştırarak enum sabitini alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ComparisonAction'ın dize temsili |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


Sağlanan sayısal değeri kullanarak ComparisonAction enum'ının yeni sabitini oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | intValue | int | ComparisonAction'ın sayısal temsili |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


ComparisonAction'ın dize temsili.


**Returns:**
java.lang.String - enum sabitinin dize değeri

### toInt() {#toInt--}
```
public int toInt()
```


ComparisonAction'ın sayısal temsili.


**Returns:**
int - enum sabitinin sayısal değeri

