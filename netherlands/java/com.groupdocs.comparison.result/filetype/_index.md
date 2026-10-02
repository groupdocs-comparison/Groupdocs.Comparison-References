---
title: "FileType"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "De FileType-enum vertegenwoordigt het type bestand dat wordt gebruikt in het documentvergelijkingsproces."
type: docs
weight: 16
url: /nl/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

De FileType-enum vertegenwoordigt het type bestand dat wordt gebruikt in het documentvergelijkingsproces.


Het definieert verschillende bestandstypen zoals Word-documenten, PDF-bestanden en meer.
Biedt methoden om een lijst te verkrijgen van alle bestandstypen die worden ondersteund door GroupDocs.Comparison, bestandstype te detecteren op basis van extensie, enz.
Gebruik deze enum om het bestandstype op te geven bij het werken met de GroupDocs.Comparison-bibliotheek.

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


Voorbeeldgebruik:

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


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Onbekend type |
|
|  | [AS](#AS) | ActionScript-programmeertaalformaat |
|
|  | [AS3](#AS3) | ActionScript-programmeertaalformaat |
|
|  | [ASM](#ASM) | Assembler-programmeertaalformaat |
|
|  | [BAT](#BAT) | Scriptbestand in DOS, OS/2 en Microsoft Windows |
|
|  | [CMD](#CMD) | Scriptbestand in DOS, OS/2 en Microsoft Windows |
|
|  | [C](#C) | C-gebaseerde programmeertaalformaat |
|
|  | [H](#H) | C-gebaseerde headerbestanden bevatten definities van Functions en Variables |
|
|  | [PDF](#PDF) | Adobe Portable Document-formaat |
|
|  | [DOC](#DOC) | Microsoft Word 97-2003-document |
|
|  | [DOCM](#DOCM) | Microsoft Word macro-ondersteund document |
|
|  | [DOCX](#DOCX) | Microsoft Word-document |
|
|  | [DOT](#DOT) | Microsoft Word 97-2003-sjabloon |
|
|  | [DOTM](#DOTM) | Microsoft Word macro-ondersteunde sjabloon |
|
|  | [DOTX](#DOTX) | Microsoft Word-sjabloon |
|
|  | [XLS](#XLS) | Microsoft Excel 97-2003-werkblad |
|
|  | [XLT](#XLT) | Microsoft Excel-sjabloon |
|
|  | [XLSX](#XLSX) | Microsoft Excel-werkblad |
|
|  | [XLTM](#XLTM) | Microsoft Excel macro-ondersteunde sjabloon |
|
|  | [XLSB](#XLSB) | Microsoft Excel binair werkblad |
|
|  | [XLSM](#XLSM) | Microsoft Excel macro-ondersteund werkblad |
|
|  | [POT](#POT) | Microsoft PowerPoint-sjabloon |
|
|  | [POTX](#POTX) | Microsoft PowerPoint-sjabloon |
|
|  | [POTM](#POTM) | Microsoft PowerPoint-sjabloon met ondersteuning voor macro's |
|
|  | [PPS](#PPS) | Microsoft PowerPoint 97-2003 diavoorstelling |
|
|  | [PPSX](#PPSX) | Microsoft PowerPoint diavoorstelling |
|
|  | [PPTX](#PPTX) | Microsoft PowerPoint-presentatie |
|
|  | [PPT](#PPT) | Microsoft PowerPoint 97-2003-presentatie |
|
|  | [PPTM](#PPTM) | Microsoft PowerPoint macro-ondersteunde presentatie |
|
|  | [PPSM](#PPSM) | Microsoft PowerPoint macro-ondersteunde diavoorstellingspresentatie |
|
|  | [VSDX](#VSDX) | Microsoft Visio-tekening |
|
|  | [VSD](#VSD) | Microsoft Visio 2003-2010-tekening |
|
|  | [VSS](#VSS) | Microsoft Visio 2003-2010 sjabloon |
|
|  | [VST](#VST) | Microsoft Visio 2003-2010-sjabloon |
|
|  | [VDX](#VDX) | Microsoft Visio 2003-2010 XML-tekening |
|
|  | [ONE](#ONE) | Microsoft OneNote-document |
|
|  | [ODT](#ODT) | OpenDocument-tekst |
|
|  | [ODP](#ODP) | OpenDocument-presentatie |
|
|  | [OTP](#OTP) | OpenDocument-presentatiesjabloon |
|
|  | [ODS](#ODS) | OpenDocument-spreadsheet |
|
|  | [OTT](#OTT) | OpenDocument-tekstsjabloon |
|
|  | [RTF](#RTF) | Rich Text-document |
|
|  | [TXT](#TXT) | Platte tekstdocument |
|
|  | [CSV](#CSV) | Komma-gescheiden waardenbestand |
|
|  | [HTML](#HTML) | HyperText-opmaaktaal |
|
|  | [MHTML](#MHTML) | Mime HTML |
|
|  | [MOBI](#MOBI) | Mobipocket e-boekformaat |
|
|  | [DCM](#DCM) | Digitale beeldvorming en communicatie in de geneeskunde |
|
|  | [DJVU](#DJVU) | Deja Vu-formaat |
|
|  | [DWG](#DWG) | Autodesk-ontwerpgegevensformaten |
|
|  | [DXF](#DXF) | AutoCAD-tekenuitwisseling |
|
|  | [BMP](#BMP) | Bitmap-afbeelding |
|
|  | [GIF](#GIF) | Grafisch uitwisselingsformaat |
|
|  | [JPEG](#JPEG) | Joint Photographic Experts Group |
|
|  | [JPG](#JPG) | Joint Photographic Experts Group |
|
|  | [PNG](#PNG) | Portable Network Graphics |
|
|  | [SVG](#SVG) | Scalar Vector Graphics |
|
|  | [EML](#EML) | E-mailbericht |
|
|  | [EMLX](#EMLX) | Apple Mail e-mailbestand |
|
|  | [MSG](#MSG) | Microsoft Outlook e-mailbericht |
|
|  | [CAD](#CAD) | CAD-bestandsformaat |
|
|  | [CPP](#CPP) | C-gebaseerde programmeertaalformaat |
|
|  | [CC](#CC) | C-gebaseerde programmeertaalformaat |
|
|  | [CXX](#CXX) | C-gebaseerde programmeertaalformaat |
|
|  | [HXX](#HXX) | Headerbestanden die geschreven zijn in de C++-programmeertaal |
|
|  | [HH](#HH) | Headerinformatie waarnaar verwezen wordt door een C++-broncodebestand |
|
|  | [HPP](#HPP) | Headerbestanden die geschreven zijn in de C++-programmeertaal |
|
|  | [CMAKE](#CMAKE) | Tool voor het beheren van het buildproces van software |
|
|  | [CS](#CS) | CSharp-programmeertaalformaat |
|
|  | [CSX](#CSX) | CSharp-scriptbestandformaat |
|
|  | [CAKE](#CAKE) | CSharp cross-platform build-automatiseringssysteemformaat |
|
|  | [DIFF](#DIFF) | Data-vergelijkingstoolformaat |
|
|  | [PATCH](#PATCH) | Lijst-van-verschillen-formaat |
|
|  | [REJ](#REJ) | Afgewezen bestandenformaat |
|
|  | [GROOVY](#GROOVY) | Broncodebestand geschreven in Groovy-formaat |
|
|  | [GVY](#GVY) | Broncodebestand geschreven in Groovy-formaat |
|
|  | [GRADLE](#GRADLE) | Build-automatiseringssysteemformaat |
|
|  | [HAML](#HAML) | Opmaaktaal voor vereenvoudigde HTML-generatie |
|
|  | [JS](#JS) | JavaScript-programmeertaalformaat |
|
|  | [ES6](#ES6) | JavaScript-gestandaardiseerde scripttaalformaat |
|
|  | [MJS](#MJS) | Extensie voor EcmaScript (ES) modulebestanden |
|
|  | [PAC](#PAC) | Proxy Auto-Configuration-bestand voor JavaScript-functieformaat |
|
|  | [JSON](#JSON) | Lichtgewichtformaat voor het opslaan en transporteren van gegevens |
|
|  | [BOWERRC](#BOWERRC) | Configuratiebestand voor pakketbeheer aan de serverzijde |
|
|  | [JSHINTRC](#JSHINTRC) | JavaScript-codekwaliteitsinstrument |
|
|  | [JSCSRC](#JSCSRC) | JavaScript-configuratiebestandformaat |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | Manifestbestand bevat informatie over de app |
|
|  | [JSMAP](#JSMAP) | JSON-bestand dat informatie bevat over hoe code terug te vertalen naar broncode |
|
|  | [HAR](#HAR) | Het HTTP-archiefformaat |
|
|  | [JAVA](#JAVA) | Java-programmeertaalformaat |
|
|  | [LESS](#LESS) | Dynamische preprocessor stylesheet-taalformaat |
|
|  | [LOG](#LOG) | Logging houdt een register bij van gebeurtenissen, processen, berichten en communicatie |
|
|  | [MAKE](#MAKE) | Makefile is een bestand dat een reeks richtlijnen bevat die door een make build-automatiseringstool worden gebruikt om een doel te genereren |
|
|  | [MK](#MK) | Makefile is een bestand dat een reeks richtlijnen bevat die door een make build-automatiseringstool worden gebruikt om een doel te genereren |
|
|  | [MD](#MD) | Markdown-taalformaat |
|
|  | [MKD](#MKD) | Markdown-taalformaat |
|
|  | [MDWN](#MDWN) | Markdown-taalformaat |
|
|  | [MDOWN](#MDOWN) | Markdown-taalformaat |
|
|  | [MARKDOWN](#MARKDOWN) | Markdown-taalformaat |
|
|  | [MARKDN](#MARKDN) | Markdown-taalformaat |
|
|  | [MDTXT](#MDTXT) | Markdown-taalformaat |
|
|  | [MDTEXT](#MDTEXT) | Markdown-taalformaat |
|
|  | [ML](#ML) | Caml-programmeertaalformaat |
|
|  | [MLI](#MLI) | Caml-programmeertaalformaat |
|
|  | [OBJC](#OBJC) | Objective-C-programmeertaalformaat |
|
|  | [OBJCP](#OBJCP) | Objective-C++-programmeertaalformaat |
|
|  | [PHP](#PHP) | PHP-programmeertaalformaat |
|
|  | [PHP4](#PHP4) | PHP-programmeertaalformaat |
|
|  | [PHP5](#PHP5) | PHP-programmeertaalformaat |
|
|  | [PHTML](#PHTML) | Standaard bestandsextensie voor PHP 2-programma's formaat |
|
|  | [CTP](#CTP) | CakePHP-sjabloonformaat |
|
|  | [PL](#PL) | Perl-programmeertaalformaat |
|
|  | [PM](#PM) | Perl-moduulformaat |
|
|  | [POD](#POD) | Perl lichte opmaaktaalformaat |
|
|  | [T](#T) | Perl-testbestandsformaat |
|
|  | [PSGI](#PSGI) | Interface tussen webservers en webapplicaties en -frameworks geschreven in de Perl-programmering |
|
|  | [P6](#P6) | Perl-programmeertaalformaat |
|
|  | [PL6](#PL6) | Perl-programmeertaalformaat |
|
|  | [PM6](#PM6) | Perl-moduulformaat |
|
|  | [NQP](#NQP) | Tussentaal die wordt gebruikt om de Rakuto Perl 6-compiler te bouwen |
|
|  | [PROP](#PROP) | Eigenschappenbestandsformaat |
|
|  | [CFG](#CFG) | Configuratiebestand dat wordt gebruikt voor het opslaan van instellingen |
|
|  | [CONF](#CONF) | Configuratiebestand dat wordt gebruikt op Unix- en Linux-gebaseerde systemen |
|
|  | [DIR](#DIR) | Directory is een locatie voor het opslaan van bestanden op de computer |
|
|  | [PY](#PY) | Python-programmeertaalformaat |
|
|  | [RPY](#RPY) | Python-gebaseerde bestandsengine om games te maken en uit te voeren |
|
|  | [PYW](#PYW) | Bestanden die in Windows worden gebruikt om aan te geven dat een script moet worden uitgevoerd |
|
|  | [CPY](#CPY) | Controller Python-scriptformaat |
|
|  | [GYP](#GYP) | Build-automatiseringstoolformaat |
|
|  | [GYPI](#GYPI) | Build-automatiseringstoolformaat |
|
|  | [PYI](#PYI) | Python-interfacebestandsformaat |
|
|  | [IPY](#IPY) | IPython-scriptformaat |
|
|  | [RST](#RST) | Lichte opmaaktaal |
|
|  | [RB](#RB) | Ruby-programmeertaalformaat |
|
|  | [ERB](#ERB) | Ruby-programmeertaalformaat |
|
|  | [RJS](#RJS) | Ruby-programmeertaalformaat |
|
|  | [GEMSPEC](#GEMSPEC) | Ontwikkelaarsbestand dat de attributen van een RubyGems specificeert |
|
|  | [RAKE](#RAKE) | Ruby build-automatiseringstool |
|
|  | [RU](#RU) | Rack-configuratiebestandsformaat |
|
|  | [PODSPEC](#PODSPEC) | Ruby-buildinstellingenformaat |
|
|  | [RBI](#RBI) | Ruby-interfacebestandsformaat |
|
|  | [SASS](#SASS) | Stylesheet-taalformaat |
|
|  | [SCSS](#SCSS) | Stylesheet-taalformaat |
|
|  | [SCALA](#SCALA) | Scala Programmeertaal formaat |
|
|  | [SBT](#SBT) | SBT-buildtool voor Scala-formaat |
|
|  | [SC](#SC) | Scala-werkbladformaat |
|
|  | [SH](#SH) | Script geprogrammeerd voor bash-formaat |
|
|  | [BASH](#BASH) | Type interpreter dat shellopdrachten verwerkt |
|
|  | [BASHRC](#BASHRC) | Bestand bepaalt het gedrag van interactieve shells |
|
|  | [EBUILD](#EBUILD) | Gespecialiseerd bash-script dat compilatie- en installatieprocedures voor softwarepakketten automatiseert |
|
|  | [SQL](#SQL) | Structured Query Language-formaat |
|
|  | [DSQL](#DSQL) | Dynamisch Structured Query Language-formaat |
|
|  | [VIM](#VIM) | Vim-broncodebestand formaat |
|
|  | [YAML](#YAML) | Menselijk leesbare data-serialisatietaal formaat |
|
|  | [YML](#YML) | Menselijk leesbare data-serialisatietaal formaat |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | Retourneer FileType op basis van bestandsnaam of extensie |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Haalt lijst op van ondersteunde bestandstypen |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Controleert de gelijkheid van opgegeven bestandstypen |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Controleert of opgegeven bestandstypen niet gelijk zijn |
|
|  | [getFileFormat()](#getFileFormat--) | Haalt tekstbeschrijving op van het bestandstype |
|
|  | [getExtension()](#getExtension--) | Haalt de extensie op van het bestandstype |
|
|  | [toString()](#toString--) | Haalt stringrepresentatie op van [FileType](../../com.groupdocs.comparison.result/filetype), bijvoorbeeld |
'PHP Programmeertaal formaat (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Onbekend type


### AS {#AS}
```
public static final FileType AS
```


ActionScript-programmeertaalformaat


### AS3 {#AS3}
```
public static final FileType AS3
```


ActionScript-programmeertaalformaat


### ASM {#ASM}
```
public static final FileType ASM
```


Assembler-programmeertaalformaat


### BAT {#BAT}
```
public static final FileType BAT
```


Scriptbestand in DOS, OS/2 en Microsoft Windows


### CMD {#CMD}
```
public static final FileType CMD
```


Scriptbestand in DOS, OS/2 en Microsoft Windows


### C {#C}
```
public static final FileType C
```


C-gebaseerde programmeertaalformaat


### H {#H}
```
public static final FileType H
```


C-gebaseerde headerbestanden bevatten definities van Functions en Variables


### PDF {#PDF}
```
public static final FileType PDF
```


Adobe Portable Document-formaat


### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word 97-2003-document


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Microsoft Word macro-ondersteund document


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word-document


### DOT {#DOT}
```
public static final FileType DOT
```


Microsoft Word 97-2003-sjabloon


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Microsoft Word macro-ondersteunde sjabloon


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Microsoft Word-sjabloon


### XLS {#XLS}
```
public static final FileType XLS
```


Microsoft Excel 97-2003-werkblad


### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel-sjabloon


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel-werkblad


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel macro-ondersteunde sjabloon


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Microsoft Excel binair werkblad


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Microsoft Excel macro-ondersteund werkblad


### POT {#POT}
```
public static final FileType POT
```


Microsoft PowerPoint-sjabloon


### POTX {#POTX}
```
public static final FileType POTX
```


Microsoft PowerPoint-sjabloon


### POTM {#POTM}
```
public static final FileType POTM
```


Microsoft PowerPoint-sjabloon met ondersteuning voor macro's


### PPS {#PPS}
```
public static final FileType PPS
```


Microsoft PowerPoint 97-2003 diavoorstelling


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Microsoft PowerPoint diavoorstelling


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Microsoft PowerPoint-presentatie


### PPT {#PPT}
```
public static final FileType PPT
```


Microsoft PowerPoint 97-2003-presentatie


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Microsoft PowerPoint macro-ondersteunde presentatie


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Microsoft PowerPoint macro-ondersteunde diavoorstellingspresentatie


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Visio-tekening


### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio 2003-2010-tekening


### VSS {#VSS}
```
public static final FileType VSS
```


Microsoft Visio 2003-2010 sjabloon


### VST {#VST}
```
public static final FileType VST
```


Microsoft Visio 2003-2010-sjabloon


### VDX {#VDX}
```
public static final FileType VDX
```


Microsoft Visio 2003-2010 XML-tekening


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote-document


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument-tekst


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument-presentatie


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument-presentatiesjabloon


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument-spreadsheet


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument-tekstsjabloon


### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text-document


### TXT {#TXT}
```
public static final FileType TXT
```


Platte tekstdocument


### CSV {#CSV}
```
public static final FileType CSV
```


Komma-gescheiden waardenbestand


### HTML {#HTML}
```
public static final FileType HTML
```


HyperText-opmaaktaal


### MHTML {#MHTML}
```
public static final FileType MHTML
```


Mime HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket e-boekformaat


### DCM {#DCM}
```
public static final FileType DCM
```


Digitale beeldvorming en communicatie in de geneeskunde


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Deja Vu-formaat


### DWG {#DWG}
```
public static final FileType DWG
```


Autodesk-ontwerpgegevensformaten


### DXF {#DXF}
```
public static final FileType DXF
```


AutoCAD-tekenuitwisseling


### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap-afbeelding


### GIF {#GIF}
```
public static final FileType GIF
```


Grafisch uitwisselingsformaat


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


Portable Network Graphics


### SVG {#SVG}
```
public static final FileType SVG
```


Scalar Vector Graphics


### EML {#EML}
```
public static final FileType EML
```


E-mailbericht


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail e-mailbestand


### MSG {#MSG}
```
public static final FileType MSG
```


Microsoft Outlook e-mailbericht


### CAD {#CAD}
```
public static final FileType CAD
```


CAD-bestandsformaat


### CPP {#CPP}
```
public static final FileType CPP
```


C-gebaseerde programmeertaalformaat


### CC {#CC}
```
public static final FileType CC
```


C-gebaseerde programmeertaalformaat


### CXX {#CXX}
```
public static final FileType CXX
```


C-gebaseerde programmeertaalformaat


### HXX {#HXX}
```
public static final FileType HXX
```


Headerbestanden die geschreven zijn in de C++-programmeertaal


### HH {#HH}
```
public static final FileType HH
```


Headerinformatie waarnaar verwezen wordt door een C++-broncodebestand


### HPP {#HPP}
```
public static final FileType HPP
```


Headerbestanden die geschreven zijn in de C++-programmeertaal


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Tool voor het beheren van het buildproces van software


### CS {#CS}
```
public static final FileType CS
```


CSharp-programmeertaalformaat


### CSX {#CSX}
```
public static final FileType CSX
```


CSharp-scriptbestandformaat


### CAKE {#CAKE}
```
public static final FileType CAKE
```


CSharp cross-platform build-automatiseringssysteemformaat


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Data-vergelijkingstoolformaat


### PATCH {#PATCH}
```
public static final FileType PATCH
```


Lijst-van-verschillen-formaat


### REJ {#REJ}
```
public static final FileType REJ
```


Afgewezen bestandenformaat


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Broncodebestand geschreven in Groovy-formaat


### GVY {#GVY}
```
public static final FileType GVY
```


Broncodebestand geschreven in Groovy-formaat


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


Build-automatiseringssysteemformaat


### HAML {#HAML}
```
public static final FileType HAML
```


Opmaaktaal voor vereenvoudigde HTML-generatie


### JS {#JS}
```
public static final FileType JS
```


JavaScript-programmeertaalformaat


### ES6 {#ES6}
```
public static final FileType ES6
```


JavaScript-gestandaardiseerde scripttaalformaat


### MJS {#MJS}
```
public static final FileType MJS
```


Extensie voor EcmaScript (ES) modulebestanden


### PAC {#PAC}
```
public static final FileType PAC
```


Proxy Auto-Configuration-bestand voor JavaScript-functieformaat


### JSON {#JSON}
```
public static final FileType JSON
```


Lichtgewichtformaat voor het opslaan en transporteren van gegevens


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


Configuratiebestand voor pakketbeheer aan de serverzijde


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


JavaScript-codekwaliteitsinstrument


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


JavaScript-configuratiebestandformaat


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


Manifestbestand bevat informatie over de app


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


JSON-bestand dat informatie bevat over hoe code terug te vertalen naar broncode


### HAR {#HAR}
```
public static final FileType HAR
```


Het HTTP-archiefformaat


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java-programmeertaalformaat


### LESS {#LESS}
```
public static final FileType LESS
```


Dynamische preprocessor stylesheet-taalformaat


### LOG {#LOG}
```
public static final FileType LOG
```


Logging houdt een register bij van gebeurtenissen, processen, berichten en communicatie


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile is een bestand dat een reeks richtlijnen bevat die door een make build-automatiseringstool worden gebruikt om een doel te genereren


### MK {#MK}
```
public static final FileType MK
```


Makefile is een bestand dat een reeks richtlijnen bevat die door een make build-automatiseringstool worden gebruikt om een doel te genereren


### MD {#MD}
```
public static final FileType MD
```


Markdown-taalformaat


### MKD {#MKD}
```
public static final FileType MKD
```


Markdown-taalformaat


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Markdown-taalformaat


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Markdown-taalformaat


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Markdown-taalformaat


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Markdown-taalformaat


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Markdown-taalformaat


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Markdown-taalformaat


### ML {#ML}
```
public static final FileType ML
```


Caml-programmeertaalformaat


### MLI {#MLI}
```
public static final FileType MLI
```


Caml-programmeertaalformaat


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Objective-C-programmeertaalformaat


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Objective-C++-programmeertaalformaat


### PHP {#PHP}
```
public static final FileType PHP
```


PHP-programmeertaalformaat


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


PHP-programmeertaalformaat


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


PHP-programmeertaalformaat


### PHTML {#PHTML}
```
public static final FileType PHTML
```


Standaard bestandsextensie voor PHP 2-programma's formaat


### CTP {#CTP}
```
public static final FileType CTP
```


CakePHP-sjabloonformaat


### PL {#PL}
```
public static final FileType PL
```


Perl-programmeertaalformaat


### PM {#PM}
```
public static final FileType PM
```


Perl-moduulformaat


### POD {#POD}
```
public static final FileType POD
```


Perl lichte opmaaktaalformaat


### T {#T}
```
public static final FileType T
```


Perl-testbestandsformaat


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Interface tussen webservers en webapplicaties en -frameworks geschreven in de Perl-programmering


### P6 {#P6}
```
public static final FileType P6
```


Perl-programmeertaalformaat


### PL6 {#PL6}
```
public static final FileType PL6
```


Perl-programmeertaalformaat


### PM6 {#PM6}
```
public static final FileType PM6
```


Perl-moduulformaat


### NQP {#NQP}
```
public static final FileType NQP
```


Tussentaal die wordt gebruikt om de Rakuto Perl 6-compiler te bouwen


### PROP {#PROP}
```
public static final FileType PROP
```


Eigenschappenbestandsformaat


### CFG {#CFG}
```
public static final FileType CFG
```


Configuratiebestand dat wordt gebruikt voor het opslaan van instellingen


### CONF {#CONF}
```
public static final FileType CONF
```


Configuratiebestand dat wordt gebruikt op Unix- en Linux-gebaseerde systemen


### DIR {#DIR}
```
public static final FileType DIR
```


Directory is een locatie voor het opslaan van bestanden op de computer


### PY {#PY}
```
public static final FileType PY
```


Python-programmeertaalformaat


### RPY {#RPY}
```
public static final FileType RPY
```


Python-gebaseerde bestandsengine om games te maken en uit te voeren


### PYW {#PYW}
```
public static final FileType PYW
```


Bestanden die in Windows worden gebruikt om aan te geven dat een script moet worden uitgevoerd


### CPY {#CPY}
```
public static final FileType CPY
```


Controller Python-scriptformaat


### GYP {#GYP}
```
public static final FileType GYP
```


Build-automatiseringstoolformaat


### GYPI {#GYPI}
```
public static final FileType GYPI
```


Build-automatiseringstoolformaat


### PYI {#PYI}
```
public static final FileType PYI
```


Python-interfacebestandsformaat


### IPY {#IPY}
```
public static final FileType IPY
```


IPython-scriptformaat


### RST {#RST}
```
public static final FileType RST
```


Lichte opmaaktaal


### RB {#RB}
```
public static final FileType RB
```


Ruby-programmeertaalformaat


### ERB {#ERB}
```
public static final FileType ERB
```


Ruby-programmeertaalformaat


### RJS {#RJS}
```
public static final FileType RJS
```


Ruby-programmeertaalformaat


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


Ontwikkelaarsbestand dat de attributen van een RubyGems specificeert


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Ruby build-automatiseringstool


### RU {#RU}
```
public static final FileType RU
```


Rack-configuratiebestandsformaat


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Ruby-buildinstellingenformaat


### RBI {#RBI}
```
public static final FileType RBI
```


Ruby-interfacebestandsformaat


### SASS {#SASS}
```
public static final FileType SASS
```


Stylesheet-taalformaat


### SCSS {#SCSS}
```
public static final FileType SCSS
```


Stylesheet-taalformaat


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala Programmeertaal formaat


### SBT {#SBT}
```
public static final FileType SBT
```


SBT-buildtool voor Scala-formaat


### SC {#SC}
```
public static final FileType SC
```


Scala-werkbladformaat


### SH {#SH}
```
public static final FileType SH
```


Script geprogrammeerd voor bash-formaat


### BASH {#BASH}
```
public static final FileType BASH
```


Type interpreter dat shellopdrachten verwerkt


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


Bestand bepaalt het gedrag van interactieve shells


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


Gespecialiseerd bash-script dat compilatie- en installatieprocedures voor softwarepakketten automatiseert


### SQL {#SQL}
```
public static final FileType SQL
```


Structured Query Language-formaat


### DSQL {#DSQL}
```
public static final FileType DSQL
```


Dynamisch Structured Query Language-formaat


### VIM {#VIM}
```
public static final FileType VIM
```


Vim-broncodebestand formaat


### YAML {#YAML}
```
public static final FileType YAML
```


Menselijk leesbare data-serialisatietaal formaat


### YML {#YML}
```
public static final FileType YML
```


Menselijk leesbare data-serialisatietaal formaat


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


Retourneer FileType op basis van bestandsnaam of extensie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Bestandsnaam of extensie, niet null |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Haalt lijst op van ondersteunde bestandstypen


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - lijst van FileType

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


Controleert de gelijkheid van opgegeven bestandstypen


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Linker [FileType](../../com.groupdocs.comparison.result/filetype) object. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Rechter [FileType](../../com.groupdocs.comparison.result/filetype) object. |
|

**Returns:**
boolean - true als gelijk, anders false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


Controleert of opgegeven bestandstypen niet gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Linker [FileType](../../com.groupdocs.comparison.result/filetype) object. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Rechter [FileType](../../com.groupdocs.comparison.result/filetype) object. |
|

**Returns:**
boolean - true als niet gelijk, anders false

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


Haalt tekstbeschrijving op van het bestandstype


**Returns:**
java.lang.String - beschrijving van het bestandstype

### getExtension() {#getExtension--}
```
public String getExtension()
```


Haalt de extensie op van het bestandstype


**Returns:**
java.lang.String - extensie van het bestandstype

### toString() {#toString--}
```
public String toString()
```


Haalt stringrepresentatie op van [FileType](../../com.groupdocs.comparison.result/filetype), bijvoorbeeld
'PHP Programmeertaal formaat (.php)'



**Returns:**
java.lang.String - stringrepresentatie

