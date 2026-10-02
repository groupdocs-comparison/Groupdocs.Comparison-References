---
title: "Licens"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Klassen License tillhandahåller metoder för att ange och tillämpa licenser för GroupDocs.Comparison."
type: docs
weight: 10
url: /sv/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Klassen License tillhandahåller metoder för att ange och tillämpa licenser för GroupDocs.Comparison.


Den gör att du kan aktivera eller inaktivera specifika funktioner i biblioteket baserat på den tillämpade licensen.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Exempel på användning:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [License()](#License--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | Hämtar ett värde som indikerar om licensen har satts eller inte. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Ställer in en licens för Comparison med hjälp av en inmatningsström. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Ställer in en licens för Comparison med hjälp av licensfilens sökväg. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Ställer in en licens för Comparison med hjälp av licensfilens sökväg. |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


Hämtar ett värde som indikerar om licensen har satts eller inte.


**Returns:**
boolean - true om licensen sattes framgångsrikt, annars false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Ställer in en licens för Comparison med hjälp av en inmatningsström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Licensströmmen, null återställer licensen |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Ställer in en licens för Comparison med hjälp av licensfilens sökväg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Licensfilens sökväg |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Ställer in en licens för Comparison med hjälp av licensfilens sökväg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | licensePath | java.lang.String | Licensfilens sökväg |
|

