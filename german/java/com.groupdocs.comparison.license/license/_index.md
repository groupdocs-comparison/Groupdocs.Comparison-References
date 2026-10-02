---
title: "Lizenz"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Die License Klasse stellt Methoden zum Festlegen und Anwenden von Lizenzen für GroupDocs.Comparison bereit."
type: docs
weight: 10
url: /de/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Die License Klasse stellt Methoden zum Festlegen und Anwenden von Lizenzen für GroupDocs.Comparison bereit.


Es ermöglicht Ihnen, bestimmte Funktionen der Bibliothek basierend auf der angewendeten Lizenz zu aktivieren oder zu deaktivieren.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Beispielverwendung:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [License()](#License--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | Gibt einen Wert zurück, der angibt, ob die Lizenz gesetzt wurde oder nicht. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Setzt eine Lizenz für Comparison mithilfe eines Eingabestreams. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Setzt eine Lizenz für Comparison mithilfe des Lizenzdateipfads. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Setzt eine Lizenz für Comparison mithilfe des Lizenzdateipfads. |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


Gibt einen Wert zurück, der angibt, ob die Lizenz gesetzt wurde oder nicht.


**Returns:**
boolescher Wert – true, wenn die Lizenz erfolgreich gesetzt wurde, sonst false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Setzt eine Lizenz für Comparison mithilfe eines Eingabestreams.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Der Lizenz-Stream, null hebt die Lizenz auf |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Setzt eine Lizenz für Comparison mithilfe des Lizenzdateipfads.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Der Pfad zur Lizenzdatei |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Setzt eine Lizenz für Comparison mithilfe des Lizenzdateipfads.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | licensePath | java.lang.String | Der Pfad zur Lizenzdatei |
|

