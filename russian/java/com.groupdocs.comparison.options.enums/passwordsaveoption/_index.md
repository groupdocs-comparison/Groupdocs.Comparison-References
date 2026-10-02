---
title: "PasswordSaveOption"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Перечисляет варианты сохранения информации о пароле в документе во время процесса сравнения."
type: docs
weight: 14
url: /ru/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

Перечисляет варианты сохранения информации о пароле в документе во время процесса сравнения.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [NONE](#NONE) | Не сохранять пароль. |
|
|  | [SOURCE](#SOURCE) | Использовать пароль из исходного документа. |
|
|  | [TARGET](#TARGET) | Использовать пароль из целевого документа. |
|
|  | [USER](#USER) | \* Использовать пароль, предоставленный пользователем. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Разбирает строковое представление PasswordSaveOption, чтобы получить константу перечисления. |
|
|  | [toString()](#toString--) | Строковое представление PasswordSaveOption. |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


Не сохранять пароль.


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


Использовать пароль из исходного документа.


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


Использовать пароль из целевого документа.


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* Использовать пароль, предоставленный пользователем.


### values() {#values--}
```
public static PasswordSaveOption[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PasswordSaveOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PasswordSaveOption valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


Разбирает строковое представление PasswordSaveOption, чтобы получить константу перечисления.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Строковое представление PasswordSaveOption |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Строковое представление PasswordSaveOption.


**Returns:**
java.lang.String — строковое значение константы перечисления

