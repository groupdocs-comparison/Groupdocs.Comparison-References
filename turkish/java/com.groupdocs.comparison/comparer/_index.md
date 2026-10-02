---
title: "Comparer"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Comparer sınıfı, belgeleri karşılaştırma ve karşılaştırma sonuçları üretme işlevselliği sağlar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

Comparer sınıfı, belgeleri karşılaştırma ve karşılaştırma sonuçları üretme işlevselliği sağlar.


PDF, Word, Excel, PowerPoint ve daha fazlası gibi çeşitli belge türlerini karşılaştırmanıza olanak tanır.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | Belirtilen kaynak dosya yolu ile Comparer sınıfının yeni bir örneğini başlatır. |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen klasör yolu ve karşılaştırma seçenekleri ile Comparer sınıfının yeni bir örneğini başlatır. |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | Belirtilen kaynak dosya yolu ile Comparer sınıfının yeni bir örneğini başlatır. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Belirtilen kaynak dosya yolu ve [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ile Comparer'ın yeni bir örneğini başlatır. |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Belirtilen kaynak dosya yolu ve [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ile Comparer'ın yeni bir örneğini başlatır. |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen kaynak dosya yolu ve [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ile Comparer'ın yeni bir örneğini başlatır. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Belirtilen kaynak dosya yolu, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen kaynak dosya yolu, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır. |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | Belirtilen kaynak dosya yolu ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır. |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | Belirtilen kaynak dosya yolu ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır. |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Belirtilen kaynak dosya yolu, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır. |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen kaynak dosya yolu, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır. |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | Belirtilen kaynak belge akışı ile Comparer sınıfının yeni bir örneğini başlatır. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Belirtilen kaynak belge akışı ve [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ile Comparer'ın yeni bir örneğini başlatır. |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | Belirtilen kaynak belge akışı ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Belirtilen belge akışı, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır. |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | Belirtilen [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSource()](#getSource--) | Karşılaştırılan kaynak belgeyi alır. |
|
|  | [getTargets()](#getTargets--) | Kaynak dosyayla karşılaştırılacak hedef belgelerin listesi. |
|
|  | [compare()](#compare--) | Belirtilen dosyayı hedef belgelerle, sonucu kaydetmeden ve varsayılan seçeneklerle karşılaştırır. |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve bir karşılaştırma sonucu oluşturur. |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve bir karşılaştırma sonucu oluşturur. |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu çıktı akışına yazar. |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar. |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar. |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu çıktı akışına yazar. |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve sonucu kaydetmez. |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar. |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar. |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar. |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve sonucu kaydetmez. |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan çıktı akışına yazar. |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar. |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen dizini hedef dizinle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna kaydeder. |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen dizini hedef dizinle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna kaydeder. |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar. |
|
|  | [add(String filePath)](#add-java.lang.String-) | Belirtilen hedef belgeyi karşılaştırma sürecine ekler. |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen hedef belgeyi veya klasörü karşılaştırma sürecine ekler. |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | Belirtilen hedef belgeyi karşılaştırma sürecine ekler. |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | Belirtilen hedef belgeleri karşılaştırma sürecine ekler. |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | Belirtilen hedef belgeleri karşılaştırma sürecine ekler. |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Belirtilen hedef belgeyi, belirtilen yükleme seçenekleriyle birlikte karşılaştırma sürecine ekler. |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Belirtilen hedef belgeyi, belirtilen yükleme seçenekleriyle birlikte karşılaştırma sürecine ekler. |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Belirtilen hedef belgeyi, belirtilen yükleme seçenekleriyle birlikte karşılaştırma sürecine ekler. |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | Belirtilen hedef belgeyi karşılaştırma sürecine ekler. |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | Belirtilen hedef belgeleri karşılaştırma sürecine ekler. |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Belirtilen hedef belgeyi, belirtilen yükleme seçenekleriyle birlikte karşılaştırma sürecine ekler. |
|
|  | [getChanges()](#getChanges--) | Karşılaştırma sürecinde tespit edilen değişiklikleri temsil eden [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnelerinden oluşan bir dizi alır. |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | Karşılaştırma sürecinde tespit edilen değişiklikleri temsil eden [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnelerinden oluşan bir dizi alır. |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | Değişiklikleri kabul eder veya reddeder ve bunları sonuç belgesine uygular. |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | Değişiklikleri kabul eder veya reddeder ve bunları ortaya çıkan belgeye uygular. |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | Değişiklikleri kabul eder veya reddeder ve bunları ortaya çıkan belgeye uygular. |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Değişiklikleri kabul eder veya reddeder ve bunları ortaya çıkan belgeye uygular. |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Değişiklikleri kabul eder veya reddeder ve bunları ortaya çıkan belgeye uygular. |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Değişiklikleri kabul eder veya reddeder ve bunları ortaya çıkan belgeye uygular. |
|
|  | [getResultString()](#getResultString--) | Karşılaştırmadan sonra sonuç dizesini alır (Yalnızca Metin Karşılaştırması için). |
|
|  | [getSourceFolder()](#getSourceFolder--) | Karşılaştırılan kaynak klasörü döndürür. |
|
|  | [getTargetFolder()](#getTargetFolder--) | Karşılaştırılan hedef klasörü döndürür. |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | Kendine karşı karşılaştırma kontrolü (e498c23). |
|
|  | [close()](#close--) | Kaynakları serbest bırakır. |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


Belirtilen kaynak dosya yolu ile Comparer sınıfının yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Kaynak belgeye giden yol |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


Belirtilen klasör yolu ve karşılaştırma seçenekleri ile Comparer sınıfının yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Kaynak belgeye veya klasöre giden yol |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Klasör karşılaştırması için karşılaştırma seçenekleri |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


Belirtilen kaynak dosya yolu ile Comparer sınıfının yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Kaynak belgeye giden yol |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


Belirtilen kaynak dosya yolu ve [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ile Comparer'ın yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Kaynak belgeye giden yol |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Belgeye uygulanacak özel yükleme seçenekleri |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


Belirtilen kaynak dosya yolu ve [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ile Comparer'ın yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Kaynak belgeye giden yol |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Belgeye uygulanacak özel yükleme seçenekleri |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


Belirtilen kaynak dosya yolu ve [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ile Comparer'ın yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Kaynak belgeye giden yol |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Klasör karşılaştırması için karşılaştırma seçenekleri |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Belirtilen kaynak dosya yolu, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Kaynak belgeye giden yol |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Belgeye uygulanacak özel yükleme seçenekleri |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Karşılaştırma sürecinde kullanılacak karşılaştırıcı ayarları |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Belirtilen kaynak dosya yolu, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Karşılaştırılacak kaynak belgeye, klasöre veya metne giden yol |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Belgeye uygulanacak özel yükleme seçenekleri |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Karşılaştırma sürecinde kullanılacak karşılaştırıcı ayarları |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Klasör karşılaştırması için karşılaştırma seçenekleri |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


Belirtilen kaynak dosya yolu ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Kaynak belgeye giden yol |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Karşılaştırma sürecinde kullanılacak karşılaştırıcı ayarları |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


Belirtilen kaynak dosya yolu ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Kaynak belgeye giden yol |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Karşılaştırma sürecinde kullanılacak karşılaştırıcı ayarları |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Belirtilen kaynak dosya yolu, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Kaynak belgeye giden yol |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Belgeye uygulanacak özel yükleme seçenekleri |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Karşılaştırma sürecinde kullanılacak karşılaştırıcı ayarları |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Belirtilen kaynak dosya yolu, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Kaynak belgeye veya klasöre giden yol |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Belgeye uygulanacak özel yükleme seçenekleri |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Karşılaştırma sürecinde kullanılacak karşılaştırıcı ayarları |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Klasör karşılaştırması için karşılaştırma seçenekleri |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


Belirtilen kaynak belge akışı ile Comparer sınıfının yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Kaynak belgenin giriş akışı |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


Belirtilen kaynak belge akışı ve [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ile Comparer'ın yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Kaynak belgenin giriş akışı |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Belgeye uygulanacak özel yükleme seçenekleri |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


Belirtilen kaynak belge akışı ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Kaynak belgenin giriş akışı |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Karşılaştırma sürecinde kullanılacak karşılaştırıcı ayarları |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


Belirtilen belge akışı, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) ve [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Karşılaştırılacak bir belgenin verileri içeren akış |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Belgeye uygulanacak özel yükleme seçenekleri |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Karşılaştırma sürecinde kullanılacak karşılaştırıcı ayarları |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


Belirtilen [ComparerSettings](../../com.groupdocs.comparison/comparersettings) ile Comparer sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | ayarlar |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


Karşılaştırılan kaynak belgeyi alır.


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


Kaynak dosyayla karşılaştırılacak hedef belgelerin listesi.


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - hedef belgeler

### compare() {#compare--}
```
public final Path compare()
```


Belirtilen dosyayı hedef belgelerle, sonucu kaydetmeden ve varsayılan seçeneklerle karşılaştırır.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - sonuç belgesinin yolu veya null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve bir karşılaştırma sonucu oluşturur.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Sonuç belgesi yolu |
|

**Returns:**
java.nio.file.Path - sonuç dosyasının yolu veya null. Bazı durumlarda uzantısı değiştirilebilir

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve bir karşılaştırma sonucu oluşturur.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sonuç belgesi yolu |
|

**Returns:**
java.nio.file.Path - sonuç dosyasının yolu, bazı durumlarda uzantısı değiştirilebilir

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu çıktı akışına yazar.


Not: Dönüş değeri null olduğunda, outputStream'e yazılan veriyi kullanın

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Sonuç belgesi akışı |
|

**Returns:**
java.nio.file.Path - outputStream'ten veri kullanılmalıysa sonuç dosyasının yolu veya null. Bazı durumlarda sonuç dosyasının uzantısı değiştirilebilir

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Sonuç belgesi dosya yolu |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Karşılaştırma sürecinde kullanılacak karşılaştırma seçenekleri |
|

**Returns:**
java.nio.file.Path - sonuç dosyasının yolu, bazı durumlarda uzantısı değiştirilebilir

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sonuç belgesi dosya yolu |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Karşılaştırma sürecinde kullanılacak karşılaştırma seçenekleri |
|

**Returns:**
java.nio.file.Path - sonuç dosyasının yolu, bazı durumlarda uzantısı değiştirilebilir

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu çıktı akışına yazar.


Not: Dönüş değeri null olduğunda, outputStream'e yazılan veriyi kullanın.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | akış | java.io.OutputStream | Sonuç belgesi akışı |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Karşılaştırma sürecinde kullanılacak karşılaştırma seçenekleri |
|

**Returns:**
java.nio.file.Path - outputStream'ten veri kullanılmalıysa sonuç dosyasının yolu veya null. Bazı durumlarda sonuç dosyasının uzantısı değiştirilebilir

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve sonucu kaydetmez.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Kaydetme seçenekleri |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Karşılaştırma sürecinde kullanılacak karşılaştırma seçenekleri |
|

**Returns:**
java.nio.file.Path - sonuç belgesinin yolu veya null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Sonuç belgesi dosya yolu |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Kaydetme seçenekleri |
|

**Returns:**
java.nio.file.Path - sonuç dosyasının yolu, bazı durumlarda uzantısı değiştirilebilir

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sonuç belgesi dosya yolu |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Kaydetme seçenekleri |
|

**Returns:**
java.nio.file.Path - sonuç dosyasının yolu, bazı durumlarda uzantısı değiştirilebilir

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar.


Not: Dönüş değeri null olduğunda, outputStream'e yazılan veriyi kullanın

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | akış | java.io.OutputStream | Sonuç belgesi akışı |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Kaydetme seçenekleri |
|

**Returns:**
java.nio.file.Path - outputStream'ten veri kullanılmalıysa sonuç dosyasının yolu veya null. Bazı durumlarda sonuç dosyasının uzantısı değiştirilebilir

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve sonucu kaydetmez.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Karşılaştırma sürecinde kullanılacak karşılaştırma seçenekleri |
|

**Returns:**
java.nio.file.Path - sonuç dosyasının yolu veya null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan çıktı akışına yazar.


Not: Dönüş değeri null olduğunda, outputStream'e yazılan veriyi kullanın

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Sonuç belgesi akışı |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sonuç belgesini kaydetmek için kullanılacak kaydetme seçenekleri |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Karşılaştırma sürecinde kullanılacak karşılaştırma seçenekleri |
|

**Returns:**
java.nio.file.Path - outputStream'ten veri kullanılmalıysa sonuç dosyasının yolu veya null. Bazı durumlarda sonuç dosyasının uzantısı değiştirilebilir

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Sonuç belgesi dosya yolu |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sonuç belgesini kaydetmek için kullanılacak kaydetme seçenekleri |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Karşılaştırma sürecinde kullanılacak karşılaştırma seçenekleri |
|

**Returns:**
java.nio.file.Path - sonuç dosyasının yolu, bazı durumlarda uzantısı değiştirilebilir

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


Belirtilen dizini hedef dizinle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Karşılaştırma sonucunun kaydedileceği dosya yolu. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Dizin karşılaştırma sürecinde kullanılacak seçenekler. |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


Belirtilen dizini hedef dizinle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Karşılaştırma sonucunun kaydedileceği dosya yolu. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Dizin karşılaştırma sürecinde kullanılacak seçenekler. |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Belirtilen dosyayı hedef belgelerle karşılaştırır ve karşılaştırma sonucunu sağlanan dosya yoluna yazar.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sonuç belgesi dosya yolu |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sonuç belgesini kaydetmek için kullanılacak kaydetme seçenekleri |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Karşılaştırma sürecinde kullanılacak karşılaştırma seçenekleri |
|

**Returns:**
java.nio.file.Path - sonuç dosyasının yolu, bazı durumlarda uzantısı değiştirilebilir

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


Belirtilen hedef belgeyi karşılaştırma sürecine ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Eklenecek hedef belgenin yolu |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


Belirtilen hedef belgeyi veya klasörü karşılaştırma sürecine ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Eklenecek hedef belge veya klasörün yolu |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Karşılaştırma için seçenekler |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


Belirtilen hedef belgeyi karşılaştırma sürecine ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Eklenecek hedef belgenin yolu |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


Belirtilen hedef belgeleri karşılaştırma sürecine ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | Eklenecek hedef belgelerin yolları |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


Belirtilen hedef belgeleri karşılaştırma sürecine ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | Eklenecek hedef belgelerin yolları |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


Belirtilen hedef belgeyi, belirtilen yükleme seçenekleriyle birlikte karşılaştırma sürecine ekler.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Eklenecek hedef belgenin yolu |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Belgeye uygulanacak özel yükleme seçenekleri |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


Belirtilen hedef belgeyi, belirtilen yükleme seçenekleriyle birlikte karşılaştırma sürecine ekler.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Eklenecek hedef belgenin yolu |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Belgeye uygulanacak özel yükleme seçenekleri |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


Belirtilen hedef belgeyi, belirtilen yükleme seçenekleriyle birlikte karşılaştırma sürecine ekler.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Eklenecek hedef belge veya klasörün yolu |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Karşılaştırma için seçenekler |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


Belirtilen hedef belgeyi karşılaştırma sürecine ekler.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Karşılaştırılacak bir belgenin verileri içeren akış |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


Belirtilen hedef belgeleri karşılaştırma sürecine ekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belgeler | java.io.InputStream[] | Karşılaştırılacak belgelerin verilerini içeren akışlar |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


Belirtilen hedef belgeyi, belirtilen yükleme seçenekleriyle birlikte karşılaştırma sürecine ekler.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Karşılaştırılacak bir belgenin verileri içeren akış |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Belgeye uygulanacak özel yükleme seçenekleri |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Karşılaştırma sürecinde tespit edilen değişiklikleri temsil eden [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnelerinden oluşan bir dizi alır.


Kaynak belge ile hedef belge(ler) arasındaki değişiklikler hakkında ayrıntılı bilgi almak için bu yöntemi kullanın.
Her bir [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnesi, değişiklik türü, etkilenen alan gibi bilgileri içerir,
ve değişiklik öncesi ve sonrası içeriği.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - karşılaştırma sürecinde tespit edilen değişiklikleri temsil eden [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnelerinin bir dizisi

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


Karşılaştırma sürecinde tespit edilen değişiklikleri temsil eden [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnelerinden oluşan bir dizi alır.


Kaynak belge ile hedef belge(ler) arasındaki değişiklikler hakkında ayrıntılı bilgi almak için bu yöntemi kullanın.
Her bir [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnesi, değişiklik türü, etkilenen alan gibi bilgileri içerir,
ve değişiklik öncesi ve sonrası içeriği.


Parametre [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) değişiklikleri farklı bir şekilde filtrelemeye izin verir.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | Değişiklikleri filtrelemeye izin veren nesne |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - karşılaştırma sürecinde tespit edilen değişiklikleri temsil eden [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) nesnelerinin bir dizisi

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


Değişiklikleri kabul eder veya reddeder ve bunları sonuç belgesine uygular.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Sonuç belgesi dosya yolu |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Değişikliklerin uygulanma sürecini yapılandırmak için özel uygulama değişiklik seçenekleri |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


Değişiklikleri kabul eder veya reddeder ve bunları ortaya çıkan belgeye uygular.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sonuç belgesi dosya yolu |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Değişikliklerin uygulanma sürecini yapılandırmak için özel uygulama değişiklik seçenekleri |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


Değişiklikleri kabul eder veya reddeder ve bunları ortaya çıkan belgeye uygular.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Sonuç belgesi çıktı akışı |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Değişikliklerin uygulanma sürecini yapılandırmak için özel uygulama değişiklik seçenekleri |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Değişiklikleri kabul eder veya reddeder ve bunları ortaya çıkan belgeye uygular.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Sonuç belgesi dosya yolu |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sonuç belgesinin kaydedilmesini yapılandırmak için kaydetme seçenekleri |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Değişikliklerin uygulanma sürecini yapılandırmak için özel uygulama değişiklik seçenekleri |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Değişiklikleri kabul eder veya reddeder ve bunları ortaya çıkan belgeye uygular.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sonuç belgesi dosya yolu |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sonuç belgesinin kaydedilmesini yapılandırmak için kaydetme seçenekleri |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Değişikliklerin uygulanma sürecini yapılandırmak için özel uygulama değişiklik seçenekleri |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Değişiklikleri kabul eder veya reddeder ve bunları ortaya çıkan belgeye uygular.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Sonuç belgesi çıktı akışı |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sonuç belgesinin kaydedilmesini yapılandırmak için kaydetme seçenekleri |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Değişikliklerin uygulanma sürecini yapılandırmak için özel uygulama değişiklik seçenekleri |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


Karşılaştırmadan sonra sonuç dizesini alır (Yalnızca Metin Karşılaştırması için).


**Returns:**
java.lang.String - sonuç dizesi

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


Karşılaştırılan kaynak klasörü döndürür.


**Returns:**
java.lang.String - kaynak klasör

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


Karşılaştırılan hedef klasörü döndürür.


**Returns:**
java.lang.String - hedef klasör

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


Kendi kendine karşılaştırma kontrolü (e498c23). C# 7a7668c dahili; core.common testlerinin çağırabilmesi için genel tutuldu.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


Kaynakları serbest bırakır.


