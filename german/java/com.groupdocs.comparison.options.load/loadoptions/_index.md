---
title: "LoadOptions"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Ermöglicht das Angeben zusätzlicher Optionen beim Laden eines Dokuments."
type: docs
weight: 10
url: /de/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Ermöglicht das Angeben zusätzlicher Optionen beim Laden eines Dokuments.


Beispielverwendung:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initialisiert eine neue Instanz der Klasse LoadOptions. |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | Initialisiert eine neue Instanz der Klasse LoadOptions mit einem Flag, das bedeutet, dass die Eingabezeichenfolge ein zu vergleichender Text und kein Pfad ist. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initialisiert eine neue Instanz der Klasse LoadOptions mit einem Passwort zum Laden des Dokuments. |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | Initialisiert eine neue Instanz der Klasse LoadOptions mit einem Flag, das bedeutet, dass die Eingabezeichenfolge ein zu vergleichender Text und ein Passwort zum Laden des Dokuments ist. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | Initialisiert eine neue Instanz der Klasse LoadOptions mit einem Dateityp. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | Gibt ein Flag zurück, das anzeigt, dass die an den [Comparer](../../com.groupdocs.comparison/comparer)-Konstruktor oder die Methode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) übergebene Zeichenfolge ein Vergleichstext und kein Dateipfad ist (nur für Textvergleich). |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | Setzt ein Flag, das anzeigt, dass die an den [Comparer](../../com.groupdocs.comparison/comparer)-Konstruktor oder die Methode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) übergebene Zeichenfolge ein Vergleichstext und kein Dateipfad ist (nur für Textvergleich). |
|
|  | [getPassword()](#getPassword--) | Gibt ein Passwort zurück, das zum Laden eines Dokuments verwendet wird. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Setzt ein Passwort, das zum Laden eines Dokuments verwendet werden soll. |
|
|  | [getFontDirectories()](#getFontDirectories--) | Gibt eine Liste von Verzeichnissen zurück, in denen Schriftdateien zum Laden eines Dokuments abgelegt sind. |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Setzt eine Liste von Verzeichnissen, in denen Schriftdateien zum Laden eines Dokuments abgelegt sind. |
|
|  | [getFileType()](#getFileType--) | Gibt den Typ einer zu ladenden Datei zurück. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Legt einen Typ einer Datei fest, die geladen wird. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialisiert eine neue Instanz der Klasse LoadOptions.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


Initialisiert eine neue Instanz der Klasse LoadOptions mit einem Flag, das bedeutet, dass die Eingabezeichenfolge ein zu vergleichender Text und kein Pfad ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | isLoadText | boolean | Das Flag, das bedeutet, dass die Eingabezeichenfolge ein zu vergleichender Text und kein Pfad ist. |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initialisiert eine neue Instanz der Klasse LoadOptions mit einem Passwort zum Laden des Dokuments.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Passwort | java.lang.String | Das Passwort zum Laden des Dokuments |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


Initialisiert eine neue Instanz der Klasse LoadOptions mit einem Flag, das bedeutet, dass die Eingabezeichenfolge ein zu vergleichender Text und ein Passwort zum Laden des Dokuments ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | isLoadText | boolean | Das Flag, das bedeutet, dass die Eingabezeichenfolge ein zu vergleichender Text und kein Pfad ist. |
|
|  | Passwort | java.lang.String | Das Passwort zum Laden des Dokuments |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


Initialisiert eine neue Instanz der Klasse LoadOptions mit einem Dateityp.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Der Typ der Datei |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


Gibt ein Flag zurück, das anzeigt, dass die an den [Comparer](../../com.groupdocs.comparison/comparer)-Konstruktor oder die Methode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) übergebene Zeichenfolge ein Vergleichstext und kein Dateipfad ist (nur für Textvergleich).


**Returns:**
boolean - true, wenn die Eingabezeichenfolge ein zu vergleichender Text ist, sonst false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


Setzt ein Flag, das anzeigt, dass die an den [Comparer](../../com.groupdocs.comparison/comparer)-Konstruktor oder die Methode [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) übergebene Zeichenfolge ein Vergleichstext und kein Dateipfad ist (nur für Textvergleich).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true, wenn die Eingabezeichenfolge ein zu vergleichender Text ist, sonst false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gibt ein Passwort zurück, das zum Laden eines Dokuments verwendet wird.


**Returns:**
java.lang.String - das Passwort zum Laden des Dokuments

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Setzt ein Passwort, das zum Laden eines Dokuments verwendet werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Das Passwort zum Laden des Dokuments |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


Gibt eine Liste von Verzeichnissen zurück, in denen Schriftdateien zum Laden eines Dokuments abgelegt sind.


**Returns:**
java.util.List<java.lang.String> - die Liste der Verzeichnisse mit Schriftdateien

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


Setzt eine Liste von Verzeichnissen, in denen Schriftdateien zum Laden eines Dokuments abgelegt sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.util.List<java.lang.String> | Die Liste der Verzeichnisse mit Schriftdateien |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Gibt den Typ einer zu ladenden Datei zurück.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


Legt einen Typ einer Datei fest, die geladen wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Der Typ der Datei |
|

