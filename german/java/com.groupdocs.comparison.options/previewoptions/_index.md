---
title: "PreviewOptions"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt Optionen zum Erzeugen von Dokumentvorschauen im Vergleichsprozess bereit."
type: docs
weight: 15
url: /de/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Stellt Optionen zum Erzeugen von Dokumentvorschauen im Vergleichsprozess bereit.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Initialisiert eine neue Instanz der PreviewOptions-Klasse und gibt die Delegates.CreatePageStream-Funktion an. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Initialisiert eine neue Instanz der PreviewOptions-Klasse und gibt die [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction)-Funktion an. |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Initialisiert eine neue Instanz der PreviewOptions-Klasse und gibt die Delegates.CreatePageStream- und Delegates.ReleasePageStream-Funktion an. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Initialisiert eine neue Instanz der PreviewOptions-Klasse und gibt die [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction)- und [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction)-Funktion an. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | Ruft eine Funktion zum Erstellen des Ausgabe-Seitenvorschau-Streams ab. |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Setzt eine Funktion zum Erstellen des Ausgabe-Seitenvorschau-Streams. |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Setzt eine Funktion zum Erstellen des Ausgabe-Seitenvorschau-Streams. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Ruft eine Funktion zum Freigeben des Ausgabe-Seitenvorschau-Streams ab. |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Ruft eine Funktion zum Freigeben des Ausgabe-Seitenvorschau-Streams ab. |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Setzt eine Funktion zum Freigeben des Ausgabe-Seitenvorschau-Streams. |
|
|  | [getWidth()](#getWidth--) | Ermittelt die Breite der Vorschaubilder. |
|
|  | [setWidth(int value)](#setWidth-int-) | Legt die Breite der Vorschaubilder fest. |
|
|  | [getHeight()](#getHeight--) | Ermittelt die Höhe der Vorschaubilder. |
|
|  | [setHeight(int value)](#setHeight-int-) | Legt die Höhe der Vorschaubilder fest. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Ermittelt ein Array von Seitenzahlen, für die Vorschaubilder erzeugt werden. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Legt ein Array von Seitenzahlen fest, für die Vorschaubilder erzeugt werden. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Ermittelt das Format der Vorschaubilder. |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | Legt das Format der Vorschaubilder fest. |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Initialisiert eine neue Instanz der PreviewOptions-Klasse und gibt die Delegates.CreatePageStream-Funktion an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Die Funktion zum Erstellen des Ausgabeseiten-Vorschau-Streams. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


Initialisiert eine neue Instanz der PreviewOptions-Klasse und gibt die [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction)-Funktion an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Die Funktion zum Erstellen des Ausgabeseiten-Vorschau-Streams. |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Initialisiert eine neue Instanz der PreviewOptions-Klasse und gibt die Delegates.CreatePageStream- und Delegates.ReleasePageStream-Funktion an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Die Funktion zum Erstellen des Ausgabeseiten-Vorschau-Streams. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Die Funktion zum Freigeben des Ausgabeseiten-Vorschau-Streams. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


Initialisiert eine neue Instanz der PreviewOptions-Klasse und gibt die [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction)- und [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction)-Funktion an.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Die Funktion zum Erstellen des Ausgabeseiten-Vorschau-Streams. |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Die Funktion zum Freigeben des Ausgabeseiten-Vorschau-Streams. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


Ruft eine Funktion zum Erstellen des Ausgabe-Seitenvorschau-Streams ab.


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


Setzt eine Funktion zum Erstellen des Ausgabe-Seitenvorschau-Streams.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | Die Funktion zum Erstellen des Ausgabeseiten-Vorschau-Streams. |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


Setzt eine Funktion zum Erstellen des Ausgabe-Seitenvorschau-Streams.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | Die Funktion zum Erstellen des Ausgabeseiten-Vorschau-Streams. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


Ruft eine Funktion zum Freigeben des Ausgabe-Seitenvorschau-Streams ab.


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


Ruft eine Funktion zum Freigeben des Ausgabe-Seitenvorschau-Streams ab.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | Die Funktion zum Freigeben des Ausgabeseiten-Vorschau-Streams. |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


Setzt eine Funktion zum Freigeben des Ausgabe-Seitenvorschau-Streams.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Die Funktion zum Freigeben des Ausgabeseiten-Vorschau-Streams. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ermittelt die Breite der Vorschaubilder.


**Returns:**
int - die Breite der Vorschaubilder.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Legt die Breite der Vorschaubilder fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Breite der Vorschaubilder. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ermittelt die Höhe der Vorschaubilder.


**Returns:**
int - die Höhe der Vorschaubilder.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Legt die Höhe der Vorschaubilder fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Die Höhe der Vorschaubilder. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Ermittelt ein Array von Seitenzahlen, für die Vorschaubilder erzeugt werden.


**Returns:**
int[] - Seitenzahlen-Array

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Legt ein Array von Seitenzahlen fest, für die Vorschaubilder erzeugt werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int[] | Seitenzahlen-Array |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


Ermittelt das Format der Vorschaubilder.


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


Legt das Format der Vorschaubilder fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | Format der Vorschaubilder |
|

