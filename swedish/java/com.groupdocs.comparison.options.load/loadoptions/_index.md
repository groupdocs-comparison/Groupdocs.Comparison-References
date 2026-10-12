---
title: "LoadOptions"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Tillåter att ange ytterligare alternativ när ett dokument läses in."
type: docs
weight: 10
url: /sv/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Tillåter att ange ytterligare alternativ när ett dokument läses in.


Exempel på användning:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initierar en ny instans av klassen LoadOptions. |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | Initierar en ny instans av klassen LoadOptions med en flagga som betyder att inmatningssträngen är en text att jämföra, inte en sökväg. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initierar en ny instans av klassen LoadOptions med ett lösenord för att läsa in dokumentet. |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | Initierar en ny instans av klassen LoadOptions med en flagga som betyder att inmatningssträngen är en text att jämföra och ett lösenord för att läsa in dokumentet. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | Initierar en ny instans av klassen LoadOptions med en filtyp. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | Hämtar en flagga som indikerar att strängen som skickas till [Comparer](../../com.groupdocs.comparison/comparer) konstruktor eller till [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) metod är jämförelsetext, inte filsökvägar (Endast för textjämförelse). |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | Ställer in en flagga som indikerar att strängen som skickas till [Comparer](../../com.groupdocs.comparison/comparer) konstruktor eller till [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) metod är jämförelsetext, inte filsökvägar (Endast för textjämförelse). |
|
|  | [getPassword()](#getPassword--) | Hämtar ett lösenord som kommer att användas för att läsa in ett dokument. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ställer in ett lösenord som ska användas för att läsa in ett dokument. |
|
|  | [getFontDirectories()](#getFontDirectories--) | Hämtar en lista över kataloger där teckensnitts-filer för att läsa in ett dokument är placerade. |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Ställer in en lista över kataloger där teckensnitts-filer för att läsa in ett dokument är placerade. |
|
|  | [getFileType()](#getFileType--) | Hämtar en filtyp som laddas. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Anger en typ av en fil som laddas. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initierar en ny instans av klassen LoadOptions.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


Initierar en ny instans av klassen LoadOptions med en flagga som betyder att inmatningssträngen är en text att jämföra, inte en sökväg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | isLoadText | boolean | Flaggan som betyder att inmatningssträngen är en text att jämföra, inte en sökväg |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initierar en ny instans av klassen LoadOptions med ett lösenord för att läsa in dokumentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | lösenord | java.lang.String | Lösenordet för att ladda dokumentet |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


Initierar en ny instans av klassen LoadOptions med en flagga som betyder att inmatningssträngen är en text att jämföra och ett lösenord för att läsa in dokumentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | isLoadText | boolean | Flaggan som betyder att inmatningssträngen är en text att jämföra, inte en sökväg |
|
|  | lösenord | java.lang.String | Lösenordet för att ladda dokumentet |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


Initierar en ny instans av klassen LoadOptions med en filtyp.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Typen av filen |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


Hämtar en flagga som indikerar att strängen som skickas till [Comparer](../../com.groupdocs.comparison/comparer) konstruktor eller till [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) metod är jämförelsetext, inte filsökvägar (Endast för textjämförelse).


**Returns:**
boolean - sant om inmatningssträngen är en text att jämföra, annars falskt

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


Ställer in en flagga som indikerar att strängen som skickas till [Comparer](../../com.groupdocs.comparison/comparer) konstruktor eller till [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) metod är jämförelsetext, inte filsökvägar (Endast för textjämförelse).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | boolean | Sant om inmatningssträngen är en text att jämföra, annars falskt |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Hämtar ett lösenord som kommer att användas för att läsa in ett dokument.


**Returns:**
java.lang.String - lösenordet för att ladda dokumentet

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ställer in ett lösenord som ska användas för att läsa in ett dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Lösenordet för att ladda dokumentet |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


Hämtar en lista över kataloger där teckensnitts-filer för att läsa in ett dokument är placerade.


**Returns:**
java.util.List<java.lang.String> - listan över kataloger med teckensnitts-filer

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


Ställer in en lista över kataloger där teckensnitts-filer för att läsa in ett dokument är placerade.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.util.List<java.lang.String> | Listan över kataloger med teckensnitts-filer |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Hämtar en filtyp som laddas.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


Anger en typ av en fil som laddas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Typen av filen |
|

