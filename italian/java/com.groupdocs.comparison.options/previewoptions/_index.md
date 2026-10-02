---
title: "PreviewOptions"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Fornisce opzioni per generare anteprime dei documenti nel processo di confronto."
type: docs
weight: 15
url: /it/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Fornisce opzioni per generare anteprime dei documenti nel processo di confronto.


Esempio di utilizzo:

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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Inizializza una nuova istanza della classe PreviewOptions specificando la funzione Delegates.CreatePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Inizializza una nuova istanza della classe PreviewOptions specificando la funzione [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction). |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Inizializza una nuova istanza della classe PreviewOptions specificando le funzioni Delegates.CreatePageStream e Delegates.ReleasePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Inizializza una nuova istanza della classe PreviewOptions specificando le funzioni [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) e [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | Ottiene una funzione per creare lo stream di anteprima della pagina di output. |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Imposta una funzione per creare lo stream di anteprima della pagina di output. |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | Imposta una funzione per creare lo stream di anteprima della pagina di output. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Ottiene una funzione per rilasciare lo stream di anteprima della pagina di output. |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Ottiene una funzione per rilasciare lo stream di anteprima della pagina di output. |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | Imposta una funzione per rilasciare lo stream di anteprima della pagina di output. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza delle immagini di anteprima. |
|
|  | [setWidth(int value)](#setWidth-int-) | Imposta la larghezza delle immagini di anteprima. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza delle immagini di anteprima. |
|
|  | [setHeight(int value)](#setHeight-int-) | Imposta l'altezza delle immagini di anteprima. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Ottiene un array di numeri di pagina per i quali verranno generate le immagini di anteprima. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Imposta un array di numeri di pagina per i quali verranno generate le immagini di anteprima. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Ottiene il formato delle immagini di anteprima. |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | Imposta il formato delle immagini di anteprima. |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Inizializza una nuova istanza della classe PreviewOptions specificando la funzione Delegates.CreatePageStream.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | La funzione per creare lo stream di anteprima della pagina di output. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


Inizializza una nuova istanza della classe PreviewOptions specificando la funzione [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | La funzione per creare lo stream di anteprima della pagina di output. |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Inizializza una nuova istanza della classe PreviewOptions specificando le funzioni Delegates.CreatePageStream e Delegates.ReleasePageStream.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | La funzione per creare lo stream di anteprima della pagina di output. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | La funzione per rilasciare lo stream di anteprima della pagina di output. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


Inizializza una nuova istanza della classe PreviewOptions specificando le funzioni [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) e [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | La funzione per creare lo stream di anteprima della pagina di output. |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | La funzione per rilasciare lo stream di anteprima della pagina di output. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


Ottiene una funzione per creare lo stream di anteprima della pagina di output.


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


Imposta una funzione per creare lo stream di anteprima della pagina di output.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | La funzione per creare lo stream di anteprima della pagina di output. |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


Imposta una funzione per creare lo stream di anteprima della pagina di output.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | La funzione per creare lo stream di anteprima della pagina di output. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


Ottiene una funzione per rilasciare lo stream di anteprima della pagina di output.


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


Ottiene una funzione per rilasciare lo stream di anteprima della pagina di output.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | La funzione per rilasciare lo stream di anteprima della pagina di output. |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


Imposta una funzione per rilasciare lo stream di anteprima della pagina di output.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | La funzione per rilasciare lo stream di anteprima della pagina di output. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ottiene la larghezza delle immagini di anteprima.


**Returns:**
int - la larghezza delle immagini di anteprima.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Imposta la larghezza delle immagini di anteprima.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | La larghezza delle immagini di anteprima. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ottiene l'altezza delle immagini di anteprima.


**Returns:**
int - l'altezza delle immagini di anteprima.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Imposta l'altezza delle immagini di anteprima.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'altezza delle immagini di anteprima. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Ottiene un array di numeri di pagina per i quali verranno generate le immagini di anteprima.


**Returns:**
int[] - array di numeri di pagina

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Imposta un array di numeri di pagina per i quali verranno generate le immagini di anteprima.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int[] | Array di numeri di pagina |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


Ottiene il formato delle immagini di anteprima.


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


Imposta il formato delle immagini di anteprima.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | Formato delle immagini di anteprima |
|

