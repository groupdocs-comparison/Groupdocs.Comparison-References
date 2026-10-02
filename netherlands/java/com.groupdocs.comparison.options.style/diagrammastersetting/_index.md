---
title: "DiagramMasterSetting"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Stelt de instellingen voor diagrammastervergelijking voor."
type: docs
weight: 10
url: /nl/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

Stelt de instellingen voor diagrammastervergelijking voor.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | Initialiseert een nieuw exemplaar van de DiagramMasterSetting-klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | Haalt een vlag op die aangeeft of het bronmasterpad zal worden gebruikt. |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | Haalt een vlag op die aangeeft of het bronmasterpad moet worden gebruikt. |
|
|  | [getMasterPath()](#getMasterPath--) | Haalt een masterpad op dat zal worden gebruikt om documenten te renderen. |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | Stelt een masterpad in dat moet worden gebruikt om documenten te renderen. |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


Initialiseert een nieuw exemplaar van de DiagramMasterSetting-klasse.


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


Haalt een vlag op die aangeeft of het bronmasterpad zal worden gebruikt.


**Returns:**
boolean - true als het bronmasterpad wordt weergegeven, anders false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


Haalt een vlag op die aangeeft of het bronmasterpad moet worden gebruikt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true als het bronmasterpad moet worden weergegeven, anders false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


Haalt een masterpad op dat zal worden gebruikt om documenten te renderen. MasterPath is nodig om een resultaatsdocument te maken van een set standaardvormen.


**Returns:**
java.lang.String - pad van masterdocument als het is ingesteld, anders standaard masterpad

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


Stelt een masterpad in dat moet worden gebruikt om documenten te renderen. MasterPath is nodig om een resultaatsdocument te maken van een set standaardvormen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Pad van masterdocument als het is ingesteld, anders standaard masterpad |
|

