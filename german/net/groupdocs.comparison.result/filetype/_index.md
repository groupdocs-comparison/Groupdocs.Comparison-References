---
title: "FileType"
second_title: "GroupDocs.Comparison für .NET API-Referenz"
description: "Stellt den Dateityp dar. Bietet Methoden, um eine Liste aller von GroupDocs.Comparison unterstützten Dateitypen zu erhalten, den Dateityp anhand der Erweiterung zu erkennen usw."
type: docs
weight: 480
url: /de/net/groupdocs.comparison.result/filetype/
---
## FileType class

Stellt den Dateityp dar. Bietet Methoden, um eine Liste aller von GroupDocs.Comparison unterstützten Dateitypen zu erhalten, den Dateityp anhand der Erweiterung zu erkennen usw.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.comparison.result/filetype/extension) { get; } | Dateierweiterung |
| [FileFormat](../../groupdocs.comparison.result/filetype/fileformat) { get; } | Dateiformat |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.comparison.result/filetype/fromfilenameorextension)(string) | Dateityp basierend auf Dateiname oder Erweiterung zurückgeben |
| [Equals](../../groupdocs.comparison.result/filetype/equals#equals)(FileType) | Überprüfung der Dateityp-Äquivalenz |
| override [Equals](../../groupdocs.comparison.result/filetype/equals#equals_1)(object) | Äquivalenzprüfung mit Objekt |
| override [GetHashCode](../../groupdocs.comparison.result/filetype/gethashcode)() | Hashcode ermitteln |
| override [ToString](../../groupdocs.comparison.result/filetype/tostring)() | ToString |
| static [GetSupportedFileTypes](../../groupdocs.comparison.result/filetype/getsupportedfiletypes)() | Aufzählung der unterstützten Dateitypen abrufen |
| [operator ==](../../groupdocs.comparison.result/filetype/op_equality) | Operatorüberladung |
| [operator !=](../../groupdocs.comparison.result/filetype/op_inequality) | Operatorüberladung |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [AS](../../groupdocs.comparison.result/filetype/as) | ActionScript-Programmiersprachenformat |
| static readonly [AS3](../../groupdocs.comparison.result/filetype/as3) | ActionScript-Programmiersprachenformat |
| static readonly [ASM](../../groupdocs.comparison.result/filetype/asm) | ASM-Format |
| static readonly [BASH](../../groupdocs.comparison.result/filetype/bash) | Typ des Interpreters, der Shell-Befehle verarbeitet |
| static readonly [BASHRC](../../groupdocs.comparison.result/filetype/bashrc) | Datei bestimmt das Verhalten interaktiver Shells |
| static readonly [BAT](../../groupdocs.comparison.result/filetype/bat) | Skriptdatei in DOS, OS/2 und Microsoft Windows |
| static readonly [BMP](../../groupdocs.comparison.result/filetype/bmp) | Bitmap-Bild |
| static readonly [BOWERRC](../../groupdocs.comparison.result/filetype/bowerrc) | Konfigurationsdatei für die Paketverwaltung auf der Serverseite |
| static readonly [C](../../groupdocs.comparison.result/filetype/c) | C-basierte Programmiersprachenformat |
| static readonly [CAD](../../groupdocs.comparison.result/filetype/cad) | CAD-Dateiformat |
| static readonly [CAKE](../../groupdocs.comparison.result/filetype/cake) | CSharp plattformübergreifendes Build-Automatisierungssystem-Format |
| static readonly [CC](../../groupdocs.comparison.result/filetype/cc) | C-basierte Programmiersprachenformat |
| static readonly [CFG](../../groupdocs.comparison.result/filetype/cfg) | Konfigurationsdatei zum Speichern von Einstellungen |
| static readonly [CMAKE](../../groupdocs.comparison.result/filetype/cmake) | Werkzeug zur Verwaltung des Build-Prozesses von Software |
| static readonly [CMD](../../groupdocs.comparison.result/filetype/cmd) | Skriptdatei in DOS, OS/2 und Microsoft Windows |
| static readonly [CONF](../../groupdocs.comparison.result/filetype/conf) | Konfigurationsdatei, die auf Unix- und Linux-basierten Systemen verwendet wird |
| static readonly [CPP](../../groupdocs.comparison.result/filetype/cpp) | C-basierte Programmiersprachenformat |
| static readonly [CPY](../../groupdocs.comparison.result/filetype/cpy) | Controller-Python-Skriptformat |
| static readonly [CS](../../groupdocs.comparison.result/filetype/cs) | CSharp-Programmiersprachenformat |
| static readonly [CSV](../../groupdocs.comparison.result/filetype/csv) | Kommagetrennte Werte-Datei |
| static readonly [CSX](../../groupdocs.comparison.result/filetype/csx) | CSharp-Skriptdateiformat |
| static readonly [CTP](../../groupdocs.comparison.result/filetype/ctp) | CakePHP-Vorlagenformat |
| static readonly [CXX](../../groupdocs.comparison.result/filetype/cxx) | C-basierte Programmiersprachenformat |
| static readonly [DCM](../../groupdocs.comparison.result/filetype/dcm) | Digitale Bildgebung und Kommunikation in der Medizin |
| static readonly [DIFF](../../groupdocs.comparison.result/filetype/diff) | Datenvergleichswerkzeug-Format |
| static readonly [DIR](../../groupdocs.comparison.result/filetype/dir) | Verzeichnis ist ein Ort zum Speichern von Dateien auf dem Computer |
| static readonly [DJVU](../../groupdocs.comparison.result/filetype/djvu) | Deja Vu-Format |
| static readonly [DOC](../../groupdocs.comparison.result/filetype/doc) | Microsoft Word 97-2003-Dokument |
| static readonly [DOCM](../../groupdocs.comparison.result/filetype/docm) | Microsoft Word Makro-aktiviertes Dokument |
| static readonly [DOCX](../../groupdocs.comparison.result/filetype/docx) | Microsoft Word Dokument |
| static readonly [DOT](../../groupdocs.comparison.result/filetype/dot) | Microsoft Word 97-2003-Vorlage |
| static readonly [DOTM](../../groupdocs.comparison.result/filetype/dotm) | Microsoft Word Makro-aktivierte Vorlage |
| static readonly [DOTX](../../groupdocs.comparison.result/filetype/dotx) | Microsoft Word Vorlage |
| static readonly [DSQL](../../groupdocs.comparison.result/filetype/dsql) | Dynamisches Structured Query Language-Format |
| static readonly [DWG](../../groupdocs.comparison.result/filetype/dwg) | Autodesk Design-Datenformate |
| static readonly [DXF](../../groupdocs.comparison.result/filetype/dxf) | AutoCAD-Zeichnungsaustausch |
| static readonly [EBUILD](../../groupdocs.comparison.result/filetype/ebuild) | Spezialisiertes Bash-Skript, das die Kompilierungs- und Installationsvorgänge für Softwarepakete automatisiert |
| static readonly [EML](../../groupdocs.comparison.result/filetype/eml) | E-Mail-Nachricht |
| static readonly [EMLX](../../groupdocs.comparison.result/filetype/emlx) | Apple Mail E-Mail-Datei |
| static readonly [ERB](../../groupdocs.comparison.result/filetype/erb) | Ruby-Programmiersprachenformat |
| static readonly [ES6](../../groupdocs.comparison.result/filetype/es6) | JavaScript standardisiertes Skriptsprachenformat |
| static readonly [GEMSPEC](../../groupdocs.comparison.result/filetype/gemspec) | Entwicklerdatei, die die Attribute eines RubyGems angibt |
| static readonly [GIF](../../groupdocs.comparison.result/filetype/gif) | Graphics Interchange Format |
| static readonly [GRADLE](../../groupdocs.comparison.result/filetype/gradle) | Build-Automation-Systemformat |
| static readonly [GROOVY](../../groupdocs.comparison.result/filetype/groovy) | Quellcodedatei, die im Groovy-Format geschrieben ist |
| static readonly [GVY](../../groupdocs.comparison.result/filetype/gvy) | Quellcodedatei, die im Groovy-Format geschrieben ist |
| static readonly [GYP](../../groupdocs.comparison.result/filetype/gyp) | Build-Automation-Werkzeugformat |
| static readonly [GYPI](../../groupdocs.comparison.result/filetype/gypi) | Build-Automation-Werkzeugformat |
| static readonly [H](../../groupdocs.comparison.result/filetype/h) | C-basierte Header-Dateien enthalten Definitionen von Funktionen und Variablen |
| static readonly [HAML](../../groupdocs.comparison.result/filetype/haml) | Markup-Sprache für vereinfachte HTML-Generierung |
| static readonly [HAR](../../groupdocs.comparison.result/filetype/har) | Das HTTP-Archivformat |
| static readonly [HH](../../groupdocs.comparison.result/filetype/hh) | Header-Informationen, auf die von einer C++-Quellcodedatei verwiesen wird |
| static readonly [HPP](../../groupdocs.comparison.result/filetype/hpp) | Header-Dateien, die in der Programmiersprache C++ geschrieben sind |
| static readonly [HTML](../../groupdocs.comparison.result/filetype/html) | HyperText-Markup-Sprache |
| static readonly [HXX](../../groupdocs.comparison.result/filetype/hxx) | Header-Dateien, die in der Programmiersprache C++ geschrieben sind |
| static readonly [IPY](../../groupdocs.comparison.result/filetype/ipy) | IPython-Skriptformat |
| static readonly [JAVA](../../groupdocs.comparison.result/filetype/java) | Java-Programmiersprachenformat |
| static readonly [JPEG](../../groupdocs.comparison.result/filetype/jpeg) | Joint Photographic Experts Group |
| static readonly [JS](../../groupdocs.comparison.result/filetype/js) | JavaScript-Programmiersprachenformat |
| static readonly [JSCSRC](../../groupdocs.comparison.result/filetype/jscsrc) | JavaScript-Konfigurationsdateiformat |
| static readonly [JSHINTRC](../../groupdocs.comparison.result/filetype/jshintrc) | JavaScript-Codequalitätswerkzeug |
| static readonly [JSMAP](../../groupdocs.comparison.result/filetype/jsmap) | JSON-Datei, die Informationen darüber enthält, wie Code zurück in Quellcode übersetzt wird |
| static readonly [JSON](../../groupdocs.comparison.result/filetype/json) | Leichtgewichtiges Format zum Speichern und Transportieren von Daten |
| static readonly [LESS](../../groupdocs.comparison.result/filetype/less) | Dynamisches Präprozessor-Stylesheet-Sprachformat |
| static readonly [LOG](../../groupdocs.comparison.result/filetype/log) | Logging führt ein Register von Ereignissen, Prozessen, Nachrichten und Kommunikation |
| static readonly [MAKE](../../groupdocs.comparison.result/filetype/make) | Makefile ist eine Datei, die eine Menge von Direktiven enthält, die von einem Make-Build-Automatisierungstool verwendet werden, um ein Ziel zu erzeugen |
| static readonly [MARKDN](../../groupdocs.comparison.result/filetype/markdn) | Markdown-Sprachformat |
| static readonly [MARKDOWN](../../groupdocs.comparison.result/filetype/markdown) | Markdown-Sprachformat |
| static readonly [MD](../../groupdocs.comparison.result/filetype/md) | Markdown-Sprachformat |
| static readonly [MDOWN](../../groupdocs.comparison.result/filetype/mdown) | Markdown-Sprachformat |
| static readonly [MDTEXT](../../groupdocs.comparison.result/filetype/mdtext) | Markdown-Sprachformat |
| static readonly [MDTXT](../../groupdocs.comparison.result/filetype/mdtxt) | Markdown-Sprachformat |
| static readonly [MDWN](../../groupdocs.comparison.result/filetype/mdwn) | Markdown-Sprachformat |
| static readonly [MHTML](../../groupdocs.comparison.result/filetype/mhtml) | Mime HTML |
| static readonly [MJS](../../groupdocs.comparison.result/filetype/mjs) | Erweiterung für EcmaScript (ES)-Moduldateien |
| static readonly [MK](../../groupdocs.comparison.result/filetype/mk) | Makefile ist eine Datei, die eine Menge von Direktiven enthält, die von einem Make-Build-Automatisierungstool verwendet werden, um ein Ziel zu erzeugen |
| static readonly [MKD](../../groupdocs.comparison.result/filetype/mkd) | Markdown-Sprachformat |
| static readonly [ML](../../groupdocs.comparison.result/filetype/ml) | Caml-Programmiersprachenformat |
| static readonly [MLI](../../groupdocs.comparison.result/filetype/mli) | Caml-Programmiersprachenformat |
| static readonly [MOBI](../../groupdocs.comparison.result/filetype/mobi) | Mobipocket-E-Book-Format |
| static readonly [MSG](../../groupdocs.comparison.result/filetype/msg) | Microsoft Outlook-E-Mail-Nachricht |
| static readonly [NQP](../../groupdocs.comparison.result/filetype/nqp) | Zwischensprache, die zum Erstellen des Rakudo Perl 6-Compilers verwendet wird |
| static readonly [OBJC](../../groupdocs.comparison.result/filetype/objc) | Objective‑C-Programmiersprachenformat |
| static readonly [OBJCP](../../groupdocs.comparison.result/filetype/objcp) | Objective‑C++-Programmiersprachenformat |
| static readonly [ODP](../../groupdocs.comparison.result/filetype/odp) | OpenDocument-Präsentation |
| static readonly [ODS](../../groupdocs.comparison.result/filetype/ods) | OpenDocument-Tabellenkalkulation |
| static readonly [ODT](../../groupdocs.comparison.result/filetype/odt) | OpenDocument-Text |
| static readonly [ONE](../../groupdocs.comparison.result/filetype/one) | Microsoft OneNote-Dokument |
| static readonly [OTP](../../groupdocs.comparison.result/filetype/otp) | OpenDocument-Präsentationsvorlage |
| static readonly [OTT](../../groupdocs.comparison.result/filetype/ott) | OpenDocument-Textvorlage |
| static readonly [P6](../../groupdocs.comparison.result/filetype/p6) | Perl-Programmiersprache-Format |
| static readonly [PAC](../../groupdocs.comparison.result/filetype/pac) | Proxy Auto-Configuration-Datei für JavaScript-Funktionsformat |
| static readonly [PATCH](../../groupdocs.comparison.result/filetype/patch) | Liste-der-Unterschiede-Format |
| static readonly [PDF](../../groupdocs.comparison.result/filetype/pdf) | Adobe Portable Document-Format |
| static readonly [PHP](../../groupdocs.comparison.result/filetype/php) | PHP-Programmiersprache-Format |
| static readonly [PHP4](../../groupdocs.comparison.result/filetype/php4) | PHP-Programmiersprache-Format |
| static readonly [PHP5](../../groupdocs.comparison.result/filetype/php5) | PHP-Programmiersprache-Format |
| static readonly [PHTML](../../groupdocs.comparison.result/filetype/phtml) | Standard-Dateierweiterung für PHP 2-Programme-Format |
| static readonly [PL](../../groupdocs.comparison.result/filetype/pl) | Perl-Programmiersprache-Format |
| static readonly [PL6](../../groupdocs.comparison.result/filetype/pl6) | Perl-Programmiersprache-Format |
| static readonly [PM](../../groupdocs.comparison.result/filetype/pm) | Perl-Modul-Format |
| static readonly [PM6](../../groupdocs.comparison.result/filetype/pm6) | Perl-Modul-Format |
| static readonly [PNG](../../groupdocs.comparison.result/filetype/png) | Portable Network Graphics |
| static readonly [POD](../../groupdocs.comparison.result/filetype/pod) | Perl-leichtgewichtige Auszeichnungssprache-Format |
| static readonly [PODSPEC](../../groupdocs.comparison.result/filetype/podspec) | Ruby-Build-Einstellungen-Format |
| static readonly [POT](../../groupdocs.comparison.result/filetype/pot) | Microsoft PowerPoint-Vorlage |
| static readonly [POTX](../../groupdocs.comparison.result/filetype/potx) | Microsoft PowerPoint-Vorlage |
| static readonly [PPS](../../groupdocs.comparison.result/filetype/pps) | Microsoft PowerPoint 97-2003-Folienpräsentation |
| static readonly [PPSX](../../groupdocs.comparison.result/filetype/ppsx) | Microsoft PowerPoint-Folienpräsentation |
| static readonly [PPT](../../groupdocs.comparison.result/filetype/ppt) | Microsoft PowerPoint 97-2003-Präsentation |
| static readonly [PPTX](../../groupdocs.comparison.result/filetype/pptx) | Microsoft PowerPoint-Präsentation |
| static readonly [PROP](../../groupdocs.comparison.result/filetype/prop) | Properties-Dateiformat |
| static readonly [PSGI](../../groupdocs.comparison.result/filetype/psgi) | Schnittstelle zwischen Webservern und Webanwendungen und -Frameworks, die in der Perl-Programmierung geschrieben sind |
| static readonly [PY](../../groupdocs.comparison.result/filetype/py) | Python-Programmiersprache-Format |
| static readonly [PYI](../../groupdocs.comparison.result/filetype/pyi) | Python Schnittstellen-Dateiformat |
| static readonly [PYW](../../groupdocs.comparison.result/filetype/pyw) | Dateien, die in Windows verwendet werden, um anzuzeigen, dass ein Skript ausgeführt werden muss |
| static readonly [RAKE](../../groupdocs.comparison.result/filetype/rake) | Ruby Build-Automatisierungstool |
| static readonly [RB](../../groupdocs.comparison.result/filetype/rb) | Ruby-Programmiersprachenformat |
| static readonly [RBI](../../groupdocs.comparison.result/filetype/rbi) | Ruby Schnittstellen-Dateiformat |
| static readonly [REJ](../../groupdocs.comparison.result/filetype/rej) | Format abgelehnter Dateien |
| static readonly [RJS](../../groupdocs.comparison.result/filetype/rjs) | Ruby-Programmiersprachenformat |
| static readonly [RPY](../../groupdocs.comparison.result/filetype/rpy) | Python-basierte Datei-Engine zum Erstellen und Ausführen von Spielen |
| static readonly [RST](../../groupdocs.comparison.result/filetype/rst) | Leichte Auszeichnungssprache |
| static readonly [RTF](../../groupdocs.comparison.result/filetype/rtf) | Rich-Text-Dokument |
| static readonly [RU](../../groupdocs.comparison.result/filetype/ru) | Rack-Konfigurationsdateiformat |
| static readonly [SASS](../../groupdocs.comparison.result/filetype/sass) | Format der Stylesheet-Sprache |
| static readonly [SBT](../../groupdocs.comparison.result/filetype/sbt) | SBT-Build-Tool für Scala-Format |
| static readonly [SC](../../groupdocs.comparison.result/filetype/sc) | Scala-Arbeitsblattformat |
| static readonly [SCALA](../../groupdocs.comparison.result/filetype/scala) | Format der Scala-Programmiersprache |
| static readonly [SCSS](../../groupdocs.comparison.result/filetype/scss) | Format der Stylesheet-Sprache |
| static readonly [SH](../../groupdocs.comparison.result/filetype/sh) | Für bash programmiertes Skriptformat |
| static readonly [SQL](../../groupdocs.comparison.result/filetype/sql) | Structured Query Language-Format |
| static readonly [SVG](../../groupdocs.comparison.result/filetype/svg) | Scalar Vector Graphics |
| static readonly [T](../../groupdocs.comparison.result/filetype/t) | Perl-Testdateiformat |
| static readonly [TXT](../../groupdocs.comparison.result/filetype/txt) | Klartextdokument |
| static readonly [UNKNOWN](../../groupdocs.comparison.result/filetype/unknown) | Unbekannter Typ |
| static readonly [VDX](../../groupdocs.comparison.result/filetype/vdx) | Microsoft Visio 2003-2010 XML-Zeichnung |
| static readonly [VIM](../../groupdocs.comparison.result/filetype/vim) | Vim-Quellcodedateiformat |
| static readonly [VSD](../../groupdocs.comparison.result/filetype/vsd) | Microsoft Visio 2003-2010 Zeichnung |
| static readonly [VSDX](../../groupdocs.comparison.result/filetype/vsdx) | Microsoft Visio Zeichnung |
| static readonly [VSS](../../groupdocs.comparison.result/filetype/vss) | Microsoft Visio 2003-2010 Schablone |
| static readonly [VST](../../groupdocs.comparison.result/filetype/vst) | Microsoft Visio 2003-2010 Vorlage |
| static readonly [WEBMANIFEST](../../groupdocs.comparison.result/filetype/webmanifest) | Manifestdatei enthält Informationen über die App |
| static readonly [XLS](../../groupdocs.comparison.result/filetype/xls) | Microsoft Excel 97-2003-Arbeitsblatt |
| static readonly [XLSB](../../groupdocs.comparison.result/filetype/xlsb) | Microsoft Excel Binäres Arbeitsblatt |
| static readonly [XLSM](../../groupdocs.comparison.result/filetype/xlsm) | Microsoft Excel Makroaktiviertes Arbeitsblatt |
| static readonly [XLSX](../../groupdocs.comparison.result/filetype/xlsx) | Microsoft Excel Arbeitsblatt |
| static readonly [XLT](../../groupdocs.comparison.result/filetype/xlt) | Microsoft Excel Vorlage |
| static readonly [XLTM](../../groupdocs.comparison.result/filetype/xltm) | Microsoft Excel makroaktivierte Vorlage |
| static readonly [YAML](../../groupdocs.comparison.result/filetype/yaml) | Menschenlesbares Datenserialisierungs‑Sprachformat |
| static readonly [YML](../../groupdocs.comparison.result/filetype/yml) | Menschenlesbares Datenserialisierungs‑Sprachformat |

### Bemerkungen

**Learn more**

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* Learn more about getting supported file types in C#: [How to get supported file formats in C#](https://docs.groupdocs.com/display/comparisonnet/Get+supported+file+formats)

### Siehe auch

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.Comparison.dll -->
