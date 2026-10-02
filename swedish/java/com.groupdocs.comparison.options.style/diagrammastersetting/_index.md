---
title: "DiagramMasterSetting"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Representerar inställningarna för diagramhuvudjämförelse."
type: docs
weight: 10
url: /sv/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

Representerar inställningarna för diagramhuvudjämförelse.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | Initierar en ny instans av klassen DiagramMasterSetting. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | Hämtar en flagga som indikerar om källmaster-sökvägen kommer att användas. |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | Hämtar en flagga som indikerar om källmaster-sökvägen bör användas. |
|
|  | [getMasterPath()](#getMasterPath--) | Hämtar en master-sökväg som kommer att användas för att rendera dokument. |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | Ställer in en master-sökväg som ska användas för att rendera dokument. |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


Initierar en ny instans av klassen DiagramMasterSetting.


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


Hämtar en flagga som indikerar om källmaster-sökvägen kommer att användas.


**Returns:**
boolean - true om käll-master-sökvägen kommer att visas, annars false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


Hämtar en flagga som indikerar om källmaster-sökvägen bör användas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | true om käll-master-sökvägen ska visas, annars false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


Hämtar en master-sökväg som kommer att användas för att rendera dokument. MasterPath behövs för att skapa ett resultatsdokument från en uppsättning standardformer.


**Returns:**
java.lang.String - sökväg till master-dokumentet om den är angiven, annars standard-master-sökväg

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


Ställer in en master-sökväg som ska användas för att rendera dokument. MasterPath behövs för att skapa ett resultatsdokument från en uppsättning standardformer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Sökväg till master-dokumentet om den är angiven, annars standard-master-sökväg |
|

