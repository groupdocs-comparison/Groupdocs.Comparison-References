---
title: "PreviewFormats"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Elenca i formati di anteprima supportati per il confronto dei documenti."
type: docs
weight: 15
url: /it/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

Elenca i formati di anteprima supportati per il confronto dei documenti.
L'enum PreviewFormats fornisce un elenco di formati che possono essere utilizzati per generare anteprime dei documenti confrontati.

I formati supportati includono:

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);

    comparer.getTargets().get(0).generatePreview(previewOptions);
 }
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [PNG](#PNG) | PNG - può consumare una notevole quantità di spazio su disco o traffico di rete se la pagina contiene numerose grafiche a colori. |
|
|  | [JPEG](#JPEG) | Jpeg - offre un'elaborazione più veloce con un minore utilizzo di spazio su disco e traffico di rete, ma può comportare una qualità dell'immagine inferiore. |
|
|  | [BMP](#BMP) | BMP - offre la migliore qualità dell'immagine ma richiede un'elaborazione più lenta con un maggiore utilizzo di spazio su disco e traffico di rete. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analizza la rappresentazione stringa di PreviewFormats per ottenere la costante enum. |
|
|  | [toString()](#toString--) | Rappresentazione stringa di PreviewFormats. |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - può consumare una notevole quantità di spazio su disco o traffico di rete se la pagina contiene numerose grafiche a colori. Formato di anteprima predefinito.


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - offre un'elaborazione più veloce con un minore utilizzo di spazio su disco e traffico di rete, ma può comportare una qualità dell'immagine inferiore.


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - offre la migliore qualità dell'immagine ma richiede un'elaborazione più lenta con un maggiore utilizzo di spazio su disco e traffico di rete.


### values() {#values--}
```
public static PreviewFormats[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PreviewFormats[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PreviewFormats valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


Analizza la rappresentazione stringa di PreviewFormats per ottenere la costante enum.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La rappresentazione stringa di PreviewFormats |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa di PreviewFormats.


**Returns:**
java.lang.String - valore stringa della costante dell'enumerazione

