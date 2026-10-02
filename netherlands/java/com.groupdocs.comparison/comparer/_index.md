---
title: "Comparer"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "De Comparer-klasse biedt functionaliteit voor het vergelijken van documenten en het genereren van vergelijkingsresultaten."
type: docs
weight: 10
url: /nl/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

De Comparer-klasse biedt functionaliteit voor het vergelijken van documenten en het genereren van vergelijkingsresultaten.


Het stelt u in staat om verschillende soorten documenten te vergelijken, zoals PDF, Word, Excel, PowerPoint en meer.


Voorbeeldgebruik:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad. |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven mappad en vergelijkingsopties. |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Initialiseert een nieuw exemplaar van Comparer met het opgegeven bronbestandspad en [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Initialiseert een nieuw exemplaar van Comparer met het opgegeven bronbestandspad en [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Initialiseert een nieuw exemplaar van Comparer met het opgegeven bronbestandspad en [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) en [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) en [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad en [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad en [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) en [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) en [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met de opgegeven brondocumentstroom. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Initialiseert een nieuw exemplaar van Comparer met de opgegeven brondocumentstroom en [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met de opgegeven brondocumentstroom en [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met de opgegeven documentstroom, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) en [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | Initialiseert een nieuw exemplaar van de Comparer-klasse met de opgegeven [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSource()](#getSource--) | Haalt het brondocument op dat wordt vergeleken. |
|
|  | [getTargets()](#getTargets--) | Lijst van doeldocumenten om te vergelijken met het bronbestand. |
|
|  | [compare()](#compare--) | Vergelijkt het opgegeven bestand met de doeldocumenten zonder het resultaat op te slaan met standaardopties. |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | Vergelijkt het opgegeven bestand met de doeldocumenten en genereert een vergelijkingsresultaat. |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | Vergelijkt het opgegeven bestand met de doeldocumenten en genereert een vergelijkingsresultaat. |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar de uitvoerstroom. |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad. |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad. |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar de uitvoerstroom. |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Vergelijkt het opgegeven bestand met de doeldocumenten zonder het resultaat op te slaan. |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad. |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad. |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad. |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | Vergelijkt het opgegeven bestand met de doeldocumenten zonder het resultaat op te slaan. |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar de opgegeven uitvoerstroom. |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad. |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Vergelijkt de opgegeven map met de doelmap en slaat het vergelijkingsresultaat op naar het opgegeven bestandspad. |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Vergelijkt de opgegeven map met de doelmap en slaat het vergelijkingsresultaat op naar het opgegeven bestandspad. |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad. |
|
|  | [add(String filePath)](#add-java.lang.String-) | Voegt het opgegeven doeldocument toe aan het vergelijkingsproces. |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Voegt het opgegeven doeldocument of map toe aan het vergelijkingsproces. |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | Voegt het opgegeven doeldocument toe aan het vergelijkingsproces. |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | Voegt de opgegeven doeldocumenten toe aan het vergelijkingsproces. |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | Voegt de opgegeven doeldocumenten toe aan het vergelijkingsproces. |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Voegt het opgegeven doeldocument toe aan het vergelijkingsproces met de gespecificeerde laadopties. |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Voegt het opgegeven doeldocument toe aan het vergelijkingsproces met de gespecificeerde laadopties. |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Voegt het opgegeven doeldocument toe aan het vergelijkingsproces met de gespecificeerde laadopties. |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | Voegt het opgegeven doeldocument toe aan het vergelijkingsproces. |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | Voegt de opgegeven doeldocumenten toe aan het vergelijkingsproces. |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Voegt het opgegeven doeldocument toe aan het vergelijkingsproces met de gespecificeerde laadopties. |
|
|  | [getChanges()](#getChanges--) | Haalt een array op van [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objecten die de tijdens het vergelijkingsproces gedetecteerde wijzigingen weergeven. |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | Haalt een array op van [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objecten die de tijdens het vergelijkingsproces gedetecteerde wijzigingen weergeven. |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepteert of wijst wijzigingen af en past ze toe op het resultaatsdocument. |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepteert of wijst wijzigingen af en past ze toe op het resulterende document. |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepteert of wijst wijzigingen af en past ze toe op het resulterende document. |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepteert of wijst wijzigingen af en past ze toe op het resulterende document. |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepteert of wijst wijzigingen af en past ze toe op het resulterende document. |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Accepteert of wijst wijzigingen af en past ze toe op het resulterende document. |
|
|  | [getResultString()](#getResultString--) | Haalt de resultaatsreeks op na vergelijking (alleen voor Tekstvergelijking). |
|
|  | [getSourceFolder()](#getSourceFolder--) | Retourneert de bronmap die wordt vergeleken. |
|
|  | [getTargetFolder()](#getTargetFolder--) | Retourneert de doelmap die wordt vergeleken. |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | Zelfvergelijkingscontrole (e498c23). |
|
|  | [close()](#close--) | Geeft bronnen vrij. |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het pad naar het brondocument |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven mappad en vergelijkingsopties.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het pad naar het brondocument of de map |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De vergelijkingsopties voor mapvergelijking |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Het pad naar het brondocument |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


Initialiseert een nieuw exemplaar van Comparer met het opgegeven bronbestandspad en [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het pad naar het brondocument |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De aangepaste laadopties die op het document moeten worden toegepast |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


Initialiseert een nieuw exemplaar van Comparer met het opgegeven bronbestandspad en [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Het pad naar het brondocument |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De aangepaste laadopties die op het document moeten worden toegepast |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


Initialiseert een nieuw exemplaar van Comparer met het opgegeven bronbestandspad en [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Het pad naar het brondocument |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De vergelijkingsopties voor mapvergelijking |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) en [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het pad naar het brondocument |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De aangepaste laadopties die op het document moeten worden toegepast |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | De comparer-instellingen die moeten worden gebruikt voor het vergelijkingsproces |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) en [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het pad naar het brondocument, de map of de te vergelijken tekst |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De aangepaste laadopties die op het document moeten worden toegepast |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | De comparer-instellingen die moeten worden gebruikt voor het vergelijkingsproces |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De vergelijkingsopties voor mapvergelijking |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad en [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het pad naar het brondocument |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | De comparer-instellingen die moeten worden gebruikt voor het vergelijkingsproces |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad en [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Het pad naar het brondocument |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | De comparer-instellingen die moeten worden gebruikt voor het vergelijkingsproces |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) en [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Het pad naar het brondocument |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De aangepaste laadopties die op het document moeten worden toegepast |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | De comparer-instellingen die moeten worden gebruikt voor het vergelijkingsproces |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met het opgegeven bronbestandspad, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) en [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Het pad naar het brondocument of de map |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De aangepaste laadopties die op het document moeten worden toegepast |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | De comparer-instellingen die moeten worden gebruikt voor het vergelijkingsproces |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De vergelijkingsopties voor mapvergelijking |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met de opgegeven brondocumentstroom.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De invoerstroom van het brondocument |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


Initialiseert een nieuw exemplaar van Comparer met de opgegeven brondocumentstroom en [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De invoerstroom van het brondocument |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De aangepaste laadopties die op het document moeten worden toegepast |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met de opgegeven brondocumentstroom en [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De invoerstroom van het brondocument |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | De comparer-instellingen die moeten worden gebruikt voor het vergelijkingsproces |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met de opgegeven documentstroom, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) en [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De stroom met gegevens van een document dat moet worden vergeleken |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De aangepaste laadopties die op het document moeten worden toegepast |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | De comparer-instellingen die moeten worden gebruikt voor het vergelijkingsproces |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


Initialiseert een nieuw exemplaar van de Comparer-klasse met de opgegeven [ComparerSettings](../../com.groupdocs.comparison/comparersettings).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | de instellingen |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


Haalt het brondocument op dat wordt vergeleken.


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


Lijst van doeldocumenten om te vergelijken met het bronbestand.


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - de doel-documenten

### compare() {#compare--}
```
public final Path compare()
```


Vergelijkt het opgegeven bestand met de doeldocumenten zonder het resultaat op te slaan met standaardopties.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - het pad van het resultaatdocument of null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


Vergelijkt het opgegeven bestand met de doeldocumenten en genereert een vergelijkingsresultaat.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Resultaatdocumentpad |
|

**Returns:**
java.nio.file.Path - pad van het resultaatbestand of null. In sommige situaties kan de extensie worden gewijzigd

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


Vergelijkt het opgegeven bestand met de doeldocumenten en genereert een vergelijkingsresultaat.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Resultaatdocumentpad |
|

**Returns:**
java.nio.file.Path - pad van het resultaatbestand, in sommige situaties kan de extensie worden gewijzigd

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar de uitvoerstroom.


Opmerking: In gevallen waarin de retourwaarde null is, gebruik de gegevens die in outputStream zijn geschreven

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Resultaatdocumentstroom |
|

**Returns:**
java.nio.file.Path - pad van het resultaatbestand of null wanneer gegevens van  outputStream  moeten worden gebruikt. In sommige situaties kan de extensie van het resultaatbestand worden gewijzigd

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Pad van het resultaatdocumentbestand |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De vergelijkingsopties die moeten worden gebruikt voor het vergelijkingsproces |
|

**Returns:**
java.nio.file.Path - pad van het resultaatbestand, in sommige situaties kan de extensie worden gewijzigd

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Pad van het resultaatdocumentbestand |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De vergelijkingsopties die moeten worden gebruikt voor het vergelijkingsproces |
|

**Returns:**
java.nio.file.Path - pad van het resultaatbestand, in sommige situaties kan de extensie worden gewijzigd

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar de uitvoerstroom.


Opmerking: In het geval dat de retourwaarde null is, gebruik de gegevens die in outputStream zijn geschreven.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stroom | java.io.OutputStream | Resultaatdocumentstroom |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De vergelijkingsopties die moeten worden gebruikt voor het vergelijkingsproces |
|

**Returns:**
java.nio.file.Path - pad van het resultaatbestand of null wanneer gegevens van  outputStream  moeten worden gebruikt. In sommige situaties kan de extensie van het resultaatbestand worden gewijzigd

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


Vergelijkt het opgegeven bestand met de doeldocumenten zonder het resultaat op te slaan.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opslaanopties |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De vergelijkingsopties die moeten worden gebruikt voor het vergelijkingsproces |
|

**Returns:**
java.nio.file.Path - het pad van het resultaatdocument of null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Pad van het resultaatdocumentbestand |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opslaanopties |
|

**Returns:**
java.nio.file.Path - pad van het resultaatbestand, in sommige situaties kan de extensie worden gewijzigd

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Pad van het resultaatdocumentbestand |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opslaanopties |
|

**Returns:**
java.nio.file.Path - pad van het resultaatbestand, in sommige situaties kan de extensie worden gewijzigd

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad.


Opmerking: In het geval dat de retourwaarde null is, gebruik de gegevens die in outputStream zijn geschreven

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stroom | java.io.OutputStream | Resultaatdocumentstroom |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Opslaanopties |
|

**Returns:**
java.nio.file.Path - pad van het resultaatbestand of null wanneer gegevens van  outputStream  moeten worden gebruikt. In sommige situaties kan de extensie van het resultaatbestand worden gewijzigd

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


Vergelijkt het opgegeven bestand met de doeldocumenten zonder het resultaat op te slaan.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De vergelijkingsopties die moeten worden gebruikt voor het vergelijkingsproces |
|

**Returns:**
java.nio.file.Path - het pad naar het resultaatbestand of null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar de opgegeven uitvoerstroom.


Opmerking: In het geval dat de retourwaarde null is, gebruik de gegevens die in outputStream zijn geschreven

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Resultaatdocumentstroom |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | De opslagopties die gebruikt moeten worden voor het opslaan van het resultaatdocument |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De vergelijkingsopties die moeten worden gebruikt voor het vergelijkingsproces |
|

**Returns:**
java.nio.file.Path - pad van het resultaatbestand of null wanneer gegevens van  outputStream  moeten worden gebruikt. In sommige situaties kan de extensie van het resultaatbestand worden gewijzigd

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Pad van het resultaatdocumentbestand |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | De opslagopties die gebruikt moeten worden voor het opslaan van het resultaatdocument |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De vergelijkingsopties die moeten worden gebruikt voor het vergelijkingsproces |
|

**Returns:**
java.nio.file.Path - pad van het resultaatbestand, in sommige situaties kan de extensie worden gewijzigd

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


Vergelijkt de opgegeven map met de doelmap en slaat het vergelijkingsresultaat op naar het opgegeven bestandspad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad waar het vergelijkingsresultaat zal worden opgeslagen. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De opties die gebruikt moeten worden voor het mapvergelijkingsproces. |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


Vergelijkt de opgegeven map met de doelmap en slaat het vergelijkingsresultaat op naar het opgegeven bestandspad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Het bestandspad waar het vergelijkingsresultaat zal worden opgeslagen. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De opties die gebruikt moeten worden voor het mapvergelijkingsproces. |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Vergelijkt het opgegeven bestand met de doeldocumenten en schrijft een vergelijkingsresultaat naar het opgegeven bestandspad.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Pad van het resultaatdocumentbestand |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | De opslagopties die gebruikt moeten worden voor het opslaan van het resultaatdocument |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De vergelijkingsopties die moeten worden gebruikt voor het vergelijkingsproces |
|

**Returns:**
java.nio.file.Path - pad van het resultaatbestand, in sommige situaties kan de extensie worden gewijzigd

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


Voegt het opgegeven doeldocument toe aan het vergelijkingsproces.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het pad naar het doeldocument dat moet worden toegevoegd |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


Voegt het opgegeven doeldocument of map toe aan het vergelijkingsproces.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het pad naar het doeldocument of de map die moet worden toegevoegd |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De opties voor de vergelijking |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


Voegt het opgegeven doeldocument toe aan het vergelijkingsproces.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Het pad naar het doeldocument dat moet worden toegevoegd |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


Voegt de opgegeven doeldocumenten toe aan het vergelijkingsproces.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | Paden naar de doeldocumenten die moeten worden toegevoegd |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


Voegt de opgegeven doeldocumenten toe aan het vergelijkingsproces.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | Paden naar de doeldocumenten die moeten worden toegevoegd |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


Voegt het opgegeven doeldocument toe aan het vergelijkingsproces met de gespecificeerde laadopties.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Pad naar het doeldocument dat moet worden toegevoegd |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De aangepaste laadopties die op het document moeten worden toegepast |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


Voegt het opgegeven doeldocument toe aan het vergelijkingsproces met de gespecificeerde laadopties.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Pad naar het doeldocument dat moet worden toegevoegd |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De aangepaste laadopties die op het document moeten worden toegepast |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


Voegt het opgegeven doeldocument toe aan het vergelijkingsproces met de gespecificeerde laadopties.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Het pad naar het doeldocument of de map die moet worden toegevoegd |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | De opties voor de vergelijking |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


Voegt het opgegeven doeldocument toe aan het vergelijkingsproces.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De stroom met gegevens van een document dat moet worden vergeleken |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


Voegt de opgegeven doeldocumenten toe aan het vergelijkingsproces.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | documents | java.io.InputStream[] | Streams met gegevens van documenten die moeten worden vergeleken |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


Voegt het opgegeven doeldocument toe aan het vergelijkingsproces met de gespecificeerde laadopties.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De stroom met gegevens van een document dat moet worden vergeleken |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De aangepaste laadopties die op het document moeten worden toegepast |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Haalt een array op van [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objecten die de tijdens het vergelijkingsproces gedetecteerde wijzigingen weergeven.


Gebruik deze methode om gedetailleerde informatie te krijgen over de wijzigingen tussen het brondocument en het doeldocument(en).
Elk [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) object bevat informatie zoals het type wijziging, het getroffen gebied,
en de inhoud vóór en na de wijziging.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - een array van [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objecten die de wijzigingen vertegenwoordigen die tijdens het vergelijkingsproces zijn gedetecteerd

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


Haalt een array op van [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objecten die de tijdens het vergelijkingsproces gedetecteerde wijzigingen weergeven.


Gebruik deze methode om gedetailleerde informatie te krijgen over de wijzigingen tussen het brondocument en het doeldocument(en).
Elk [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) object bevat informatie zoals het type wijziging, het getroffen gebied,
en de inhoud vóór en na de wijziging.


Parameter [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) maakt het mogelijk om wijzigingen op verschillende manieren te filteren.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | Het object dat het filteren van wijzigingen mogelijk maakt |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - een array van [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objecten die de wijzigingen vertegenwoordigen die tijdens het vergelijkingsproces zijn gedetecteerd

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


Accepteert of wijst wijzigingen af en past ze toe op het resultaatsdocument.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Pad van het resultaatdocumentbestand |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | De aangepaste toepaswijzigingsopties om het proces van het toepassen van wijzigingen te configureren |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


Accepteert of wijst wijzigingen af en past ze toe op het resulterende document.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Pad van het resultaatdocumentbestand |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | De aangepaste toepaswijzigingsopties om het proces van het toepassen van wijzigingen te configureren |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


Accepteert of wijst wijzigingen af en past ze toe op het resulterende document.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | Uitvoerstream van het resultaatdocument |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | De aangepaste toepaswijzigingsopties om het proces van het toepassen van wijzigingen te configureren |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Accepteert of wijst wijzigingen af en past ze toe op het resulterende document.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Pad van het resultaatdocumentbestand |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | De opslagopties om het opslaan van het resultaatdocument te configureren |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | De aangepaste toepaswijzigingsopties om het proces van het toepassen van wijzigingen te configureren |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Accepteert of wijst wijzigingen af en past ze toe op het resulterende document.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Pad van het resultaatdocumentbestand |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | De opslagopties om het opslaan van het resultaatdocument te configureren |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | De aangepaste toepaswijzigingsopties om het proces van het toepassen van wijzigingen te configureren |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Accepteert of wijst wijzigingen af en past ze toe op het resulterende document.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | Uitvoerstream van het resultaatdocument |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | De opslagopties om het opslaan van het resultaatdocument te configureren |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | De aangepaste toepaswijzigingsopties om het proces van het toepassen van wijzigingen te configureren |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


Haalt de resultaatsreeks op na vergelijking (alleen voor Tekstvergelijking).


**Returns:**
java.lang.String - de resultaatstring

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


Retourneert de bronmap die wordt vergeleken.


**Returns:**
java.lang.String - de bronmap

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


Retourneert de doelmap die wordt vergeleken.


**Returns:**
java.lang.String - de doelmap

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


Zelfvergelijkingscontrole (e498c23). C# 7a7668c intern; publiek gehouden zodat core.common-tests kunnen aanroepen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


Geeft bronnen vrij.


