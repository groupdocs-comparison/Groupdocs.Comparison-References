---
title: "Licenza"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "La classe License fornisce metodi per impostare e applicare le licenze per GroupDocs.Comparison."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

La classe License fornisce metodi per impostare e applicare le licenze per GroupDocs.Comparison.


Consente di abilitare o disabilitare funzionalità specifiche della libreria in base alla licenza applicata.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Esempio di utilizzo:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [License()](#License--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | Restituisce un valore che indica se la licenza è stata impostata o meno. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Imposta una licenza per Comparison utilizzando lo stream di input. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Imposta una licenza per Comparison utilizzando il percorso del file di licenza. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Imposta una licenza per Comparison utilizzando il percorso del file di licenza. |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


Restituisce un valore che indica se la licenza è stata impostata o meno.


**Returns:**
boolean - true se la licenza è stata impostata correttamente, altrimenti false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Imposta una licenza per Comparison utilizzando lo stream di input.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Lo stream di licenza, null rimuove la licenza |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Imposta una licenza per Comparison utilizzando il percorso del file di licenza.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Il percorso del file di licenza |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Imposta una licenza per Comparison utilizzando il percorso del file di licenza.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | licensePath | java.lang.String | Il percorso del file di licenza |
|

