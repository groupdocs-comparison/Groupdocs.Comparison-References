---
title: "StyleChangeInfo"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "StyleChangeInfo sınıfı, karşılaştırılan bir belgede stil değişikliği hakkında bilgi temsil eder."
type: docs
weight: 13
url: /tr/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

StyleChangeInfo sınıfı, karşılaştırılan bir belgede stil değişikliği hakkında bilgi temsil eder.


Değiştirilen özellik adı, değişim öncesi ve sonrası değerler gibi ayrıntıları sağlar.
Belge karşılaştırma işlemi sırasında stil değişiklikleri hakkında bilgi almak için bu sınıfı kullanın.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | Değiştirilen özelliğin adını alır. |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | Değiştirilen özelliğin adını ayarlar. |
|
|  | [getNewValue()](#getNewValue--) | Özelliğin yeni değerini alır. |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | Özelliğin yeni değerini ayarlar. |
|
|  | [getOldValue()](#getOldValue--) | Özelliğin eski değerini alır. |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | Özelliğin eski değerini ayarlar. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


Değiştirilen özelliğin adını alır.


**Returns:**
java.lang.String - özelliğin adı

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


Değiştirilen özelliğin adını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Özelliğin adı |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


Özelliğin yeni değerini alır.


**Returns:**
java.lang.Object - özelliğin yeni değeri

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


Özelliğin yeni değerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.Object | Özelliğin yeni değeri |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


Özelliğin eski değerini alır.


**Returns:**
java.lang.Object - özelliğin eski değeri

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


Özelliğin eski değerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.Object | Özelliğin eski değeri |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
