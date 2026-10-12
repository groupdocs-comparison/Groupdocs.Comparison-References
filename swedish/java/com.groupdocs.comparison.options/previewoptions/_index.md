---
title: "PreviewOptions"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Tillhandahåller alternativ för att generera dokumentförhandsgranskningar i jämförelseprocessen."
type: docs
weight: 15
url: /sv/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Tillhandahåller alternativ för att generera dokumentförhandsgranskningar i jämförelseprocessen.


Exempel på användning:

````

 try (Comparer comparer = new Comparer(sourceFile)) {

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);
    previewOptions.setPageNumbers(new int[]{1, 2});

    comparer.getSource().generatePreview(previewOptions);
 }
 
````


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Initierar en ny instans av klassen PreviewOptions som specificerar funktionen Delegates.CreatePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Initierar en ny instans av klassen PreviewOptions som specificerar funktionen [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction). |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Initierar en ny instans av klassen PreviewOptions som specificerar funktionerna Delegates.CreatePageStream och Delegates.ReleasePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Initierar en ny instans av klassen PreviewOptions som specificerar funktionerna [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) och [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | Hämtar en funktion för att skapa förhandsgranskningsström för utskriftsida. |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Ställer in en funktion för att skapa förhandsgranskningsström för utskriftsida. |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Ställer in en funktion för att skapa förhandsgranskningsström för utskriftsida. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Hämtar en funktion för att släppa förhandsgranskningsström för utskriftsida. |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Hämtar en funktion för att släppa förhandsgranskningsström för utskriftsida. |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Ställer in en funktion för att släppa förhandsgranskningsström för utskriftsida. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på förhandsgranskningsbilderna. |
|
|  | [setWidth(int value)](#setWidth-int-) | Ställer in bredden på förhandsgranskningsbilderna. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på förhandsgranskningsbilderna. |
|
|  | [setHeight(int value)](#setHeight-int-) | Ställer in höjden på förhandsgranskningsbilderna. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Hämtar en array av sidnummer för vilka förhandsgranskningsbilder kommer att genereras. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Ställer in en array av sidnummer för vilka förhandsgranskningsbilder kommer att genereras. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Hämtar ett format för förhandsgranskningsbilder. |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | Ställer in ett format för förhandsgranskningsbilder. |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Initierar en ny instans av klassen PreviewOptions som specificerar funktionen Delegates.CreatePageStream.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Funktionen för att skapa utdata sidförhandsgranskningsström. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


Initierar en ny instans av klassen PreviewOptions som specificerar funktionen [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Funktionen för att skapa utdata sidförhandsgranskningsström. |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Initierar en ny instans av klassen PreviewOptions som specificerar funktionerna Delegates.CreatePageStream och Delegates.ReleasePageStream.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Funktionen för att skapa utdata sidförhandsgranskningsström. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Funktionen för att frigöra utdata sidförhandsgranskningsström. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


Initierar en ny instans av klassen PreviewOptions som specificerar funktionerna [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) och [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Funktionen för att skapa utdata sidförhandsgranskningsström. |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Funktionen för att frigöra utdata sidförhandsgranskningsström. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


Hämtar en funktion för att skapa förhandsgranskningsström för utskriftsida.


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


Ställer in en funktion för att skapa förhandsgranskningsström för utskriftsida.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Funktionen för att skapa utdata sidförhandsgranskningsström. |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


Ställer in en funktion för att skapa förhandsgranskningsström för utskriftsida.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Funktionen för att skapa utdata sidförhandsgranskningsström. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


Hämtar en funktion för att släppa förhandsgranskningsström för utskriftsida.


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


Hämtar en funktion för att släppa förhandsgranskningsström för utskriftsida.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Funktionen för att frigöra utdata sidförhandsgranskningsström. |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


Ställer in en funktion för att släppa förhandsgranskningsström för utskriftsida.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Funktionen för att frigöra utdata sidförhandsgranskningsström. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar bredden på förhandsgranskningsbilderna.


**Returns:**
int – bredden på förhandsgranskningsbilderna.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ställer in bredden på förhandsgranskningsbilderna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Bredden på förhandsgranskningsbilderna. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar höjden på förhandsgranskningsbilderna.


**Returns:**
int – höjden på förhandsgranskningsbilderna.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ställer in höjden på förhandsgranskningsbilderna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int | Höjden på förhandsgranskningsbilderna. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Hämtar en array av sidnummer för vilka förhandsgranskningsbilder kommer att genereras.


**Returns:**
int[] – array med sidnummer

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Ställer in en array av sidnummer för vilka förhandsgranskningsbilder kommer att genereras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | int[] | Array med sidnummer |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


Hämtar ett format för förhandsgranskningsbilder.


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


Ställer in ett format för förhandsgranskningsbilder.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | Format för förhandsgranskningsbilder |
|

