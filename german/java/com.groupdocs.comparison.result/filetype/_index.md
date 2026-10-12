---
title: "FileType"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Das Enum FileType repräsentiert den Typ einer Datei, die im Dokumentenvergleichsprozess verwendet wird."
type: docs
weight: 16
url: /de/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

Das Enum FileType repräsentiert den Typ einer Datei, die im Dokumentenvergleichsprozess verwendet wird.


Es definiert verschiedene Dateitypen wie Word-Dokumente, PDF-Dateien und mehr.
Stellt Methoden bereit, um eine Liste aller von GroupDocs.Comparison unterstützten Dateitypen zu erhalten, den Dateityp anhand der Erweiterung zu erkennen usw.
Verwenden Sie dieses Enum, um den Dateityp beim Arbeiten mit der GroupDocs.Comparison-Bibliothek anzugeben.

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


Beispielverwendung:

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


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Unbekannter Typ |
|
|  | [AS](#AS) | ActionScript-Programmiersprachenformat |
|
|  | [AS3](#AS3) | ActionScript-Programmiersprachenformat |
|
|  | [ASM](#ASM) | Assembler-Programmiersprachenformat |
|
|  | [BAT](#BAT) | Skriptdatei in DOS, OS/2 und Microsoft Windows |
|
|  | [CMD](#CMD) | Skriptdatei in DOS, OS/2 und Microsoft Windows |
|
|  | [C](#C) | C-basierter Programmiersprachenformat |
|
|  | [H](#H) | C-basierte Header-Dateien enthalten Definitionen von Funktionen und Variablen |
|
|  | [PDF](#PDF) | Adobe Portable Document Format |
|
|  | [DOC](#DOC) | Microsoft Word 97-2003-Dokument |
|
|  | [DOCM](#DOCM) | Microsoft Word Makro-aktiviertes Dokument |
|
|  | [DOCX](#DOCX) | Microsoft Word-Dokument |
|
|  | [DOT](#DOT) | Microsoft Word 97-2003-Vorlage |
|
|  | [DOTM](#DOTM) | Microsoft Word Makro-aktivierte Vorlage |
|
|  | [DOTX](#DOTX) | Microsoft Word-Vorlage |
|
|  | [XLS](#XLS) | Microsoft Excel 97-2003-Arbeitsblatt |
|
|  | [XLT](#XLT) | Microsoft Excel-Vorlage |
|
|  | [XLSX](#XLSX) | Microsoft Excel-Arbeitsblatt |
|
|  | [XLTM](#XLTM) | Microsoft Excel Makro-aktivierte Vorlage |
|
|  | [XLSB](#XLSB) | Microsoft Excel Binäres Arbeitsblatt |
|
|  | [XLSM](#XLSM) | Microsoft Excel Makroaktiviertes Arbeitsblatt |
|
|  | [POT](#POT) | Microsoft PowerPoint Vorlage |
|
|  | [POTX](#POTX) | Microsoft PowerPoint Vorlage |
|
|  | [POTM](#POTM) | Microsoft PowerPoint Vorlage mit Unterstützung für Makros |
|
|  | [PPS](#PPS) | Microsoft PowerPoint 97-2003 Diashow |
|
|  | [PPSX](#PPSX) | Microsoft PowerPoint Diashow |
|
|  | [PPTX](#PPTX) | Microsoft PowerPoint Präsentation |
|
|  | [PPT](#PPT) | Microsoft PowerPoint 97-2003 Präsentation |
|
|  | [PPTM](#PPTM) | Microsoft PowerPoint Makroaktivierte Präsentation |
|
|  | [PPSM](#PPSM) | Microsoft PowerPoint Makroaktivierte Diashow-Präsentation |
|
|  | [VSDX](#VSDX) | Microsoft Visio Zeichnung |
|
|  | [VSD](#VSD) | Microsoft Visio 2003-2010 Zeichnung |
|
|  | [VSS](#VSS) | Microsoft Visio 2003-2010 Schablone |
|
|  | [VST](#VST) | Microsoft Visio 2003-2010 Vorlage |
|
|  | [VDX](#VDX) | Microsoft Visio 2003-2010 XML-Zeichnung |
|
|  | [ONE](#ONE) | Microsoft OneNote Dokument |
|
|  | [ODT](#ODT) | OpenDocument Text |
|
|  | [ODP](#ODP) | OpenDocument Präsentation |
|
|  | [OTP](#OTP) | OpenDocument Präsentationsvorlage |
|
|  | [ODS](#ODS) | OpenDocument Tabellenkalkulation |
|
|  | [OTT](#OTT) | OpenDocument Textvorlage |
|
|  | [RTF](#RTF) | Rich-Text-Dokument |
|
|  | [TXT](#TXT) | Nur-Text-Dokument |
|
|  | [CSV](#CSV) | Kommagetrennte Werte-Datei |
|
|  | [HTML](#HTML) | HyperText-Markup-Sprache |
|
|  | [MHTML](#MHTML) | Mime-HTML |
|
|  | [MOBI](#MOBI) | Mobipocket-E-Book-Format |
|
|  | [DCM](#DCM) | Digitale Bildgebung und Kommunikation in der Medizin |
|
|  | [DJVU](#DJVU) | Deja-Vu-Format |
|
|  | [DWG](#DWG) | Autodesk-Design-Datenformate |
|
|  | [DXF](#DXF) | AutoCAD-Zeichnungsaustausch |
|
|  | [BMP](#BMP) | Bitmap-Bild |
|
|  | [GIF](#GIF) | Grafik-Austauschformat |
|
|  | [JPEG](#JPEG) | Joint Photographic Experts Group |
|
|  | [JPG](#JPG) | Joint Photographic Experts Group |
|
|  | [PNG](#PNG) | Portable Network Graphics |
|
|  | [SVG](#SVG) | Skalare Vektor-Grafiken |
|
|  | [EML](#EML) | E-Mail-Nachricht |
|
|  | [EMLX](#EMLX) | Apple Mail E-Mail-Datei |
|
|  | [MSG](#MSG) | Microsoft Outlook E-Mail-Nachricht |
|
|  | [CAD](#CAD) | CAD-Dateiformat |
|
|  | [CPP](#CPP) | C-basierter Programmiersprachenformat |
|
|  | [CC](#CC) | C-basierter Programmiersprachenformat |
|
|  | [CXX](#CXX) | C-basierter Programmiersprachenformat |
|
|  | [HXX](#HXX) | Header-Dateien, die in der C++-Programmiersprache geschrieben sind |
|
|  | [HH](#HH) | Header-Informationen, auf die von einer C++-Quelldatei verwiesen wird |
|
|  | [HPP](#HPP) | Header-Dateien, die in der C++-Programmiersprache geschrieben sind |
|
|  | [CMAKE](#CMAKE) | Werkzeug zur Verwaltung des Build-Prozesses von Software |
|
|  | [CS](#CS) | CSharp-Programmiersprachenformat |
|
|  | [CSX](#CSX) | CSharp-Skriptdateiformat |
|
|  | [CAKE](#CAKE) | CSharp-Plattformübergreifendes Build-Automatisierungssystem-Format |
|
|  | [DIFF](#DIFF) | Datenvergleichswerkzeug-Format |
|
|  | [PATCH](#PATCH) | Format für Unterschiedsliste |
|
|  | [REJ](#REJ) | Format für abgelehnte Dateien |
|
|  | [GROOVY](#GROOVY) | Quellcodedatei im Groovy-Format |
|
|  | [GVY](#GVY) | Quellcodedatei im Groovy-Format |
|
|  | [GRADLE](#GRADLE) | Build-Automatisierungssystem-Format |
|
|  | [HAML](#HAML) | Auszeichnungssprache zur vereinfachten HTML-Generierung |
|
|  | [JS](#JS) | JavaScript-Programmiersprachen-Format |
|
|  | [ES6](#ES6) | Standardisiertes Skriptsprachenformat für JavaScript |
|
|  | [MJS](#MJS) | Erweiterung für EcmaScript (ES)-Moduldateien |
|
|  | [PAC](#PAC) | Proxy-Auto-Configuration-Datei für JavaScript-Funktionsformat |
|
|  | [JSON](#JSON) | Leichtgewichtiges Format zum Speichern und Transportieren von Daten |
|
|  | [BOWERRC](#BOWERRC) | Konfigurationsdatei für Paketverwaltung auf der Serverseite |
|
|  | [JSHINTRC](#JSHINTRC) | JavaScript-Codequalitätswerkzeug |
|
|  | [JSCSRC](#JSCSRC) | JavaScript-Konfigurationsdateiformat |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | Manifestdatei enthält Informationen über die Anwendung |
|
|  | [JSMAP](#JSMAP) | JSON-Datei, die Informationen darüber enthält, wie Code zurück in Quellcode übersetzt wird |
|
|  | [HAR](#HAR) | Das HTTP-Archive-Format |
|
|  | [JAVA](#JAVA) | Java-Programmiersprachen-Format |
|
|  | [LESS](#LESS) | Dynamisches Präprozessor-Stylesheet-Sprachformat |
|
|  | [LOG](#LOG) | Logging führt ein Register von Ereignissen, Prozessen, Nachrichten und Kommunikation |
|
|  | [MAKE](#MAKE) | Makefile ist eine Datei, die eine Reihe von Anweisungen enthält, die von einem Make-Build-Automatisierungswerkzeug verwendet werden, um ein Ziel zu erzeugen |
|
|  | [MK](#MK) | Makefile ist eine Datei, die eine Reihe von Anweisungen enthält, die von einem Make-Build-Automatisierungswerkzeug verwendet werden, um ein Ziel zu erzeugen |
|
|  | [MD](#MD) | Markdown-Sprachformat |
|
|  | [MKD](#MKD) | Markdown-Sprachformat |
|
|  | [MDWN](#MDWN) | Markdown-Sprachformat |
|
|  | [MDOWN](#MDOWN) | Markdown-Sprachformat |
|
|  | [MARKDOWN](#MARKDOWN) | Markdown-Sprachformat |
|
|  | [MARKDN](#MARKDN) | Markdown-Sprachformat |
|
|  | [MDTXT](#MDTXT) | Markdown-Sprachformat |
|
|  | [MDTEXT](#MDTEXT) | Markdown-Sprachformat |
|
|  | [ML](#ML) | Caml-Programmiersprachen-Format |
|
|  | [MLI](#MLI) | Caml-Programmiersprachen-Format |
|
|  | [OBJC](#OBJC) | Objective-C-Programmiersprachen-Format |
|
|  | [OBJCP](#OBJCP) | Objective-C++-Programmiersprachen-Format |
|
|  | [PHP](#PHP) | PHP-Programmiersprachen-Format |
|
|  | [PHP4](#PHP4) | PHP-Programmiersprachen-Format |
|
|  | [PHP5](#PHP5) | PHP-Programmiersprachen-Format |
|
|  | [PHTML](#PHTML) | Standard-Dateierweiterung für PHP‑2‑Programme |
|
|  | [CTP](#CTP) | CakePHP-Vorlagenformat |
|
|  | [PL](#PL) | Perl-Programmiersprachenformat |
|
|  | [PM](#PM) | Perl-Modulformat |
|
|  | [POD](#POD) | Perl-Leichtgewichts-Markup-Sprachformat |
|
|  | [T](#T) | Perl-Testdateiformat |
|
|  | [PSGI](#PSGI) | Schnittstelle zwischen Webservern und Webanwendungen sowie Frameworks, die in der Perl-Programmierung geschrieben wurden |
|
|  | [P6](#P6) | Perl-Programmiersprachenformat |
|
|  | [PL6](#PL6) | Perl-Programmiersprachenformat |
|
|  | [PM6](#PM6) | Perl-Modulformat |
|
|  | [NQP](#NQP) | Zwischensprache, die zum Erstellen des Rakuto Perl 6‑Compilers verwendet wird |
|
|  | [PROP](#PROP) | Properties-Dateiformat |
|
|  | [CFG](#CFG) | Konfigurationsdatei, die zum Speichern von Einstellungen verwendet wird |
|
|  | [CONF](#CONF) | Konfigurationsdatei, die auf Unix- und Linux-basierten Systemen verwendet wird |
|
|  | [DIR](#DIR) | Verzeichnis ist ein Ort zum Speichern von Dateien auf dem Computer |
|
|  | [PY](#PY) | Python-Programmiersprachenformat |
|
|  | [RPY](#RPY) | Python-basierte Dateimotor zum Erstellen und Ausführen von Spielen |
|
|  | [PYW](#PYW) | Dateien, die in Windows verwendet werden, um anzuzeigen, dass ein Skript ausgeführt werden muss |
|
|  | [CPY](#CPY) | Controller-Python-Skriptformat |
|
|  | [GYP](#GYP) | Build-Automatisierungstool-Format |
|
|  | [GYPI](#GYPI) | Build-Automatisierungstool-Format |
|
|  | [PYI](#PYI) | Python-Schnittstellendateiformat |
|
|  | [IPY](#IPY) | IPython-Skriptformat |
|
|  | [RST](#RST) | Leichtgewichtige Auszeichnungssprache |
|
|  | [RB](#RB) | Ruby-Programmiersprachenformat |
|
|  | [ERB](#ERB) | Ruby-Programmiersprachenformat |
|
|  | [RJS](#RJS) | Ruby-Programmiersprachenformat |
|
|  | [GEMSPEC](#GEMSPEC) | Entwicklerdatei, die die Attribute eines RubyGems spezifiziert |
|
|  | [RAKE](#RAKE) | Ruby-Build-Automatisierungstool |
|
|  | [RU](#RU) | Rack-Konfigurationsdateiformat |
|
|  | [PODSPEC](#PODSPEC) | Ruby-Build-Einstellungen-Format |
|
|  | [RBI](#RBI) | Ruby-Schnittstellendateiformat |
|
|  | [SASS](#SASS) | Stylesheet-Sprachformat |
|
|  | [SCSS](#SCSS) | Stylesheet-Sprachformat |
|
|  | [SCALA](#SCALA) | Scala Programmiersprache Format |
|
|  | [SBT](#SBT) | SBT Build-Tool für Scala-Format |
|
|  | [SC](#SC) | Scala-Arbeitsblatt-Format |
|
|  | [SH](#SH) | Skript programmiert für bash-Format |
|
|  | [BASH](#BASH) | Typ des Interpreters, der Shell-Befehle verarbeitet |
|
|  | [BASHRC](#BASHRC) | Datei bestimmt das Verhalten interaktiver Shells |
|
|  | [EBUILD](#EBUILD) | Spezialisiertes bash-Skript, das die Kompilierungs- und Installationsvorgänge für Softwarepakete automatisiert |
|
|  | [SQL](#SQL) | Structured Query Language-Format |
|
|  | [DSQL](#DSQL) | Dynamic Structured Query Language-Format |
|
|  | [VIM](#VIM) | Vim-Quellcodedatei-Format |
|
|  | [YAML](#YAML) | Menschlich lesbare Datenserialisierungs-Sprache-Format |
|
|  | [YML](#YML) | Menschlich lesbare Datenserialisierungs-Sprache-Format |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | Gibt FileType basierend auf Dateiname oder Erweiterung zurück |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Ermittelt Liste der unterstützten Dateitypen |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Prüft die Gleichheit der bereitgestellten Dateitypen |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Prüft, ob die bereitgestellten Dateitypen nicht gleich sind |
|
|  | [getFileFormat()](#getFileFormat--) | Ermittelt Textbeschreibung des Dateityps |
|
|  | [getExtension()](#getExtension--) | Ermittelt die Erweiterung des Dateityps |
|
|  | [toString()](#toString--) | Ermittelt die String-Darstellung von [FileType](../../com.groupdocs.comparison.result/filetype), zum Beispiel |
'PHP Programmiersprache Format (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Unbekannter Typ


### AS {#AS}
```
public static final FileType AS
```


ActionScript-Programmiersprachenformat


### AS3 {#AS3}
```
public static final FileType AS3
```


ActionScript-Programmiersprachenformat


### ASM {#ASM}
```
public static final FileType ASM
```


Assembler-Programmiersprachenformat


### BAT {#BAT}
```
public static final FileType BAT
```


Skriptdatei in DOS, OS/2 und Microsoft Windows


### CMD {#CMD}
```
public static final FileType CMD
```


Skriptdatei in DOS, OS/2 und Microsoft Windows


### C {#C}
```
public static final FileType C
```


C-basierter Programmiersprachenformat


### H {#H}
```
public static final FileType H
```


C-basierte Header-Dateien enthalten Definitionen von Funktionen und Variablen


### PDF {#PDF}
```
public static final FileType PDF
```


Adobe Portable Document Format


### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word 97-2003-Dokument


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Microsoft Word Makro-aktiviertes Dokument


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word-Dokument


### DOT {#DOT}
```
public static final FileType DOT
```


Microsoft Word 97-2003-Vorlage


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Microsoft Word Makro-aktivierte Vorlage


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Microsoft Word-Vorlage


### XLS {#XLS}
```
public static final FileType XLS
```


Microsoft Excel 97-2003-Arbeitsblatt


### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel-Vorlage


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel-Arbeitsblatt


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel Makro-aktivierte Vorlage


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Microsoft Excel Binäres Arbeitsblatt


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Microsoft Excel Makroaktiviertes Arbeitsblatt


### POT {#POT}
```
public static final FileType POT
```


Microsoft PowerPoint Vorlage


### POTX {#POTX}
```
public static final FileType POTX
```


Microsoft PowerPoint Vorlage


### POTM {#POTM}
```
public static final FileType POTM
```


Microsoft PowerPoint Vorlage mit Unterstützung für Makros


### PPS {#PPS}
```
public static final FileType PPS
```


Microsoft PowerPoint 97-2003 Diashow


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Microsoft PowerPoint Diashow


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Microsoft PowerPoint Präsentation


### PPT {#PPT}
```
public static final FileType PPT
```


Microsoft PowerPoint 97-2003 Präsentation


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Microsoft PowerPoint Makroaktivierte Präsentation


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Microsoft PowerPoint Makroaktivierte Diashow-Präsentation


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Visio Zeichnung


### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio 2003-2010 Zeichnung


### VSS {#VSS}
```
public static final FileType VSS
```


Microsoft Visio 2003-2010 Schablone


### VST {#VST}
```
public static final FileType VST
```


Microsoft Visio 2003-2010 Vorlage


### VDX {#VDX}
```
public static final FileType VDX
```


Microsoft Visio 2003-2010 XML-Zeichnung


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote Dokument


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Text


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Präsentation


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Präsentationsvorlage


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Tabellenkalkulation


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Textvorlage


### RTF {#RTF}
```
public static final FileType RTF
```


Rich-Text-Dokument


### TXT {#TXT}
```
public static final FileType TXT
```


Nur-Text-Dokument


### CSV {#CSV}
```
public static final FileType CSV
```


Kommagetrennte Werte-Datei


### HTML {#HTML}
```
public static final FileType HTML
```


HyperText-Markup-Sprache


### MHTML {#MHTML}
```
public static final FileType MHTML
```


Mime-HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket-E-Book-Format


### DCM {#DCM}
```
public static final FileType DCM
```


Digitale Bildgebung und Kommunikation in der Medizin


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Deja-Vu-Format


### DWG {#DWG}
```
public static final FileType DWG
```


Autodesk-Design-Datenformate


### DXF {#DXF}
```
public static final FileType DXF
```


AutoCAD-Zeichnungsaustausch


### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap-Bild


### GIF {#GIF}
```
public static final FileType GIF
```


Grafik-Austauschformat


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


Skalare Vektor-Grafiken


### EML {#EML}
```
public static final FileType EML
```


E-Mail-Nachricht


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail E-Mail-Datei


### MSG {#MSG}
```
public static final FileType MSG
```


Microsoft Outlook E-Mail-Nachricht


### CAD {#CAD}
```
public static final FileType CAD
```


CAD-Dateiformat


### CPP {#CPP}
```
public static final FileType CPP
```


C-basierter Programmiersprachenformat


### CC {#CC}
```
public static final FileType CC
```


C-basierter Programmiersprachenformat


### CXX {#CXX}
```
public static final FileType CXX
```


C-basierter Programmiersprachenformat


### HXX {#HXX}
```
public static final FileType HXX
```


Header-Dateien, die in der C++-Programmiersprache geschrieben sind


### HH {#HH}
```
public static final FileType HH
```


Header-Informationen, auf die von einer C++-Quelldatei verwiesen wird


### HPP {#HPP}
```
public static final FileType HPP
```


Header-Dateien, die in der C++-Programmiersprache geschrieben sind


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Werkzeug zur Verwaltung des Build-Prozesses von Software


### CS {#CS}
```
public static final FileType CS
```


CSharp-Programmiersprachenformat


### CSX {#CSX}
```
public static final FileType CSX
```


CSharp-Skriptdateiformat


### CAKE {#CAKE}
```
public static final FileType CAKE
```


CSharp-Plattformübergreifendes Build-Automatisierungssystem-Format


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Datenvergleichswerkzeug-Format


### PATCH {#PATCH}
```
public static final FileType PATCH
```


Format für Unterschiedsliste


### REJ {#REJ}
```
public static final FileType REJ
```


Format für abgelehnte Dateien


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Quellcodedatei im Groovy-Format


### GVY {#GVY}
```
public static final FileType GVY
```


Quellcodedatei im Groovy-Format


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


Build-Automatisierungssystem-Format


### HAML {#HAML}
```
public static final FileType HAML
```


Auszeichnungssprache zur vereinfachten HTML-Generierung


### JS {#JS}
```
public static final FileType JS
```


JavaScript-Programmiersprachen-Format


### ES6 {#ES6}
```
public static final FileType ES6
```


Standardisiertes Skriptsprachenformat für JavaScript


### MJS {#MJS}
```
public static final FileType MJS
```


Erweiterung für EcmaScript (ES)-Moduldateien


### PAC {#PAC}
```
public static final FileType PAC
```


Proxy-Auto-Configuration-Datei für JavaScript-Funktionsformat


### JSON {#JSON}
```
public static final FileType JSON
```


Leichtgewichtiges Format zum Speichern und Transportieren von Daten


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


Konfigurationsdatei für Paketverwaltung auf der Serverseite


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


JavaScript-Codequalitätswerkzeug


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


JavaScript-Konfigurationsdateiformat


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


Manifestdatei enthält Informationen über die Anwendung


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


JSON-Datei, die Informationen darüber enthält, wie Code zurück in Quellcode übersetzt wird


### HAR {#HAR}
```
public static final FileType HAR
```


Das HTTP-Archive-Format


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java-Programmiersprachen-Format


### LESS {#LESS}
```
public static final FileType LESS
```


Dynamisches Präprozessor-Stylesheet-Sprachformat


### LOG {#LOG}
```
public static final FileType LOG
```


Logging führt ein Register von Ereignissen, Prozessen, Nachrichten und Kommunikation


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile ist eine Datei, die eine Reihe von Anweisungen enthält, die von einem Make-Build-Automatisierungswerkzeug verwendet werden, um ein Ziel zu erzeugen


### MK {#MK}
```
public static final FileType MK
```


Makefile ist eine Datei, die eine Reihe von Anweisungen enthält, die von einem Make-Build-Automatisierungswerkzeug verwendet werden, um ein Ziel zu erzeugen


### MD {#MD}
```
public static final FileType MD
```


Markdown-Sprachformat


### MKD {#MKD}
```
public static final FileType MKD
```


Markdown-Sprachformat


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Markdown-Sprachformat


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Markdown-Sprachformat


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Markdown-Sprachformat


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Markdown-Sprachformat


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Markdown-Sprachformat


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Markdown-Sprachformat


### ML {#ML}
```
public static final FileType ML
```


Caml-Programmiersprachen-Format


### MLI {#MLI}
```
public static final FileType MLI
```


Caml-Programmiersprachen-Format


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Objective-C-Programmiersprachen-Format


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Objective-C++-Programmiersprachen-Format


### PHP {#PHP}
```
public static final FileType PHP
```


PHP-Programmiersprachen-Format


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


PHP-Programmiersprachen-Format


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


PHP-Programmiersprachen-Format


### PHTML {#PHTML}
```
public static final FileType PHTML
```


Standard-Dateierweiterung für PHP‑2‑Programme


### CTP {#CTP}
```
public static final FileType CTP
```


CakePHP-Vorlagenformat


### PL {#PL}
```
public static final FileType PL
```


Perl-Programmiersprachenformat


### PM {#PM}
```
public static final FileType PM
```


Perl-Modulformat


### POD {#POD}
```
public static final FileType POD
```


Perl-Leichtgewichts-Markup-Sprachformat


### T {#T}
```
public static final FileType T
```


Perl-Testdateiformat


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Schnittstelle zwischen Webservern und Webanwendungen sowie Frameworks, die in der Perl-Programmierung geschrieben wurden


### P6 {#P6}
```
public static final FileType P6
```


Perl-Programmiersprachenformat


### PL6 {#PL6}
```
public static final FileType PL6
```


Perl-Programmiersprachenformat


### PM6 {#PM6}
```
public static final FileType PM6
```


Perl-Modulformat


### NQP {#NQP}
```
public static final FileType NQP
```


Zwischensprache, die zum Erstellen des Rakuto Perl 6‑Compilers verwendet wird


### PROP {#PROP}
```
public static final FileType PROP
```


Properties-Dateiformat


### CFG {#CFG}
```
public static final FileType CFG
```


Konfigurationsdatei, die zum Speichern von Einstellungen verwendet wird


### CONF {#CONF}
```
public static final FileType CONF
```


Konfigurationsdatei, die auf Unix- und Linux-basierten Systemen verwendet wird


### DIR {#DIR}
```
public static final FileType DIR
```


Verzeichnis ist ein Ort zum Speichern von Dateien auf dem Computer


### PY {#PY}
```
public static final FileType PY
```


Python-Programmiersprachenformat


### RPY {#RPY}
```
public static final FileType RPY
```


Python-basierte Dateimotor zum Erstellen und Ausführen von Spielen


### PYW {#PYW}
```
public static final FileType PYW
```


Dateien, die in Windows verwendet werden, um anzuzeigen, dass ein Skript ausgeführt werden muss


### CPY {#CPY}
```
public static final FileType CPY
```


Controller-Python-Skriptformat


### GYP {#GYP}
```
public static final FileType GYP
```


Build-Automatisierungstool-Format


### GYPI {#GYPI}
```
public static final FileType GYPI
```


Build-Automatisierungstool-Format


### PYI {#PYI}
```
public static final FileType PYI
```


Python-Schnittstellendateiformat


### IPY {#IPY}
```
public static final FileType IPY
```


IPython-Skriptformat


### RST {#RST}
```
public static final FileType RST
```


Leichtgewichtige Auszeichnungssprache


### RB {#RB}
```
public static final FileType RB
```


Ruby-Programmiersprachenformat


### ERB {#ERB}
```
public static final FileType ERB
```


Ruby-Programmiersprachenformat


### RJS {#RJS}
```
public static final FileType RJS
```


Ruby-Programmiersprachenformat


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


Entwicklerdatei, die die Attribute eines RubyGems spezifiziert


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Ruby-Build-Automatisierungstool


### RU {#RU}
```
public static final FileType RU
```


Rack-Konfigurationsdateiformat


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Ruby-Build-Einstellungen-Format


### RBI {#RBI}
```
public static final FileType RBI
```


Ruby-Schnittstellendateiformat


### SASS {#SASS}
```
public static final FileType SASS
```


Stylesheet-Sprachformat


### SCSS {#SCSS}
```
public static final FileType SCSS
```


Stylesheet-Sprachformat


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala Programmiersprache Format


### SBT {#SBT}
```
public static final FileType SBT
```


SBT Build-Tool für Scala-Format


### SC {#SC}
```
public static final FileType SC
```


Scala-Arbeitsblatt-Format


### SH {#SH}
```
public static final FileType SH
```


Skript programmiert für bash-Format


### BASH {#BASH}
```
public static final FileType BASH
```


Typ des Interpreters, der Shell-Befehle verarbeitet


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


Datei bestimmt das Verhalten interaktiver Shells


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


Spezialisiertes bash-Skript, das die Kompilierungs- und Installationsvorgänge für Softwarepakete automatisiert


### SQL {#SQL}
```
public static final FileType SQL
```


Structured Query Language-Format


### DSQL {#DSQL}
```
public static final FileType DSQL
```


Dynamic Structured Query Language-Format


### VIM {#VIM}
```
public static final FileType VIM
```


Vim-Quellcodedatei-Format


### YAML {#YAML}
```
public static final FileType YAML
```


Menschlich lesbare Datenserialisierungs-Sprache-Format


### YML {#YML}
```
public static final FileType YML
```


Menschlich lesbare Datenserialisierungs-Sprache-Format


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


Gibt FileType basierend auf Dateiname oder Erweiterung zurück


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Dateiname oder Erweiterung, nicht null |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Ermittelt Liste der unterstützten Dateitypen


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - Liste von FileType

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


Prüft die Gleichheit der bereitgestellten Dateitypen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Linkes [FileType](../../com.groupdocs.comparison.result/filetype) Objekt. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Rechtes [FileType](../../com.groupdocs.comparison.result/filetype) Objekt. |
|

**Returns:**
boolean - true, wenn gleich, sonst false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


Prüft, ob die bereitgestellten Dateitypen nicht gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Linkes [FileType](../../com.groupdocs.comparison.result/filetype) Objekt. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Rechtes [FileType](../../com.groupdocs.comparison.result/filetype) Objekt. |
|

**Returns:**
boolean - true, wenn nicht gleich, sonst false

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


Ermittelt Textbeschreibung des Dateityps


**Returns:**
java.lang.String - Dateityp-Beschreibung

### getExtension() {#getExtension--}
```
public String getExtension()
```


Ermittelt die Erweiterung des Dateityps


**Returns:**
java.lang.String - Erweiterung des Dateityps

### toString() {#toString--}
```
public String toString()
```


Ermittelt die String-Darstellung von [FileType](../../com.groupdocs.comparison.result/filetype), zum Beispiel
'PHP Programmiersprache Format (.php)'



**Returns:**
java.lang.String - Zeichenkettenrepräsentation

