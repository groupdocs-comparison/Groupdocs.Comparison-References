---
title: "PreviewOptions"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Biedt opties voor het genereren van documentvoorbeelden in het vergelijkingsproces."
type: docs
weight: 15
url: /nl/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Biedt opties voor het genereren van documentvoorbeelden in het vergelijkingsproces.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Initialiseert een nieuw exemplaar van de PreviewOptions-klasse met vermelding van de Delegates.CreatePageStream-functie. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Initialiseert een nieuw exemplaar van de PreviewOptions-klasse met vermelding van de [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction)-functie. |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Initialiseert een nieuw exemplaar van de PreviewOptions-klasse met vermelding van de Delegates.CreatePageStream- en Delegates.ReleasePageStream-functies. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Initialiseert een nieuw exemplaar van de PreviewOptions-klasse met vermelding van de [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction)- en [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction)-functies. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | Haalt een functie op om een output-pagina-previewstream te maken. |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Stelt een functie in om een output-pagina-previewstream te maken. |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Stelt een functie in om een output-pagina-previewstream te maken. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Haalt een functie op om een output-pagina-previewstream vrij te geven. |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Haalt een functie op om een output-pagina-previewstream vrij te geven. |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Stelt een functie in om een output-pagina-previewstream vrij te geven. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van de voorbeeldafbeeldingen op. |
|
|  | [setWidth(int value)](#setWidth-int-) | Stelt de breedte van de voorbeeldafbeeldingen in. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van de voorbeeldafbeeldingen op. |
|
|  | [setHeight(int value)](#setHeight-int-) | Stelt de hoogte van de voorbeeldafbeeldingen in. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Haalt een array met paginanummers op waarvoor voorbeeldafbeeldingen worden gegenereerd. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Stelt een array met paginanummers in waarvoor voorbeeldafbeeldingen worden gegenereerd. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Haalt een formaat van voorbeeldafbeeldingen op. |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | Stelt een formaat van voorbeeldafbeeldingen in. |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Initialiseert een nieuw exemplaar van de PreviewOptions-klasse met vermelding van de Delegates.CreatePageStream-functie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | De functie om een outputpagina-voorbeeldstroom te maken. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


Initialiseert een nieuw exemplaar van de PreviewOptions-klasse met vermelding van de [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction)-functie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | De functie om een outputpagina-voorbeeldstroom te maken. |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Initialiseert een nieuw exemplaar van de PreviewOptions-klasse met vermelding van de Delegates.CreatePageStream- en Delegates.ReleasePageStream-functies.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | De functie om een outputpagina-voorbeeldstroom te maken. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | De functie om de outputpagina-voorbeeldstroom vrij te geven. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


Initialiseert een nieuw exemplaar van de PreviewOptions-klasse met vermelding van de [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction)- en [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction)-functies.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | De functie om een outputpagina-voorbeeldstroom te maken. |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | De functie om de outputpagina-voorbeeldstroom vrij te geven. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


Haalt een functie op om een output-pagina-previewstream te maken.


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


Stelt een functie in om een output-pagina-previewstream te maken.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | De functie om een outputpagina-voorbeeldstroom te maken. |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


Stelt een functie in om een output-pagina-previewstream te maken.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | De functie om een outputpagina-voorbeeldstroom te maken. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


Haalt een functie op om een output-pagina-previewstream vrij te geven.


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


Haalt een functie op om een output-pagina-previewstream vrij te geven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | De functie om de outputpagina-voorbeeldstroom vrij te geven. |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


Stelt een functie in om een output-pagina-previewstream vrij te geven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | De functie om de outputpagina-voorbeeldstroom vrij te geven. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt de breedte van de voorbeeldafbeeldingen op.


**Returns:**
int - de breedte van de voorbeeldafbeeldingen.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Stelt de breedte van de voorbeeldafbeeldingen in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De breedte van de voorbeeldafbeeldingen. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt de hoogte van de voorbeeldafbeeldingen op.


**Returns:**
int - de hoogte van de voorbeeldafbeeldingen.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stelt de hoogte van de voorbeeldafbeeldingen in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De hoogte van de voorbeeldafbeeldingen. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Haalt een array met paginanummers op waarvoor voorbeeldafbeeldingen worden gegenereerd.


**Returns:**
int[] - array met paginanummers

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Stelt een array met paginanummers in waarvoor voorbeeldafbeeldingen worden gegenereerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int[] | Array met paginanummers |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


Haalt een formaat van voorbeeldafbeeldingen op.


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


Stelt een formaat van voorbeeldafbeeldingen in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | Formaat van voorbeeldafbeeldingen |
|

