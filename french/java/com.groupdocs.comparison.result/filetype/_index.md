---
title: "FileType"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "L'énumération FileType représente le type de fichier utilisé dans le processus de comparaison de documents."
type: docs
weight: 16
url: /fr/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

L'énumération FileType représente le type de fichier utilisé dans le processus de comparaison de documents.


Il définit différents types de fichiers tels que les documents Word, les fichiers PDF, et plus encore.
Fournit des méthodes pour obtenir la liste de tous les types de fichiers pris en charge par GroupDocs.Comparison, détecter le type de fichier par extension, etc.
Utilisez cette énumération pour spécifier le type de fichier lors de l'utilisation de la bibliothèque GroupDocs.Comparison.

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


Exemple d'utilisation :

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


## Champs

| Champ | Description |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Type inconnu |
|
|  | [AS](#AS) | format du langage de programmation ActionScript |
|
|  | [AS3](#AS3) | format du langage de programmation ActionScript |
|
|  | [ASM](#ASM) | format du langage de programmation Assembleur |
|
|  | [BAT](#BAT) | Fichier script sous DOS, OS/2 et Microsoft Windows |
|
|  | [CMD](#CMD) | Fichier script sous DOS, OS/2 et Microsoft Windows |
|
|  | [C](#C) | format du langage de programmation basé sur C |
|
|  | [H](#H) | Les fichiers d'en-tête basés sur C contiennent des définitions de Functions et de Variables |
|
|  | [PDF](#PDF) | format Adobe Portable Document |
|
|  | [DOC](#DOC) | Document Microsoft Word 97-2003 |
|
|  | [DOCM](#DOCM) | Document Microsoft Word avec macros activées |
|
|  | [DOCX](#DOCX) | Document Microsoft Word |
|
|  | [DOT](#DOT) | Modèle Microsoft Word 97-2003 |
|
|  | [DOTM](#DOTM) | Modèle Microsoft Word avec macros activées |
|
|  | [DOTX](#DOTX) | Modèle Microsoft Word |
|
|  | [XLS](#XLS) | Feuille de calcul Microsoft Excel 97-2003 |
|
|  | [XLT](#XLT) | Modèle Microsoft Excel |
|
|  | [XLSX](#XLSX) | Feuille de calcul Microsoft Excel |
|
|  | [XLTM](#XLTM) | Modèle Microsoft Excel avec macros activées |
|
|  | [XLSB](#XLSB) | Feuille de calcul binaire Microsoft Excel |
|
|  | [XLSM](#XLSM) | Feuille de calcul Microsoft Excel avec macros activées |
|
|  | [POT](#POT) | Modèle Microsoft PowerPoint |
|
|  | [POTX](#POTX) | Modèle Microsoft PowerPoint |
|
|  | [POTM](#POTM) | Modèle Microsoft PowerPoint avec prise en charge des macros |
|
|  | [PPS](#PPS) | Diaporama Microsoft PowerPoint 97-2003 |
|
|  | [PPSX](#PPSX) | Diaporama Microsoft PowerPoint |
|
|  | [PPTX](#PPTX) | Présentation Microsoft PowerPoint |
|
|  | [PPT](#PPT) | Présentation Microsoft PowerPoint 97-2003 |
|
|  | [PPTM](#PPTM) | Présentation Microsoft PowerPoint avec macros activées |
|
|  | [PPSM](#PPSM) | Diaporama de présentation Microsoft PowerPoint avec macros activées |
|
|  | [VSDX](#VSDX) | Dessin Microsoft Visio |
|
|  | [VSD](#VSD) | Dessin Microsoft Visio 2003-2010 |
|
|  | [VSS](#VSS) | Pochoir Microsoft Visio 2003-2010 |
|
|  | [VST](#VST) | Modèle Microsoft Visio 2003-2010 |
|
|  | [VDX](#VDX) | Dessin XML Microsoft Visio 2003-2010 |
|
|  | [ONE](#ONE) | Document Microsoft OneNote |
|
|  | [ODT](#ODT) | Texte OpenDocument |
|
|  | [ODP](#ODP) | Présentation OpenDocument |
|
|  | [OTP](#OTP) | Modèle de présentation OpenDocument |
|
|  | [ODS](#ODS) | Feuille de calcul OpenDocument |
|
|  | [OTT](#OTT) | Modèle de texte OpenDocument |
|
|  | [RTF](#RTF) | Document texte enrichi |
|
|  | [TXT](#TXT) | Document texte brut |
|
|  | [CSV](#CSV) | Fichier de valeurs séparées par des virgules |
|
|  | [HTML](#HTML) | Langage de balisage hypertexte |
|
|  | [MHTML](#MHTML) | Mime HTML |
|
|  | [MOBI](#MOBI) | Format de livre électronique Mobipocket |
|
|  | [DCM](#DCM) | Imagerie numérique et communications en médecine |
|
|  | [DJVU](#DJVU) | Format Deja Vu |
|
|  | [DWG](#DWG) | Formats de données de conception Autodesk |
|
|  | [DXF](#DXF) | Échange de dessins AutoCAD |
|
|  | [BMP](#BMP) | Image bitmap |
|
|  | [GIF](#GIF) | Format d'échange d'images |
|
|  | [JPEG](#JPEG) | Groupe d'experts en photographie conjointe |
|
|  | [JPG](#JPG) | Groupe d'experts en photographie conjointe |
|
|  | [PNG](#PNG) | Graphiques réseau portables |
|
|  | [SVG](#SVG) | Graphiques vectoriels scalaires |
|
|  | [EML](#EML) | Message e-mail |
|
|  | [EMLX](#EMLX) | Fichier e-mail Apple Mail |
|
|  | [MSG](#MSG) | Message e-mail Microsoft Outlook |
|
|  | [CAD](#CAD) | Format de fichier CAD |
|
|  | [CPP](#CPP) | format du langage de programmation basé sur C |
|
|  | [CC](#CC) | format du langage de programmation basé sur C |
|
|  | [CXX](#CXX) | format du langage de programmation basé sur C |
|
|  | [HXX](#HXX) | Fichiers d'en-tête écrits en langage de programmation C++ |
|
|  | [HH](#HH) | Informations d'en-tête référencées par un fichier source C++ |
|
|  | [HPP](#HPP) | Fichiers d'en-tête écrits en langage de programmation C++ |
|
|  | [CMAKE](#CMAKE) | Outil de gestion du processus de compilation du logiciel |
|
|  | [CS](#CS) | Format du langage de programmation CSharp |
|
|  | [CSX](#CSX) | Format de fichier script CSharp |
|
|  | [CAKE](#CAKE) | Format du système d'automatisation de compilation multiplateforme CSharp |
|
|  | [DIFF](#DIFF) | Format de l'outil de comparaison de données |
|
|  | [PATCH](#PATCH) | Format de la liste des différences |
|
|  | [REJ](#REJ) | Format des fichiers rejetés |
|
|  | [GROOVY](#GROOVY) | Fichier de code source écrit au format Groovy |
|
|  | [GVY](#GVY) | Fichier de code source écrit au format Groovy |
|
|  | [GRADLE](#GRADLE) | Format du système d'automatisation de construction |
|
|  | [HAML](#HAML) | Langage de balisage pour la génération simplifiée de HTML |
|
|  | [JS](#JS) | Format du langage de programmation JavaScript |
|
|  | [ES6](#ES6) | Format du langage de script standardisé JavaScript |
|
|  | [MJS](#MJS) | Extension pour les fichiers de module EcmaScript (ES) |
|
|  | [PAC](#PAC) | Fichier de configuration automatique de proxy pour le format de fonction JavaScript |
|
|  | [JSON](#JSON) | Format léger pour le stockage et le transport de données |
|
|  | [BOWERRC](#BOWERRC) | Fichier de configuration pour le contrôle des paquets côté serveur |
|
|  | [JSHINTRC](#JSHINTRC) | Outil de qualité du code JavaScript |
|
|  | [JSCSRC](#JSCSRC) | Format du fichier de configuration JavaScript |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | Le fichier manifeste inclut des informations sur l'application |
|
|  | [JSMAP](#JSMAP) | Fichier JSON contenant des informations sur la façon de traduire le code en code source |
|
|  | [HAR](#HAR) | Le format HTTP Archive |
|
|  | [JAVA](#JAVA) | Format du langage de programmation Java |
|
|  | [LESS](#LESS) | Format du langage de feuille de style préprocesseur dynamique |
|
|  | [LOG](#LOG) | La journalisation conserve un registre des événements, processus, messages et communications |
|
|  | [MAKE](#MAKE) | Makefile est un fichier contenant un ensemble de directives utilisées par un outil d'automatisation de construction make pour générer une cible/objectif |
|
|  | [MK](#MK) | Makefile est un fichier contenant un ensemble de directives utilisées par un outil d'automatisation de construction make pour générer une cible/objectif |
|
|  | [MD](#MD) | Format du langage Markdown |
|
|  | [MKD](#MKD) | Format du langage Markdown |
|
|  | [MDWN](#MDWN) | Format du langage Markdown |
|
|  | [MDOWN](#MDOWN) | Format du langage Markdown |
|
|  | [MARKDOWN](#MARKDOWN) | Format du langage Markdown |
|
|  | [MARKDN](#MARKDN) | Format du langage Markdown |
|
|  | [MDTXT](#MDTXT) | Format du langage Markdown |
|
|  | [MDTEXT](#MDTEXT) | Format du langage Markdown |
|
|  | [ML](#ML) | Format du langage de programmation Caml |
|
|  | [MLI](#MLI) | Format du langage de programmation Caml |
|
|  | [OBJC](#OBJC) | Format du langage de programmation Objective-C |
|
|  | [OBJCP](#OBJCP) | Format du langage de programmation Objective-C++ |
|
|  | [PHP](#PHP) | Format du langage de programmation PHP |
|
|  | [PHP4](#PHP4) | Format du langage de programmation PHP |
|
|  | [PHP5](#PHP5) | Format du langage de programmation PHP |
|
|  | [PHTML](#PHTML) | Extension de fichier standard pour les programmes PHP 2 format |
|
|  | [CTP](#CTP) | Format du modèle CakePHP |
|
|  | [PL](#PL) | Format du langage de programmation Perl |
|
|  | [PM](#PM) | Format du module Perl |
|
|  | [POD](#POD) | Format du langage de balisage léger Perl |
|
|  | [T](#T) | Format de fichier de test Perl |
|
|  | [PSGI](#PSGI) | Interface entre serveurs web et applications web et frameworks écrits en Perl |
|
|  | [P6](#P6) | Format du langage de programmation Perl |
|
|  | [PL6](#PL6) | Format du langage de programmation Perl |
|
|  | [PM6](#PM6) | Format du module Perl |
|
|  | [NQP](#NQP) | Langage intermédiaire utilisé pour construire le compilateur Rakuto Perl 6 |
|
|  | [PROP](#PROP) | Format de fichier de propriétés |
|
|  | [CFG](#CFG) | Fichier de configuration utilisé pour stocker les paramètres |
|
|  | [CONF](#CONF) | Fichier de configuration utilisé sur les systèmes basés sur Unix et Linux |
|
|  | [DIR](#DIR) | Un répertoire est un emplacement pour stocker des fichiers sur l'ordinateur |
|
|  | [PY](#PY) | Format du langage de programmation Python |
|
|  | [RPY](#RPY) | Moteur de fichiers basé sur Python pour créer et exécuter des jeux |
|
|  | [PYW](#PYW) | Fichiers utilisés sous Windows pour indiquer qu'un script doit être exécuté |
|
|  | [CPY](#CPY) | Format du script Python de contrôleur |
|
|  | [GYP](#GYP) | Format d'outil d'automatisation de construction |
|
|  | [GYPI](#GYPI) | Format d'outil d'automatisation de construction |
|
|  | [PYI](#PYI) | Format de fichier d'interface Python |
|
|  | [IPY](#IPY) | Format de script IPython |
|
|  | [RST](#RST) | Langage de balisage léger |
|
|  | [RB](#RB) | Format du langage de programmation Ruby |
|
|  | [ERB](#ERB) | Format du langage de programmation Ruby |
|
|  | [RJS](#RJS) | Format du langage de programmation Ruby |
|
|  | [GEMSPEC](#GEMSPEC) | Fichier développeur qui spécifie les attributs d'un RubyGems |
|
|  | [RAKE](#RAKE) | Outil d'automatisation de construction Ruby |
|
|  | [RU](#RU) | Format de fichier de configuration Rack |
|
|  | [PODSPEC](#PODSPEC) | Format des paramètres de construction Ruby |
|
|  | [RBI](#RBI) | Format de fichier d'interface Ruby |
|
|  | [SASS](#SASS) | Format du langage de feuille de style |
|
|  | [SCSS](#SCSS) | Format du langage de feuille de style |
|
|  | [SCALA](#SCALA) | Format du langage de programmation Scala |
|
|  | [SBT](#SBT) | Outil de construction SBT pour le format Scala |
|
|  | [SC](#SC) | Format de feuille de travail Scala |
|
|  | [SH](#SH) | Script programmé pour le format bash |
|
|  | [BASH](#BASH) | Type d'interpréteur qui traite les commandes shell |
|
|  | [BASHRC](#BASHRC) | Le fichier détermine le comportement des shells interactifs |
|
|  | [EBUILD](#EBUILD) | Script bash spécialisé qui automatise les procédures de compilation et d'installation des paquets logiciels |
|
|  | [SQL](#SQL) | Format du Structured Query Language |
|
|  | [DSQL](#DSQL) | Format du Dynamic Structured Query Language |
|
|  | [VIM](#VIM) | Format de fichier source Vim |
|
|  | [YAML](#YAML) | Format de langage de sérialisation de données lisible par l'homme |
|
|  | [YML](#YML) | Format de langage de sérialisation de données lisible par l'homme |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | Renvoie le FileType basé sur le nom de fichier ou l'extension |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Obtient la liste des types de fichiers pris en charge |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Vérifie l'égalité des types de fichiers fournis |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Vérifie que les types de fichiers fournis ne sont pas égaux |
|
|  | [getFileFormat()](#getFileFormat--) | Obtient la description textuelle du type de fichier |
|
|  | [getExtension()](#getExtension--) | Obtient l'extension du type de fichier |
|
|  | [toString()](#toString--) | Obtient la représentation sous forme de chaîne de [FileType](../../com.groupdocs.comparison.result/filetype), par exemple |
'Format du langage de programmation PHP (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Type inconnu


### AS {#AS}
```
public static final FileType AS
```


format du langage de programmation ActionScript


### AS3 {#AS3}
```
public static final FileType AS3
```


format du langage de programmation ActionScript


### ASM {#ASM}
```
public static final FileType ASM
```


format du langage de programmation Assembleur


### BAT {#BAT}
```
public static final FileType BAT
```


Fichier script sous DOS, OS/2 et Microsoft Windows


### CMD {#CMD}
```
public static final FileType CMD
```


Fichier script sous DOS, OS/2 et Microsoft Windows


### C {#C}
```
public static final FileType C
```


format du langage de programmation basé sur C


### H {#H}
```
public static final FileType H
```


Les fichiers d'en-tête basés sur C contiennent des définitions de Functions et de Variables


### PDF {#PDF}
```
public static final FileType PDF
```


format Adobe Portable Document


### DOC {#DOC}
```
public static final FileType DOC
```


Document Microsoft Word 97-2003


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Document Microsoft Word avec macros activées


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Document Microsoft Word


### DOT {#DOT}
```
public static final FileType DOT
```


Modèle Microsoft Word 97-2003


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Modèle Microsoft Word avec macros activées


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Modèle Microsoft Word


### XLS {#XLS}
```
public static final FileType XLS
```


Feuille de calcul Microsoft Excel 97-2003


### XLT {#XLT}
```
public static final FileType XLT
```


Modèle Microsoft Excel


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Feuille de calcul Microsoft Excel


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Modèle Microsoft Excel avec macros activées


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Feuille de calcul binaire Microsoft Excel


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Feuille de calcul Microsoft Excel avec macros activées


### POT {#POT}
```
public static final FileType POT
```


Modèle Microsoft PowerPoint


### POTX {#POTX}
```
public static final FileType POTX
```


Modèle Microsoft PowerPoint


### POTM {#POTM}
```
public static final FileType POTM
```


Modèle Microsoft PowerPoint avec prise en charge des macros


### PPS {#PPS}
```
public static final FileType PPS
```


Diaporama Microsoft PowerPoint 97-2003


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Diaporama Microsoft PowerPoint


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Présentation Microsoft PowerPoint


### PPT {#PPT}
```
public static final FileType PPT
```


Présentation Microsoft PowerPoint 97-2003


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Présentation Microsoft PowerPoint avec macros activées


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Diaporama de présentation Microsoft PowerPoint avec macros activées


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Dessin Microsoft Visio


### VSD {#VSD}
```
public static final FileType VSD
```


Dessin Microsoft Visio 2003-2010


### VSS {#VSS}
```
public static final FileType VSS
```


Pochoir Microsoft Visio 2003-2010


### VST {#VST}
```
public static final FileType VST
```


Modèle Microsoft Visio 2003-2010


### VDX {#VDX}
```
public static final FileType VDX
```


Dessin XML Microsoft Visio 2003-2010


### ONE {#ONE}
```
public static final FileType ONE
```


Document Microsoft OneNote


### ODT {#ODT}
```
public static final FileType ODT
```


Texte OpenDocument


### ODP {#ODP}
```
public static final FileType ODP
```


Présentation OpenDocument


### OTP {#OTP}
```
public static final FileType OTP
```


Modèle de présentation OpenDocument


### ODS {#ODS}
```
public static final FileType ODS
```


Feuille de calcul OpenDocument


### OTT {#OTT}
```
public static final FileType OTT
```


Modèle de texte OpenDocument


### RTF {#RTF}
```
public static final FileType RTF
```


Document texte enrichi


### TXT {#TXT}
```
public static final FileType TXT
```


Document texte brut


### CSV {#CSV}
```
public static final FileType CSV
```


Fichier de valeurs séparées par des virgules


### HTML {#HTML}
```
public static final FileType HTML
```


Langage de balisage hypertexte


### MHTML {#MHTML}
```
public static final FileType MHTML
```


Mime HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Format de livre électronique Mobipocket


### DCM {#DCM}
```
public static final FileType DCM
```


Imagerie numérique et communications en médecine


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Format Deja Vu


### DWG {#DWG}
```
public static final FileType DWG
```


Formats de données de conception Autodesk


### DXF {#DXF}
```
public static final FileType DXF
```


Échange de dessins AutoCAD


### BMP {#BMP}
```
public static final FileType BMP
```


Image bitmap


### GIF {#GIF}
```
public static final FileType GIF
```


Format d'échange d'images


### JPEG {#JPEG}
```
public static final FileType JPEG
```


Groupe d'experts en photographie conjointe


### JPG {#JPG}
```
public static final FileType JPG
```


Groupe d'experts en photographie conjointe


### PNG {#PNG}
```
public static final FileType PNG
```


Graphiques réseau portables


### SVG {#SVG}
```
public static final FileType SVG
```


Graphiques vectoriels scalaires


### EML {#EML}
```
public static final FileType EML
```


Message e-mail


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Fichier e-mail Apple Mail


### MSG {#MSG}
```
public static final FileType MSG
```


Message e-mail Microsoft Outlook


### CAD {#CAD}
```
public static final FileType CAD
```


Format de fichier CAD


### CPP {#CPP}
```
public static final FileType CPP
```


format du langage de programmation basé sur C


### CC {#CC}
```
public static final FileType CC
```


format du langage de programmation basé sur C


### CXX {#CXX}
```
public static final FileType CXX
```


format du langage de programmation basé sur C


### HXX {#HXX}
```
public static final FileType HXX
```


Fichiers d'en-tête écrits en langage de programmation C++


### HH {#HH}
```
public static final FileType HH
```


Informations d'en-tête référencées par un fichier source C++


### HPP {#HPP}
```
public static final FileType HPP
```


Fichiers d'en-tête écrits en langage de programmation C++


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Outil de gestion du processus de compilation du logiciel


### CS {#CS}
```
public static final FileType CS
```


Format du langage de programmation CSharp


### CSX {#CSX}
```
public static final FileType CSX
```


Format de fichier script CSharp


### CAKE {#CAKE}
```
public static final FileType CAKE
```


Format du système d'automatisation de compilation multiplateforme CSharp


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Format de l'outil de comparaison de données


### PATCH {#PATCH}
```
public static final FileType PATCH
```


Format de la liste des différences


### REJ {#REJ}
```
public static final FileType REJ
```


Format des fichiers rejetés


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Fichier de code source écrit au format Groovy


### GVY {#GVY}
```
public static final FileType GVY
```


Fichier de code source écrit au format Groovy


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


Format du système d'automatisation de construction


### HAML {#HAML}
```
public static final FileType HAML
```


Langage de balisage pour la génération simplifiée de HTML


### JS {#JS}
```
public static final FileType JS
```


Format du langage de programmation JavaScript


### ES6 {#ES6}
```
public static final FileType ES6
```


Format du langage de script standardisé JavaScript


### MJS {#MJS}
```
public static final FileType MJS
```


Extension pour les fichiers de module EcmaScript (ES)


### PAC {#PAC}
```
public static final FileType PAC
```


Fichier de configuration automatique de proxy pour le format de fonction JavaScript


### JSON {#JSON}
```
public static final FileType JSON
```


Format léger pour le stockage et le transport de données


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


Fichier de configuration pour le contrôle des paquets côté serveur


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


Outil de qualité du code JavaScript


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


Format du fichier de configuration JavaScript


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


Le fichier manifeste inclut des informations sur l'application


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


Fichier JSON contenant des informations sur la façon de traduire le code en code source


### HAR {#HAR}
```
public static final FileType HAR
```


Le format HTTP Archive


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Format du langage de programmation Java


### LESS {#LESS}
```
public static final FileType LESS
```


Format du langage de feuille de style préprocesseur dynamique


### LOG {#LOG}
```
public static final FileType LOG
```


La journalisation conserve un registre des événements, processus, messages et communications


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile est un fichier contenant un ensemble de directives utilisées par un outil d'automatisation de construction make pour générer une cible/objectif


### MK {#MK}
```
public static final FileType MK
```


Makefile est un fichier contenant un ensemble de directives utilisées par un outil d'automatisation de construction make pour générer une cible/objectif


### MD {#MD}
```
public static final FileType MD
```


Format du langage Markdown


### MKD {#MKD}
```
public static final FileType MKD
```


Format du langage Markdown


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Format du langage Markdown


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Format du langage Markdown


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Format du langage Markdown


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Format du langage Markdown


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Format du langage Markdown


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Format du langage Markdown


### ML {#ML}
```
public static final FileType ML
```


Format du langage de programmation Caml


### MLI {#MLI}
```
public static final FileType MLI
```


Format du langage de programmation Caml


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Format du langage de programmation Objective-C


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Format du langage de programmation Objective-C++


### PHP {#PHP}
```
public static final FileType PHP
```


Format du langage de programmation PHP


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


Format du langage de programmation PHP


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


Format du langage de programmation PHP


### PHTML {#PHTML}
```
public static final FileType PHTML
```


Extension de fichier standard pour les programmes PHP 2 format


### CTP {#CTP}
```
public static final FileType CTP
```


Format du modèle CakePHP


### PL {#PL}
```
public static final FileType PL
```


Format du langage de programmation Perl


### PM {#PM}
```
public static final FileType PM
```


Format du module Perl


### POD {#POD}
```
public static final FileType POD
```


Format du langage de balisage léger Perl


### T {#T}
```
public static final FileType T
```


Format de fichier de test Perl


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Interface entre serveurs web et applications web et frameworks écrits en Perl


### P6 {#P6}
```
public static final FileType P6
```


Format du langage de programmation Perl


### PL6 {#PL6}
```
public static final FileType PL6
```


Format du langage de programmation Perl


### PM6 {#PM6}
```
public static final FileType PM6
```


Format du module Perl


### NQP {#NQP}
```
public static final FileType NQP
```


Langage intermédiaire utilisé pour construire le compilateur Rakuto Perl 6


### PROP {#PROP}
```
public static final FileType PROP
```


Format de fichier de propriétés


### CFG {#CFG}
```
public static final FileType CFG
```


Fichier de configuration utilisé pour stocker les paramètres


### CONF {#CONF}
```
public static final FileType CONF
```


Fichier de configuration utilisé sur les systèmes basés sur Unix et Linux


### DIR {#DIR}
```
public static final FileType DIR
```


Un répertoire est un emplacement pour stocker des fichiers sur l'ordinateur


### PY {#PY}
```
public static final FileType PY
```


Format du langage de programmation Python


### RPY {#RPY}
```
public static final FileType RPY
```


Moteur de fichiers basé sur Python pour créer et exécuter des jeux


### PYW {#PYW}
```
public static final FileType PYW
```


Fichiers utilisés sous Windows pour indiquer qu'un script doit être exécuté


### CPY {#CPY}
```
public static final FileType CPY
```


Format du script Python de contrôleur


### GYP {#GYP}
```
public static final FileType GYP
```


Format d'outil d'automatisation de construction


### GYPI {#GYPI}
```
public static final FileType GYPI
```


Format d'outil d'automatisation de construction


### PYI {#PYI}
```
public static final FileType PYI
```


Format de fichier d'interface Python


### IPY {#IPY}
```
public static final FileType IPY
```


Format de script IPython


### RST {#RST}
```
public static final FileType RST
```


Langage de balisage léger


### RB {#RB}
```
public static final FileType RB
```


Format du langage de programmation Ruby


### ERB {#ERB}
```
public static final FileType ERB
```


Format du langage de programmation Ruby


### RJS {#RJS}
```
public static final FileType RJS
```


Format du langage de programmation Ruby


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


Fichier développeur qui spécifie les attributs d'un RubyGems


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Outil d'automatisation de construction Ruby


### RU {#RU}
```
public static final FileType RU
```


Format de fichier de configuration Rack


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Format des paramètres de construction Ruby


### RBI {#RBI}
```
public static final FileType RBI
```


Format de fichier d'interface Ruby


### SASS {#SASS}
```
public static final FileType SASS
```


Format du langage de feuille de style


### SCSS {#SCSS}
```
public static final FileType SCSS
```


Format du langage de feuille de style


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Format du langage de programmation Scala


### SBT {#SBT}
```
public static final FileType SBT
```


Outil de construction SBT pour le format Scala


### SC {#SC}
```
public static final FileType SC
```


Format de feuille de travail Scala


### SH {#SH}
```
public static final FileType SH
```


Script programmé pour le format bash


### BASH {#BASH}
```
public static final FileType BASH
```


Type d'interpréteur qui traite les commandes shell


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


Le fichier détermine le comportement des shells interactifs


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


Script bash spécialisé qui automatise les procédures de compilation et d'installation des paquets logiciels


### SQL {#SQL}
```
public static final FileType SQL
```


Format du Structured Query Language


### DSQL {#DSQL}
```
public static final FileType DSQL
```


Format du Dynamic Structured Query Language


### VIM {#VIM}
```
public static final FileType VIM
```


Format de fichier source Vim


### YAML {#YAML}
```
public static final FileType YAML
```


Format de langage de sérialisation de données lisible par l'homme


### YML {#YML}
```
public static final FileType YML
```


Format de langage de sérialisation de données lisible par l'homme


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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


Renvoie le FileType basé sur le nom de fichier ou l'extension


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Nom de fichier ou extension, non nul |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Obtient la liste des types de fichiers pris en charge


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - liste de FileType

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


Vérifie l'égalité des types de fichiers fournis


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Objet [FileType](../../com.groupdocs.comparison.result/filetype) de gauche. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Objet [FileType](../../com.groupdocs.comparison.result/filetype) de droite. |
|

**Returns:**
booléen - vrai si égal, sinon faux

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


Vérifie que les types de fichiers fournis ne sont pas égaux


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Objet [FileType](../../com.groupdocs.comparison.result/filetype) de gauche. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Objet [FileType](../../com.groupdocs.comparison.result/filetype) de droite. |
|

**Returns:**
booléen - vrai si différent, sinon faux

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


Obtient la description textuelle du type de fichier


**Returns:**
java.lang.String - description du type de fichier

### getExtension() {#getExtension--}
```
public String getExtension()
```


Obtient l'extension du type de fichier


**Returns:**
java.lang.String - extension du type de fichier

### toString() {#toString--}
```
public String toString()
```


Obtient la représentation sous forme de chaîne de [FileType](../../com.groupdocs.comparison.result/filetype), par exemple
'Format du langage de programmation PHP (.php)'



**Returns:**
java.lang.String - représentation sous forme de chaîne

