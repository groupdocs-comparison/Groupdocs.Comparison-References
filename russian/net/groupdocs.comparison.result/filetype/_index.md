---
title: "FileType"
second_title: "Справочник API GroupDocs.Comparison для .NET"
description: "Представляет тип файла. Предоставляет методы для получения списка всех типов файлов, поддерживаемых GroupDocs.Comparison, определения типа файла по расширению и т.д."
type: docs
weight: 480
url: /ru/net/groupdocs.comparison.result/filetype/
---
## FileType class

Представляет тип файла. Предоставляет методы для получения списка всех типов файлов, поддерживаемых GroupDocs.Comparison, определения типа файла по расширению и т.д.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.comparison.result/filetype/extension) { get; } | Расширение файла |
| [FileFormat](../../groupdocs.comparison.result/filetype/fileformat) { get; } | Формат файла |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.comparison.result/filetype/fromfilenameorextension)(string) | Возврат FileType на основе имени файла или расширения |
| [Equals](../../groupdocs.comparison.result/filetype/equals#equals)(FileType) | Проверка эквивалентности типа файла |
| override [Equals](../../groupdocs.comparison.result/filetype/equals#equals_1)(object) | Проверка эквивалентности с объектом |
| override [GetHashCode](../../groupdocs.comparison.result/filetype/gethashcode)() | Получить хеш‑код |
| override [ToString](../../groupdocs.comparison.result/filetype/tostring)() | ToString |
| static [GetSupportedFileTypes](../../groupdocs.comparison.result/filetype/getsupportedfiletypes)() | Получить перечисление поддерживаемых типов файлов |
| [operator ==](../../groupdocs.comparison.result/filetype/op_equality) | Перегрузка оператора |
| [operator !=](../../groupdocs.comparison.result/filetype/op_inequality) | Перегрузка оператора |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [AS](../../groupdocs.comparison.result/filetype/as) | Формат языка программирования ActionScript |
| static readonly [AS3](../../groupdocs.comparison.result/filetype/as3) | Формат языка программирования ActionScript |
| static readonly [ASM](../../groupdocs.comparison.result/filetype/asm) | Формат ASM |
| static readonly [BASH](../../groupdocs.comparison.result/filetype/bash) | Тип интерпретатора, обрабатывающего команды оболочки |
| static readonly [BASHRC](../../groupdocs.comparison.result/filetype/bashrc) | Файл определяет поведение интерактивных оболочек |
| static readonly [BAT](../../groupdocs.comparison.result/filetype/bat) | Скриптовый файл в DOS, OS/2 и Microsoft Windows |
| static readonly [BMP](../../groupdocs.comparison.result/filetype/bmp) | Bitmap‑изображение |
| static readonly [BOWERRC](../../groupdocs.comparison.result/filetype/bowerrc) | Файл конфигурации для управления пакетами на стороне сервера |
| static readonly [C](../../groupdocs.comparison.result/filetype/c) | Формат языка программирования, основанного на C |
| static readonly [CAD](../../groupdocs.comparison.result/filetype/cad) | Формат файла CAD |
| static readonly [CAKE](../../groupdocs.comparison.result/filetype/cake) | Формат системы кроссплатформенной автоматизации сборки CSharp |
| static readonly [CC](../../groupdocs.comparison.result/filetype/cc) | Формат языка программирования, основанного на C |
| static readonly [CFG](../../groupdocs.comparison.result/filetype/cfg) | Файл конфигурации, используемый для хранения настроек |
| static readonly [CMAKE](../../groupdocs.comparison.result/filetype/cmake) | Инструмент для управления процессом сборки программного обеспечения |
| static readonly [CMD](../../groupdocs.comparison.result/filetype/cmd) | Скриптовый файл в DOS, OS/2 и Microsoft Windows |
| static readonly [CONF](../../groupdocs.comparison.result/filetype/conf) | Файл конфигурации, используемый в системах на базе Unix и Linux |
| static readonly [CPP](../../groupdocs.comparison.result/filetype/cpp) | Формат языка программирования, основанного на C |
| static readonly [CPY](../../groupdocs.comparison.result/filetype/cpy) | Формат скрипта контроллера Python |
| static readonly [CS](../../groupdocs.comparison.result/filetype/cs) | Формат языка программирования CSharp |
| static readonly [CSV](../../groupdocs.comparison.result/filetype/csv) | Файл со значениями, разделёнными запятыми |
| static readonly [CSX](../../groupdocs.comparison.result/filetype/csx) | Формат скриптового файла CSharp |
| static readonly [CTP](../../groupdocs.comparison.result/filetype/ctp) | Формат шаблона CakePHP |
| static readonly [CXX](../../groupdocs.comparison.result/filetype/cxx) | Формат языка программирования, основанного на C |
| static readonly [DCM](../../groupdocs.comparison.result/filetype/dcm) | Цифровая визуализация и коммуникация в медицине |
| static readonly [DIFF](../../groupdocs.comparison.result/filetype/diff) | Формат инструмента сравнения данных |
| static readonly [DIR](../../groupdocs.comparison.result/filetype/dir) | Каталог — это место для хранения файлов на компьютере |
| static readonly [DJVU](../../groupdocs.comparison.result/filetype/djvu) | Формат Deja Vu |
| static readonly [DOC](../../groupdocs.comparison.result/filetype/doc) | Документ Microsoft Word 97-2003 |
| static readonly [DOCM](../../groupdocs.comparison.result/filetype/docm) | Документ Microsoft Word с поддержкой макросов |
| static readonly [DOCX](../../groupdocs.comparison.result/filetype/docx) | Документ Microsoft Word |
| static readonly [DOT](../../groupdocs.comparison.result/filetype/dot) | Шаблон Microsoft Word 97-2003 |
| static readonly [DOTM](../../groupdocs.comparison.result/filetype/dotm) | Шаблон Microsoft Word с поддержкой макросов |
| static readonly [DOTX](../../groupdocs.comparison.result/filetype/dotx) | Шаблон Microsoft Word |
| static readonly [DSQL](../../groupdocs.comparison.result/filetype/dsql) | Формат динамического структурированного языка запросов |
| static readonly [DWG](../../groupdocs.comparison.result/filetype/dwg) | Форматы данных дизайна Autodesk |
| static readonly [DXF](../../groupdocs.comparison.result/filetype/dxf) | Обмен чертежами AutoCAD |
| static readonly [EBUILD](../../groupdocs.comparison.result/filetype/ebuild) | Специализированный bash‑скрипт, автоматизирующий процедуры компиляции и установки программных пакетов |
| static readonly [EML](../../groupdocs.comparison.result/filetype/eml) | Электронное письмо |
| static readonly [EMLX](../../groupdocs.comparison.result/filetype/emlx) | Файл электронного письма Apple Mail |
| static readonly [ERB](../../groupdocs.comparison.result/filetype/erb) | Формат языка программирования Ruby |
| static readonly [ES6](../../groupdocs.comparison.result/filetype/es6) | Формат стандартизированного скриптового языка JavaScript |
| static readonly [GEMSPEC](../../groupdocs.comparison.result/filetype/gemspec) | Файл разработчика, определяющий атрибуты RubyGems |
| static readonly [GIF](../../groupdocs.comparison.result/filetype/gif) | Формат обмена графикой |
| static readonly [GRADLE](../../groupdocs.comparison.result/filetype/gradle) | Формат системы автоматизации сборки |
| static readonly [GROOVY](../../groupdocs.comparison.result/filetype/groovy) | Файл исходного кода, написанный на Groovy |
| static readonly [GVY](../../groupdocs.comparison.result/filetype/gvy) | Файл исходного кода, написанный на Groovy |
| static readonly [GYP](../../groupdocs.comparison.result/filetype/gyp) | Формат инструмента автоматизации сборки |
| static readonly [GYPI](../../groupdocs.comparison.result/filetype/gypi) | Формат инструмента автоматизации сборки |
| static readonly [H](../../groupdocs.comparison.result/filetype/h) | Заголовочные файлы на C содержат определения функций и переменных |
| static readonly [HAML](../../groupdocs.comparison.result/filetype/haml) | Язык разметки для упрощённого создания HTML |
| static readonly [HAR](../../groupdocs.comparison.result/filetype/har) | Формат HTTP Archive |
| static readonly [HH](../../groupdocs.comparison.result/filetype/hh) | Информация заголовка, на которую ссылается файл исходного кода C++ |
| static readonly [HPP](../../groupdocs.comparison.result/filetype/hpp) | Файлы заголовков, написанные на языке программирования C++ |
| static readonly [HTML](../../groupdocs.comparison.result/filetype/html) | Язык гипертекстовой разметки |
| static readonly [HXX](../../groupdocs.comparison.result/filetype/hxx) | Файлы заголовков, написанные на языке программирования C++ |
| static readonly [IPY](../../groupdocs.comparison.result/filetype/ipy) | Формат скриптов IPython |
| static readonly [JAVA](../../groupdocs.comparison.result/filetype/java) | Формат языка программирования Java |
| static readonly [JPEG](../../groupdocs.comparison.result/filetype/jpeg) | Группа экспертов по совместной фотографии |
| static readonly [JS](../../groupdocs.comparison.result/filetype/js) | Формат языка программирования JavaScript |
| static readonly [JSCSRC](../../groupdocs.comparison.result/filetype/jscsrc) | Формат файла конфигурации JavaScript |
| static readonly [JSHINTRC](../../groupdocs.comparison.result/filetype/jshintrc) | Инструмент контроля качества кода JavaScript |
| static readonly [JSMAP](../../groupdocs.comparison.result/filetype/jsmap) | JSON‑файл, содержащий информацию о том, как преобразовать код обратно в исходный код |
| static readonly [JSON](../../groupdocs.comparison.result/filetype/json) | Лёгкий формат для хранения и передачи данных |
| static readonly [LESS](../../groupdocs.comparison.result/filetype/less) | Формат языка таблиц стилей динамического препроцессора |
| static readonly [LOG](../../groupdocs.comparison.result/filetype/log) | Ведение журналов сохраняет реестр событий, процессов, сообщений и коммуникаций |
| static readonly [MAKE](../../groupdocs.comparison.result/filetype/make) | Makefile — это файл, содержащий набор директив, используемых инструментом автоматизации сборки make для создания цели/задачи |
| static readonly [MARKDN](../../groupdocs.comparison.result/filetype/markdn) | Формат языка разметки Markdown |
| static readonly [MARKDOWN](../../groupdocs.comparison.result/filetype/markdown) | Формат языка разметки Markdown |
| static readonly [MD](../../groupdocs.comparison.result/filetype/md) | Формат языка разметки Markdown |
| static readonly [MDOWN](../../groupdocs.comparison.result/filetype/mdown) | Формат языка разметки Markdown |
| static readonly [MDTEXT](../../groupdocs.comparison.result/filetype/mdtext) | Формат языка разметки Markdown |
| static readonly [MDTXT](../../groupdocs.comparison.result/filetype/mdtxt) | Формат языка разметки Markdown |
| static readonly [MDWN](../../groupdocs.comparison.result/filetype/mdwn) | Формат языка разметки Markdown |
| static readonly [MHTML](../../groupdocs.comparison.result/filetype/mhtml) | Mime HTML |
| static readonly [MJS](../../groupdocs.comparison.result/filetype/mjs) | Расширение для файлов модулей EcmaScript (ES) |
| static readonly [MK](../../groupdocs.comparison.result/filetype/mk) | Makefile — это файл, содержащий набор директив, используемых инструментом автоматизации сборки make для создания цели/задачи |
| static readonly [MKD](../../groupdocs.comparison.result/filetype/mkd) | Формат языка разметки Markdown |
| static readonly [ML](../../groupdocs.comparison.result/filetype/ml) | Формат языка программирования Caml |
| static readonly [MLI](../../groupdocs.comparison.result/filetype/mli) | Формат языка программирования Caml |
| static readonly [MOBI](../../groupdocs.comparison.result/filetype/mobi) | Формат электронных книг Mobipocket |
| static readonly [MSG](../../groupdocs.comparison.result/filetype/msg) | Электронное сообщение Microsoft Outlook |
| static readonly [NQP](../../groupdocs.comparison.result/filetype/nqp) | Промежуточный язык, используемый для построения компилятора Rakudo Perl 6 |
| static readonly [OBJC](../../groupdocs.comparison.result/filetype/objc) | Формат языка программирования Objective‑C |
| static readonly [OBJCP](../../groupdocs.comparison.result/filetype/objcp) | Формат языка программирования Objective‑C++ |
| static readonly [ODP](../../groupdocs.comparison.result/filetype/odp) | OpenDocument Презентация |
| static readonly [ODS](../../groupdocs.comparison.result/filetype/ods) | OpenDocument Таблица |
| static readonly [ODT](../../groupdocs.comparison.result/filetype/odt) | OpenDocument Текст |
| static readonly [ONE](../../groupdocs.comparison.result/filetype/one) | Документ Microsoft OneNote |
| static readonly [OTP](../../groupdocs.comparison.result/filetype/otp) | OpenDocument Презентация Шаблон |
| static readonly [OTT](../../groupdocs.comparison.result/filetype/ott) | OpenDocument Текст Шаблон |
| static readonly [P6](../../groupdocs.comparison.result/filetype/p6) | Perl Язык программирования формат |
| static readonly [PAC](../../groupdocs.comparison.result/filetype/pac) | Proxy Auto-Configuration файл для JavaScript функция формат |
| static readonly [PATCH](../../groupdocs.comparison.result/filetype/patch) | Список различий формат |
| static readonly [PDF](../../groupdocs.comparison.result/filetype/pdf) | Adobe Portable Document формат |
| static readonly [PHP](../../groupdocs.comparison.result/filetype/php) | PHP Язык программирования формат |
| static readonly [PHP4](../../groupdocs.comparison.result/filetype/php4) | PHP Язык программирования формат |
| static readonly [PHP5](../../groupdocs.comparison.result/filetype/php5) | PHP Язык программирования формат |
| static readonly [PHTML](../../groupdocs.comparison.result/filetype/phtml) | Стандартный файл расширение для PHP 2 программ формат |
| static readonly [PL](../../groupdocs.comparison.result/filetype/pl) | Perl Язык программирования формат |
| static readonly [PL6](../../groupdocs.comparison.result/filetype/pl6) | Perl Язык программирования формат |
| static readonly [PM](../../groupdocs.comparison.result/filetype/pm) | Perl модуль формат |
| static readonly [PM6](../../groupdocs.comparison.result/filetype/pm6) | Perl модуль формат |
| static readonly [PNG](../../groupdocs.comparison.result/filetype/png) | Portable Network Graphics |
| static readonly [POD](../../groupdocs.comparison.result/filetype/pod) | Perl язык облегчённой разметки формат |
| static readonly [PODSPEC](../../groupdocs.comparison.result/filetype/podspec) | Ruby настройки сборки формат |
| static readonly [POT](../../groupdocs.comparison.result/filetype/pot) | Microsoft PowerPoint шаблон |
| static readonly [POTX](../../groupdocs.comparison.result/filetype/potx) | Microsoft PowerPoint Шаблон |
| static readonly [PPS](../../groupdocs.comparison.result/filetype/pps) | Microsoft PowerPoint 97-2003 Слайд-шоу |
| static readonly [PPSX](../../groupdocs.comparison.result/filetype/ppsx) | Microsoft PowerPoint Слайд-шоу |
| static readonly [PPT](../../groupdocs.comparison.result/filetype/ppt) | Microsoft PowerPoint 97-2003 Презентация |
| static readonly [PPTX](../../groupdocs.comparison.result/filetype/pptx) | Microsoft PowerPoint Презентация |
| static readonly [PROP](../../groupdocs.comparison.result/filetype/prop) | Свойства файл формат |
| static readonly [PSGI](../../groupdocs.comparison.result/filetype/psgi) | Интерфейс между веб‑серверами и веб‑приложениями и фреймворками, написанными на Perl |
| static readonly [PY](../../groupdocs.comparison.result/filetype/py) | Python Язык программирования формат |
| static readonly [PYI](../../groupdocs.comparison.result/filetype/pyi) | Формат файла интерфейса Python |
| static readonly [PYW](../../groupdocs.comparison.result/filetype/pyw) | Файлы, используемые в Windows для указания, что скрипт необходимо выполнить |
| static readonly [RAKE](../../groupdocs.comparison.result/filetype/rake) | Инструмент автоматизации сборки Ruby |
| static readonly [RB](../../groupdocs.comparison.result/filetype/rb) | Формат языка программирования Ruby |
| static readonly [RBI](../../groupdocs.comparison.result/filetype/rbi) | Формат файла интерфейса Ruby |
| static readonly [REJ](../../groupdocs.comparison.result/filetype/rej) | Формат отклонённых файлов |
| static readonly [RJS](../../groupdocs.comparison.result/filetype/rjs) | Формат языка программирования Ruby |
| static readonly [RPY](../../groupdocs.comparison.result/filetype/rpy) | Файловый движок на основе Python для создания и запуска игр |
| static readonly [RST](../../groupdocs.comparison.result/filetype/rst) | Лёгкий язык разметки |
| static readonly [RTF](../../groupdocs.comparison.result/filetype/rtf) | Документ Rich Text |
| static readonly [RU](../../groupdocs.comparison.result/filetype/ru) | Формат файла конфигурации Rack |
| static readonly [SASS](../../groupdocs.comparison.result/filetype/sass) | Формат языка таблиц стилей |
| static readonly [SBT](../../groupdocs.comparison.result/filetype/sbt) | Формат инструмента сборки SBT для Scala |
| static readonly [SC](../../groupdocs.comparison.result/filetype/sc) | Формат листа Scala |
| static readonly [SCALA](../../groupdocs.comparison.result/filetype/scala) | Формат языка программирования Scala |
| static readonly [SCSS](../../groupdocs.comparison.result/filetype/scss) | Формат языка таблиц стилей |
| static readonly [SH](../../groupdocs.comparison.result/filetype/sh) | Формат скрипта, написанного для bash |
| static readonly [SQL](../../groupdocs.comparison.result/filetype/sql) | Формат Structured Query Language |
| static readonly [SVG](../../groupdocs.comparison.result/filetype/svg) | Scalar Vector Graphics |
| static readonly [T](../../groupdocs.comparison.result/filetype/t) | Формат тестового файла Perl |
| static readonly [TXT](../../groupdocs.comparison.result/filetype/txt) | Документ простого текста |
| static readonly [UNKNOWN](../../groupdocs.comparison.result/filetype/unknown) | Неизвестный тип |
| static readonly [VDX](../../groupdocs.comparison.result/filetype/vdx) | Microsoft Visio 2003-2010 XML Drawing |
| static readonly [VIM](../../groupdocs.comparison.result/filetype/vim) | Формат файла исходного кода Vim |
| static readonly [VSD](../../groupdocs.comparison.result/filetype/vsd) | Microsoft Visio 2003-2010 Drawing |
| static readonly [VSDX](../../groupdocs.comparison.result/filetype/vsdx) | Microsoft Visio Drawing |
| static readonly [VSS](../../groupdocs.comparison.result/filetype/vss) | Microsoft Visio 2003-2010 Stencil |
| static readonly [VST](../../groupdocs.comparison.result/filetype/vst) | Microsoft Visio 2003-2010 Template |
| static readonly [WEBMANIFEST](../../groupdocs.comparison.result/filetype/webmanifest) | Файл манифеста содержит информацию о приложении |
| static readonly [XLS](../../groupdocs.comparison.result/filetype/xls) | Microsoft Excel 97‑2003 лист |
| static readonly [XLSB](../../groupdocs.comparison.result/filetype/xlsb) | Microsoft Excel бинарный лист |
| static readonly [XLSM](../../groupdocs.comparison.result/filetype/xlsm) | Microsoft Excel лист с поддержкой макросов |
| static readonly [XLSX](../../groupdocs.comparison.result/filetype/xlsx) | Microsoft Excel лист |
| static readonly [XLT](../../groupdocs.comparison.result/filetype/xlt) | Microsoft Excel шаблон |
| static readonly [XLTM](../../groupdocs.comparison.result/filetype/xltm) | Microsoft Excel шаблон с поддержкой макросов |
| static readonly [YAML](../../groupdocs.comparison.result/filetype/yaml) | Человекочитаемый формат языка сериализации данных |
| static readonly [YML](../../groupdocs.comparison.result/filetype/yml) | Человекочитаемый формат языка сериализации данных |

### Примечания

**Learn more**

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* Learn more about getting supported file types in C#: [How to get supported file formats in C#](https://docs.groupdocs.com/display/comparisonnet/Get+supported+file+formats)

### См. также

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Comparison.dll -->
