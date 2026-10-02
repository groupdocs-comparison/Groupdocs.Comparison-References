---
title: "CompareOptions"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Belge karşılaştırma sürecini yapılandırmaya izin verir."
type: docs
weight: 11
url: /tr/java/com.groupdocs.comparison.options/compareoptions/
---
**Inheritance:**
java.lang.Object
```
public class CompareOptions
```

Belge karşılaştırma sürecini yapılandırmaya izin verir.


Örnek kullanım:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final StyleSettings styleSettings = new StyleSettings();
     styleSettings.setHighlightColor(Color.RED);
     styleSettings.setFontColor(Color.GREEN);
     styleSettings.setUnderline(true);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [CompareOptions()](#CompareOptions--) | CompareOptions sınıfının yeni bir örneğini başlatır. |
|
|  | [CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)](#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-) | CompareOptions sınıfının farklı stiller için ayarlarla yeni bir örneğini başlatır. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ignoreChangeSettings](#ignoreChangeSettings) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getIgnoreChangeSettings()](#getIgnoreChangeSettings--) | Benzerliğe dayalı değişiklikleri yok saymak için ayarları al. |
|
|  | [setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)](#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-) | Benzerliğe dayalı değişiklikleri yok saymak için ayarları ayarlar. |
|
|  | [getUserMasterPath()](#getUserMasterPath--) | Diyagramlar için kullanıcı ana şablonunun yolunu alır. |
|
|  | [setUserMasterPath(String userMasterPath)](#setUserMasterPath-java.lang.String-) | Diyagramlar için kullanıcı ana şablonunun yolunu ayarlar. |
|
|  | [getComparisonType()](#getComparisonType--) | Kaynak ve hedef belgelerin tipini, Comparison'ın nasıl karşılaştırılacağını bilmesi için [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) nesnesi olarak alır. |
|
|  | [setComparisonType(ComparisonType comparisonType)](#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-) | Kaynak ve hedef belgelerin tipini, Comparison'ın nasıl karşılaştırılacağını bilmesi için [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) nesnesi olarak ayarlar. |
|
|  | [getPaperSize()](#getPaperSize--) | Sonuç belgesindeki kağıt boyutunu [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) nesnesi olarak alır. |
|
|  | [setPaperSize(PaperSize value)](#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-) | Sonuç belgesindeki kağıt boyutunu [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) nesnesi olarak ayarlar. |
|
|  | [getCalculateCoordinatesMode()](#getCalculateCoordinatesMode--) | Koordinat hesaplama modunu [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) nesnesi olarak alır. |
|
|  | [setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)](#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-) | Koordinat hesaplama modunu [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) nesnesi olarak ayarlar. |
|
|  | [isShowDeletedContent()](#isShowDeletedContent--) | Sonuç belgesinde silinen bileşenlerin gösterilip gösterilmeyeceğini belirten bir bayrağı alır. |
|
|  | [setShowDeletedContent(boolean value)](#setShowDeletedContent-boolean-) | Sonuç belgesinde silinen bileşenlerin gösterilip gösterilmeyeceğini belirten bir bayrağı ayarlar. |
|
|  | [isShowInsertedContent()](#isShowInsertedContent--) | Sonuç belgesinde eklenen bileşenlerin gösterilip gösterilmeyeceğini belirten bir bayrağı alır. |
|
|  | [setShowInsertedContent(boolean value)](#setShowInsertedContent-boolean-) | Sonuç belgesinde eklenen bileşenlerin gösterilip gösterilmeyeceğini belirten bir bayrağı ayarlar. |
|
|  | [isGenerateSummaryPage()](#isGenerateSummaryPage--) | Sonuç belgesine tespit edilen değişiklik istatistikleriyle özet sayfa eklenip eklenmeyeceğini belirten bir bayrağı alır. |
|
|  | [setGenerateSummaryPage(boolean value)](#setGenerateSummaryPage-boolean-) | Sonuç belgesine tespit edilen değişiklik istatistikleriyle özet sayfa eklenip eklenmeyeceğini belirten bir bayrağı ayarlar. |
|
|  | [isExtendedSummaryPage()](#isExtendedSummaryPage--) | Özet sayfaya genişletilmiş dosya karşılaştırma bilgilerinin eklenip eklenmeyeceğini belirten bir bayrağı alır. |
|
|  | [setExtendedSummaryPage(boolean value)](#setExtendedSummaryPage-boolean-) | Özet sayfaya genişletilmiş dosya karşılaştırma bilgilerinin eklenip eklenmeyeceğini belirten bir bayrağı ayarlar. |
|
|  | [isShowOnlySummaryPage()](#isShowOnlySummaryPage--) | Sonuç belgesinde sadece tespit edilen değişikliklerin istatistikleriyle bir sayfa bırakılıp bırakılmayacağını belirten bir bayrağı alır. |
|
|  | [setShowOnlySummaryPage(boolean value)](#setShowOnlySummaryPage-boolean-) | Sonuç belgesinde sadece tespit edilen değişikliklerin istatistikleriyle bir sayfa bırakılıp bırakılmayacağını belirten bir bayrağı ayarlar. |
|
|  | [isDetectStyleChanges()](#isDetectStyleChanges--) | Stil değişikliklerini tespit edip etmeyeceğini belirten bir bayrağı alır. |
|
|  | [setDetectStyleChanges(boolean value)](#setDetectStyleChanges-boolean-) | Stil değişikliklerini tespit edip etmeyeceğini belirten bir bayrağı ayarlar. |
|
|  | [isMarkNestedContent()](#isMarkNestedContent--) | Silinen veya eklenen öğelerin alt öğelerinin silinmiş veya eklenmiş olarak işaretlenip işaretlenmeyeceğini gösteren bir bayrak alır. |
|
|  | [setMarkNestedContent(boolean value)](#setMarkNestedContent-boolean-) | Silinen veya eklenen öğelerin alt öğelerinin silinmiş veya eklenmiş olarak işaretlenip işaretlenmeyeceğini gösteren bir bayrağı ayarlar. |
|
|  | [isCalculateCoordinates()](#isCalculateCoordinates--) | Değiştirilen bileşenler için koordinatların hesaplanıp hesaplanmayacağını gösteren bir bayrak alır. |
|
|  | [setCalculateCoordinates(boolean value)](#setCalculateCoordinates-boolean-) | Değiştirilen bileşenler için koordinatların hesaplanıp hesaplanmayacağını gösteren bir bayrağı ayarlar. |
|
|  | [isHeaderFootersComparison()](#isHeaderFootersComparison--) | Üstbilgi/altbilgi içeriklerinin karşılaştırılıp karşılaştırılmayacağını gösteren bir bayrak alır. |
|
|  | [setHeaderFootersComparison(boolean value)](#setHeaderFootersComparison-boolean-) | Üstbilgi/altbilgi içeriklerinin karşılaştırılıp karşılaştırılmayacağını gösteren bir bayrağı ayarlar. |
|
|  | [getDetalisationLevel()](#getDetalisationLevel--) | Karşılaştırma detaylandırma seviyesini, [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) olarak alır. |
|
|  | [setDetalisationLevel(DetalisationLevel value)](#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-) | Karşılaştırma detaylandırma seviyesini, [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) olarak ayarlar. |
|
|  | [isMarkChangedContent()](#isMarkChangedContent--) | Word Processing'deki şekiller ve Image belgelerindeki dikdörtgenler için çerçevelerin kullanılıp kullanılmayacağını gösteren bir bayrak alır. |
|
|  | [setMarkChangedContent(boolean value)](#setMarkChangedContent-boolean-) | Word Processing'deki şekiller ve Image belgelerindeki dikdörtgenler için çerçevelerin kullanılıp kullanılmayacağını gösteren bir bayrağı ayarlar. |
|
|  | [getInsertedItemStyle()](#getInsertedItemStyle--) | Eklenecek öğelere uygulanacak stil ayarlarını alır. |
|
|  | [setInsertedItemStyle(StyleSettings value)](#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Eklenecek öğelere uygulanacak stil ayarlarını ayarlar. |
|
|  | [getDeletedItemStyle()](#getDeletedItemStyle--) | Silinecek öğelere uygulanacak stil ayarlarını alır. |
|
|  | [setDeletedItemStyle(StyleSettings value)](#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Silinecek öğelere uygulanacak stil ayarlarını ayarlar. |
|
|  | [getChangedItemStyle()](#getChangedItemStyle--) | Değiştirilen öğelere uygulanacak stil ayarlarını alır. |
|
|  | [setChangedItemStyle(StyleSettings value)](#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-) | Değiştirilen öğelere uygulanacak stil ayarlarını ayarlar. |
|
|  | [getSensitivityOfComparison()](#getSensitivityOfComparison--) | Karşılaştırma duyarlılığını alır. |
|
|  | [setSensitivityOfComparison(int value)](#setSensitivityOfComparison-int-) | Karşılaştırma duyarlılığını ayarlar. |
|
|  | [setSensitivityOfComparisonForTables(Integer value)](#setSensitivityOfComparisonForTables-java.lang.Integer-) | Tablolar için karşılaştırma duyarlılığını ayarlar. |
|
|  | [getSensitivityOfComparisonForTables()](#getSensitivityOfComparisonForTables--) | Tablolar için karşılaştırma duyarlılığını al. |
|
|  | [setWordsSeparatorChars(char[] value)](#setWordsSeparatorChars-char---) | Metni kelimelere bölmek için kullanılacak ayraçların bir dizisini ayarlar. |
|
|  | [getPasswordSaveOption()](#getPasswordSaveOption--) | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) nesnesiyle temsil edilen bir şifre kaydetme seçeneğini alır. |
|
|  | [setPasswordSaveOption(PasswordSaveOption value)](#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-) | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) nesnesiyle temsil edilen bir şifre kaydetme seçeneğini ayarlar. |
|
|  | [getOriginalSize()](#getOriginalSize--) | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) nesnesiyle temsil edilen karşılaştırılan belgelerin orijinal boyutlarını alır. |
|
|  | [setOriginalSize(OriginalSize value)](#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-) | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) nesnesiyle temsil edilen karşılaştırılan belgelerin orijinal boyutlarını ayarlar. |
|
|  | [getDiagramMasterSetting()](#getDiagramMasterSetting--) | Diagram belgeleri için ana sayfa ayarını, [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) nesnesiyle temsil edilen, alır. |
|
|  | [setDiagramMasterSetting(DiagramMasterSetting value)](#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-) | Diagram belgeleri için ana sayfa ayarını, [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) nesnesiyle temsil edilen, ayarlar. |
|
|  | [isDirectoryCompare()](#isDirectoryCompare--) | Dizin karşılaştırmasının etkin olup olmadığını gösteren bir bayrağı döndürür. |
|
|  | [setDirectoryCompare(boolean directoryCompare)](#setDirectoryCompare-boolean-) | Dizin karşılaştırmasının etkinleştirilip etkinleştirilmeyeceğini gösteren bir bayrağı ayarlar. |
|
|  | [isShowOnlyChanged()](#isShowOnlyChanged--) | Yalnızca değişen öğelerin gösterilip gösterilmeyeceğini belirten bir boolean değer döndürür. |
|
|  | [setShowOnlyChanged(boolean showOnlyChanged)](#setShowOnlyChanged-boolean-) | Yalnızca değişen öğelerin gösterilip gösterilmeyeceğini belirten değeri ayarlar. |
|
|  | [getFolderComparisonExtension()](#getFolderComparisonExtension--) | Sonuç klasör karşılaştırma dosyasının biçimini alır. |
|
|  | [setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)](#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-) | Sonuç klasör karşılaştırma dosyasının biçimini ayarlar. |
|
### CompareOptions() {#CompareOptions--}
```
public CompareOptions()
```


CompareOptions sınıfının yeni bir örneğini başlatır.


### CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle) {#CompareOptions-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-com.groupdocs.comparison.options.style.StyleSettings-}
```
public CompareOptions(StyleSettings insertedItemStyle, StyleSettings deletedItemStyle, StyleSettings changedItemStyle)
```


CompareOptions sınıfının farklı stiller için ayarlarla yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | insertedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Eklenen öğeler için stil ayarları |
|
|  | deletedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Silinen öğeler için stil ayarları |
|
|  | changedItemStyle | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Değiştirilen stil öğeleri için stil ayarları |
|

### ignoreChangeSettings {#ignoreChangeSettings}
```
public IgnoreChangeSensitivitySettings ignoreChangeSettings
```


### getIgnoreChangeSettings() {#getIgnoreChangeSettings--}
```
public IgnoreChangeSensitivitySettings getIgnoreChangeSettings()
```


Benzerliğe dayalı değişiklikleri yok saymak için ayarları al.


**Returns:**
com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings - Değişiklikleri yok saymak için ayarlar.

### setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings) {#setIgnoreChangeSettings-com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings-}
```
public void setIgnoreChangeSettings(IgnoreChangeSensitivitySettings ignoreChangeSettings)
```


Benzerliğe dayalı değişiklikleri yok saymak için ayarları ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ignoreChangeSettings | com.groupdocs.comparison.options.IgnoreChangeSensitivitySettings | Değişiklikleri yok saymak için ayarlar. |
|

### getUserMasterPath() {#getUserMasterPath--}
```
public String getUserMasterPath()
```


Diyagramlar için kullanıcı ana şablonunun yolunu alır.


**Returns:**
java.lang.String - Diagramlar için kullanıcı ana şablonunun yolu.

### setUserMasterPath(String userMasterPath) {#setUserMasterPath-java.lang.String-}
```
public void setUserMasterPath(String userMasterPath)
```


Diyagramlar için kullanıcı ana şablonunun yolunu ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | userMasterPath | java.lang.String | Diagramlar için kullanıcı ana şablonunun yolu. |
|

### getComparisonType() {#getComparisonType--}
```
public ComparisonType getComparisonType()
```


Kaynak ve hedef belgelerin tipini, Comparison'ın nasıl karşılaştırılacağını bilmesi için [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) nesnesi olarak alır.
Bu seçenek ayarlandığında, [LoadOptions.getFileType()](../../com.groupdocs.comparison.options.load/loadoptions#getFileType--) seçeneği atlanacaktır.


**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - the type of source and target documents

### setComparisonType(ComparisonType comparisonType) {#setComparisonType-com.groupdocs.comparison.options.enums.ComparisonType-}
```
public void setComparisonType(ComparisonType comparisonType)
```


Kaynak ve hedef belgelerin tipini, Comparison'ın nasıl karşılaştırılacağını bilmesi için [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) nesnesi olarak ayarlar.
Bu seçenek ayarlandığında, [LoadOptions.setFileType(FileType)](../../com.groupdocs.comparison.options.load/loadoptions#setFileType-FileType-) seçeneği atlanacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | comparisonType | [ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) | Kaynak ve hedef belgelerin türü |
|

### getPaperSize() {#getPaperSize--}
```
public final PaperSize getPaperSize()
```


Sonuç belgesindeki kağıt boyutunu [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) nesnesi olarak alır.


**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - the size of a paper in result document

### setPaperSize(PaperSize value) {#setPaperSize-com.groupdocs.comparison.options.enums.PaperSize-}
```
public final void setPaperSize(PaperSize value)
```


Sonuç belgesindeki kağıt boyutunu [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) nesnesi olarak ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [PaperSize](../../com.groupdocs.comparison.options.enums/papersize) | Sonuç belgesindeki kağıdın boyutu |
|

### getCalculateCoordinatesMode() {#getCalculateCoordinatesMode--}
```
public CalculateCoordinatesModeEnumeration getCalculateCoordinatesMode()
```


Koordinat hesaplama modunu [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) nesnesi olarak alır.


**Returns:**
[CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) - the calculate coordinates mode

### setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode) {#setCalculateCoordinatesMode-com.groupdocs.comparison.options.enums.CalculateCoordinatesModeEnumeration-}
```
public void setCalculateCoordinatesMode(CalculateCoordinatesModeEnumeration calculateCoordinatesMode)
```


Koordinat hesaplama modunu [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) nesnesi olarak ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | calculateCoordinatesMode | [CalculateCoordinatesModeEnumeration](../../com.groupdocs.comparison.options.enums/calculatecoordinatesmodeenumeration) | Koordinatları hesaplama modu |
|

### isShowDeletedContent() {#isShowDeletedContent--}
```
public final boolean isShowDeletedContent()
```


Sonuç belgesinde silinen bileşenlerin gösterilip gösterilmeyeceğini belirten bir bayrağı alır.


**Returns:**
boolean - sonuç belgesindeki silinen bileşenler gösterilecekse true, aksi takdirde false

### setShowDeletedContent(boolean value) {#setShowDeletedContent-boolean-}
```
public final void setShowDeletedContent(boolean value)
```


Sonuç belgesinde silinen bileşenlerin gösterilip gösterilmeyeceğini belirten bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | sonuç belgesindeki silinen bileşenler gösterilecekse true, aksi takdirde false |
|

### isShowInsertedContent() {#isShowInsertedContent--}
```
public final boolean isShowInsertedContent()
```


Sonuç belgesinde eklenen bileşenlerin gösterilip gösterilmeyeceğini belirten bir bayrağı alır.


**Returns:**
boolean - true ise sonuç belgesindeki eklenen bileşenler gösterilmeli, aksi takdirde false

### setShowInsertedContent(boolean value) {#setShowInsertedContent-boolean-}
```
public final void setShowInsertedContent(boolean value)
```


Sonuç belgesinde eklenen bileşenlerin gösterilip gösterilmeyeceğini belirten bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true ise sonuç belgesindeki eklenen bileşenler gösterilmeli, aksi takdirde false |
|

### isGenerateSummaryPage() {#isGenerateSummaryPage--}
```
public final boolean isGenerateSummaryPage()
```


Sonuç belgesine tespit edilen değişiklik istatistikleriyle özet sayfa eklenip eklenmeyeceğini belirten bir bayrağı alır.


**Returns:**
boolean - true ise özet sayfa eklenecek, aksi takdirde false

### setGenerateSummaryPage(boolean value) {#setGenerateSummaryPage-boolean-}
```
public final void setGenerateSummaryPage(boolean value)
```


Sonuç belgesine tespit edilen değişiklik istatistikleriyle özet sayfa eklenip eklenmeyeceğini belirten bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true ise özet sayfa eklenmeli, aksi takdirde false |
|

### isExtendedSummaryPage() {#isExtendedSummaryPage--}
```
public boolean isExtendedSummaryPage()
```


Özet sayfaya genişletilmiş dosya karşılaştırma bilgilerinin eklenip eklenmeyeceğini belirten bir bayrağı alır.


**Returns:**
boolean - true ise genişletilmiş dosya karşılaştırma bilgileri özet sayfaya eklenecek, aksi takdirde false

### setExtendedSummaryPage(boolean value) {#setExtendedSummaryPage-boolean-}
```
public void setExtendedSummaryPage(boolean value)
```


Özet sayfaya genişletilmiş dosya karşılaştırma bilgilerinin eklenip eklenmeyeceğini belirten bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true ise genişletilmiş dosya karşılaştırma bilgileri özet sayfaya eklenmeli, aksi takdirde false |
|

### isShowOnlySummaryPage() {#isShowOnlySummaryPage--}
```
public boolean isShowOnlySummaryPage()
```


Sonuç belgesinde sadece tespit edilen değişikliklerin istatistikleriyle bir sayfa bırakılıp bırakılmayacağını belirten bir bayrağı alır.


**Returns:**
boolean - true ise sonuç belgesinde yalnızca tespit edilen değişikliklerin istatistiklerini içeren bir sayfa bırakılacak, aksi takdirde false

### setShowOnlySummaryPage(boolean value) {#setShowOnlySummaryPage-boolean-}
```
public void setShowOnlySummaryPage(boolean value)
```


Sonuç belgesinde sadece tespit edilen değişikliklerin istatistikleriyle bir sayfa bırakılıp bırakılmayacağını belirten bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true ise sonuç belgesinde yalnızca tespit edilen değişikliklerin istatistiklerini içeren bir sayfa bırakılmalı, aksi takdirde false |
|

### isDetectStyleChanges() {#isDetectStyleChanges--}
```
public final boolean isDetectStyleChanges()
```


Stil değişikliklerini tespit edip etmeyeceğini belirten bir bayrağı alır.


**Returns:**
boolean - true ise stil değişiklikleri tespit edilecek, aksi takdirde false

### setDetectStyleChanges(boolean value) {#setDetectStyleChanges-boolean-}
```
public final void setDetectStyleChanges(boolean value)
```


Stil değişikliklerini tespit edip etmeyeceğini belirten bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true ise stil değişiklikleri tespit edilmeli, aksi takdirde false |
|

### isMarkNestedContent() {#isMarkNestedContent--}
```
public final boolean isMarkNestedContent()
```


Silinen veya eklenen öğelerin alt öğelerinin silinmiş veya eklenmiş olarak işaretlenip işaretlenmeyeceğini gösteren bir bayrak alır.


**Returns:**
boolean - true ise silinen veya eklenen öğelerin alt öğeleri silinmiş veya eklenmiş olarak işaretlenecek, aksi takdirde false

### setMarkNestedContent(boolean value) {#setMarkNestedContent-boolean-}
```
public final void setMarkNestedContent(boolean value)
```


Silinen veya eklenen öğelerin alt öğelerinin silinmiş veya eklenmiş olarak işaretlenip işaretlenmeyeceğini gösteren bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true ise silinen veya eklenen öğelerin alt öğeleri silinmiş veya eklenmiş olarak işaretlenmeli, aksi takdirde false |
|

### isCalculateCoordinates() {#isCalculateCoordinates--}
```
public final boolean isCalculateCoordinates()
```


Değiştirilen bileşenler için koordinatların hesaplanıp hesaplanmayacağını gösteren bir bayrak alır.


**Returns:**
boolean - true ise değiştirilen bileşenlerin koordinatları hesaplanacak, aksi takdirde false

### setCalculateCoordinates(boolean value) {#setCalculateCoordinates-boolean-}
```
public final void setCalculateCoordinates(boolean value)
```


Değiştirilen bileşenler için koordinatların hesaplanıp hesaplanmayacağını gösteren bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true ise değiştirilen bileşenlerin koordinatları hesaplanmalı, aksi takdirde false |
|

### isHeaderFootersComparison() {#isHeaderFootersComparison--}
```
public final boolean isHeaderFootersComparison()
```


Üstbilgi/altbilgi içeriklerinin karşılaştırılıp karşılaştırılmayacağını gösteren bir bayrak alır.


**Returns:**
boolean - true ise üstbilgi/altbilgi içerikleri karşılaştırılacak, aksi takdirde false

### setHeaderFootersComparison(boolean value) {#setHeaderFootersComparison-boolean-}
```
public final void setHeaderFootersComparison(boolean value)
```


Üstbilgi/altbilgi içeriklerinin karşılaştırılıp karşılaştırılmayacağını gösteren bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true ise üstbilgi/altbilgi içerikleri karşılaştırılmalı, aksi takdirde false |
|

### getDetalisationLevel() {#getDetalisationLevel--}
```
public final DetalisationLevel getDetalisationLevel()
```


Karşılaştırma detaylandırma seviyesini, [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) olarak alır.
Varsayılan değer [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW) olarak belirlenmiştir.


**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - the level of comparison detalization

### setDetalisationLevel(DetalisationLevel value) {#setDetalisationLevel-com.groupdocs.comparison.options.style.DetalisationLevel-}
```
public final void setDetalisationLevel(DetalisationLevel value)
```


Karşılaştırma detaylandırma seviyesini, [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) olarak ayarlar.
Varsayılan değer [DetalisationLevel.LOW](../../com.groupdocs.comparison.options.style/detalisationlevel#LOW) olarak belirlenmiştir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) | Karşılaştırma detaylandırma seviyesi |
|

### isMarkChangedContent() {#isMarkChangedContent--}
```
public final boolean isMarkChangedContent()
```


Word Processing'deki şekiller ve Image belgelerindeki dikdörtgenler için çerçevelerin kullanılıp kullanılmayacağını gösteren bir bayrak alır.


**Returns:**
boolean - true ise çerçeveler kullanılacak, aksi takdirde false

### setMarkChangedContent(boolean value) {#setMarkChangedContent-boolean-}
```
public final void setMarkChangedContent(boolean value)
```


Word Processing'deki şekiller ve Image belgelerindeki dikdörtgenler için çerçevelerin kullanılıp kullanılmayacağını gösteren bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true ise çerçeveler kullanılmalı, aksi takdirde false |
|

### getInsertedItemStyle() {#getInsertedItemStyle--}
```
public final StyleSettings getInsertedItemStyle()
```


Eklenecek öğelere uygulanacak stil ayarlarını alır.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of inserted items

### setInsertedItemStyle(StyleSettings value) {#setInsertedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setInsertedItemStyle(StyleSettings value)
```


Eklenecek öğelere uygulanacak stil ayarlarını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Eklenen öğelerin stil ayarları |
|

### getDeletedItemStyle() {#getDeletedItemStyle--}
```
public final StyleSettings getDeletedItemStyle()
```


Silinecek öğelere uygulanacak stil ayarlarını alır.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of deleted items

### setDeletedItemStyle(StyleSettings value) {#setDeletedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setDeletedItemStyle(StyleSettings value)
```


Silinecek öğelere uygulanacak stil ayarlarını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Silinen öğelerin stil ayarları |
|

### getChangedItemStyle() {#getChangedItemStyle--}
```
public final StyleSettings getChangedItemStyle()
```


Değiştirilen öğelere uygulanacak stil ayarlarını alır.


**Returns:**
[StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) - style settings of changed items

### setChangedItemStyle(StyleSettings value) {#setChangedItemStyle-com.groupdocs.comparison.options.style.StyleSettings-}
```
public final void setChangedItemStyle(StyleSettings value)
```


Değiştirilen öğelere uygulanacak stil ayarlarını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [StyleSettings](../../com.groupdocs.comparison.options.style/stylesettings) | Değiştirilen öğelerin stil ayarları |
|

### getSensitivityOfComparison() {#getSensitivityOfComparison--}
```
public final int getSensitivityOfComparison()
```


Karşılaştırma duyarlılığını alır.
İki karşılaştırılan nesnenin tüm öğelerine göre silinen ve eklenen öğelerin yüzdesi.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
int - karşılaştırmanın duyarlılığı

### setSensitivityOfComparison(int value) {#setSensitivityOfComparison-int-}
```
public final void setSensitivityOfComparison(int value)
```


Karşılaştırma duyarlılığını ayarlar.
İki karşılaştırılan nesnenin tüm öğelerine göre silinen ve eklenen öğelerin yüzdesi.

* If this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Karşılaştırmanın duyarlılığı |
|

### setSensitivityOfComparisonForTables(Integer value) {#setSensitivityOfComparisonForTables-java.lang.Integer-}
```
public void setSensitivityOfComparisonForTables(Integer value)
```


Tablolar için karşılaştırma duyarlılığını ayarlar.
Değer null ise, SensitivityOfComparison yerine kullanılır. İki karşılaştırılan nesnenin silinen ve eklenen öğelerinin, bu nesnelerin tüm öğelerine oranla yüzde değeri.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.Integer | Tablolar için karşılaştırma duyarlılığı |
|

### getSensitivityOfComparisonForTables() {#getSensitivityOfComparisonForTables--}
```
public final Integer getSensitivityOfComparisonForTables()
```


Tablolar için karşılaştırma duyarlılığını al.
Değer null ise, SensitivityOfComparison yerine kullanılır. İki karşılaştırılan nesnenin silinen ve eklenen öğelerinin, bu nesnelerin tüm öğelerine oranla yüzde değeri.

* if this percentage if exceeded, the object aren't compared but are considered completely inserted and deleted.
* Min value - 0% =\> The comparison doesn't occur for any length of the common subsequence of two compared object.
* Default value - 75% =\> Comparison occurs, if the percentage of deleted and inserted elements of two compared object with respect to all elements of these objects isn't more then 75.
* Max value - 100% =\> The comparison occurs at any length of the common subsequence of two compared objects.


**Returns:**
java.lang.Integer - Tablolar için karşılaştırma duyarlılığı

### setWordsSeparatorChars(char[] value) {#setWordsSeparatorChars-char---}
```
public final void setWordsSeparatorChars(char[] value)
```


Metni kelimelere bölmek için kullanılacak ayraçların bir dizisini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | char[] | Metni kelimelere bölmek için kullanılan ayırıcıların dizisi |
|

### getPasswordSaveOption() {#getPasswordSaveOption--}
```
public final PasswordSaveOption getPasswordSaveOption()
```


[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) nesnesiyle temsil edilen bir şifre kaydetme seçeneğini alır.


**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - the password save option

### setPasswordSaveOption(PasswordSaveOption value) {#setPasswordSaveOption-com.groupdocs.comparison.options.enums.PasswordSaveOption-}
```
public final void setPasswordSaveOption(PasswordSaveOption value)
```


[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) nesnesiyle temsil edilen bir şifre kaydetme seçeneğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) | Parola kaydetme seçeneği |
|

### getOriginalSize() {#getOriginalSize--}
```
public final OriginalSize getOriginalSize()
```


[OriginalSize](../../com.groupdocs.comparison.options/originalsize) nesnesiyle temsil edilen karşılaştırılan belgelerin orijinal boyutlarını alır.


**Returns:**
[OriginalSize](../../com.groupdocs.comparison.options/originalsize) - the original size of documents

### setOriginalSize(OriginalSize value) {#setOriginalSize-com.groupdocs.comparison.options.OriginalSize-}
```
public final void setOriginalSize(OriginalSize value)
```


[OriginalSize](../../com.groupdocs.comparison.options/originalsize) nesnesiyle temsil edilen karşılaştırılan belgelerin orijinal boyutlarını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [OriginalSize](../../com.groupdocs.comparison.options/originalsize) | Belgelerin orijinal boyutu |
|

### getDiagramMasterSetting() {#getDiagramMasterSetting--}
```
public final DiagramMasterSetting getDiagramMasterSetting()
```


Diagram belgeleri için ana sayfa ayarını, [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) nesnesiyle temsil edilen, alır.


**Returns:**
[DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) - the diagram master page setting

### setDiagramMasterSetting(DiagramMasterSetting value) {#setDiagramMasterSetting-com.groupdocs.comparison.options.style.DiagramMasterSetting-}
```
public final void setDiagramMasterSetting(DiagramMasterSetting value)
```


Diagram belgeleri için ana sayfa ayarını, [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) nesnesiyle temsil edilen, ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [DiagramMasterSetting](../../com.groupdocs.comparison.options.style/diagrammastersetting) | Diyagram ana sayfa ayarı |
|

### isDirectoryCompare() {#isDirectoryCompare--}
```
public boolean isDirectoryCompare()
```


Dizin karşılaştırmasının etkin olup olmadığını gösteren bir bayrağı döndürür.


**Returns:**
boolean - dizin karşılaştırması etkinse true, aksi takdirde false

### setDirectoryCompare(boolean directoryCompare) {#setDirectoryCompare-boolean-}
```
public void setDirectoryCompare(boolean directoryCompare)
```


Dizin karşılaştırmasının etkinleştirilip etkinleştirilmeyeceğini gösteren bir bayrağı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | directoryCompare | boolean | dizin karşılaştırması etkinleştirilecekse true, aksi takdirde false |
|

### isShowOnlyChanged() {#isShowOnlyChanged--}
```
public boolean isShowOnlyChanged()
```


Yalnızca değişen öğelerin gösterilip gösterilmeyeceğini belirten bir boolean değer döndürür.


**Returns:**
boolean - yalnızca değişen öğeler gösterilecekse true, aksi takdirde false

### setShowOnlyChanged(boolean showOnlyChanged) {#setShowOnlyChanged-boolean-}
```
public void setShowOnlyChanged(boolean showOnlyChanged)
```


Yalnızca değişen öğelerin gösterilip gösterilmeyeceğini belirten değeri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | showOnlyChanged | boolean | yalnızca değişen öğelerin gösterilip gösterilmeyeceğini belirten boolean değer |
|

### getFolderComparisonExtension() {#getFolderComparisonExtension--}
```
public FolderComparisonExtension getFolderComparisonExtension()
```


Sonuç klasör karşılaştırma dosyasının biçimini alır.


**Returns:**
com.groupdocs.comparison.options.enums.FolderComparisonExtension - sonuç klasör karşılaştırma dosyasının formatını temsil eden FolderComparisonExtension

### setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension) {#setFolderComparisonExtension-com.groupdocs.comparison.options.enums.FolderComparisonExtension-}
```
public void setFolderComparisonExtension(FolderComparisonExtension folderComparisonExtension)
```


Sonuç klasör karşılaştırma dosyasının biçimini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | folderComparisonExtension | com.groupdocs.comparison.options.enums.FolderComparisonExtension | sonuç klasör karşılaştırma dosyasının formatını temsil eden FolderComparisonExtension |
|

