---
title: "GetChangeOptions"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Ermöglicht die Konfiguration von Filtern zum Abrufen bestimmter Änderungstypen aus dem Vergleichsergebnis."
type: docs
weight: 13
url: /de/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

Ermöglicht die Konfiguration von Filtern zum Abrufen bestimmter Änderungstypen aus dem Vergleichsergebnis.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | Initialisiert eine neue Instanz der GetChangeOptions-Klasse. |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | Initialisiert eine neue Instanz der GetChangeOptions-Klasse für den angegebenen Filtertyp. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFilter()](#getFilter--) | Ruft den Filter ab, um bestimmte Änderungstypen aus dem Vergleichsergebnis zu erhalten. |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | Setzt den Filter, um bestimmte Änderungstypen aus dem Vergleichsergebnis zu erhalten. |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


Initialisiert eine neue Instanz der GetChangeOptions-Klasse.


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


Initialisiert eine neue Instanz der GetChangeOptions-Klasse für den angegebenen Filtertyp.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


Ruft den Filter ab, um bestimmte Änderungstypen aus dem Vergleichsergebnis zu erhalten.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


Setzt den Filter, um bestimmte Änderungstypen aus dem Vergleichsergebnis zu erhalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | Der Filter, der die abzurufenden Änderungstypen angibt. |
|

