---
title: "FileType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Перечисление FileType представляет тип файла, используемого в процессе сравнения документов."
type: docs
weight: 16
url: /ru/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

Перечисление FileType представляет тип файла, используемого в процессе сравнения документов.


Он определяет различные типы файлов, такие как документы Word, PDF‑файлы и другие.
Предоставляет методы для получения списка всех типов файлов, поддерживаемых GroupDocs.Comparison, определения типа файла по расширению и т.д.
Используйте этот перечисление для указания типа файла при работе с библиотекой GroupDocs.Comparison.

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


Пример использования:

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


## Поля

| Поле | Описание |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Неизвестный тип |
|
|  | [AS](#AS) | Формат языка программирования ActionScript |
|
|  | [AS3](#AS3) | Формат языка программирования ActionScript |
|
|  | [ASM](#ASM) | Формат языка программирования Assembler |
|
|  | [BAT](#BAT) | Скриптовый файл в DOS, OS/2 и Microsoft Windows |
|
|  | [CMD](#CMD) | Скриптовый файл в DOS, OS/2 и Microsoft Windows |
|
|  | [C](#C) | Формат языка программирования C |
|
|  | [H](#H) | Заголовочные файлы на основе C содержат определения функций и переменных |
|
|  | [PDF](#PDF) | Формат Adobe Portable Document |
|
|  | [DOC](#DOC) | Документ Microsoft Word 97‑2003 |
|
|  | [DOCM](#DOCM) | Документ Microsoft Word с поддержкой макросов |
|
|  | [DOCX](#DOCX) | Документ Microsoft Word |
|
|  | [DOT](#DOT) | Шаблон Microsoft Word 97‑2003 |
|
|  | [DOTM](#DOTM) | Шаблон Microsoft Word с поддержкой макросов |
|
|  | [DOTX](#DOTX) | Шаблон Microsoft Word |
|
|  | [XLS](#XLS) | Лист Microsoft Excel 97‑2003 |
|
|  | [XLT](#XLT) | Шаблон Microsoft Excel |
|
|  | [XLSX](#XLSX) | Лист Microsoft Excel |
|
|  | [XLTM](#XLTM) | Шаблон Microsoft Excel с поддержкой макросов |
|
|  | [XLSB](#XLSB) | Microsoft Excel Бинарный лист |
|
|  | [XLSM](#XLSM) | Microsoft Excel лист с поддержкой макросов |
|
|  | [POT](#POT) | Microsoft PowerPoint шаблон |
|
|  | [POTX](#POTX) | Microsoft PowerPoint Шаблон |
|
|  | [POTM](#POTM) | Microsoft PowerPoint шаблон с поддержкой макросов |
|
|  | [PPS](#PPS) | Microsoft PowerPoint 97-2003 слайд-шоу |
|
|  | [PPSX](#PPSX) | Microsoft PowerPoint слайд-шоу |
|
|  | [PPTX](#PPTX) | Microsoft PowerPoint презентация |
|
|  | [PPT](#PPT) | Microsoft PowerPoint 97-2003 презентация |
|
|  | [PPTM](#PPTM) | Microsoft PowerPoint презентация с поддержкой макросов |
|
|  | [PPSM](#PPSM) | Microsoft PowerPoint презентация слайд-шоу с поддержкой макросов |
|
|  | [VSDX](#VSDX) | Microsoft Visio чертеж |
|
|  | [VSD](#VSD) | Microsoft Visio 2003-2010 чертеж |
|
|  | [VSS](#VSS) | Microsoft Visio 2003-2010 трафарет |
|
|  | [VST](#VST) | Microsoft Visio 2003-2010 шаблон |
|
|  | [VDX](#VDX) | Microsoft Visio 2003-2010 XML чертеж |
|
|  | [ONE](#ONE) | Microsoft OneNote документ |
|
|  | [ODT](#ODT) | OpenDocument Текст |
|
|  | [ODP](#ODP) | OpenDocument Презентация |
|
|  | [OTP](#OTP) | OpenDocument шаблон презентации |
|
|  | [ODS](#ODS) | OpenDocument Таблица |
|
|  | [OTT](#OTT) | OpenDocument шаблон текста |
|
|  | [RTF](#RTF) | Документ в формате Rich Text |
|
|  | [TXT](#TXT) | Документ в простом тексте |
|
|  | [CSV](#CSV) | Файл со значениями, разделёнными запятыми |
|
|  | [HTML](#HTML) | Язык гипертекстовой разметки |
|
|  | [MHTML](#MHTML) | Mime HTML |
|
|  | [MOBI](#MOBI) | Формат электронных книг Mobipocket |
|
|  | [DCM](#DCM) | Цифровая визуализация и коммуникация в медицине |
|
|  | [DJVU](#DJVU) | Формат Deja Vu |
|
|  | [DWG](#DWG) | Форматы данных Autodesk Design |
|
|  | [DXF](#DXF) | Обмен чертежами AutoCAD |
|
|  | [BMP](#BMP) | Растровое изображение |
|
|  | [GIF](#GIF) | Формат обмена графикой |
|
|  | [JPEG](#JPEG) | Объединённая группа фотографических экспертов |
|
|  | [JPG](#JPG) | Объединённая группа фотографических экспертов |
|
|  | [PNG](#PNG) | Переносимая сетевая графика |
|
|  | [SVG](#SVG) | Скалярная векторная графика |
|
|  | [EML](#EML) | Электронное письмо |
|
|  | [EMLX](#EMLX) | Файл электронного письма Apple Mail |
|
|  | [MSG](#MSG) | Электронное письмо Microsoft Outlook |
|
|  | [CAD](#CAD) | Формат файлов CAD |
|
|  | [CPP](#CPP) | Формат языка программирования C |
|
|  | [CC](#CC) | Формат языка программирования C |
|
|  | [CXX](#CXX) | Формат языка программирования C |
|
|  | [HXX](#HXX) | Файлы заголовков, написанные на языке программирования C++ |
|
|  | [HH](#HH) | Информация заголовка, на которую ссылается файл исходного кода C++ |
|
|  | [HPP](#HPP) | Файлы заголовков, написанные на языке программирования C++ |
|
|  | [CMAKE](#CMAKE) | Инструмент для управления процессом сборки программного обеспечения |
|
|  | [CS](#CS) | Формат языка программирования CSharp |
|
|  | [CSX](#CSX) | Формат скриптового файла CSharp |
|
|  | [CAKE](#CAKE) | Формат кроссплатформенной системы автоматизации сборки CSharp |
|
|  | [DIFF](#DIFF) | Формат инструмента сравнения данных |
|
|  | [PATCH](#PATCH) | Формат списка различий |
|
|  | [REJ](#REJ) | Формат отклонённых файлов |
|
|  | [GROOVY](#GROOVY) | Файл исходного кода, написанный в формате Groovy |
|
|  | [GVY](#GVY) | Файл исходного кода, написанный в формате Groovy |
|
|  | [GRADLE](#GRADLE) | Формат системы автоматизации сборки |
|
|  | [HAML](#HAML) | Язык разметки для упрощённого создания HTML |
|
|  | [JS](#JS) | Формат языка программирования JavaScript |
|
|  | [ES6](#ES6) | Формат стандартизированного скриптового языка JavaScript |
|
|  | [MJS](#MJS) | Расширение для файлов модулей EcmaScript (ES) |
|
|  | [PAC](#PAC) | Файл автоматической настройки прокси для формата функции JavaScript |
|
|  | [JSON](#JSON) | Лёгкий формат для хранения и передачи данных |
|
|  | [BOWERRC](#BOWERRC) | Файл конфигурации для управления пакетами на стороне сервера |
|
|  | [JSHINTRC](#JSHINTRC) | Инструмент контроля качества кода JavaScript |
|
|  | [JSCSRC](#JSCSRC) | Формат файла конфигурации JavaScript |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | Файл манифеста содержит информацию о приложении |
|
|  | [JSMAP](#JSMAP) | JSON‑файл, содержащий информацию о том, как преобразовать код обратно в исходный код |
|
|  | [HAR](#HAR) | Формат HTTP Archive |
|
|  | [JAVA](#JAVA) | Формат языка программирования Java |
|
|  | [LESS](#LESS) | Формат динамического языка таблиц стилей препроцессора |
|
|  | [LOG](#LOG) | Ведение журнала сохраняет реестр событий, процессов, сообщений и коммуникаций |
|
|  | [MAKE](#MAKE) | Makefile — это файл, содержащий набор директив, используемых инструментом автоматизации сборки make для создания цели/задачи |
|
|  | [MK](#MK) | Makefile — это файл, содержащий набор директив, используемых инструментом автоматизации сборки make для создания цели/задачи |
|
|  | [MD](#MD) | Формат языка Markdown |
|
|  | [MKD](#MKD) | Формат языка Markdown |
|
|  | [MDWN](#MDWN) | Формат языка Markdown |
|
|  | [MDOWN](#MDOWN) | Формат языка Markdown |
|
|  | [MARKDOWN](#MARKDOWN) | Формат языка Markdown |
|
|  | [MARKDN](#MARKDN) | Формат языка Markdown |
|
|  | [MDTXT](#MDTXT) | Формат языка Markdown |
|
|  | [MDTEXT](#MDTEXT) | Формат языка Markdown |
|
|  | [ML](#ML) | Формат языка программирования Caml |
|
|  | [MLI](#MLI) | Формат языка программирования Caml |
|
|  | [OBJC](#OBJC) | Формат языка программирования Objective-C |
|
|  | [OBJCP](#OBJCP) | Формат языка программирования Objective-C++ |
|
|  | [PHP](#PHP) | Формат языка программирования PHP |
|
|  | [PHP4](#PHP4) | Формат языка программирования PHP |
|
|  | [PHP5](#PHP5) | Формат языка программирования PHP |
|
|  | [PHTML](#PHTML) | Стандартное расширение файла для программ PHP 2 |
|
|  | [CTP](#CTP) | Формат шаблона CakePHP |
|
|  | [PL](#PL) | Формат языка программирования Perl |
|
|  | [PM](#PM) | Формат модуля Perl |
|
|  | [POD](#POD) | Формат облегчённого разметочного языка Perl |
|
|  | [T](#T) | Формат тестового файла Perl |
|
|  | [PSGI](#PSGI) | Интерфейс между веб‑серверами и веб‑приложениями и фреймворками, написанными на языке Perl |
|
|  | [P6](#P6) | Формат языка программирования Perl |
|
|  | [PL6](#PL6) | Формат языка программирования Perl |
|
|  | [PM6](#PM6) | Формат модуля Perl |
|
|  | [NQP](#NQP) | Промежуточный язык, используемый для создания компилятора Rakudo Perl 6 |
|
|  | [PROP](#PROP) | Формат файла свойств |
|
|  | [CFG](#CFG) | Файл конфигурации, используемый для хранения настроек |
|
|  | [CONF](#CONF) | Файл конфигурации, используемый в системах на базе Unix и Linux |
|
|  | [DIR](#DIR) | Каталог — это место для хранения файлов на компьютере |
|
|  | [PY](#PY) | Формат языка программирования Python |
|
|  | [RPY](#RPY) | Файловый движок на основе Python для создания и запуска игр |
|
|  | [PYW](#PYW) | Файлы, используемые в Windows, указывающие, что скрипт необходимо выполнить |
|
|  | [CPY](#CPY) | Формат контроллерного скрипта Python |
|
|  | [GYP](#GYP) | Формат инструмента автоматизации сборки |
|
|  | [GYPI](#GYPI) | Формат инструмента автоматизации сборки |
|
|  | [PYI](#PYI) | Формат файла интерфейса Python |
|
|  | [IPY](#IPY) | Формат скрипта IPython |
|
|  | [RST](#RST) | Облегчённый разметочный язык |
|
|  | [RB](#RB) | Формат языка программирования Ruby |
|
|  | [ERB](#ERB) | Формат языка программирования Ruby |
|
|  | [RJS](#RJS) | Формат языка программирования Ruby |
|
|  | [GEMSPEC](#GEMSPEC) | Файл разработчика, определяющий атрибуты RubyGems |
|
|  | [RAKE](#RAKE) | Инструмент автоматизации сборки Ruby |
|
|  | [RU](#RU) | Формат конфигурационного файла Rack |
|
|  | [PODSPEC](#PODSPEC) | Формат настроек сборки Ruby |
|
|  | [RBI](#RBI) | Формат файла интерфейса Ruby |
|
|  | [SASS](#SASS) | Формат языка таблиц стилей |
|
|  | [SCSS](#SCSS) | Формат языка таблиц стилей |
|
|  | [SCALA](#SCALA) | Формат языка программирования Scala |
|
|  | [SBT](#SBT) | Формат инструмента сборки SBT для Scala |
|
|  | [SC](#SC) | Формат рабочего листа Scala |
|
|  | [SH](#SH) | Формат скрипта, написанного для bash |
|
|  | [BASH](#BASH) | Тип интерпретатора, который обрабатывает команды оболочки |
|
|  | [BASHRC](#BASHRC) | Файл определяет поведение интерактивных оболочек |
|
|  | [EBUILD](#EBUILD) | Специализированный скрипт bash, который автоматизирует процедуры компиляции и установки программных пакетов |
|
|  | [SQL](#SQL) | Формат Structured Query Language |
|
|  | [DSQL](#DSQL) | Формат Dynamic Structured Query Language |
|
|  | [VIM](#VIM) | Формат файла исходного кода Vim |
|
|  | [YAML](#YAML) | Формат языка сериализации данных, читаемого человеком |
|
|  | [YML](#YML) | Формат языка сериализации данных, читаемого человеком |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | Возвращает FileType на основе имени файла или расширения |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Получает список поддерживаемых типов файлов |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Проверяет равенство предоставленных типов файлов |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Проверяет, что предоставленные типы файлов не равны |
|
|  | [getFileFormat()](#getFileFormat--) | Получает текстовое описание типа файла |
|
|  | [getExtension()](#getExtension--) | Получает расширение типа файла |
|
|  | [toString()](#toString--) | Получает строковое представление [FileType](../../com.groupdocs.comparison.result/filetype), например |
'Формат языка программирования PHP (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Неизвестный тип


### AS {#AS}
```
public static final FileType AS
```


Формат языка программирования ActionScript


### AS3 {#AS3}
```
public static final FileType AS3
```


Формат языка программирования ActionScript


### ASM {#ASM}
```
public static final FileType ASM
```


Формат языка программирования Assembler


### BAT {#BAT}
```
public static final FileType BAT
```


Скриптовый файл в DOS, OS/2 и Microsoft Windows


### CMD {#CMD}
```
public static final FileType CMD
```


Скриптовый файл в DOS, OS/2 и Microsoft Windows


### C {#C}
```
public static final FileType C
```


Формат языка программирования C


### H {#H}
```
public static final FileType H
```


Заголовочные файлы на основе C содержат определения функций и переменных


### PDF {#PDF}
```
public static final FileType PDF
```


Формат Adobe Portable Document


### DOC {#DOC}
```
public static final FileType DOC
```


Документ Microsoft Word 97‑2003


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Документ Microsoft Word с поддержкой макросов


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Документ Microsoft Word


### DOT {#DOT}
```
public static final FileType DOT
```


Шаблон Microsoft Word 97‑2003


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Шаблон Microsoft Word с поддержкой макросов


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Шаблон Microsoft Word


### XLS {#XLS}
```
public static final FileType XLS
```


Лист Microsoft Excel 97‑2003


### XLT {#XLT}
```
public static final FileType XLT
```


Шаблон Microsoft Excel


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Лист Microsoft Excel


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Шаблон Microsoft Excel с поддержкой макросов


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Microsoft Excel Бинарный лист


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Microsoft Excel лист с поддержкой макросов


### POT {#POT}
```
public static final FileType POT
```


Microsoft PowerPoint шаблон


### POTX {#POTX}
```
public static final FileType POTX
```


Microsoft PowerPoint Шаблон


### POTM {#POTM}
```
public static final FileType POTM
```


Microsoft PowerPoint шаблон с поддержкой макросов


### PPS {#PPS}
```
public static final FileType PPS
```


Microsoft PowerPoint 97-2003 слайд-шоу


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Microsoft PowerPoint слайд-шоу


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Microsoft PowerPoint презентация


### PPT {#PPT}
```
public static final FileType PPT
```


Microsoft PowerPoint 97-2003 презентация


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Microsoft PowerPoint презентация с поддержкой макросов


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Microsoft PowerPoint презентация слайд-шоу с поддержкой макросов


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Visio чертеж


### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio 2003-2010 чертеж


### VSS {#VSS}
```
public static final FileType VSS
```


Microsoft Visio 2003-2010 трафарет


### VST {#VST}
```
public static final FileType VST
```


Microsoft Visio 2003-2010 шаблон


### VDX {#VDX}
```
public static final FileType VDX
```


Microsoft Visio 2003-2010 XML чертеж


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote документ


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Текст


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Презентация


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument шаблон презентации


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Таблица


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument шаблон текста


### RTF {#RTF}
```
public static final FileType RTF
```


Документ в формате Rich Text


### TXT {#TXT}
```
public static final FileType TXT
```


Документ в простом тексте


### CSV {#CSV}
```
public static final FileType CSV
```


Файл со значениями, разделёнными запятыми


### HTML {#HTML}
```
public static final FileType HTML
```


Язык гипертекстовой разметки


### MHTML {#MHTML}
```
public static final FileType MHTML
```


Mime HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Формат электронных книг Mobipocket


### DCM {#DCM}
```
public static final FileType DCM
```


Цифровая визуализация и коммуникация в медицине


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Формат Deja Vu


### DWG {#DWG}
```
public static final FileType DWG
```


Форматы данных Autodesk Design


### DXF {#DXF}
```
public static final FileType DXF
```


Обмен чертежами AutoCAD


### BMP {#BMP}
```
public static final FileType BMP
```


Растровое изображение


### GIF {#GIF}
```
public static final FileType GIF
```


Формат обмена графикой


### JPEG {#JPEG}
```
public static final FileType JPEG
```


Объединённая группа фотографических экспертов


### JPG {#JPG}
```
public static final FileType JPG
```


Объединённая группа фотографических экспертов


### PNG {#PNG}
```
public static final FileType PNG
```


Переносимая сетевая графика


### SVG {#SVG}
```
public static final FileType SVG
```


Скалярная векторная графика


### EML {#EML}
```
public static final FileType EML
```


Электронное письмо


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Файл электронного письма Apple Mail


### MSG {#MSG}
```
public static final FileType MSG
```


Электронное письмо Microsoft Outlook


### CAD {#CAD}
```
public static final FileType CAD
```


Формат файлов CAD


### CPP {#CPP}
```
public static final FileType CPP
```


Формат языка программирования C


### CC {#CC}
```
public static final FileType CC
```


Формат языка программирования C


### CXX {#CXX}
```
public static final FileType CXX
```


Формат языка программирования C


### HXX {#HXX}
```
public static final FileType HXX
```


Файлы заголовков, написанные на языке программирования C++


### HH {#HH}
```
public static final FileType HH
```


Информация заголовка, на которую ссылается файл исходного кода C++


### HPP {#HPP}
```
public static final FileType HPP
```


Файлы заголовков, написанные на языке программирования C++


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Инструмент для управления процессом сборки программного обеспечения


### CS {#CS}
```
public static final FileType CS
```


Формат языка программирования CSharp


### CSX {#CSX}
```
public static final FileType CSX
```


Формат скриптового файла CSharp


### CAKE {#CAKE}
```
public static final FileType CAKE
```


Формат кроссплатформенной системы автоматизации сборки CSharp


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Формат инструмента сравнения данных


### PATCH {#PATCH}
```
public static final FileType PATCH
```


Формат списка различий


### REJ {#REJ}
```
public static final FileType REJ
```


Формат отклонённых файлов


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Файл исходного кода, написанный в формате Groovy


### GVY {#GVY}
```
public static final FileType GVY
```


Файл исходного кода, написанный в формате Groovy


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


Формат системы автоматизации сборки


### HAML {#HAML}
```
public static final FileType HAML
```


Язык разметки для упрощённого создания HTML


### JS {#JS}
```
public static final FileType JS
```


Формат языка программирования JavaScript


### ES6 {#ES6}
```
public static final FileType ES6
```


Формат стандартизированного скриптового языка JavaScript


### MJS {#MJS}
```
public static final FileType MJS
```


Расширение для файлов модулей EcmaScript (ES)


### PAC {#PAC}
```
public static final FileType PAC
```


Файл автоматической настройки прокси для формата функции JavaScript


### JSON {#JSON}
```
public static final FileType JSON
```


Лёгкий формат для хранения и передачи данных


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


Файл конфигурации для управления пакетами на стороне сервера


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


Инструмент контроля качества кода JavaScript


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


Формат файла конфигурации JavaScript


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


Файл манифеста содержит информацию о приложении


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


JSON‑файл, содержащий информацию о том, как преобразовать код обратно в исходный код


### HAR {#HAR}
```
public static final FileType HAR
```


Формат HTTP Archive


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Формат языка программирования Java


### LESS {#LESS}
```
public static final FileType LESS
```


Формат динамического языка таблиц стилей препроцессора


### LOG {#LOG}
```
public static final FileType LOG
```


Ведение журнала сохраняет реестр событий, процессов, сообщений и коммуникаций


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Makefile — это файл, содержащий набор директив, используемых инструментом автоматизации сборки make для создания цели/задачи


### MK {#MK}
```
public static final FileType MK
```


Makefile — это файл, содержащий набор директив, используемых инструментом автоматизации сборки make для создания цели/задачи


### MD {#MD}
```
public static final FileType MD
```


Формат языка Markdown


### MKD {#MKD}
```
public static final FileType MKD
```


Формат языка Markdown


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Формат языка Markdown


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Формат языка Markdown


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Формат языка Markdown


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Формат языка Markdown


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Формат языка Markdown


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Формат языка Markdown


### ML {#ML}
```
public static final FileType ML
```


Формат языка программирования Caml


### MLI {#MLI}
```
public static final FileType MLI
```


Формат языка программирования Caml


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Формат языка программирования Objective-C


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Формат языка программирования Objective-C++


### PHP {#PHP}
```
public static final FileType PHP
```


Формат языка программирования PHP


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


Формат языка программирования PHP


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


Формат языка программирования PHP


### PHTML {#PHTML}
```
public static final FileType PHTML
```


Стандартное расширение файла для программ PHP 2


### CTP {#CTP}
```
public static final FileType CTP
```


Формат шаблона CakePHP


### PL {#PL}
```
public static final FileType PL
```


Формат языка программирования Perl


### PM {#PM}
```
public static final FileType PM
```


Формат модуля Perl


### POD {#POD}
```
public static final FileType POD
```


Формат облегчённого разметочного языка Perl


### T {#T}
```
public static final FileType T
```


Формат тестового файла Perl


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Интерфейс между веб‑серверами и веб‑приложениями и фреймворками, написанными на языке Perl


### P6 {#P6}
```
public static final FileType P6
```


Формат языка программирования Perl


### PL6 {#PL6}
```
public static final FileType PL6
```


Формат языка программирования Perl


### PM6 {#PM6}
```
public static final FileType PM6
```


Формат модуля Perl


### NQP {#NQP}
```
public static final FileType NQP
```


Промежуточный язык, используемый для создания компилятора Rakudo Perl 6


### PROP {#PROP}
```
public static final FileType PROP
```


Формат файла свойств


### CFG {#CFG}
```
public static final FileType CFG
```


Файл конфигурации, используемый для хранения настроек


### CONF {#CONF}
```
public static final FileType CONF
```


Файл конфигурации, используемый в системах на базе Unix и Linux


### DIR {#DIR}
```
public static final FileType DIR
```


Каталог — это место для хранения файлов на компьютере


### PY {#PY}
```
public static final FileType PY
```


Формат языка программирования Python


### RPY {#RPY}
```
public static final FileType RPY
```


Файловый движок на основе Python для создания и запуска игр


### PYW {#PYW}
```
public static final FileType PYW
```


Файлы, используемые в Windows, указывающие, что скрипт необходимо выполнить


### CPY {#CPY}
```
public static final FileType CPY
```


Формат контроллерного скрипта Python


### GYP {#GYP}
```
public static final FileType GYP
```


Формат инструмента автоматизации сборки


### GYPI {#GYPI}
```
public static final FileType GYPI
```


Формат инструмента автоматизации сборки


### PYI {#PYI}
```
public static final FileType PYI
```


Формат файла интерфейса Python


### IPY {#IPY}
```
public static final FileType IPY
```


Формат скрипта IPython


### RST {#RST}
```
public static final FileType RST
```


Облегчённый разметочный язык


### RB {#RB}
```
public static final FileType RB
```


Формат языка программирования Ruby


### ERB {#ERB}
```
public static final FileType ERB
```


Формат языка программирования Ruby


### RJS {#RJS}
```
public static final FileType RJS
```


Формат языка программирования Ruby


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


Файл разработчика, определяющий атрибуты RubyGems


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Инструмент автоматизации сборки Ruby


### RU {#RU}
```
public static final FileType RU
```


Формат конфигурационного файла Rack


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Формат настроек сборки Ruby


### RBI {#RBI}
```
public static final FileType RBI
```


Формат файла интерфейса Ruby


### SASS {#SASS}
```
public static final FileType SASS
```


Формат языка таблиц стилей


### SCSS {#SCSS}
```
public static final FileType SCSS
```


Формат языка таблиц стилей


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Формат языка программирования Scala


### SBT {#SBT}
```
public static final FileType SBT
```


Формат инструмента сборки SBT для Scala


### SC {#SC}
```
public static final FileType SC
```


Формат рабочего листа Scala


### SH {#SH}
```
public static final FileType SH
```


Формат скрипта, написанного для bash


### BASH {#BASH}
```
public static final FileType BASH
```


Тип интерпретатора, который обрабатывает команды оболочки


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


Файл определяет поведение интерактивных оболочек


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


Специализированный скрипт bash, который автоматизирует процедуры компиляции и установки программных пакетов


### SQL {#SQL}
```
public static final FileType SQL
```


Формат Structured Query Language


### DSQL {#DSQL}
```
public static final FileType DSQL
```


Формат Dynamic Structured Query Language


### VIM {#VIM}
```
public static final FileType VIM
```


Формат файла исходного кода Vim


### YAML {#YAML}
```
public static final FileType YAML
```


Формат языка сериализации данных, читаемого человеком


### YML {#YML}
```
public static final FileType YML
```


Формат языка сериализации данных, читаемого человеком


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


Возвращает FileType на основе имени файла или расширения


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Имя файла или расширение, не null |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Получает список поддерживаемых типов файлов


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - список FileType

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


Проверяет равенство предоставленных типов файлов


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Левый объект [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Правый объект [FileType](../../com.groupdocs.comparison.result/filetype). |
|

**Returns:**
boolean - true если равны, иначе false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


Проверяет, что предоставленные типы файлов не равны


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Левый объект [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Правый объект [FileType](../../com.groupdocs.comparison.result/filetype). |
|

**Returns:**
boolean - true если не равно, иначе false

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


Получает текстовое описание типа файла


**Returns:**
java.lang.String - описание типа файла

### getExtension() {#getExtension--}
```
public String getExtension()
```


Получает расширение типа файла


**Returns:**
java.lang.String - расширение типа файла

### toString() {#toString--}
```
public String toString()
```


Получает строковое представление [FileType](../../com.groupdocs.comparison.result/filetype), например
'Формат языка программирования PHP (.php)'



**Returns:**
java.lang.String - строковое представление

