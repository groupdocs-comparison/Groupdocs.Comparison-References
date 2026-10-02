---
title: "DiagramMasterSetting"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Stellt die Einstellungen für den Diagramm-Master-Vergleich dar."
type: docs
weight: 10
url: /de/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

Stellt die Einstellungen für den Diagramm-Master-Vergleich dar.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | Initialisiert eine neue Instanz der Klasse DiagramMasterSetting. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | Gibt ein Flag zurück, das angibt, ob der Quell-Master-Pfad verwendet wird. |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | Gibt ein Flag zurück, das angibt, ob der Quell-Master-Pfad verwendet werden sollte. |
|
|  | [getMasterPath()](#getMasterPath--) | Liefert einen Master-Pfad, der zum Rendern von Dokumenten verwendet wird. |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | Setzt einen Master-Pfad, der zum Rendern von Dokumenten verwendet werden soll. |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


Initialisiert eine neue Instanz der Klasse DiagramMasterSetting.


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


Gibt ein Flag zurück, das angibt, ob der Quell-Master-Pfad verwendet wird.


**Returns:**
boolean - true, wenn der Quell-Master-Pfad angezeigt wird, andernfalls false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


Gibt ein Flag zurück, das angibt, ob der Quell-Master-Pfad verwendet werden sollte.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn der Quell-Master-Pfad angezeigt werden soll, andernfalls false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


Liefert einen Master-Pfad, der zum Rendern von Dokumenten verwendet wird. MasterPath wird benötigt, um ein Ergebnisdokument aus einer Menge von Standardformen zu erstellen.


**Returns:**
java.lang.String - Pfad des Master-Dokuments, falls festgelegt, andernfalls Standard-Master-Pfad

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


Setzt einen Master-Pfad, der zum Rendern von Dokumenten verwendet werden soll. MasterPath wird benötigt, um ein Ergebnisdokument aus einer Menge von Standardformen zu erstellen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Pfad des Master-Dokuments, falls festgelegt, andernfalls Standard-Master-Pfad |
|

