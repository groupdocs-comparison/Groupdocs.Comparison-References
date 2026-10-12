---
title: "Лицензия"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Класс License предоставляет методы для установки и применения лицензий для GroupDocs.Comparison."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Класс License предоставляет методы для установки и применения лицензий для GroupDocs.Comparison.


Это позволяет включать или отключать определённые функции библиотеки в зависимости от применённой лицензии.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Пример использования:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [License()](#License--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | Возвращает значение, указывающее, была ли установлена лицензия. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Устанавливает лицензию для Comparison, используя поток ввода. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Устанавливает лицензию для Comparison, используя путь к файлу лицензии. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Устанавливает лицензию для Comparison, используя путь к файлу лицензии. |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


Возвращает значение, указывающее, была ли установлена лицензия.


**Returns:**
boolean — true, если лицензия была успешно установлена, иначе false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Устанавливает лицензию для Comparison, используя поток ввода.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Поток лицензии, null сбрасывает лицензию. |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Устанавливает лицензию для Comparison, используя путь к файлу лицензии.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Путь к файлу лицензии. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Устанавливает лицензию для Comparison, используя путь к файлу лицензии.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | licensePath | java.lang.String | Путь к файлу лицензии. |
|

