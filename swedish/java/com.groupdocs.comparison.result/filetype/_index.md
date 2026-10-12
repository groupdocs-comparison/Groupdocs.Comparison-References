---
title: "FileType"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Enumen FileType representerar typen av en fil som används i dokumentjämförelseprocessen."
type: docs
weight: 16
url: /sv/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

Enumen FileType representerar typen av en fil som används i dokumentjämförelseprocessen.


Den definierar olika filtyper såsom Word-dokument, PDF-filer och mer.
Tillhandahåller metoder för att hämta en lista över alla filtyper som stöds av GroupDocs.Comparison, upptäcka filtyp via filändelse osv.
Använd den här enum för att ange filtypen när du arbetar med GroupDocs.Comparison-biblioteket.

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


Exempel på användning:

````

  // Set the file type to Word document
  final FileType fileType = FileType.DOCX;
  // Perform comparison using the specified file type
  final LoadOptions loadOptions = new LoadOptions(fileType);
  try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
      comparer.add(targetFile);

      comparer.compare(resultFile, compareOptions);
 }
 
````


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Okänd typ |
|
|  | [AS](#AS) | ActionScript-programspråksformat |
|
|  | [AS3](#AS3) | ActionScript-programspråksformat |
|
|  | [ASM](#ASM) | Assembler-programspråksformat |
|
|  | [BAT](#BAT) | Skriptfil i DOS, OS/2 och Microsoft Windows |
|
|  | [CMD](#CMD) | Skriptfil i DOS, OS/2 och Microsoft Windows |
|
|  | [C](#C) | C-baserat programspråksformat |
|
|  | [H](#H) | C-baserade headerfiler innehåller definitioner av funktioner och variabler |
|
|  | [PDF](#PDF) | Adobe Portable Document-format |
|
|  | [DOC](#DOC) | Microsoft Word 97-2003-dokument |
|
|  | [DOCM](#DOCM) | Microsoft Word makroaktiverat dokument |
|
|  | [DOCX](#DOCX) | Microsoft Word-dokument |
|
|  | [DOT](#DOT) | Microsoft Word 97-2003-mall |
|
|  | [DOTM](#DOTM) | Microsoft Word makroaktiverad mall |
|
|  | [DOTX](#DOTX) | Microsoft Word-mall |
|
|  | [XLS](#XLS) | Microsoft Excel 97-2003-kalkylblad |
|
|  | [XLT](#XLT) | Microsoft Excel-mall |
|
|  | [XLSX](#XLSX) | Microsoft Excel-kalkylblad |
|
|  | [XLTM](#XLTM) | Microsoft Excel makroaktiverad mall |
|
|  | [XLSB](#XLSB) | Microsoft Excel binärt arbetsblad |
|
|  | [XLSM](#XLSM) | Microsoft Excel makroaktiverat arbetsblad |
|
|  | [POT](#POT) | Microsoft PowerPoint-mall |
|
|  | [POTX](#POTX) | Microsoft PowerPoint-mall |
|
|  | [POTM](#POTM) | Microsoft PowerPoint-mall med stöd för makron |
|
|  | [PPS](#PPS) | Microsoft PowerPoint 97-2003 bildspel |
|
|  | [PPSX](#PPSX) | Microsoft PowerPoint bildspel |
|
|  | [PPTX](#PPTX) | Microsoft PowerPoint-presentation |
|
|  | [PPT](#PPT) | Microsoft PowerPoint 97-2003-presentation |
|
|  | [PPTM](#PPTM) | Microsoft PowerPoint makroaktiverad presentation |
|
|  | [PPSM](#PPSM) | Microsoft PowerPoint makroaktiverad bildspelspresentation |
|
|  | [VSDX](#VSDX) | Microsoft Visio-ritning |
|
|  | [VSD](#VSD) | Microsoft Visio 2003-2010-ritning |
|
|  | [VSS](#VSS) | Microsoft Visio 2003-2010-stencil |
|
|  | [VST](#VST) | Microsoft Visio 2003-2010-mall |
|
|  | [VDX](#VDX) | Microsoft Visio 2003-2010 XML-ritning |
|
|  | [ONE](#ONE) | Microsoft OneNote-dokument |
|
|  | [ODT](#ODT) | OpenDocument-text |
|
|  | [ODP](#ODP) | OpenDocument-presentation |
|
|  | [OTP](#OTP) | OpenDocument-presentationmall |
|
|  | [ODS](#ODS) | OpenDocument-kalkylblad |
|
|  | [OTT](#OTT) | OpenDocument-textmall |
|
|  | [RTF](#RTF) | Rich Text-dokument |
|
|  | [TXT](#TXT) | Vanligt textdokument |
|
|  | [CSV](#CSV) | Kommaavgränsad värdefil |
|
|  | [HTML](#HTML) | HyperText-märkspråk |
|
|  | [MHTML](#MHTML) | Mime HTML |
|
|  | [MOBI](#MOBI) | Mobipocket e-bokformat |
|
|  | [DCM](#DCM) | Digital avbildning och kommunikation inom medicin |
|
|  | [DJVU](#DJVU) | Deja Vu-format |
|
|  | [DWG](#DWG) | Autodesk Design Data-format |
|
|  | [DXF](#DXF) | AutoCAD ritningsutbyte |
|
|  | [BMP](#BMP) | Bitmap-bild |
|
|  | [GIF](#GIF) | Grafiskt utbytesformat |
|
|  | [JPEG](#JPEG) | Joint Photographic Experts Group |
|
|  | [JPG](#JPG) | Joint Photographic Experts Group |
|
|  | [PNG](#PNG) | Bärbara nätverksgrafik |
|
|  | [SVG](#SVG) | Skalär vektorgrafik |
|
|  | [EML](#EML) | E-postmeddelande |
|
|  | [EMLX](#EMLX) | Apple Mail e-postfil |
|
|  | [MSG](#MSG) | Microsoft Outlook e-postmeddelande |
|
|  | [CAD](#CAD) | CAD-filformat |
|
|  | [CPP](#CPP) | C-baserat programspråksformat |
|
|  | [CC](#CC) | C-baserat programspråksformat |
|
|  | [CXX](#CXX) | C-baserat programspråksformat |
|
|  | [HXX](#HXX) | Header-filer som är skrivna i C++-programspråket |
|
|  | [HH](#HH) | Header-information som refereras av en C++-källkodfil |
|
|  | [HPP](#HPP) | Header-filer som är skrivna i C++-programspråket |
|
|  | [CMAKE](#CMAKE) | Verktyg för att hantera byggprocessen för programvara |
|
|  | [CS](#CS) | CSharp-programspråksformat |
|
|  | [CSX](#CSX) | CSharp-skriptfilformat |
|
|  | [CAKE](#CAKE) | CSharp cross-plattform byggautomatiseringssystemformat |
|
|  | [DIFF](#DIFF) | Datajämförelseverktygsformat |
|
|  | [PATCH](#PATCH) | Lista över skillnader-format |
|
|  | [REJ](#REJ) | Avvisade filer-format |
|
|  | [GROOVY](#GROOVY) | Källkodfil skriven i Groovy-format |
|
|  | [GVY](#GVY) | Källkodfil skriven i Groovy-format |
|
|  | [GRADLE](#GRADLE) | Format för byggautomatiseringssystem |
|
|  | [HAML](#HAML) | Märkningsspråk för förenklad HTML-generering |
|
|  | [JS](#JS) | JavaScript-programmeringsspråkformat |
|
|  | [ES6](#ES6) | JavaScript-standardiserat skriptspråkformat |
|
|  | [MJS](#MJS) | Filändelse för EcmaScript (ES)-modulfiler |
|
|  | [PAC](#PAC) | Proxy Auto-Configuration-fil för JavaScript-funktionsformat |
|
|  | [JSON](#JSON) | Lättviktigt format för lagring och transport av data |
|
|  | [BOWERRC](#BOWERRC) | Konfigurationsfil för paketkontroll på serversidan |
|
|  | [JSHINTRC](#JSHINTRC) | JavaScript-verktyg för kodkvalitet |
|
|  | [JSCSRC](#JSCSRC) | JavaScript-konfigurationsfilformat |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | Manifestfilen innehåller information om appen |
|
|  | [JSMAP](#JSMAP) | JSON-fil som innehåller information om hur man översätter kod tillbaka till källkod |
|
|  | [HAR](#HAR) | HTTP Archive-formatet |
|
|  | [JAVA](#JAVA) | Java-programmeringsspråkformat |
|
|  | [LESS](#LESS) | Dynamiskt preprocessor-stilmallspråkformat |
|
|  | [LOG](#LOG) | Loggning håller ett register över händelser, processer, meddelanden och kommunikation |
|
|  | [MAKE](#MAKE) | Makefile är en fil som innehåller en uppsättning direktiv som används av ett make-byggautomatiseringsverktyg för att generera ett mål |
|
|  | [MK](#MK) | Makefile är en fil som innehåller en uppsättning direktiv som används av ett make-byggautomatiseringsverktyg för att generera ett mål |
|
|  | [MD](#MD) | Markdown-språkformat |
|
|  | [MKD](#MKD) | Markdown-språkformat |
|
|  | [MDWN](#MDWN) | Markdown-språkformat |
|
|  | [MDOWN](#MDOWN) | Markdown-språkformat |
|
|  | [MARKDOWN](#MARKDOWN) | Markdown-språkformat |
|
|  | [MARKDN](#MARKDN) | Markdown-språkformat |
|
|  | [MDTXT](#MDTXT) | Markdown-språkformat |
|
|  | [MDTEXT](#MDTEXT) | Markdown-språkformat |
|
|  | [ML](#ML) | Caml-programmeringsspråkformat |
|
|  | [MLI](#MLI) | Caml-programmeringsspråkformat |
|
|  | [OBJC](#OBJC) | Objective-C-programmeringsspråkformat |
|
|  | [OBJCP](#OBJCP) | Objective-C++-programmeringsspråkformat |
|
|  | [PHP](#PHP) | PHP-programmeringsspråkformat |
|
|  | [PHP4](#PHP4) | PHP-programmeringsspråkformat |
|
|  | [PHP5](#PHP5) | PHP-programmeringsspråkformat |
|
|  | [PHTML](#PHTML) | Standard filändelse för PHP 2-programformat |
|
|  | [CTP](#CTP) | CakePHP-mallformat |
|
|  | [PL](#PL) | Perl programspråksformat |
|
|  | [PM](#PM) | Perl-modulformat |
|
|  | [POD](#POD) | Perl lättviktigt märkspråkformat |
|
|  | [T](#T) | Perl testfilformat |
|
|  | [PSGI](#PSGI) | Gränssnitt mellan webbservrar och webbapplikationer samt ramverk skrivna i Perl-programmering |
|
|  | [P6](#P6) | Perl programspråksformat |
|
|  | [PL6](#PL6) | Perl programspråksformat |
|
|  | [PM6](#PM6) | Perl-modulformat |
|
|  | [NQP](#NQP) | Mellanspråk som används för att bygga Rakudo Perl 6-kompilatorn |
|
|  | [PROP](#PROP) | Egenskapsfilformat |
|
|  | [CFG](#CFG) | Konfigurationsfil som används för att lagra inställningar |
|
|  | [CONF](#CONF) | Konfigurationsfil som används på Unix- och Linux-baserade system |
|
|  | [DIR](#DIR) | Katalog är en plats för att lagra filer på datorn |
|
|  | [PY](#PY) | Python programspråksformat |
|
|  | [RPY](#RPY) | Python-baserad filmotor för att skapa och köra spel |
|
|  | [PYW](#PYW) | Filer som används i Windows för att ange att ett skript ska köras |
|
|  | [CPY](#CPY) | Controller Python-skriptformat |
|
|  | [GYP](#GYP) | Byggautomatiseringsverktygsformat |
|
|  | [GYPI](#GYPI) | Byggautomatiseringsverktygsformat |
|
|  | [PYI](#PYI) | Python-gränssnittsfilformat |
|
|  | [IPY](#IPY) | IPython-skriptformat |
|
|  | [RST](#RST) | Lättviktigt märkspråk |
|
|  | [RB](#RB) | Ruby programspråksformat |
|
|  | [ERB](#ERB) | Ruby programspråksformat |
|
|  | [RJS](#RJS) | Ruby programspråksformat |
|
|  | [GEMSPEC](#GEMSPEC) | Utvecklarfil som specificerar attributen för en RubyGems |
|
|  | [RAKE](#RAKE) | Ruby byggautomatiseringsverktyg |
|
|  | [RU](#RU) | Rack-konfigurationsfilformat |
|
|  | [PODSPEC](#PODSPEC) | Ruby bygginställningsformat |
|
|  | [RBI](#RBI) | Ruby-gränssnittsfilformat |
|
|  | [SASS](#SASS) | Stilmallspråkformat |
|
|  | [SCSS](#SCSS) | Stilmallspråkformat |
|
|  | [SCALA](#SCALA) | Scala-programspråksformat |
|
|  | [SBT](#SBT) | SBT-byggverktyg för Scala-format |
|
|  | [SC](#SC) | Scala-arbetsbladformat |
|
|  | [SH](#SH) | Script programmerat för bash-format |
|
|  | [BASH](#BASH) | Typ av tolk som bearbetar shell-kommandon |
|
|  | [BASHRC](#BASHRC) | Fil bestämmer beteendet för interaktiva skal |
|
|  | [EBUILD](#EBUILD) | Specialiserat bash-script som automatiserar kompilerings- och installationsprocedurer för programvarupaket |
|
|  | [SQL](#SQL) | Structured Query Language-format |
|
|  | [DSQL](#DSQL) | Dynamic Structured Query Language-format |
|
|  | [VIM](#VIM) | Vim källkodfilformat |
|
|  | [YAML](#YAML) | Mänskligt läsbar data-serialiseringsspråksformat |
|
|  | [YML](#YML) | Mänskligt läsbar data-serialiseringsspråksformat |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | Returnera FileType baserat på filnamn eller filändelse |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Hämtar lista över stödjade filtyper |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Kontrollerar likheten för angivna filtyper |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Kontrollerar att de angivna filtyperna inte är lika |
|
|  | [getFileFormat()](#getFileFormat--) | Hämtar textbeskrivning av filtypen |
|
|  | [getExtension()](#getExtension--) | Hämtar filtypens filändelse |
|
|  | [toString()](#toString--) | Hämtar strängrepresentation av [FileType](../../com.groupdocs.comparison.result/filetype), till exempel |
'PHP Programming Language-format (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Okänd typ


### AS {#AS}
```
public static final FileType AS
```


ActionScript-programspråksformat


### AS3 {#AS3}
```
public static final FileType AS3
```


ActionScript-programspråksformat


### ASM {#ASM}
```
public static final FileType ASM
```


Assembler-programspråksformat


### BAT {#BAT}
```
public static final FileType BAT
```


Skriptfil i DOS, OS/2 och Microsoft Windows


### CMD {#CMD}
```
public static final FileType CMD
```


Skriptfil i DOS, OS/2 och Microsoft Windows


### C {#C}
```
public static final FileType C
```


C-baserat programspråksformat


### H {#H}
```
public static final FileType H
```


C-baserade headerfiler innehåller definitioner av funktioner och variabler


### PDF {#PDF}
```
public static final FileType PDF
```


Adobe Portable Document-format


### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word 97-2003-dokument


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Microsoft Word makroaktiverat dokument


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word-dokument


### DOT {#DOT}
```
public static final FileType DOT
```


Microsoft Word 97-2003-mall


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Microsoft Word makroaktiverad mall


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Microsoft Word-mall


### XLS {#XLS}
```
public static final FileType XLS
```


Microsoft Excel 97-2003-kalkylblad


### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel-mall


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel-kalkylblad


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel makroaktiverad mall


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Microsoft Excel binärt arbetsblad


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Microsoft Excel makroaktiverat arbetsblad


### POT {#POT}
```
public static final FileType POT
```


Microsoft PowerPoint-mall


### POTX {#POTX}
```
public static final FileType POTX
```


Microsoft PowerPoint-mall


### POTM {#POTM}
```
public static final FileType POTM
```


Microsoft PowerPoint-mall med stöd för makron


### PPS {#PPS}
```
public static final FileType PPS
```


Microsoft PowerPoint 97-2003 bildspel


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Microsoft PowerPoint bildspel


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Microsoft PowerPoint-presentation


### PPT {#PPT}
```
public static final FileType PPT
```


Microsoft PowerPoint 97-2003-presentation


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Microsoft PowerPoint makroaktiverad presentation


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Microsoft PowerPoint makroaktiverad bildspelspresentation


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Visio-ritning


### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio 2003-2010-ritning


### VSS {#VSS}
```
public static final FileType VSS
```


Microsoft Visio 2003-2010-stencil


### VST {#VST}
```
public static final FileType VST
```


Microsoft Visio 2003-2010-mall


### VDX {#VDX}
```
public static final FileType VDX
```


Microsoft Visio 2003-2010 XML-ritning


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote-dokument


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument-text


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument-presentation


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument-presentationmall


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument-kalkylblad


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument-textmall


### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text-dokument


### TXT {#TXT}
```
public static final FileType TXT
```


Vanligt textdokument


### CSV {#CSV}
```
public static final FileType CSV
```


Kommaavgränsad värdefil


### HTML {#HTML}
```
public static final FileType HTML
```


HyperText-märkspråk


### MHTML {#MHTML}
```
public static final FileType MHTML
```


Mime HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket e-bokformat


### DCM {#DCM}
```
public static final FileType DCM
```


Digital avbildning och kommunikation inom medicin


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Deja Vu-format


### DWG {#DWG}
```
public static final FileType DWG
```


Autodesk Design Data-format


### DXF {#DXF}
```
public static final FileType DXF
```


AutoCAD ritningsutbyte


### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap-bild


### GIF {#GIF}
```
public static final FileType GIF
```


Grafiskt utbytesformat


### JPEG {#JPEG}
```
public static final FileType JPEG
```


Joint Photographic Experts Group


### JPG {#JPG}
```
public static final FileType JPG
```


Joint Photographic Experts Group


### PNG {#PNG}
```
public static final FileType PNG
```


Bärbara nätverksgrafik


### SVG {#SVG}
```
public static final FileType SVG
```


Skalär vektorgrafik


### EML {#EML}
```
public static final FileType EML
```


E-postmeddelande


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail e-postfil


### MSG {#MSG}
```
public static final FileType MSG
```


Microsoft Outlook e-postmeddelande


### CAD {#CAD}
```
public static final FileType CAD
```


CAD-filformat


### CPP {#CPP}
```
public static final FileType CPP
```


C-baserat programspråksformat


### CC {#CC}
```
public static final FileType CC
```


C-baserat programspråksformat


### CXX {#CXX}
```
public static final FileType CXX
```


C-baserat programspråksformat


### HXX {#HXX}
```
public static final FileType HXX
```


Header-filer som är skrivna i C++-programspråket


### HH {#HH}
```
public static final FileType HH
```


Header-information som refereras av en C++-källkodfil


### HPP {#HPP}
```
public static final FileType HPP
```


Header-filer som är skrivna i C++-programspråket


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Verktyg för att hantera byggprocessen för programvara


### CS {#CS}
```
public static final FileType CS
```


CSharp-programspråksformat


### CSX {#CSX}
```
public static final FileType CSX
```


CSharp-skriptfilformat


### CAKE {#CAKE}
```
public static final FileType CAKE
```


CSharp cross-plattform byggautomatiseringssystemformat


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Datajämförelseverktygsformat


### PATCH {#PATCH}
```
public static final FileType PATCH
```


Lista över skillnader-format


### REJ {#REJ}
```
public static final FileType REJ
```


Avvisade filer-format


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Källkodfil skriven i Groovy-format


### GVY {#GVY}
```
public static final FileType GVY
```


Källkodfil skriven i Groovy-format


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


Format för byggautomatiseringssystem


### HAML {#HAML}
```
public static final FileType HAML
```


Märkningsspråk för förenklad HTML-generering


### JS {#JS}
```
public static final FileType JS
```


JavaScript-programmeringsspråkformat


### ES6 {#ES6}
```
public static final FileType ES6
```


JavaScript-standardiserat skriptspråkformat


### MJS {#MJS}
```
public static final FileType MJS
```


Filändelse för EcmaScript (ES)-modulfiler


### PAC {#PAC}
```
public static final FileType PAC
```


Proxy Auto-Configuration-fil för JavaScript-funktionsformat


### JSON {#JSON}
```
public static final FileType JSON
```


Lättviktigt format för lagring och transport av data


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


Konfigurationsfil för paketkontroll på serversidan


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


JavaScript-verktyg för kodkvalitet


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


JavaScript-konfigurationsfilformat


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


Manifestfilen innehåller information om appen


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


JSON-fil som innehåller information om hur man översätter kod tillbaka till källkod


### HAR {#HAR}
```
public static final FileType HAR
```


HTTP Archive-formatet


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java-programmeringsspråkformat


### LESS {#LESS}
```
public static final FileType LESS
```


Dynamiskt preprocessor-stilmallspråkformat


### LOG {#LOG}
```
public static final FileType LOG
```


Loggning håller ett register över händelser, processer, meddelanden och kommunikation


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile är en fil som innehåller en uppsättning direktiv som används av ett make-byggautomatiseringsverktyg för att generera ett mål


### MK {#MK}
```
public static final FileType MK
```


Makefile är en fil som innehåller en uppsättning direktiv som används av ett make-byggautomatiseringsverktyg för att generera ett mål


### MD {#MD}
```
public static final FileType MD
```


Markdown-språkformat


### MKD {#MKD}
```
public static final FileType MKD
```


Markdown-språkformat


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Markdown-språkformat


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Markdown-språkformat


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Markdown-språkformat


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Markdown-språkformat


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Markdown-språkformat


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Markdown-språkformat


### ML {#ML}
```
public static final FileType ML
```


Caml-programmeringsspråkformat


### MLI {#MLI}
```
public static final FileType MLI
```


Caml-programmeringsspråkformat


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Objective-C-programmeringsspråkformat


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Objective-C++-programmeringsspråkformat


### PHP {#PHP}
```
public static final FileType PHP
```


PHP-programmeringsspråkformat


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


PHP-programmeringsspråkformat


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


PHP-programmeringsspråkformat


### PHTML {#PHTML}
```
public static final FileType PHTML
```


Standard filändelse för PHP 2-programformat


### CTP {#CTP}
```
public static final FileType CTP
```


CakePHP-mallformat


### PL {#PL}
```
public static final FileType PL
```


Perl programspråksformat


### PM {#PM}
```
public static final FileType PM
```


Perl-modulformat


### POD {#POD}
```
public static final FileType POD
```


Perl lättviktigt märkspråkformat


### T {#T}
```
public static final FileType T
```


Perl testfilformat


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Gränssnitt mellan webbservrar och webbapplikationer samt ramverk skrivna i Perl-programmering


### P6 {#P6}
```
public static final FileType P6
```


Perl programspråksformat


### PL6 {#PL6}
```
public static final FileType PL6
```


Perl programspråksformat


### PM6 {#PM6}
```
public static final FileType PM6
```


Perl-modulformat


### NQP {#NQP}
```
public static final FileType NQP
```


Mellanspråk som används för att bygga Rakudo Perl 6-kompilatorn


### PROP {#PROP}
```
public static final FileType PROP
```


Egenskapsfilformat


### CFG {#CFG}
```
public static final FileType CFG
```


Konfigurationsfil som används för att lagra inställningar


### CONF {#CONF}
```
public static final FileType CONF
```


Konfigurationsfil som används på Unix- och Linux-baserade system


### DIR {#DIR}
```
public static final FileType DIR
```


Katalog är en plats för att lagra filer på datorn


### PY {#PY}
```
public static final FileType PY
```


Python programspråksformat


### RPY {#RPY}
```
public static final FileType RPY
```


Python-baserad filmotor för att skapa och köra spel


### PYW {#PYW}
```
public static final FileType PYW
```


Filer som används i Windows för att ange att ett skript ska köras


### CPY {#CPY}
```
public static final FileType CPY
```


Controller Python-skriptformat


### GYP {#GYP}
```
public static final FileType GYP
```


Byggautomatiseringsverktygsformat


### GYPI {#GYPI}
```
public static final FileType GYPI
```


Byggautomatiseringsverktygsformat


### PYI {#PYI}
```
public static final FileType PYI
```


Python-gränssnittsfilformat


### IPY {#IPY}
```
public static final FileType IPY
```


IPython-skriptformat


### RST {#RST}
```
public static final FileType RST
```


Lättviktigt märkspråk


### RB {#RB}
```
public static final FileType RB
```


Ruby programspråksformat


### ERB {#ERB}
```
public static final FileType ERB
```


Ruby programspråksformat


### RJS {#RJS}
```
public static final FileType RJS
```


Ruby programspråksformat


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


Utvecklarfil som specificerar attributen för en RubyGems


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Ruby byggautomatiseringsverktyg


### RU {#RU}
```
public static final FileType RU
```


Rack-konfigurationsfilformat


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Ruby bygginställningsformat


### RBI {#RBI}
```
public static final FileType RBI
```


Ruby-gränssnittsfilformat


### SASS {#SASS}
```
public static final FileType SASS
```


Stilmallspråkformat


### SCSS {#SCSS}
```
public static final FileType SCSS
```


Stilmallspråkformat


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala-programspråksformat


### SBT {#SBT}
```
public static final FileType SBT
```


SBT-byggverktyg för Scala-format


### SC {#SC}
```
public static final FileType SC
```


Scala-arbetsbladformat


### SH {#SH}
```
public static final FileType SH
```


Script programmerat för bash-format


### BASH {#BASH}
```
public static final FileType BASH
```


Typ av tolk som bearbetar shell-kommandon


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


Fil bestämmer beteendet för interaktiva skal


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


Specialiserat bash-script som automatiserar kompilerings- och installationsprocedurer för programvarupaket


### SQL {#SQL}
```
public static final FileType SQL
```


Structured Query Language-format


### DSQL {#DSQL}
```
public static final FileType DSQL
```


Dynamic Structured Query Language-format


### VIM {#VIM}
```
public static final FileType VIM
```


Vim källkodfilformat


### YAML {#YAML}
```
public static final FileType YAML
```


Mänskligt läsbar data-serialiseringsspråksformat


### YML {#YML}
```
public static final FileType YML
```


Mänskligt läsbar data-serialiseringsspråksformat


### values() {#values--}
```
public static FileType[] values()
```




**Returns:**
com.groupdocs.comparison.result.FileType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static FileType valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


Returnera FileType baserat på filnamn eller filändelse


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Filnamn eller filändelse, får inte vara null |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Hämtar lista över stödjade filtyper


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - lista över FileType

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


Kontrollerar likheten för angivna filtyper


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Vänster [FileType](../../com.groupdocs.comparison.result/filetype) objekt. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Höger [FileType](../../com.groupdocs.comparison.result/filetype) objekt. |
|

**Returns:**
boolean - true om lika, annars false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


Kontrollerar att de angivna filtyperna inte är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Vänster [FileType](../../com.groupdocs.comparison.result/filetype) objekt. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Höger [FileType](../../com.groupdocs.comparison.result/filetype) objekt. |
|

**Returns:**
boolean - sant om inte lika, annars falskt

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


Hämtar textbeskrivning av filtypen


**Returns:**
java.lang.String - filtypbeskrivning

### getExtension() {#getExtension--}
```
public String getExtension()
```


Hämtar filtypens filändelse


**Returns:**
java.lang.String - filtypens filändelse

### toString() {#toString--}
```
public String toString()
```


Hämtar strängrepresentation av [FileType](../../com.groupdocs.comparison.result/filetype), till exempel
'PHP Programming Language-format (.php)'



**Returns:**
java.lang.String - strängrepresentation

