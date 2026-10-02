---
title: "FileType"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "El enum FileType representa el tipo de archivo utilizado en el proceso de comparación de documentos."
type: docs
weight: 16
url: /es/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

El enum FileType representa el tipo de archivo utilizado en el proceso de comparación de documentos.


Define diferentes tipos de archivo como documentos Word, archivos PDF y más.
Proporciona métodos para obtener la lista de todos los tipos de archivo compatibles con GroupDocs.Comparison, detectar el tipo de archivo por extensión, etc.
Utilice este enum para especificar el tipo de archivo al trabajar con la biblioteca GroupDocs.Comparison.

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


Ejemplo de uso:

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


## Campos

| Campo | Descripción |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Tipo desconocido |
|
|  | [AS](#AS) | Formato del lenguaje de programación ActionScript |
|
|  | [AS3](#AS3) | Formato del lenguaje de programación ActionScript |
|
|  | [ASM](#ASM) | Formato del lenguaje de programación Assembler |
|
|  | [BAT](#BAT) | Archivo de script en DOS, OS/2 y Microsoft Windows |
|
|  | [CMD](#CMD) | Archivo de script en DOS, OS/2 y Microsoft Windows |
|
|  | [C](#C) | Formato del lenguaje de programación basado en C |
|
|  | [H](#H) | Los archivos de encabezado basados en C contienen definiciones de funciones y variables |
|
|  | [PDF](#PDF) | Formato de documento portátil Adobe |
|
|  | [DOC](#DOC) | Documento Microsoft Word 97-2003 |
|
|  | [DOCM](#DOCM) | Documento Microsoft Word con macros habilitadas |
|
|  | [DOCX](#DOCX) | Documento Microsoft Word |
|
|  | [DOT](#DOT) | Plantilla Microsoft Word 97-2003 |
|
|  | [DOTM](#DOTM) | Plantilla Microsoft Word con macros habilitadas |
|
|  | [DOTX](#DOTX) | Plantilla Microsoft Word |
|
|  | [XLS](#XLS) | Hoja de cálculo Microsoft Excel 97-2003 |
|
|  | [XLT](#XLT) | Plantilla Microsoft Excel |
|
|  | [XLSX](#XLSX) | Hoja de cálculo Microsoft Excel |
|
|  | [XLTM](#XLTM) | Plantilla Microsoft Excel con macros habilitadas |
|
|  | [XLSB](#XLSB) | Hoja de cálculo binaria de Microsoft Excel |
|
|  | [XLSM](#XLSM) | Hoja de cálculo habilitada para macros de Microsoft Excel |
|
|  | [POT](#POT) | Plantilla de Microsoft PowerPoint |
|
|  | [POTX](#POTX) | Plantilla de Microsoft PowerPoint |
|
|  | [POTM](#POTM) | Plantilla de Microsoft PowerPoint con soporte para macros |
|
|  | [PPS](#PPS) | Presentación de diapositivas de Microsoft PowerPoint 97-2003 |
|
|  | [PPSX](#PPSX) | Presentación de diapositivas de Microsoft PowerPoint |
|
|  | [PPTX](#PPTX) | Presentación de Microsoft PowerPoint |
|
|  | [PPT](#PPT) | Presentación de Microsoft PowerPoint 97-2003 |
|
|  | [PPTM](#PPTM) | Presentación habilitada para macros de Microsoft PowerPoint |
|
|  | [PPSM](#PPSM) | Presentación de diapositivas habilitada para macros de Microsoft PowerPoint |
|
|  | [VSDX](#VSDX) | Dibujo de Microsoft Visio |
|
|  | [VSD](#VSD) | Dibujo de Microsoft Visio 2003-2010 |
|
|  | [VSS](#VSS) | Plantilla de Microsoft Visio 2003-2010 |
|
|  | [VST](#VST) | Plantilla de Microsoft Visio 2003-2010 |
|
|  | [VDX](#VDX) | Dibujo XML de Microsoft Visio 2003-2010 |
|
|  | [ONE](#ONE) | Documento de Microsoft OneNote |
|
|  | [ODT](#ODT) | Texto OpenDocument |
|
|  | [ODP](#ODP) | Presentación OpenDocument |
|
|  | [OTP](#OTP) | Plantilla de presentación OpenDocument |
|
|  | [ODS](#ODS) | Hoja de cálculo OpenDocument |
|
|  | [OTT](#OTT) | Plantilla de texto OpenDocument |
|
|  | [RTF](#RTF) | Documento de texto enriquecido |
|
|  | [TXT](#TXT) | Documento de texto plano |
|
|  | [CSV](#CSV) | Archivo de valores separados por comas |
|
|  | [HTML](#HTML) | Lenguaje de Marcado de Hipertexto |
|
|  | [MHTML](#MHTML) | MIME HTML |
|
|  | [MOBI](#MOBI) | Formato de libro electrónico Mobipocket |
|
|  | [DCM](#DCM) | Imágenes Digitales y Comunicaciones en Medicina |
|
|  | [DJVU](#DJVU) | Formato Deja Vu |
|
|  | [DWG](#DWG) | Formatos de Datos de Diseño Autodesk |
|
|  | [DXF](#DXF) | Intercambio de Dibujos AutoCAD |
|
|  | [BMP](#BMP) | Imagen Bitmap |
|
|  | [GIF](#GIF) | Formato de Intercambio de Gráficos |
|
|  | [JPEG](#JPEG) | Grupo Conjunto de Expertos Fotográficos |
|
|  | [JPG](#JPG) | Grupo Conjunto de Expertos Fotográficos |
|
|  | [PNG](#PNG) | Gráficos Portátiles de Red |
|
|  | [SVG](#SVG) | Gráficos Vectoriales Escalares |
|
|  | [EML](#EML) | Mensaje de Correo Electrónico |
|
|  | [EMLX](#EMLX) | Archivo de Correo Electrónico Apple Mail |
|
|  | [MSG](#MSG) | Mensaje de Correo Electrónico Microsoft Outlook |
|
|  | [CAD](#CAD) | Formato de archivo CAD |
|
|  | [CPP](#CPP) | Formato del lenguaje de programación basado en C |
|
|  | [CC](#CC) | Formato del lenguaje de programación basado en C |
|
|  | [CXX](#CXX) | Formato del lenguaje de programación basado en C |
|
|  | [HXX](#HXX) | Archivos de encabezado escritos en el lenguaje de programación C++ |
|
|  | [HH](#HH) | Información de encabezado referenciada por un archivo de código fuente C++ |
|
|  | [HPP](#HPP) | Archivos de encabezado escritos en el lenguaje de programación C++ |
|
|  | [CMAKE](#CMAKE) | Herramienta para gestionar el proceso de compilación de software |
|
|  | [CS](#CS) | Formato del lenguaje de programación CSharp |
|
|  | [CSX](#CSX) | Formato de archivo de script CSharp |
|
|  | [CAKE](#CAKE) | Formato del sistema de automatización de compilación multiplataforma CSharp |
|
|  | [DIFF](#DIFF) | Formato de herramienta de comparación de datos |
|
|  | [PATCH](#PATCH) | Formato de lista de diferencias |
|
|  | [REJ](#REJ) | Formato de archivos rechazados |
|
|  | [GROOVY](#GROOVY) | Archivo de código fuente escrito en formato Groovy |
|
|  | [GVY](#GVY) | Archivo de código fuente escrito en formato Groovy |
|
|  | [GRADLE](#GRADLE) | Formato de sistema de automatización de compilación |
|
|  | [HAML](#HAML) | Lenguaje de marcado para generación simplificada de HTML |
|
|  | [JS](#JS) | Formato del lenguaje de programación JavaScript |
|
|  | [ES6](#ES6) | Formato del lenguaje de secuencias de comandos estandarizado JavaScript |
|
|  | [MJS](#MJS) | Extensión para archivos de módulo EcmaScript (ES) |
|
|  | [PAC](#PAC) | Archivo de Configuración Automática de Proxy para formato de función JavaScript |
|
|  | [JSON](#JSON) | Formato ligero para almacenar y transportar datos |
|
|  | [BOWERRC](#BOWERRC) | Archivo de configuración para control de paquetes del lado del servidor |
|
|  | [JSHINTRC](#JSHINTRC) | Herramienta de calidad de código JavaScript |
|
|  | [JSCSRC](#JSCSRC) | Formato de archivo de configuración JavaScript |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | El archivo de manifiesto incluye información sobre la aplicación |
|
|  | [JSMAP](#JSMAP) | Archivo JSON que contiene información sobre cómo traducir el código de vuelta al código fuente |
|
|  | [HAR](#HAR) | El formato HTTP Archive |
|
|  | [JAVA](#JAVA) | Formato del lenguaje de programación Java |
|
|  | [LESS](#LESS) | Formato del lenguaje de hojas de estilo de preprocesador dinámico |
|
|  | [LOG](#LOG) | El registro mantiene un catálogo de eventos, procesos, mensajes y comunicaciones |
|
|  | [MAKE](#MAKE) | Makefile es un archivo que contiene un conjunto de directivas usadas por una herramienta de automatización de compilación make para generar un objetivo/meta |
|
|  | [MK](#MK) | Makefile es un archivo que contiene un conjunto de directivas usadas por una herramienta de automatización de compilación make para generar un objetivo/meta |
|
|  | [MD](#MD) | Formato del lenguaje Markdown |
|
|  | [MKD](#MKD) | Formato del lenguaje Markdown |
|
|  | [MDWN](#MDWN) | Formato del lenguaje Markdown |
|
|  | [MDOWN](#MDOWN) | Formato del lenguaje Markdown |
|
|  | [MARKDOWN](#MARKDOWN) | Formato del lenguaje Markdown |
|
|  | [MARKDN](#MARKDN) | Formato del lenguaje Markdown |
|
|  | [MDTXT](#MDTXT) | Formato del lenguaje Markdown |
|
|  | [MDTEXT](#MDTEXT) | Formato del lenguaje Markdown |
|
|  | [ML](#ML) | Formato del lenguaje de programación Caml |
|
|  | [MLI](#MLI) | Formato del lenguaje de programación Caml |
|
|  | [OBJC](#OBJC) | Formato del lenguaje de programación Objective-C |
|
|  | [OBJCP](#OBJCP) | Formato del lenguaje de programación Objective-C++ |
|
|  | [PHP](#PHP) | Formato del lenguaje de programación PHP |
|
|  | [PHP4](#PHP4) | Formato del lenguaje de programación PHP |
|
|  | [PHP5](#PHP5) | Formato del lenguaje de programación PHP |
|
|  | [PHTML](#PHTML) | Formato de extensión de archivo estándar para programas PHP 2 |
|
|  | [CTP](#CTP) | Formato de plantilla CakePHP |
|
|  | [PL](#PL) | Formato del lenguaje de programación Perl |
|
|  | [PM](#PM) | Formato de módulo Perl |
|
|  | [POD](#POD) | Formato del lenguaje de marcado ligero Perl |
|
|  | [T](#T) | Formato de archivo de prueba Perl |
|
|  | [PSGI](#PSGI) | Interfaz entre servidores web y aplicaciones web y frameworks escritos en el lenguaje de programación Perl |
|
|  | [P6](#P6) | Formato del lenguaje de programación Perl |
|
|  | [PL6](#PL6) | Formato del lenguaje de programación Perl |
|
|  | [PM6](#PM6) | Formato de módulo Perl |
|
|  | [NQP](#NQP) | Lenguaje intermedio usado para construir el compilador Rakumo Perl 6 |
|
|  | [PROP](#PROP) | Formato de archivo de propiedades |
|
|  | [CFG](#CFG) | Archivo de configuración usado para almacenar ajustes |
|
|  | [CONF](#CONF) | Archivo de configuración usado en sistemas basados en Unix y Linux |
|
|  | [DIR](#DIR) | Directorio es una ubicación para almacenar archivos en el ordenador |
|
|  | [PY](#PY) | Formato del lenguaje de programación Python |
|
|  | [RPY](#RPY) | Motor de archivos basado en Python para crear y ejecutar juegos |
|
|  | [PYW](#PYW) | Archivos usados en Windows para indicar que un script debe ejecutarse |
|
|  | [CPY](#CPY) | Formato de script controlador Python |
|
|  | [GYP](#GYP) | Formato de herramienta de automatización de compilación |
|
|  | [GYPI](#GYPI) | Formato de herramienta de automatización de compilación |
|
|  | [PYI](#PYI) | Formato de archivo de interfaz Python |
|
|  | [IPY](#IPY) | Formato de script IPython |
|
|  | [RST](#RST) | Lenguaje de marcado ligero |
|
|  | [RB](#RB) | Formato del lenguaje de programación Ruby |
|
|  | [ERB](#ERB) | Formato del lenguaje de programación Ruby |
|
|  | [RJS](#RJS) | Formato del lenguaje de programación Ruby |
|
|  | [GEMSPEC](#GEMSPEC) | Archivo de desarrollador que especifica los atributos de un RubyGems |
|
|  | [RAKE](#RAKE) | Herramienta de automatización de compilación Ruby |
|
|  | [RU](#RU) | Formato de archivo de configuración Rack |
|
|  | [PODSPEC](#PODSPEC) | Formato de configuración de compilación Ruby |
|
|  | [RBI](#RBI) | Formato de archivo de interfaz Ruby |
|
|  | [SASS](#SASS) | Formato de lenguaje de hojas de estilo |
|
|  | [SCSS](#SCSS) | Formato de lenguaje de hojas de estilo |
|
|  | [SCALA](#SCALA) | Formato del lenguaje de programación Scala |
|
|  | [SBT](#SBT) | Formato de la herramienta de compilación SBT para Scala |
|
|  | [SC](#SC) | Formato de hoja de trabajo Scala |
|
|  | [SH](#SH) | Formato de script programado para bash |
|
|  | [BASH](#BASH) | Tipo de intérprete que procesa comandos de shell |
|
|  | [BASHRC](#BASHRC) | Archivo que determina el comportamiento de los shells interactivos |
|
|  | [EBUILD](#EBUILD) | Script bash especializado que automatiza los procedimientos de compilación e instalación de paquetes de software |
|
|  | [SQL](#SQL) | Formato de Structured Query Language |
|
|  | [DSQL](#DSQL) | Formato de Dynamic Structured Query Language |
|
|  | [VIM](#VIM) | Formato de archivo de código fuente Vim |
|
|  | [YAML](#YAML) | Formato de lenguaje de serialización de datos legible por humanos |
|
|  | [YML](#YML) | Formato de lenguaje de serialización de datos legible por humanos |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | Devuelve FileType basado en el nombre de archivo o extensión |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Obtiene la lista de tipos de archivo compatibles |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Comprueba la igualdad de los tipos de archivo proporcionados |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Comprueba que los tipos de archivo proporcionados no son iguales |
|
|  | [getFileFormat()](#getFileFormat--) | Obtiene la descripción textual del tipo de archivo |
|
|  | [getExtension()](#getExtension--) | Obtiene la extensión del tipo de archivo |
|
|  | [toString()](#toString--) | Obtiene la representación en cadena de [FileType](../../com.groupdocs.comparison.result/filetype), por ejemplo |
'Formato del lenguaje de programación PHP (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Tipo desconocido


### AS {#AS}
```
public static final FileType AS
```


Formato del lenguaje de programación ActionScript


### AS3 {#AS3}
```
public static final FileType AS3
```


Formato del lenguaje de programación ActionScript


### ASM {#ASM}
```
public static final FileType ASM
```


Formato del lenguaje de programación Assembler


### BAT {#BAT}
```
public static final FileType BAT
```


Archivo de script en DOS, OS/2 y Microsoft Windows


### CMD {#CMD}
```
public static final FileType CMD
```


Archivo de script en DOS, OS/2 y Microsoft Windows


### C {#C}
```
public static final FileType C
```


Formato del lenguaje de programación basado en C


### H {#H}
```
public static final FileType H
```


Los archivos de encabezado basados en C contienen definiciones de funciones y variables


### PDF {#PDF}
```
public static final FileType PDF
```


Formato de documento portátil Adobe


### DOC {#DOC}
```
public static final FileType DOC
```


Documento Microsoft Word 97-2003


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Documento Microsoft Word con macros habilitadas


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Documento Microsoft Word


### DOT {#DOT}
```
public static final FileType DOT
```


Plantilla Microsoft Word 97-2003


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Plantilla Microsoft Word con macros habilitadas


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Plantilla Microsoft Word


### XLS {#XLS}
```
public static final FileType XLS
```


Hoja de cálculo Microsoft Excel 97-2003


### XLT {#XLT}
```
public static final FileType XLT
```


Plantilla Microsoft Excel


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Hoja de cálculo Microsoft Excel


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Plantilla Microsoft Excel con macros habilitadas


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Hoja de cálculo binaria de Microsoft Excel


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Hoja de cálculo habilitada para macros de Microsoft Excel


### POT {#POT}
```
public static final FileType POT
```


Plantilla de Microsoft PowerPoint


### POTX {#POTX}
```
public static final FileType POTX
```


Plantilla de Microsoft PowerPoint


### POTM {#POTM}
```
public static final FileType POTM
```


Plantilla de Microsoft PowerPoint con soporte para macros


### PPS {#PPS}
```
public static final FileType PPS
```


Presentación de diapositivas de Microsoft PowerPoint 97-2003


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Presentación de diapositivas de Microsoft PowerPoint


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Presentación de Microsoft PowerPoint


### PPT {#PPT}
```
public static final FileType PPT
```


Presentación de Microsoft PowerPoint 97-2003


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Presentación habilitada para macros de Microsoft PowerPoint


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Presentación de diapositivas habilitada para macros de Microsoft PowerPoint


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Dibujo de Microsoft Visio


### VSD {#VSD}
```
public static final FileType VSD
```


Dibujo de Microsoft Visio 2003-2010


### VSS {#VSS}
```
public static final FileType VSS
```


Plantilla de Microsoft Visio 2003-2010


### VST {#VST}
```
public static final FileType VST
```


Plantilla de Microsoft Visio 2003-2010


### VDX {#VDX}
```
public static final FileType VDX
```


Dibujo XML de Microsoft Visio 2003-2010


### ONE {#ONE}
```
public static final FileType ONE
```


Documento de Microsoft OneNote


### ODT {#ODT}
```
public static final FileType ODT
```


Texto OpenDocument


### ODP {#ODP}
```
public static final FileType ODP
```


Presentación OpenDocument


### OTP {#OTP}
```
public static final FileType OTP
```


Plantilla de presentación OpenDocument


### ODS {#ODS}
```
public static final FileType ODS
```


Hoja de cálculo OpenDocument


### OTT {#OTT}
```
public static final FileType OTT
```


Plantilla de texto OpenDocument


### RTF {#RTF}
```
public static final FileType RTF
```


Documento de texto enriquecido


### TXT {#TXT}
```
public static final FileType TXT
```


Documento de texto plano


### CSV {#CSV}
```
public static final FileType CSV
```


Archivo de valores separados por comas


### HTML {#HTML}
```
public static final FileType HTML
```


Lenguaje de Marcado de Hipertexto


### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Formato de libro electrónico Mobipocket


### DCM {#DCM}
```
public static final FileType DCM
```


Imágenes Digitales y Comunicaciones en Medicina


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Formato Deja Vu


### DWG {#DWG}
```
public static final FileType DWG
```


Formatos de Datos de Diseño Autodesk


### DXF {#DXF}
```
public static final FileType DXF
```


Intercambio de Dibujos AutoCAD


### BMP {#BMP}
```
public static final FileType BMP
```


Imagen Bitmap


### GIF {#GIF}
```
public static final FileType GIF
```


Formato de Intercambio de Gráficos


### JPEG {#JPEG}
```
public static final FileType JPEG
```


Grupo Conjunto de Expertos Fotográficos


### JPG {#JPG}
```
public static final FileType JPG
```


Grupo Conjunto de Expertos Fotográficos


### PNG {#PNG}
```
public static final FileType PNG
```


Gráficos Portátiles de Red


### SVG {#SVG}
```
public static final FileType SVG
```


Gráficos Vectoriales Escalares


### EML {#EML}
```
public static final FileType EML
```


Mensaje de Correo Electrónico


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Archivo de Correo Electrónico Apple Mail


### MSG {#MSG}
```
public static final FileType MSG
```


Mensaje de Correo Electrónico Microsoft Outlook


### CAD {#CAD}
```
public static final FileType CAD
```


Formato de archivo CAD


### CPP {#CPP}
```
public static final FileType CPP
```


Formato del lenguaje de programación basado en C


### CC {#CC}
```
public static final FileType CC
```


Formato del lenguaje de programación basado en C


### CXX {#CXX}
```
public static final FileType CXX
```


Formato del lenguaje de programación basado en C


### HXX {#HXX}
```
public static final FileType HXX
```


Archivos de encabezado escritos en el lenguaje de programación C++


### HH {#HH}
```
public static final FileType HH
```


Información de encabezado referenciada por un archivo de código fuente C++


### HPP {#HPP}
```
public static final FileType HPP
```


Archivos de encabezado escritos en el lenguaje de programación C++


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Herramienta para gestionar el proceso de compilación de software


### CS {#CS}
```
public static final FileType CS
```


Formato del lenguaje de programación CSharp


### CSX {#CSX}
```
public static final FileType CSX
```


Formato de archivo de script CSharp


### CAKE {#CAKE}
```
public static final FileType CAKE
```


Formato del sistema de automatización de compilación multiplataforma CSharp


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Formato de herramienta de comparación de datos


### PATCH {#PATCH}
```
public static final FileType PATCH
```


Formato de lista de diferencias


### REJ {#REJ}
```
public static final FileType REJ
```


Formato de archivos rechazados


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Archivo de código fuente escrito en formato Groovy


### GVY {#GVY}
```
public static final FileType GVY
```


Archivo de código fuente escrito en formato Groovy


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


Formato de sistema de automatización de compilación


### HAML {#HAML}
```
public static final FileType HAML
```


Lenguaje de marcado para generación simplificada de HTML


### JS {#JS}
```
public static final FileType JS
```


Formato del lenguaje de programación JavaScript


### ES6 {#ES6}
```
public static final FileType ES6
```


Formato del lenguaje de secuencias de comandos estandarizado JavaScript


### MJS {#MJS}
```
public static final FileType MJS
```


Extensión para archivos de módulo EcmaScript (ES)


### PAC {#PAC}
```
public static final FileType PAC
```


Archivo de Configuración Automática de Proxy para formato de función JavaScript


### JSON {#JSON}
```
public static final FileType JSON
```


Formato ligero para almacenar y transportar datos


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


Archivo de configuración para control de paquetes del lado del servidor


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


Herramienta de calidad de código JavaScript


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


Formato de archivo de configuración JavaScript


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


El archivo de manifiesto incluye información sobre la aplicación


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


Archivo JSON que contiene información sobre cómo traducir el código de vuelta al código fuente


### HAR {#HAR}
```
public static final FileType HAR
```


El formato HTTP Archive


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Formato del lenguaje de programación Java


### LESS {#LESS}
```
public static final FileType LESS
```


Formato del lenguaje de hojas de estilo de preprocesador dinámico


### LOG {#LOG}
```
public static final FileType LOG
```


El registro mantiene un catálogo de eventos, procesos, mensajes y comunicaciones


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile es un archivo que contiene un conjunto de directivas usadas por una herramienta de automatización de compilación make para generar un objetivo/meta


### MK {#MK}
```
public static final FileType MK
```


Makefile es un archivo que contiene un conjunto de directivas usadas por una herramienta de automatización de compilación make para generar un objetivo/meta


### MD {#MD}
```
public static final FileType MD
```


Formato del lenguaje Markdown


### MKD {#MKD}
```
public static final FileType MKD
```


Formato del lenguaje Markdown


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Formato del lenguaje Markdown


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Formato del lenguaje Markdown


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Formato del lenguaje Markdown


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Formato del lenguaje Markdown


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Formato del lenguaje Markdown


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Formato del lenguaje Markdown


### ML {#ML}
```
public static final FileType ML
```


Formato del lenguaje de programación Caml


### MLI {#MLI}
```
public static final FileType MLI
```


Formato del lenguaje de programación Caml


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Formato del lenguaje de programación Objective-C


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Formato del lenguaje de programación Objective-C++


### PHP {#PHP}
```
public static final FileType PHP
```


Formato del lenguaje de programación PHP


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


Formato del lenguaje de programación PHP


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


Formato del lenguaje de programación PHP


### PHTML {#PHTML}
```
public static final FileType PHTML
```


Formato de extensión de archivo estándar para programas PHP 2


### CTP {#CTP}
```
public static final FileType CTP
```


Formato de plantilla CakePHP


### PL {#PL}
```
public static final FileType PL
```


Formato del lenguaje de programación Perl


### PM {#PM}
```
public static final FileType PM
```


Formato de módulo Perl


### POD {#POD}
```
public static final FileType POD
```


Formato del lenguaje de marcado ligero Perl


### T {#T}
```
public static final FileType T
```


Formato de archivo de prueba Perl


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Interfaz entre servidores web y aplicaciones web y frameworks escritos en el lenguaje de programación Perl


### P6 {#P6}
```
public static final FileType P6
```


Formato del lenguaje de programación Perl


### PL6 {#PL6}
```
public static final FileType PL6
```


Formato del lenguaje de programación Perl


### PM6 {#PM6}
```
public static final FileType PM6
```


Formato de módulo Perl


### NQP {#NQP}
```
public static final FileType NQP
```


Lenguaje intermedio usado para construir el compilador Rakumo Perl 6


### PROP {#PROP}
```
public static final FileType PROP
```


Formato de archivo de propiedades


### CFG {#CFG}
```
public static final FileType CFG
```


Archivo de configuración usado para almacenar ajustes


### CONF {#CONF}
```
public static final FileType CONF
```


Archivo de configuración usado en sistemas basados en Unix y Linux


### DIR {#DIR}
```
public static final FileType DIR
```


Directorio es una ubicación para almacenar archivos en el ordenador


### PY {#PY}
```
public static final FileType PY
```


Formato del lenguaje de programación Python


### RPY {#RPY}
```
public static final FileType RPY
```


Motor de archivos basado en Python para crear y ejecutar juegos


### PYW {#PYW}
```
public static final FileType PYW
```


Archivos usados en Windows para indicar que un script debe ejecutarse


### CPY {#CPY}
```
public static final FileType CPY
```


Formato de script controlador Python


### GYP {#GYP}
```
public static final FileType GYP
```


Formato de herramienta de automatización de compilación


### GYPI {#GYPI}
```
public static final FileType GYPI
```


Formato de herramienta de automatización de compilación


### PYI {#PYI}
```
public static final FileType PYI
```


Formato de archivo de interfaz Python


### IPY {#IPY}
```
public static final FileType IPY
```


Formato de script IPython


### RST {#RST}
```
public static final FileType RST
```


Lenguaje de marcado ligero


### RB {#RB}
```
public static final FileType RB
```


Formato del lenguaje de programación Ruby


### ERB {#ERB}
```
public static final FileType ERB
```


Formato del lenguaje de programación Ruby


### RJS {#RJS}
```
public static final FileType RJS
```


Formato del lenguaje de programación Ruby


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


Archivo de desarrollador que especifica los atributos de un RubyGems


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Herramienta de automatización de compilación Ruby


### RU {#RU}
```
public static final FileType RU
```


Formato de archivo de configuración Rack


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Formato de configuración de compilación Ruby


### RBI {#RBI}
```
public static final FileType RBI
```


Formato de archivo de interfaz Ruby


### SASS {#SASS}
```
public static final FileType SASS
```


Formato de lenguaje de hojas de estilo


### SCSS {#SCSS}
```
public static final FileType SCSS
```


Formato de lenguaje de hojas de estilo


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Formato del lenguaje de programación Scala


### SBT {#SBT}
```
public static final FileType SBT
```


Formato de la herramienta de compilación SBT para Scala


### SC {#SC}
```
public static final FileType SC
```


Formato de hoja de trabajo Scala


### SH {#SH}
```
public static final FileType SH
```


Formato de script programado para bash


### BASH {#BASH}
```
public static final FileType BASH
```


Tipo de intérprete que procesa comandos de shell


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


Archivo que determina el comportamiento de los shells interactivos


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


Script bash especializado que automatiza los procedimientos de compilación e instalación de paquetes de software


### SQL {#SQL}
```
public static final FileType SQL
```


Formato de Structured Query Language


### DSQL {#DSQL}
```
public static final FileType DSQL
```


Formato de Dynamic Structured Query Language


### VIM {#VIM}
```
public static final FileType VIM
```


Formato de archivo de código fuente Vim


### YAML {#YAML}
```
public static final FileType YAML
```


Formato de lenguaje de serialización de datos legible por humanos


### YML {#YML}
```
public static final FileType YML
```


Formato de lenguaje de serialización de datos legible por humanos


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


Devuelve FileType basado en el nombre de archivo o extensión


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | Nombre de archivo o extensión, no nulo |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Obtiene la lista de tipos de archivo compatibles


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - lista de FileType

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


Comprueba la igualdad de los tipos de archivo proporcionados


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Objeto [FileType](../../com.groupdocs.comparison.result/filetype) izquierdo. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Objeto [FileType](../../com.groupdocs.comparison.result/filetype) derecho. |
|

**Returns:**
boolean - true si es igual, de lo contrario false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


Comprueba que los tipos de archivo proporcionados no son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Objeto [FileType](../../com.groupdocs.comparison.result/filetype) izquierdo. |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Objeto [FileType](../../com.groupdocs.comparison.result/filetype) derecho. |
|

**Returns:**
boolean - verdadero si no es igual, de lo contrario falso

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


Obtiene la descripción textual del tipo de archivo


**Returns:**
java.lang.String - descripción del tipo de archivo

### getExtension() {#getExtension--}
```
public String getExtension()
```


Obtiene la extensión del tipo de archivo


**Returns:**
java.lang.String - extensión del tipo de archivo

### toString() {#toString--}
```
public String toString()
```


Obtiene la representación en cadena de [FileType](../../com.groupdocs.comparison.result/filetype), por ejemplo
'Formato del lenguaje de programación PHP (.php)'



**Returns:**
java.lang.String - representación de cadena

