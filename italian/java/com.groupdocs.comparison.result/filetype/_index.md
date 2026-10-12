---
title: "FileType"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "L'enum FileType rappresenta il tipo di file utilizzato nel processo di confronto di documenti."
type: docs
weight: 16
url: /it/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

L'enum FileType rappresenta il tipo di file utilizzato nel processo di confronto di documenti.


Definisce diversi tipi di file come documenti Word, file PDF e altro.
Fornisce metodi per ottenere l'elenco di tutti i tipi di file supportati da GroupDocs.Comparison, rilevare il tipo di file per estensione ecc.
Utilizza questo enum per specificare il tipo di file quando lavori con la libreria GroupDocs.Comparison.

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


Esempio di utilizzo:

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


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Tipo sconosciuto |
|
|  | [AS](#AS) | Formato del linguaggio di programmazione ActionScript |
|
|  | [AS3](#AS3) | Formato del linguaggio di programmazione ActionScript |
|
|  | [ASM](#ASM) | Formato del linguaggio di programmazione Assembler |
|
|  | [BAT](#BAT) | File script in DOS, OS/2 e Microsoft Windows |
|
|  | [CMD](#CMD) | File script in DOS, OS/2 e Microsoft Windows |
|
|  | [C](#C) | Formato del linguaggio di programmazione basato su C |
|
|  | [H](#H) | I file header basati su C contengono definizioni di funzioni e variabili |
|
|  | [PDF](#PDF) | Formato Adobe Portable Document |
|
|  | [DOC](#DOC) | Documento Microsoft Word 97-2003 |
|
|  | [DOCM](#DOCM) | Documento Microsoft Word con macro abilitate |
|
|  | [DOCX](#DOCX) | Documento Microsoft Word |
|
|  | [DOT](#DOT) | Modello Microsoft Word 97-2003 |
|
|  | [DOTM](#DOTM) | Modello Microsoft Word con macro abilitate |
|
|  | [DOTX](#DOTX) | Modello Microsoft Word |
|
|  | [XLS](#XLS) | Foglio di lavoro Microsoft Excel 97-2003 |
|
|  | [XLT](#XLT) | Modello Microsoft Excel |
|
|  | [XLSX](#XLSX) | Foglio di lavoro Microsoft Excel |
|
|  | [XLTM](#XLTM) | Modello Microsoft Excel con macro abilitate |
|
|  | [XLSB](#XLSB) | Foglio di lavoro binario di Microsoft Excel |
|
|  | [XLSM](#XLSM) | Foglio di lavoro abilitato alle macro di Microsoft Excel |
|
|  | [POT](#POT) | Modello di Microsoft PowerPoint |
|
|  | [POTX](#POTX) | Modello di Microsoft PowerPoint |
|
|  | [POTM](#POTM) | Modello di Microsoft PowerPoint con supporto per macro |
|
|  | [PPS](#PPS) | Presentazione diapositive di Microsoft PowerPoint 97-2003 |
|
|  | [PPSX](#PPSX) | Presentazione diapositive di Microsoft PowerPoint |
|
|  | [PPTX](#PPTX) | Presentazione di Microsoft PowerPoint |
|
|  | [PPT](#PPT) | Presentazione di Microsoft PowerPoint 97-2003 |
|
|  | [PPTM](#PPTM) | Presentazione di Microsoft PowerPoint con macro abilitate |
|
|  | [PPSM](#PPSM) | Presentazione diapositive di Microsoft PowerPoint con macro abilitate |
|
|  | [VSDX](#VSDX) | Disegno di Microsoft Visio |
|
|  | [VSD](#VSD) | Disegno di Microsoft Visio 2003-2010 |
|
|  | [VSS](#VSS) | Stencil di Microsoft Visio 2003-2010 |
|
|  | [VST](#VST) | Modello di Microsoft Visio 2003-2010 |
|
|  | [VDX](#VDX) | Disegno XML di Microsoft Visio 2003-2010 |
|
|  | [ONE](#ONE) | Documento di Microsoft OneNote |
|
|  | [ODT](#ODT) | Testo OpenDocument |
|
|  | [ODP](#ODP) | Presentazione OpenDocument |
|
|  | [OTP](#OTP) | Modello di presentazione OpenDocument |
|
|  | [ODS](#ODS) | Foglio di calcolo OpenDocument |
|
|  | [OTT](#OTT) | Modello di testo OpenDocument |
|
|  | [RTF](#RTF) | Documento di testo formattato |
|
|  | [TXT](#TXT) | Documento di testo semplice |
|
|  | [CSV](#CSV) | File di valori separati da virgola |
|
|  | [HTML](#HTML) | Linguaggio di markup HyperText |
|
|  | [MHTML](#MHTML) | MIME HTML |
|
|  | [MOBI](#MOBI) | Formato e-book Mobipocket |
|
|  | [DCM](#DCM) | Imaging digitale e comunicazioni in medicina |
|
|  | [DJVU](#DJVU) | Formato Deja Vu |
|
|  | [DWG](#DWG) | Formati di dati di progettazione Autodesk |
|
|  | [DXF](#DXF) | Scambio disegni AutoCAD |
|
|  | [BMP](#BMP) | Immagine bitmap |
|
|  | [GIF](#GIF) | Formato di scambio grafico |
|
|  | [JPEG](#JPEG) | Joint Photographic Experts Group |
|
|  | [JPG](#JPG) | Joint Photographic Experts Group |
|
|  | [PNG](#PNG) | Portable Network Graphics |
|
|  | [SVG](#SVG) | Grafica vettoriale scalare |
|
|  | [EML](#EML) | Messaggio e-mail |
|
|  | [EMLX](#EMLX) | File e-mail Apple Mail |
|
|  | [MSG](#MSG) | Messaggio e-mail Microsoft Outlook |
|
|  | [CAD](#CAD) | Formato file CAD |
|
|  | [CPP](#CPP) | Formato del linguaggio di programmazione basato su C |
|
|  | [CC](#CC) | Formato del linguaggio di programmazione basato su C |
|
|  | [CXX](#CXX) | Formato del linguaggio di programmazione basato su C |
|
|  | [HXX](#HXX) | File header scritti nel linguaggio di programmazione C++ |
|
|  | [HH](#HH) | Informazioni header a cui fa riferimento un file di codice sorgente C++ |
|
|  | [HPP](#HPP) | File header scritti nel linguaggio di programmazione C++ |
|
|  | [CMAKE](#CMAKE) | Strumento per gestire il processo di compilazione del software |
|
|  | [CS](#CS) | Formato del linguaggio di programmazione CSharp |
|
|  | [CSX](#CSX) | Formato file script CSharp |
|
|  | [CAKE](#CAKE) | Formato del sistema di automazione di build cross-platform CSharp |
|
|  | [DIFF](#DIFF) | Formato dello strumento di confronto dati |
|
|  | [PATCH](#PATCH) | Formato elenco differenze |
|
|  | [REJ](#REJ) | Formato file rifiutati |
|
|  | [GROOVY](#GROOVY) | File di codice sorgente scritto in formato Groovy |
|
|  | [GVY](#GVY) | File di codice sorgente scritto in formato Groovy |
|
|  | [GRADLE](#GRADLE) | Formato del sistema di automazione della compilazione |
|
|  | [HAML](#HAML) | Linguaggio di markup per la generazione semplificata di HTML |
|
|  | [JS](#JS) | Formato del linguaggio di programmazione JavaScript |
|
|  | [ES6](#ES6) | Formato del linguaggio di scripting standardizzato JavaScript |
|
|  | [MJS](#MJS) | Estensione per file modulo EcmaScript (ES) |
|
|  | [PAC](#PAC) | File di configurazione automatica del proxy per il formato di funzione JavaScript |
|
|  | [JSON](#JSON) | Formato leggero per l'archiviazione e il trasporto dei dati |
|
|  | [BOWERRC](#BOWERRC) | File di configurazione per il controllo dei pacchetti lato server |
|
|  | [JSHINTRC](#JSHINTRC) | Strumento per la qualità del codice JavaScript |
|
|  | [JSCSRC](#JSCSRC) | Formato del file di configurazione JavaScript |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | Il file manifest include informazioni sull'app |
|
|  | [JSMAP](#JSMAP) | File JSON che contiene informazioni su come tradurre il codice di nuovo al codice sorgente |
|
|  | [HAR](#HAR) | Il formato HTTP Archive |
|
|  | [JAVA](#JAVA) | Formato del linguaggio di programmazione Java |
|
|  | [LESS](#LESS) | Formato del linguaggio di fogli di stile preprocessor dinamico |
|
|  | [LOG](#LOG) | Il logging mantiene un registro di eventi, processi, messaggi e comunicazioni |
|
|  | [MAKE](#MAKE) | Makefile è un file contenente un insieme di direttive utilizzate da uno strumento di automazione della compilazione make per generare un obiettivo/target |
|
|  | [MK](#MK) | Makefile è un file contenente un insieme di direttive utilizzate da uno strumento di automazione della compilazione make per generare un obiettivo/target |
|
|  | [MD](#MD) | Formato del linguaggio Markdown |
|
|  | [MKD](#MKD) | Formato del linguaggio Markdown |
|
|  | [MDWN](#MDWN) | Formato del linguaggio Markdown |
|
|  | [MDOWN](#MDOWN) | Formato del linguaggio Markdown |
|
|  | [MARKDOWN](#MARKDOWN) | Formato del linguaggio Markdown |
|
|  | [MARKDN](#MARKDN) | Formato del linguaggio Markdown |
|
|  | [MDTXT](#MDTXT) | Formato del linguaggio Markdown |
|
|  | [MDTEXT](#MDTEXT) | Formato del linguaggio Markdown |
|
|  | [ML](#ML) | Formato del linguaggio di programmazione Caml |
|
|  | [MLI](#MLI) | Formato del linguaggio di programmazione Caml |
|
|  | [OBJC](#OBJC) | Formato del linguaggio di programmazione Objective-C |
|
|  | [OBJCP](#OBJCP) | Formato del linguaggio di programmazione Objective-C++ |
|
|  | [PHP](#PHP) | Formato del linguaggio di programmazione PHP |
|
|  | [PHP4](#PHP4) | Formato del linguaggio di programmazione PHP |
|
|  | [PHP5](#PHP5) | Formato del linguaggio di programmazione PHP |
|
|  | [PHTML](#PHTML) | Formato dell'estensione file standard per programmi PHP 2 |
|
|  | [CTP](#CTP) | Formato del template CakePHP |
|
|  | [PL](#PL) | Formato del linguaggio di programmazione Perl |
|
|  | [PM](#PM) | Formato del modulo Perl |
|
|  | [POD](#POD) | Formato del linguaggio di markup leggero Perl |
|
|  | [T](#T) | Formato del file di test Perl |
|
|  | [PSGI](#PSGI) | Interfaccia tra server web e applicazioni web e framework scritti in Perl |
|
|  | [P6](#P6) | Formato del linguaggio di programmazione Perl |
|
|  | [PL6](#PL6) | Formato del linguaggio di programmazione Perl |
|
|  | [PM6](#PM6) | Formato del modulo Perl |
|
|  | [NQP](#NQP) | Linguaggio intermedio usato per costruire il compilatore Rakudo Perl 6 |
|
|  | [PROP](#PROP) | Formato del file di proprietà |
|
|  | [CFG](#CFG) | File di configurazione usato per memorizzare le impostazioni |
|
|  | [CONF](#CONF) | File di configurazione usato su sistemi basati su Unix e Linux |
|
|  | [DIR](#DIR) | Una directory è una posizione per memorizzare file sul computer |
|
|  | [PY](#PY) | Formato del linguaggio di programmazione Python |
|
|  | [RPY](#RPY) | Motore di file basato su Python per creare ed eseguire giochi |
|
|  | [PYW](#PYW) | File usati in Windows per indicare che uno script deve essere eseguito |
|
|  | [CPY](#CPY) | Formato dello script Python Controller |
|
|  | [GYP](#GYP) | Formato dello strumento di automazione della compilazione |
|
|  | [GYPI](#GYPI) | Formato dello strumento di automazione della compilazione |
|
|  | [PYI](#PYI) | Formato del file di interfaccia Python |
|
|  | [IPY](#IPY) | Formato dello script IPython |
|
|  | [RST](#RST) | Linguaggio di markup leggero |
|
|  | [RB](#RB) | Formato del linguaggio di programmazione Ruby |
|
|  | [ERB](#ERB) | Formato del linguaggio di programmazione Ruby |
|
|  | [RJS](#RJS) | Formato del linguaggio di programmazione Ruby |
|
|  | [GEMSPEC](#GEMSPEC) | File di sviluppo che specifica gli attributi di un RubyGems |
|
|  | [RAKE](#RAKE) | Strumento di automazione della compilazione Ruby |
|
|  | [RU](#RU) | Formato del file di configurazione Rack |
|
|  | [PODSPEC](#PODSPEC) | Formato delle impostazioni di compilazione Ruby |
|
|  | [RBI](#RBI) | Formato del file di interfaccia Ruby |
|
|  | [SASS](#SASS) | Formato del linguaggio di fogli di stile |
|
|  | [SCSS](#SCSS) | Formato del linguaggio di fogli di stile |
|
|  | [SCALA](#SCALA) | Formato del linguaggio di programmazione Scala |
|
|  | [SBT](#SBT) | Strumento di build SBT per il formato Scala |
|
|  | [SC](#SC) | Formato del foglio di lavoro Scala |
|
|  | [SH](#SH) | Script programmato per il formato bash |
|
|  | [BASH](#BASH) | Tipo di interprete che elabora i comandi della shell |
|
|  | [BASHRC](#BASHRC) | Il file determina il comportamento delle shell interattive |
|
|  | [EBUILD](#EBUILD) | Script bash specializzato che automatizza le procedure di compilazione e installazione per i pacchetti software |
|
|  | [SQL](#SQL) | Formato Structured Query Language |
|
|  | [DSQL](#DSQL) | Formato Dynamic Structured Query Language |
|
|  | [VIM](#VIM) | Formato file di codice sorgente Vim |
|
|  | [YAML](#YAML) | Formato del linguaggio di serializzazione dati leggibile dall'uomo |
|
|  | [YML](#YML) | Formato del linguaggio di serializzazione dati leggibile dall'uomo |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | Restituisce FileType in base al nome file o all'estensione |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Ottiene l'elenco dei tipi di file supportati |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Verifica l'uguaglianza dei tipi di file forniti |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Verifica che i tipi di file forniti non siano uguali |
|
|  | [getFileFormat()](#getFileFormat--) | Ottiene la descrizione testuale del tipo di file |
|
|  | [getExtension()](#getExtension--) | Ottiene l'estensione del tipo di file |
|
|  | [toString()](#toString--) | Ottiene la rappresentazione stringa di [FileType](../../com.groupdocs.comparison.result/filetype), ad esempio |
'Formato del linguaggio di programmazione PHP (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Tipo sconosciuto


### AS {#AS}
```
public static final FileType AS
```


Formato del linguaggio di programmazione ActionScript


### AS3 {#AS3}
```
public static final FileType AS3
```


Formato del linguaggio di programmazione ActionScript


### ASM {#ASM}
```
public static final FileType ASM
```


Formato del linguaggio di programmazione Assembler


### BAT {#BAT}
```
public static final FileType BAT
```


File script in DOS, OS/2 e Microsoft Windows


### CMD {#CMD}
```
public static final FileType CMD
```


File script in DOS, OS/2 e Microsoft Windows


### C {#C}
```
public static final FileType C
```


Formato del linguaggio di programmazione basato su C


### H {#H}
```
public static final FileType H
```


I file header basati su C contengono definizioni di funzioni e variabili


### PDF {#PDF}
```
public static final FileType PDF
```


Formato Adobe Portable Document


### DOC {#DOC}
```
public static final FileType DOC
```


Documento Microsoft Word 97-2003


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Documento Microsoft Word con macro abilitate


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Documento Microsoft Word


### DOT {#DOT}
```
public static final FileType DOT
```


Modello Microsoft Word 97-2003


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Modello Microsoft Word con macro abilitate


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Modello Microsoft Word


### XLS {#XLS}
```
public static final FileType XLS
```


Foglio di lavoro Microsoft Excel 97-2003


### XLT {#XLT}
```
public static final FileType XLT
```


Modello Microsoft Excel


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Foglio di lavoro Microsoft Excel


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Modello Microsoft Excel con macro abilitate


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Foglio di lavoro binario di Microsoft Excel


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Foglio di lavoro abilitato alle macro di Microsoft Excel


### POT {#POT}
```
public static final FileType POT
```


Modello di Microsoft PowerPoint


### POTX {#POTX}
```
public static final FileType POTX
```


Modello di Microsoft PowerPoint


### POTM {#POTM}
```
public static final FileType POTM
```


Modello di Microsoft PowerPoint con supporto per macro


### PPS {#PPS}
```
public static final FileType PPS
```


Presentazione diapositive di Microsoft PowerPoint 97-2003


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Presentazione diapositive di Microsoft PowerPoint


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Presentazione di Microsoft PowerPoint


### PPT {#PPT}
```
public static final FileType PPT
```


Presentazione di Microsoft PowerPoint 97-2003


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Presentazione di Microsoft PowerPoint con macro abilitate


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Presentazione diapositive di Microsoft PowerPoint con macro abilitate


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Disegno di Microsoft Visio


### VSD {#VSD}
```
public static final FileType VSD
```


Disegno di Microsoft Visio 2003-2010


### VSS {#VSS}
```
public static final FileType VSS
```


Stencil di Microsoft Visio 2003-2010


### VST {#VST}
```
public static final FileType VST
```


Modello di Microsoft Visio 2003-2010


### VDX {#VDX}
```
public static final FileType VDX
```


Disegno XML di Microsoft Visio 2003-2010


### ONE {#ONE}
```
public static final FileType ONE
```


Documento di Microsoft OneNote


### ODT {#ODT}
```
public static final FileType ODT
```


Testo OpenDocument


### ODP {#ODP}
```
public static final FileType ODP
```


Presentazione OpenDocument


### OTP {#OTP}
```
public static final FileType OTP
```


Modello di presentazione OpenDocument


### ODS {#ODS}
```
public static final FileType ODS
```


Foglio di calcolo OpenDocument


### OTT {#OTT}
```
public static final FileType OTT
```


Modello di testo OpenDocument


### RTF {#RTF}
```
public static final FileType RTF
```


Documento di testo formattato


### TXT {#TXT}
```
public static final FileType TXT
```


Documento di testo semplice


### CSV {#CSV}
```
public static final FileType CSV
```


File di valori separati da virgola


### HTML {#HTML}
```
public static final FileType HTML
```


Linguaggio di markup HyperText


### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Formato e-book Mobipocket


### DCM {#DCM}
```
public static final FileType DCM
```


Imaging digitale e comunicazioni in medicina


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Formato Deja Vu


### DWG {#DWG}
```
public static final FileType DWG
```


Formati di dati di progettazione Autodesk


### DXF {#DXF}
```
public static final FileType DXF
```


Scambio disegni AutoCAD


### BMP {#BMP}
```
public static final FileType BMP
```


Immagine bitmap


### GIF {#GIF}
```
public static final FileType GIF
```


Formato di scambio grafico


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


Grafica vettoriale scalare


### EML {#EML}
```
public static final FileType EML
```


Messaggio e-mail


### EMLX {#EMLX}
```
public static final FileType EMLX
```


File e-mail Apple Mail


### MSG {#MSG}
```
public static final FileType MSG
```


Messaggio e-mail Microsoft Outlook


### CAD {#CAD}
```
public static final FileType CAD
```


Formato file CAD


### CPP {#CPP}
```
public static final FileType CPP
```


Formato del linguaggio di programmazione basato su C


### CC {#CC}
```
public static final FileType CC
```


Formato del linguaggio di programmazione basato su C


### CXX {#CXX}
```
public static final FileType CXX
```


Formato del linguaggio di programmazione basato su C


### HXX {#HXX}
```
public static final FileType HXX
```


File header scritti nel linguaggio di programmazione C++


### HH {#HH}
```
public static final FileType HH
```


Informazioni header a cui fa riferimento un file di codice sorgente C++


### HPP {#HPP}
```
public static final FileType HPP
```


File header scritti nel linguaggio di programmazione C++


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Strumento per gestire il processo di compilazione del software


### CS {#CS}
```
public static final FileType CS
```


Formato del linguaggio di programmazione CSharp


### CSX {#CSX}
```
public static final FileType CSX
```


Formato file script CSharp


### CAKE {#CAKE}
```
public static final FileType CAKE
```


Formato del sistema di automazione di build cross-platform CSharp


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Formato dello strumento di confronto dati


### PATCH {#PATCH}
```
public static final FileType PATCH
```


Formato elenco differenze


### REJ {#REJ}
```
public static final FileType REJ
```


Formato file rifiutati


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


File di codice sorgente scritto in formato Groovy


### GVY {#GVY}
```
public static final FileType GVY
```


File di codice sorgente scritto in formato Groovy


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


Formato del sistema di automazione della compilazione


### HAML {#HAML}
```
public static final FileType HAML
```


Linguaggio di markup per la generazione semplificata di HTML


### JS {#JS}
```
public static final FileType JS
```


Formato del linguaggio di programmazione JavaScript


### ES6 {#ES6}
```
public static final FileType ES6
```


Formato del linguaggio di scripting standardizzato JavaScript


### MJS {#MJS}
```
public static final FileType MJS
```


Estensione per file modulo EcmaScript (ES)


### PAC {#PAC}
```
public static final FileType PAC
```


File di configurazione automatica del proxy per il formato di funzione JavaScript


### JSON {#JSON}
```
public static final FileType JSON
```


Formato leggero per l'archiviazione e il trasporto dei dati


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


File di configurazione per il controllo dei pacchetti lato server


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


Strumento per la qualità del codice JavaScript


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


Formato del file di configurazione JavaScript


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


Il file manifest include informazioni sull'app


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


File JSON che contiene informazioni su come tradurre il codice di nuovo al codice sorgente


### HAR {#HAR}
```
public static final FileType HAR
```


Il formato HTTP Archive


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Formato del linguaggio di programmazione Java


### LESS {#LESS}
```
public static final FileType LESS
```


Formato del linguaggio di fogli di stile preprocessor dinamico


### LOG {#LOG}
```
public static final FileType LOG
```


Il logging mantiene un registro di eventi, processi, messaggi e comunicazioni


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile è un file contenente un insieme di direttive utilizzate da uno strumento di automazione della compilazione make per generare un obiettivo/target


### MK {#MK}
```
public static final FileType MK
```


Makefile è un file contenente un insieme di direttive utilizzate da uno strumento di automazione della compilazione make per generare un obiettivo/target


### MD {#MD}
```
public static final FileType MD
```


Formato del linguaggio Markdown


### MKD {#MKD}
```
public static final FileType MKD
```


Formato del linguaggio Markdown


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Formato del linguaggio Markdown


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Formato del linguaggio Markdown


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Formato del linguaggio Markdown


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Formato del linguaggio Markdown


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Formato del linguaggio Markdown


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Formato del linguaggio Markdown


### ML {#ML}
```
public static final FileType ML
```


Formato del linguaggio di programmazione Caml


### MLI {#MLI}
```
public static final FileType MLI
```


Formato del linguaggio di programmazione Caml


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Formato del linguaggio di programmazione Objective-C


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Formato del linguaggio di programmazione Objective-C++


### PHP {#PHP}
```
public static final FileType PHP
```


Formato del linguaggio di programmazione PHP


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


Formato del linguaggio di programmazione PHP


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


Formato del linguaggio di programmazione PHP


### PHTML {#PHTML}
```
public static final FileType PHTML
```


Formato dell'estensione file standard per programmi PHP 2


### CTP {#CTP}
```
public static final FileType CTP
```


Formato del template CakePHP


### PL {#PL}
```
public static final FileType PL
```


Formato del linguaggio di programmazione Perl


### PM {#PM}
```
public static final FileType PM
```


Formato del modulo Perl


### POD {#POD}
```
public static final FileType POD
```


Formato del linguaggio di markup leggero Perl


### T {#T}
```
public static final FileType T
```


Formato del file di test Perl


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Interfaccia tra server web e applicazioni web e framework scritti in Perl


### P6 {#P6}
```
public static final FileType P6
```


Formato del linguaggio di programmazione Perl


### PL6 {#PL6}
```
public static final FileType PL6
```


Formato del linguaggio di programmazione Perl


### PM6 {#PM6}
```
public static final FileType PM6
```


Formato del modulo Perl


### NQP {#NQP}
```
public static final FileType NQP
```


Linguaggio intermedio usato per costruire il compilatore Rakudo Perl 6


### PROP {#PROP}
```
public static final FileType PROP
```


Formato del file di proprietà


### CFG {#CFG}
```
public static final FileType CFG
```


File di configurazione usato per memorizzare le impostazioni


### CONF {#CONF}
```
public static final FileType CONF
```


File di configurazione usato su sistemi basati su Unix e Linux


### DIR {#DIR}
```
public static final FileType DIR
```


Una directory è una posizione per memorizzare file sul computer


### PY {#PY}
```
public static final FileType PY
```


Formato del linguaggio di programmazione Python


### RPY {#RPY}
```
public static final FileType RPY
```


Motore di file basato su Python per creare ed eseguire giochi


### PYW {#PYW}
```
public static final FileType PYW
```


File usati in Windows per indicare che uno script deve essere eseguito


### CPY {#CPY}
```
public static final FileType CPY
```


Formato dello script Python Controller


### GYP {#GYP}
```
public static final FileType GYP
```


Formato dello strumento di automazione della compilazione


### GYPI {#GYPI}
```
public static final FileType GYPI
```


Formato dello strumento di automazione della compilazione


### PYI {#PYI}
```
public static final FileType PYI
```


Formato del file di interfaccia Python


### IPY {#IPY}
```
public static final FileType IPY
```


Formato dello script IPython


### RST {#RST}
```
public static final FileType RST
```


Linguaggio di markup leggero


### RB {#RB}
```
public static final FileType RB
```


Formato del linguaggio di programmazione Ruby


### ERB {#ERB}
```
public static final FileType ERB
```


Formato del linguaggio di programmazione Ruby


### RJS {#RJS}
```
public static final FileType RJS
```


Formato del linguaggio di programmazione Ruby


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


File di sviluppo che specifica gli attributi di un RubyGems


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Strumento di automazione della compilazione Ruby


### RU {#RU}
```
public static final FileType RU
```


Formato del file di configurazione Rack


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Formato delle impostazioni di compilazione Ruby


### RBI {#RBI}
```
public static final FileType RBI
```


Formato del file di interfaccia Ruby


### SASS {#SASS}
```
public static final FileType SASS
```


Formato del linguaggio di fogli di stile


### SCSS {#SCSS}
```
public static final FileType SCSS
```


Formato del linguaggio di fogli di stile


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Formato del linguaggio di programmazione Scala


### SBT {#SBT}
```
public static final FileType SBT
```


Strumento di build SBT per il formato Scala


### SC {#SC}
```
public static final FileType SC
```


Formato del foglio di lavoro Scala


### SH {#SH}
```
public static final FileType SH
```


Script programmato per il formato bash


### BASH {#BASH}
```
public static final FileType BASH
```


Tipo di interprete che elabora i comandi della shell


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


Il file determina il comportamento delle shell interattive


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


Script bash specializzato che automatizza le procedure di compilazione e installazione per i pacchetti software


### SQL {#SQL}
```
public static final FileType SQL
```


Formato Structured Query Language


### DSQL {#DSQL}
```
public static final FileType DSQL
```


Formato Dynamic Structured Query Language


### VIM {#VIM}
```
public static final FileType VIM
```


Formato file di codice sorgente Vim


### YAML {#YAML}
```
public static final FileType YAML
```


Formato del linguaggio di serializzazione dati leggibile dall'uomo


### YML {#YML}
```
public static final FileType YML
```


Formato del linguaggio di serializzazione dati leggibile dall'uomo


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


Restituisce FileType in base al nome file o all'estensione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Nome file o estensione, non nullo |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Ottiene l'elenco dei tipi di file supportati


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - elenco di FileType

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


Verifica l'uguaglianza dei tipi di file forniti


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Oggetto [FileType](../../com.groupdocs.comparison.result/filetype) sinistro. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Oggetto [FileType](../../com.groupdocs.comparison.result/filetype) destro. |
|

**Returns:**
boolean - true se uguale, altrimenti false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


Verifica che i tipi di file forniti non siano uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Oggetto [FileType](../../com.groupdocs.comparison.result/filetype) sinistro. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Oggetto [FileType](../../com.groupdocs.comparison.result/filetype) destro. |
|

**Returns:**
boolean - true se non è uguale, altrimenti false

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


Ottiene la descrizione testuale del tipo di file


**Returns:**
java.lang.String - descrizione del tipo di file

### getExtension() {#getExtension--}
```
public String getExtension()
```


Ottiene l'estensione del tipo di file


**Returns:**
java.lang.String - estensione del tipo di file

### toString() {#toString--}
```
public String toString()
```


Ottiene la rappresentazione stringa di [FileType](../../com.groupdocs.comparison.result/filetype), ad esempio
'Formato del linguaggio di programmazione PHP (.php)'



**Returns:**
java.lang.String - rappresentazione della stringa

