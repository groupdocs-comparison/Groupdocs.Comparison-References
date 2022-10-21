---
title: FileType
second_title: Справочник по API GroupDocs.Comparison для .NET
description: Представляет тип файла. Предоставляет методы для получения списка всех типов файлов поддерживаемых GroupDocs.Comparison определения типа файла по расширению и т. д.
type: docs
weight: 400
url: /ru/net/groupdocs.comparison.result/filetype/
---
## FileType class

Представляет тип файла. Предоставляет методы для получения списка всех типов файлов, поддерживаемых GroupDocs.Comparison, определения типа файла по расширению и т. д.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.comparison.result/filetype/extension) { get; } | Расширение файла |
| [FileFormat](../../groupdocs.comparison.result/filetype/fileformat) { get; } | Формат файла |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromFileNameOrExtension](../../groupdocs.comparison.result/filetype/fromfilenameorextension)(string) | Вернуть тип файла на основе имени файла или расширения |
| [Equals](../../groupdocs.comparison.result/filetype/equals#equals)(FileType) | Проверка эквивалентности типов файлов |
| override [Equals](../../groupdocs.comparison.result/filetype/equals#equals_1)(object) | Проверка эквивалентности с object |
| override [GetHashCode](../../groupdocs.comparison.result/filetype/gethashcode)() | Получить хэш-код |
| override [ToString](../../groupdocs.comparison.result/filetype/tostring)() | ToString |
| static [GetSupportedFileTypes](../../groupdocs.comparison.result/filetype/getsupportedfiletypes)() | Получить перечисление поддерживаемых типов файлов |
| [operator ==](../../groupdocs.comparison.result/filetype/op_equality) | Перегрузка оператора |
| [operator !=](../../groupdocs.comparison.result/filetype/op_inequality) | Перегрузка оператора |

## Поля

| Имя | Описание |
| --- | --- |
| static [AS](../../groupdocs.comparison.result/filetype/as) | Формат языка программирования ActionScript |
| static [AS3](../../groupdocs.comparison.result/filetype/as3) | Формат языка программирования ActionScript |
| static [ASM](../../groupdocs.comparison.result/filetype/asm) | Формат ASM |
| static [BASH](../../groupdocs.comparison.result/filetype/bash) | Тип интерпретатора, который обрабатывает команды оболочки |
| static [BASHRC](../../groupdocs.comparison.result/filetype/bashrc) | Файл определяет поведение интерактивных оболочек |
| static [BAT](../../groupdocs.comparison.result/filetype/bat) | Файл сценария в DOS, OS/2 и Microsoft Windows |
| static [BMP](../../groupdocs.comparison.result/filetype/bmp) | Растровое изображение |
| static [BOWERRC](../../groupdocs.comparison.result/filetype/bowerrc) | Конфигурационный файл для управления пакетами на стороне сервера |
| static [C](../../groupdocs.comparison.result/filetype/c) | Формат языка программирования на основе C |
| static [CAD](../../groupdocs.comparison.result/filetype/cad) | Формат файла САПР |
| static [CAKE](../../groupdocs.comparison.result/filetype/cake) | Формат кроссплатформенной системы автоматизации сборки CSharp |
| static [CC](../../groupdocs.comparison.result/filetype/cc) | Формат языка программирования на основе C |
| static [CFG](../../groupdocs.comparison.result/filetype/cfg) | Конфигурационный файл, используемый для хранения настроек |
| static [CMAKE](../../groupdocs.comparison.result/filetype/cmake) | Инструмент для управления процессом сборки software |
| static [CMD](../../groupdocs.comparison.result/filetype/cmd) | Файл сценария в DOS, OS/2 и Microsoft Windows |
| static [CONF](../../groupdocs.comparison.result/filetype/conf) | Файл конфигурации, используемый в системах на базе Unix и Linux |
| static [CPP](../../groupdocs.comparison.result/filetype/cpp) | Формат языка программирования на основе C |
| static [CPY](../../groupdocs.comparison.result/filetype/cpy) | Формат сценария Python контроллера |
| static [CS](../../groupdocs.comparison.result/filetype/cs) | Формат языка программирования CSharp |
| static [CSV](../../groupdocs.comparison.result/filetype/csv) | Файл значений, разделенных запятыми |
| static [CSX](../../groupdocs.comparison.result/filetype/csx) | Формат файла сценария CSharp |
| static [CTP](../../groupdocs.comparison.result/filetype/ctp) | Формат шаблона CakePHP |
| static [CXX](../../groupdocs.comparison.result/filetype/cxx) | Формат языка программирования на основе C |
| static [DCM](../../groupdocs.comparison.result/filetype/dcm) | Цифровая визуализация и коммуникации в медицине |
| static [DIFF](../../groupdocs.comparison.result/filetype/diff) | Формат средства сравнения данных |
| static [DIR](../../groupdocs.comparison.result/filetype/dir) | Каталог — это место для хранения файлов на компьютере |
| static [DJVU](../../groupdocs.comparison.result/filetype/djvu) | Формат дежавю |
| static [DOC](../../groupdocs.comparison.result/filetype/doc) | Microsoft Word 97-2003 Документ |
| static [DOCM](../../groupdocs.comparison.result/filetype/docm) | Документ Microsoft Word с поддержкой макросов |
| static [DOCX](../../groupdocs.comparison.result/filetype/docx) | Документ Microsoft Word |
| static [DOT](../../groupdocs.comparison.result/filetype/dot) | Шаблон Microsoft Word 97-2003 |
| static [DOTM](../../groupdocs.comparison.result/filetype/dotm) | Шаблон Microsoft Word с поддержкой макросов |
| static [DOTX](../../groupdocs.comparison.result/filetype/dotx) | Шаблон Microsoft Word |
| static [DSQL](../../groupdocs.comparison.result/filetype/dsql) | Формат языка динамических структурированных запросов |
| static [DWG](../../groupdocs.comparison.result/filetype/dwg) | Форматы проектных данных Autodesk |
| static [DXF](../../groupdocs.comparison.result/filetype/dxf) | Обмен чертежами AutoCAD |
| static [EBUILD](../../groupdocs.comparison.result/filetype/ebuild) | Специализированный bash-скрипт, автоматизирующий процедуры компиляции и установки программных пакетов |
| static [EML](../../groupdocs.comparison.result/filetype/eml) | Сообщение электронной почты |
| static [EMLX](../../groupdocs.comparison.result/filetype/emlx) | Файл электронной почты Apple Mail |
| static [ERB](../../groupdocs.comparison.result/filetype/erb) | Формат языка программирования Ruby |
| static [ES6](../../groupdocs.comparison.result/filetype/es6) | Формат стандартизированного языка сценариев JavaScript |
| static [GEMSPEC](../../groupdocs.comparison.result/filetype/gemspec) | Файл разработчика, определяющий атрибуты RubyGems |
| static [GIF](../../groupdocs.comparison.result/filetype/gif) | Формат обмена графикой |
| static [GRADLE](../../groupdocs.comparison.result/filetype/gradle) | Формат системы автоматизации сборки |
| static [GROOVY](../../groupdocs.comparison.result/filetype/groovy) | Файл исходного кода, записанный в формате Groovy |
| static [GVY](../../groupdocs.comparison.result/filetype/gvy) | Файл исходного кода, записанный в формате Groovy |
| static [GYP](../../groupdocs.comparison.result/filetype/gyp) | Инструмент автоматизации сборки format |
| static [GYPI](../../groupdocs.comparison.result/filetype/gypi) | Инструмент автоматизации сборки format |
| static [H](../../groupdocs.comparison.result/filetype/h) | Файлы заголовков на языке C содержат определения функций и переменных |
| static [HAML](../../groupdocs.comparison.result/filetype/haml) | Язык разметки для упрощенного создания HTML |
| static [HAR](../../groupdocs.comparison.result/filetype/har) | Формат архива HTTP |
| static [HH](../../groupdocs.comparison.result/filetype/hh) | Информация заголовка, на которую ссылается файл исходного кода C++ |
| static [HPP](../../groupdocs.comparison.result/filetype/hpp) | Заголовочные файлы, написанные на языке программирования C++ |
| static [HTML](../../groupdocs.comparison.result/filetype/html) | Язык гипертекстовой разметки |
| static [HXX](../../groupdocs.comparison.result/filetype/hxx) | Заголовочные файлы, написанные на языке программирования C++ |
| static [IPY](../../groupdocs.comparison.result/filetype/ipy) | Формат сценария IPython |
| static [JAVA](../../groupdocs.comparison.result/filetype/java) | Формат языка программирования Java |
| static [JPEG](../../groupdocs.comparison.result/filetype/jpeg) | Объединенная группа экспертов по фотографии |
| static [JS](../../groupdocs.comparison.result/filetype/js) | Формат языка программирования JavaScript |
| static [JSCSRC](../../groupdocs.comparison.result/filetype/jscsrc) | Формат файла конфигурации JavaScript |
| static [JSHINTRC](../../groupdocs.comparison.result/filetype/jshintrc) | Инструмент качества кода JavaScript |
| static [JSMAP](../../groupdocs.comparison.result/filetype/jsmap) | Файл JSON, содержащий информацию о том, как перевести код обратно в исходный код |
| static [JSON](../../groupdocs.comparison.result/filetype/json) | Облегченный формат для хранения и передачи данных |
| static [LESS](../../groupdocs.comparison.result/filetype/less) | Формат языка таблицы стилей динамического препроцессора |
| static [LOG](../../groupdocs.comparison.result/filetype/log) | Ведение журнала ведет реестр событий, процессов, сообщений и коммуникаций |
| static [MAKE](../../groupdocs.comparison.result/filetype/make) | Makefile — это файл, содержащий набор директив, используемых инструментом автоматизации сборки make для создания target/goal |
| static [MARKDN](../../groupdocs.comparison.result/filetype/markdn) | Формат языка уценки |
| static [MARKDOWN](../../groupdocs.comparison.result/filetype/markdown) | Формат языка уценки |
| static [MD](../../groupdocs.comparison.result/filetype/md) | Формат языка уценки |
| static [MDOWN](../../groupdocs.comparison.result/filetype/mdown) | Формат языка уценки |
| static [MDTEXT](../../groupdocs.comparison.result/filetype/mdtext) | Формат языка уценки |
| static [MDTXT](../../groupdocs.comparison.result/filetype/mdtxt) | Формат языка уценки |
| static [MDWN](../../groupdocs.comparison.result/filetype/mdwn) | Формат языка уценки |
| static [MHTML](../../groupdocs.comparison.result/filetype/mhtml) | Мим HTML |
| static [MJS](../../groupdocs.comparison.result/filetype/mjs) | Расширение для файлов модуля EcmaScript (ES) |
| static [MK](../../groupdocs.comparison.result/filetype/mk) | Makefile — это файл, содержащий набор директив, используемых инструментом автоматизации сборки make для создания target/goal |
| static [MKD](../../groupdocs.comparison.result/filetype/mkd) | Формат языка уценки |
| static [ML](../../groupdocs.comparison.result/filetype/ml) | Формат языка программирования Caml |
| static [MLI](../../groupdocs.comparison.result/filetype/mli) | Формат языка программирования Caml |
| static [MOBI](../../groupdocs.comparison.result/filetype/mobi) | Формат электронной книги Mobipocket |
| static [MSG](../../groupdocs.comparison.result/filetype/msg) | Сообщение электронной почты Microsoft Outlook |
| static [NQP](../../groupdocs.comparison.result/filetype/nqp) | Промежуточный язык, используемый для сборки компилятора Rakudo Perl 6 |
| static [OBJC](../../groupdocs.comparison.result/filetype/objc) | Формат языка программирования Objective-C |
| static [OBJCP](../../groupdocs.comparison.result/filetype/objcp) | Формат языка программирования Objective-C++ |
| static [ODP](../../groupdocs.comparison.result/filetype/odp) | Презентация OpenDocument |
| static [ODS](../../groupdocs.comparison.result/filetype/ods) | Электронная таблица OpenDocument |
| static [ODT](../../groupdocs.comparison.result/filetype/odt) | Текст OpenDocument |
| static [ONE](../../groupdocs.comparison.result/filetype/one) | Документ Microsoft OneNote |
| static [OTP](../../groupdocs.comparison.result/filetype/otp) | Шаблон презентации OpenDocument |
| static [OTT](../../groupdocs.comparison.result/filetype/ott) | Текстовый шаблон OpenDocument |
| static [P6](../../groupdocs.comparison.result/filetype/p6) | Формат языка программирования Perl |
| static [PAC](../../groupdocs.comparison.result/filetype/pac) | Файл автоконфигурации прокси для функции JavaScript format |
| static [PATCH](../../groupdocs.comparison.result/filetype/patch) | Список отличий format |
| static [PDF](../../groupdocs.comparison.result/filetype/pdf) | Формат переносимых документов Adobe |
| static [PHP](../../groupdocs.comparison.result/filetype/php) | Формат языка программирования PHP |
| static [PHP4](../../groupdocs.comparison.result/filetype/php4) | Формат языка программирования PHP |
| static [PHP5](../../groupdocs.comparison.result/filetype/php5) | Формат языка программирования PHP |
| static [PHTML](../../groupdocs.comparison.result/filetype/phtml) | Стандартное расширение файла для программ PHP 2 format |
| static [PL](../../groupdocs.comparison.result/filetype/pl) | Формат языка программирования Perl |
| static [PL6](../../groupdocs.comparison.result/filetype/pl6) | Формат языка программирования Perl |
| static [PM](../../groupdocs.comparison.result/filetype/pm) | Формат модуля Perl |
| static [PM6](../../groupdocs.comparison.result/filetype/pm6) | Формат модуля Perl |
| static [PNG](../../groupdocs.comparison.result/filetype/png) | Портативная сетевая графика |
| static [POD](../../groupdocs.comparison.result/filetype/pod) | Облегченный формат языка разметки Perl |
| static [PODSPEC](../../groupdocs.comparison.result/filetype/podspec) | Формат настроек сборки Ruby |
| static [POT](../../groupdocs.comparison.result/filetype/pot) | Шаблон Microsoft PowerPoint |
| static [POTX](../../groupdocs.comparison.result/filetype/potx) | Шаблон Microsoft PowerPoint |
| static [PPS](../../groupdocs.comparison.result/filetype/pps) | Слайд-шоу Microsoft PowerPoint 97-2003 |
| static [PPSX](../../groupdocs.comparison.result/filetype/ppsx) | Слайд-шоу Microsoft PowerPoint |
| static [PPT](../../groupdocs.comparison.result/filetype/ppt) | Презентация Microsoft PowerPoint 97-2003 |
| static [PPTX](../../groupdocs.comparison.result/filetype/pptx) | Презентация Microsoft PowerPoint |
| static [PROP](../../groupdocs.comparison.result/filetype/prop) | Формат файла свойств |
| static [PSGI](../../groupdocs.comparison.result/filetype/psgi) | Интерфейс между веб-серверами и веб-приложениями и фреймворками, написанными на языке программирования Perl |
| static [PY](../../groupdocs.comparison.result/filetype/py) | Формат языка программирования Python |
| static [PYI](../../groupdocs.comparison.result/filetype/pyi) | Формат файла интерфейса Python |
| static [PYW](../../groupdocs.comparison.result/filetype/pyw) | Файлы, используемые в Windows для указания того, что сценарий необходимо запустить |
| static [RAKE](../../groupdocs.comparison.result/filetype/rake) | Инструмент автоматизации сборки Ruby |
| static [RB](../../groupdocs.comparison.result/filetype/rb) | Формат языка программирования Ruby |
| static [RBI](../../groupdocs.comparison.result/filetype/rbi) | Формат файла интерфейса Ruby |
| static [REJ](../../groupdocs.comparison.result/filetype/rej) | Отклоненные файлы формата |
| static [RJS](../../groupdocs.comparison.result/filetype/rjs) | Формат языка программирования Ruby |
| static [RPY](../../groupdocs.comparison.result/filetype/rpy) | Файловый движок на основе Python для создания и запуска игр |
| static [RST](../../groupdocs.comparison.result/filetype/rst) | Облегченный язык разметки |
| static [RTF](../../groupdocs.comparison.result/filetype/rtf) | Форматированный текстовый документ |
| static [RU](../../groupdocs.comparison.result/filetype/ru) | Формат файла конфигурации стойки |
| static [SASS](../../groupdocs.comparison.result/filetype/sass) | Формат языка таблицы стилей |
| static [SBT](../../groupdocs.comparison.result/filetype/sbt) | Инструмент сборки SBT для формата Scala |
| static [SC](../../groupdocs.comparison.result/filetype/sc) | Формат рабочего листа Scala |
| static [SCALA](../../groupdocs.comparison.result/filetype/scala) | Формат языка программирования Scala |
| static [SCSS](../../groupdocs.comparison.result/filetype/scss) | Формат языка таблицы стилей |
| static [SH](../../groupdocs.comparison.result/filetype/sh) | Скрипт, запрограммированный для формата bash |
| static [SQL](../../groupdocs.comparison.result/filetype/sql) | Формат языка структурированных запросов |
| static [SVG](../../groupdocs.comparison.result/filetype/svg) | Скалярная векторная графика |
| static [T](../../groupdocs.comparison.result/filetype/t) | Формат тестового файла Perl |
| static [TXT](../../groupdocs.comparison.result/filetype/txt) | Простой текстовый документ |
| static [UNKNOWN](../../groupdocs.comparison.result/filetype/unknown) | Неизвестный тип |
| static [VDX](../../groupdocs.comparison.result/filetype/vdx) | XML-чертеж Microsoft Visio 2003–2010 |
| static [VIM](../../groupdocs.comparison.result/filetype/vim) | Формат файла исходного кода Vim |
| static [VSD](../../groupdocs.comparison.result/filetype/vsd) | Microsoft Visio 2003-2010 Drawing |
| static [VSDX](../../groupdocs.comparison.result/filetype/vsdx) | Рисунок Microsoft Visio |
| static [VSS](../../groupdocs.comparison.result/filetype/vss) | Microsoft Visio 2003-2010 Stencil |
| static [VST](../../groupdocs.comparison.result/filetype/vst) | Шаблон Microsoft Visio 2003–2010 |
| static [WEBMANIFEST](../../groupdocs.comparison.result/filetype/webmanifest) | Файл манифеста содержит информацию о приложении |
| static [XLS](../../groupdocs.comparison.result/filetype/xls) | Рабочий лист Microsoft Excel 97-2003 |
| static [XLSB](../../groupdocs.comparison.result/filetype/xlsb) | Двоичный рабочий лист Microsoft Excel |
| static [XLSM](../../groupdocs.comparison.result/filetype/xlsm) | Рабочая таблица Microsoft Excel с поддержкой макросов |
| static [XLSX](../../groupdocs.comparison.result/filetype/xlsx) | Рабочий лист Microsoft Excel |
| static [XLT](../../groupdocs.comparison.result/filetype/xlt) | Шаблон Microsoft Excel |
| static [XLTM](../../groupdocs.comparison.result/filetype/xltm) | Шаблон Microsoft Excel с поддержкой макросов |
| static [YAML](../../groupdocs.comparison.result/filetype/yaml) | Удобочитаемый формат языка сериализации данных |
| static [YML](../../groupdocs.comparison.result/filetype/yml) | Удобочитаемый формат языка сериализации данных |

### Примечания

**Учить больше**

* Узнайте больше о форматах файлов, поддерживаемых GroupDocs. Сравнение: [Полный список поддерживаемых форматов документов](https://docs.groupdocs.com/display/comparisonnet/Supported+Document+Formats)
* Узнайте больше о получении поддерживаемых типов файлов в C#: [Как получить поддерживаемые форматы файлов в C#](https://docs.groupdocs.com/display/comparisonnet/Get+supported+file+formats)

### Смотрите также

* пространство имен [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* сборка [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
