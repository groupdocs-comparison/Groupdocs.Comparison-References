---
title: "RevisionType"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Bir belgedeki revizyon türlerini temsil eder."
type: docs
weight: 14
url: /tr/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Bir belgedeki revizyon türlerini temsil eder.


Örnek kullanım:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [INSERTION](#INSERTION) | Belgeye yeni içerik eklendiğinde bir türü temsil eder. |
|
|  | [DELETION](#DELETION) | Belgeden içerik kaldırıldığında bir türü temsil eder. |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | Üst düğüme biçimlendirme değişikliği uygulandığında bir türü temsil eder. |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | Üst stile biçimlendirme değişikliği uygulandığında bir türü temsil eder. |
|
|  | [MOVING](#MOVING) | Belgede içerik taşındığında bir türü temsil eder. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | Sağlanan sayısal değer kullanılarak RevisionType enum'ının yeni sabiti oluşturur. |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | RevisionType'ın dize temsilini ayrıştırarak enum sabitini alır. |
|
|  | [toInt()](#toInt--) | RevisionType'ın sayısal temsili. |
|
|  | [toString()](#toString--) | RevisionType'ın dize temsili. |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


Belgeye yeni içerik eklendiğinde bir türü temsil eder.


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


Belgeden içerik kaldırıldığında bir türü temsil eder.


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


Üst düğüme biçimlendirme değişikliği uygulandığında bir türü temsil eder.


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


Üst stile biçimlendirme değişikliği uygulandığında bir türü temsil eder.


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


Belgede içerik taşındığında bir türü temsil eder.


### values() {#values--}
```
public static RevisionType[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionType valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


Sağlanan sayısal değer kullanılarak RevisionType enum'ının yeni sabiti oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | toIntValue | int | RevisionType'ın sayısal temsili |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


RevisionType'ın dize temsilini ayrıştırarak enum sabitini alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | toStringValue | java.lang.String | RevisionType'ın dize temsili |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


RevisionType'ın sayısal temsili.


**Returns:**
int - enum sabitinin sayısal değeri

### toString() {#toString--}
```
public String toString()
```


RevisionType'ın dize temsili.


**Returns:**
java.lang.String - enum sabitinin dize değeri

