---
title: "Comparer"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Comparer-klassen erbjuder funktionalitet för att jämföra dokument och generera jämförelsresultat."
type: docs
weight: 10
url: /sv/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

Comparer-klassen erbjuder funktionalitet för att jämföra dokument och generera jämförelsresultat.


Den gör det möjligt att jämföra olika typer av dokument, såsom PDF, Word, Excel, PowerPoint och mer.


Exempel på användning:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | Initierar en ny instans av Comparer-klassen med den angivna källfilens sökväg. |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Initierar en ny instans av Comparer-klassen med den angivna mappens sökväg och jämförelsealternativ. |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | Initierar en ny instans av Comparer-klassen med den angivna källfilens sökväg. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Initierar en ny instans av Comparer med den angivna källfilens sökväg och [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Initierar en ny instans av Comparer med den angivna källfilens sökväg och [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Initierar en ny instans av Comparer med den angivna källfilens sökväg och [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initierar en ny instans av Comparer‑klassen med den angivna sökvägen till källfilen, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) och [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Initierar en ny instans av Comparer‑klassen med den angivna sökvägen till källfilen, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) och [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | Initierar en ny instans av Comparer‑klassen med den angivna sökvägen till källfilen och [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | Initierar en ny instans av Comparer‑klassen med den angivna sökvägen till källfilen och [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initierar en ny instans av Comparer‑klassen med den angivna sökvägen till källfilen, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) och [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Initierar en ny instans av Comparer‑klassen med den angivna sökvägen till källfilen, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) och [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | Initierar en ny instans av Comparer‑klassen med den angivna källdokumentströmmen. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Initierar en ny instans av Comparer med den angivna källdokumentströmmen och [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | Initierar en ny instans av Comparer‑klassen med den angivna källdokumentströmmen och [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Initierar en ny instans av Comparer‑klassen med den angivna dokumentströmmen, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) och [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | Initierar en ny instans av Comparer‑klassen med de angivna [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSource()](#getSource--) | Hämtar källdokumentet som jämförs. |
|
|  | [getTargets()](#getTargets--) | Lista över måldokument att jämföra med källfilen. |
|
|  | [compare()](#compare--) | Jämför den angivna filen med måldokumenten utan att spara resultatet med standardalternativ. |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | Jämför den angivna filen med måldokumenten och genererar ett jämförelseresultat. |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | Jämför den angivna filen med måldokumenten och genererar ett jämförelseresultat. |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till utdataströmmen. |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen. |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen. |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till utdataströmmen. |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Jämför den angivna filen med måldokumenten utan att spara resultatet. |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen. |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen. |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen. |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | Jämför den angivna filen med måldokumenten utan att spara resultatet. |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna utdataströmmen. |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen. |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Jämför den angivna katalogen med målkatalogen och sparar jämförelseresultatet till den angivna filsökvägen. |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Jämför den angivna katalogen med målkatalogen och sparar jämförelseresultatet till den angivna filsökvägen. |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen. |
|
|  | [add(String filePath)](#add-java.lang.String-) | Lägger till det angivna måldokumentet i jämförelseprocessen. |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Lägger till det angivna måldokumentet eller mappen i jämförelseprocessen. |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | Lägger till det angivna måldokumentet i jämförelseprocessen. |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | Lägger till de angivna måldokumenten i jämförelseprocessen. |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | Lägger till de angivna måldokumenten i jämförelseprocessen. |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Lägger till det angivna måldokumentet i jämförelseprocessen med angivna laddningsalternativ. |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Lägger till det angivna måldokumentet i jämförelseprocessen med angivna laddningsalternativ. |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Lägger till det angivna måldokumentet i jämförelseprocessen med angivna laddningsalternativ. |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | Lägger till det angivna måldokumentet i jämförelseprocessen. |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | Lägger till de angivna måldokumenten i jämförelseprocessen. |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Lägger till det angivna måldokumentet i jämförelseprocessen med angivna laddningsalternativ. |
|
|  | [getChanges()](#getChanges--) | Hämtar en array av [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objekt som representerar förändringarna som upptäckts under jämförelseprocessen. |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | Hämtar en array av [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objekt som representerar förändringarna som upptäckts under jämförelseprocessen. |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | Godkänner eller avvisar förändringar och tillämpar dem på resultatdokumentet. |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | Godkänner eller avvisar förändringar och tillämpar dem på det resulterande dokumentet. |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | Godkänner eller avvisar förändringar och tillämpar dem på det resulterande dokumentet. |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Godkänner eller avvisar förändringar och tillämpar dem på det resulterande dokumentet. |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Godkänner eller avvisar förändringar och tillämpar dem på det resulterande dokumentet. |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Godkänner eller avvisar förändringar och tillämpar dem på det resulterande dokumentet. |
|
|  | [getResultString()](#getResultString--) | Hämtar resultatssträngen efter jämförelse (Endast för textjämförelse). |
|
|  | [getSourceFolder()](#getSourceFolder--) | Returnerar källmappen som jämförs. |
|
|  | [getTargetFolder()](#getTargetFolder--) | Returnerar målmappen som jämförs. |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | Själjämförelses kontroll (e498c23). |
|
|  | [close()](#close--) | Frigör resurser. |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


Initierar en ny instans av Comparer-klassen med den angivna källfilens sökväg.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till källdokumentet |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


Initierar en ny instans av Comparer-klassen med den angivna mappens sökväg och jämförelsealternativ.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till källdokumentet eller mappen |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Jämförelsealternativen för mappjämförelse |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


Initierar en ny instans av Comparer-klassen med den angivna källfilens sökväg.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till källdokumentet |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


Initierar en ny instans av Comparer med den angivna källfilens sökväg och [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till källdokumentet |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De anpassade inläsningsalternativen som ska tillämpas på dokumentet |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


Initierar en ny instans av Comparer med den angivna källfilens sökväg och [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till källdokumentet |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De anpassade inläsningsalternativen som ska tillämpas på dokumentet |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


Initierar en ny instans av Comparer med den angivna källfilens sökväg och [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till källdokumentet |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Jämförelsealternativen för mappjämförelse |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Initierar en ny instans av Comparer‑klassen med den angivna sökvägen till källfilen, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) och [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till källdokumentet |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De anpassade inläsningsalternativen som ska tillämpas på dokumentet |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Jämförelsens inställningar som ska användas för jämförelseprocessen |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Initierar en ny instans av Comparer‑klassen med den angivna sökvägen till källfilen, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) och [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till källdokumentet eller mappen eller texten som ska jämföras |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De anpassade inläsningsalternativen som ska tillämpas på dokumentet |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Jämförelsens inställningar som ska användas för jämförelseprocessen |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Jämförelsealternativen för mappjämförelse |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


Initierar en ny instans av Comparer‑klassen med den angivna sökvägen till källfilen och [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till källdokumentet |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Jämförelsens inställningar som ska användas för jämförelseprocessen |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


Initierar en ny instans av Comparer‑klassen med den angivna sökvägen till källfilen och [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till källdokumentet |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Jämförelsens inställningar som ska användas för jämförelseprocessen |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Initierar en ny instans av Comparer‑klassen med den angivna sökvägen till källfilen, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) och [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till källdokumentet |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De anpassade inläsningsalternativen som ska tillämpas på dokumentet |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Jämförelsens inställningar som ska användas för jämförelseprocessen |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Initierar en ny instans av Comparer‑klassen med den angivna sökvägen till källfilen, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) och [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till källdokumentet eller mappen |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De anpassade inläsningsalternativen som ska tillämpas på dokumentet |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Jämförelsens inställningar som ska användas för jämförelseprocessen |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Jämförelsealternativen för mappjämförelse |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


Initierar en ny instans av Comparer‑klassen med den angivna källdokumentströmmen.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.InputStream | Inmatningsströmmen för källdokumentet |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


Initierar en ny instans av Comparer med den angivna källdokumentströmmen och [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.InputStream | Inmatningsströmmen för källdokumentet |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De anpassade inläsningsalternativen som ska tillämpas på dokumentet |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


Initierar en ny instans av Comparer‑klassen med den angivna källdokumentströmmen och [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.InputStream | Inmatningsströmmen för källdokumentet |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Jämförelsens inställningar som ska användas för jämförelseprocessen |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


Initierar en ny instans av Comparer‑klassen med den angivna dokumentströmmen, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) och [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.InputStream | Strömmen med data för ett dokument som ska jämföras |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De anpassade inläsningsalternativen som ska tillämpas på dokumentet |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Jämförelsens inställningar som ska användas för jämförelseprocessen |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


Initierar en ny instans av Comparer‑klassen med de angivna [ComparerSettings](../../com.groupdocs.comparison/comparersettings).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | inställningarna |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


Hämtar källdokumentet som jämförs.


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


Lista över måldokument att jämföra med källfilen.


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - mål dokumenten

### compare() {#compare--}
```
public final Path compare()
```


Jämför den angivna filen med måldokumenten utan att spara resultatet med standardalternativ.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - sökvägen till resultatsdokumentet eller null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


Jämför den angivna filen med måldokumenten och genererar ett jämförelseresultat.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Resultatsdokumentets sökväg |
|

**Returns:**
java.nio.file.Path - resultatsfilens sökväg eller null. I vissa situationer kan dess filändelse ändras

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


Jämför den angivna filen med måldokumenten och genererar ett jämförelseresultat.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Resultatsdokumentets sökväg |
|

**Returns:**
java.nio.file.Path - resultatsfilens sökväg, i vissa situationer kan dess filändelse ändras

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till utdataströmmen.


Obs: I fall då returvärdet är null, använd data som skrevs till outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Resultatsdokumentets ström |
|

**Returns:**
java.nio.file.Path - resultatsfilens sökväg eller null när data från  outputStream  måste användas. I vissa situationer kan resultatsfilens filändelse ändras

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Resultatsdokumentets filväg |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Jämförelsealternativen som ska användas för jämförelseprocessen |
|

**Returns:**
java.nio.file.Path - resultatsfilens sökväg, i vissa situationer kan dess filändelse ändras

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Resultatsdokumentets filväg |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Jämförelsealternativen som ska användas för jämförelseprocessen |
|

**Returns:**
java.nio.file.Path - resultatsfilens sökväg, i vissa situationer kan dess filändelse ändras

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till utdataströmmen.


Obs: Om returvärdet är null, använd data som skrevs till outputStream.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ström | java.io.OutputStream | Resultatsdokumentets ström |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Jämförelsealternativen som ska användas för jämförelseprocessen |
|

**Returns:**
java.nio.file.Path - resultatsfilens sökväg eller null när data från  outputStream  måste användas. I vissa situationer kan resultatsfilens filändelse ändras

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


Jämför den angivna filen med måldokumenten utan att spara resultatet.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sparalternativ |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Jämförelsealternativen som ska användas för jämförelseprocessen |
|

**Returns:**
java.nio.file.Path - sökvägen till resultatsdokumentet eller null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Resultatsdokumentets filväg |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sparalternativ |
|

**Returns:**
java.nio.file.Path - resultatsfilens sökväg, i vissa situationer kan dess filändelse ändras

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Resultatsdokumentets filväg |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sparalternativ |
|

**Returns:**
java.nio.file.Path - resultatsfilens sökväg, i vissa situationer kan dess filändelse ändras

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen.


Obs: Om returvärdet är null, använd data som skrevs till outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ström | java.io.OutputStream | Resultatsdokumentets ström |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sparalternativ |
|

**Returns:**
java.nio.file.Path - resultatsfilens sökväg eller null när data från  outputStream  måste användas. I vissa situationer kan resultatsfilens filändelse ändras

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


Jämför den angivna filen med måldokumenten utan att spara resultatet.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Jämförelsealternativen som ska användas för jämförelseprocessen |
|

**Returns:**
java.nio.file.Path - sökvägen till resultatfilen eller null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna utdataströmmen.


Obs: Om returvärdet är null, använd data som skrevs till outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Resultatsdokumentets ström |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sparalternativen som ska användas för att spara resultatsdokumentet |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Jämförelsealternativen som ska användas för jämförelseprocessen |
|

**Returns:**
java.nio.file.Path - resultatsfilens sökväg eller null när data från  outputStream  måste användas. I vissa situationer kan resultatsfilens filändelse ändras

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Resultatsdokumentets filväg |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sparalternativen som ska användas för att spara resultatsdokumentet |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Jämförelsealternativen som ska användas för jämförelseprocessen |
|

**Returns:**
java.nio.file.Path - resultatsfilens sökväg, i vissa situationer kan dess filändelse ändras

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


Jämför den angivna katalogen med målkatalogen och sparar jämförelseresultatet till den angivna filsökvägen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filvägen där jämförelsresultatet kommer att sparas. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Alternativen som ska användas för katalogjämförelseprocessen. |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


Jämför den angivna katalogen med målkatalogen och sparar jämförelseresultatet till den angivna filsökvägen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Filvägen där jämförelsresultatet kommer att sparas. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Alternativen som ska användas för katalogjämförelseprocessen. |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Jämför den angivna filen med måldokumenten och skriver ett jämförelseresultat till den angivna filsökvägen.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Resultatsdokumentets filväg |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sparalternativen som ska användas för att spara resultatsdokumentet |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Jämförelsealternativen som ska användas för jämförelseprocessen |
|

**Returns:**
java.nio.file.Path - resultatsfilens sökväg, i vissa situationer kan dess filändelse ändras

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


Lägger till det angivna måldokumentet i jämförelseprocessen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till mål‑dokumentet som ska läggas till |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


Lägger till det angivna måldokumentet eller mappen i jämförelseprocessen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till mål‑dokumentet eller mappen som ska läggas till |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Alternativen för jämförelsen |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


Lägger till det angivna måldokumentet i jämförelseprocessen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till mål‑dokumentet som ska läggas till |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


Lägger till de angivna måldokumenten i jämförelseprocessen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | Sökvägar till mål‑dokumenten som ska läggas till |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


Lägger till de angivna måldokumenten i jämförelseprocessen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | Sökvägar till mål‑dokumenten som ska läggas till |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


Lägger till det angivna måldokumentet i jämförelseprocessen med angivna laddningsalternativ.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökväg till mål‑dokumentet som ska läggas till |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De anpassade inläsningsalternativen som ska tillämpas på dokumentet |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


Lägger till det angivna måldokumentet i jämförelseprocessen med angivna laddningsalternativ.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökväg till mål‑dokumentet som ska läggas till |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De anpassade inläsningsalternativen som ska tillämpas på dokumentet |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


Lägger till det angivna måldokumentet i jämförelseprocessen med angivna laddningsalternativ.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till mål‑dokumentet eller mappen som ska läggas till |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Alternativen för jämförelsen |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


Lägger till det angivna måldokumentet i jämförelseprocessen.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.InputStream | Strömmen med data för ett dokument som ska jämföras |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


Lägger till de angivna måldokumenten i jämförelseprocessen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | documents | java.io.InputStream[] | Strömmar med data för dokument som ska jämföras |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


Lägger till det angivna måldokumentet i jämförelseprocessen med angivna laddningsalternativ.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.InputStream | Strömmen med data för ett dokument som ska jämföras |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | De anpassade inläsningsalternativen som ska tillämpas på dokumentet |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Hämtar en array av [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objekt som representerar förändringarna som upptäckts under jämförelseprocessen.


Använd den här metoden för att få detaljerad information om förändringarna mellan källdokumentet och mål(dokumentet).
Varje [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objekt innehåller information såsom typ av förändring, det påverkade området,
och innehållet före och efter förändringen.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - en array av [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)‑objekt som representerar förändringarna som upptäcktes under jämförelseprocessen

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


Hämtar en array av [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objekt som representerar förändringarna som upptäckts under jämförelseprocessen.


Använd den här metoden för att få detaljerad information om förändringarna mellan källdokumentet och mål(dokumentet).
Varje [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) objekt innehåller information såsom typ av förändring, det påverkade området,
och innehållet före och efter förändringen.


Parametern [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) möjliggör att filtrera förändringar på olika sätt.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | Objektet som möjliggör att filtrera förändringar |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - en array av [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo)‑objekt som representerar förändringarna som upptäcktes under jämförelseprocessen

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


Godkänner eller avvisar förändringar och tillämpar dem på resultatdokumentet.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Resultatsdokumentets filväg |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | De anpassade tillämpningsalternativen för att konfigurera processen för att tillämpa förändringar |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


Godkänner eller avvisar förändringar och tillämpar dem på det resulterande dokumentet.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Resultatsdokumentets filväg |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | De anpassade tillämpningsalternativen för att konfigurera processen för att tillämpa förändringar |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


Godkänner eller avvisar förändringar och tillämpar dem på det resulterande dokumentet.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.OutputStream | Resultatdokumentets utdata‑ström |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | De anpassade tillämpningsalternativen för att konfigurera processen för att tillämpa förändringar |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Godkänner eller avvisar förändringar och tillämpar dem på det resulterande dokumentet.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Resultatsdokumentets filväg |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sparalternativen för att konfigurera sparandet av resultatsdokumentet |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | De anpassade tillämpningsalternativen för att konfigurera processen för att tillämpa förändringar |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Godkänner eller avvisar förändringar och tillämpar dem på det resulterande dokumentet.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Resultatsdokumentets filväg |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sparalternativen för att konfigurera sparandet av resultatsdokumentet |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | De anpassade tillämpningsalternativen för att konfigurera processen för att tillämpa förändringar |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Godkänner eller avvisar förändringar och tillämpar dem på det resulterande dokumentet.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.OutputStream | Resultatdokumentets utdata‑ström |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Sparalternativen för att konfigurera sparandet av resultatsdokumentet |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | De anpassade tillämpningsalternativen för att konfigurera processen för att tillämpa förändringar |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


Hämtar resultatssträngen efter jämförelse (Endast för textjämförelse).


**Returns:**
java.lang.String - resultatssträngen

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


Returnerar källmappen som jämförs.


**Returns:**
java.lang.String - källmappen

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


Returnerar målmappen som jämförs.


**Returns:**
java.lang.String - mål‑mappen

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


Själjämförelseskontroll (e498c23). C# 7a7668c intern; hålls publik så att core.common-tester kan anropa.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


Frigör resurser.


