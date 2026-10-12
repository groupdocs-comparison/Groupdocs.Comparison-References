---
title: "DiagramMasterSetting"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Rappresenta le impostazioni per il confronto del diagramma master."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

Rappresenta le impostazioni per il confronto del diagramma master.


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final DiagramMasterSetting diagramMasterSetting = new DiagramMasterSetting();
    diagramMasterSetting.setMasterPath(masterFilePath);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDiagramMasterSetting(diagramMasterSetting);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | Inizializza una nuova istanza della classe DiagramMasterSetting. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | Ottiene un flag che indica se il percorso master di origine sarà usato. |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | Ottiene un flag che indica se il percorso master di origine dovrebbe essere usato. |
|
|  | [getMasterPath()](#getMasterPath--) | Ottiene un percorso master che verrà utilizzato per renderizzare i documenti. |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | Imposta un percorso master che dovrebbe essere utilizzato per renderizzare i documenti. |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


Inizializza una nuova istanza della classe DiagramMasterSetting.


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


Ottiene un flag che indica se il percorso master di origine sarà usato.


**Returns:**
boolean - true se il percorso master di origine verrà mostrato, altrimenti false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


Ottiene un flag che indica se il percorso master di origine dovrebbe essere usato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true se il percorso master di origine dovrebbe essere mostrato, altrimenti false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


Ottiene un percorso master che verrà utilizzato per renderizzare i documenti. MasterPath è necessario per creare un documento risultato da un insieme di forme predefinite.


**Returns:**
java.lang.String - percorso del documento master se impostato, altrimenti percorso master predefinito

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


Imposta un percorso master che dovrebbe essere utilizzato per renderizzare i documenti. MasterPath è necessario per creare un documento risultato da un insieme di forme predefinite.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Percorso del documento master se impostato, altrimenti percorso master predefinito |
|

