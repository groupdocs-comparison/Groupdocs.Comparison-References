---
title: "MemoryCleaner"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Очищает различные ресурсы для освобождения памяти."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.common/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Очищает различные ресурсы для освобождения памяти.


Этот класс предоставляет методы для очистки памяти кучи, удаления временных файлов и очистки информации реестра шрифтов.
Он также включает метод для безопасной очистки thread-local экземпляров текущего потока.


Пример использования:

````

 // Clean heap memory, keeping font settings
 MemoryCleaner.clearKeepingFontSettings();

 // Clean heap memory and delete temp files
 MemoryCleaner.clear();

 // Clean heap memory from static PDF instances
 MemoryCleaner.clearStaticInstances();

 // Delete all temp files created by PDF in the system temp directory
 MemoryCleaner.clearAllTempFiles();

 // Clear font registry information from heap memory
 MemoryCleaner.clearFontRegistry();

 // Safely clear thread-local instances for the current thread
 MemoryCleaner.clearCurrentThreadLocals();
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Очищает память кучи от статических PDF‑экземпляров (static и threadLocal) и удаляет все временные файлы. |
|
|  | [clear()](#clear--) | Очищает память кучи от статических PDF‑экземпляров (static и threadLocal) и удаляет все временные файлы. |
|
|  | [clearStaticInstances()](#clearStaticInstances--) | Очищает память кучи от статических PDF‑экземпляров. |
|
|  | [clearAllTempFiles()](#clearAllTempFiles--) | Удаляет временные файлы, созданные GroupDocs.Comparison, в системном каталоге временных файлов. |
|
|  | [clearFontRegistry()](#clearFontRegistry--) | Очищает информацию реестра шрифтов из памяти кучи. |
|
|  | [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Безопасно очищает память кучи от thread-local экземпляров текущего потока. |
|
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Очищает память кучи от статических PDF‑экземпляров (static и threadLocal) и удаляет все временные файлы.
Этот метод не влияет на настройки шрифта.


### clear() {#clear--}
```
public static void clear()
```


Очищает память кучи от статических PDF‑экземпляров (static и threadLocal) и удаляет все временные файлы.


### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Очищает память кучи от статических PDF‑экземпляров.


### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Удаляет временные файлы, созданные GroupDocs.Comparison, в системном каталоге временных файлов.


### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Очищает информацию реестра шрифтов из памяти кучи.


### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Безопасно очищает память кучи от thread-local экземпляров текущего потока.


