---
title: "MemoryCleaner"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Limpia diferentes recursos para liberar memoria."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.common/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Limpia diferentes recursos para liberar memoria.


Esta clase proporciona métodos para liberar la memoria del montón, eliminar archivos temporales y borrar la información del registro de fuentes.
También incluye un método para borrar de forma segura las instancias thread-local del hilo actual.


Ejemplo de uso:

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


## Constructores

| Constructor | Descripción |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Libera la memoria del montón de las instancias PDF estáticas (estáticas y threadLocal) y elimina todos los archivos temporales. |
|
|  | [clear()](#clear--) | Libera la memoria del montón de las instancias PDF estáticas (estáticas y threadLocal) y elimina todos los archivos temporales. |
|
|  | [clearStaticInstances()](#clearStaticInstances--) | Libera la memoria del montón de las instancias PDF estáticas. |
|
|  | [clearAllTempFiles()](#clearAllTempFiles--) | Elimina los archivos temporales creados por GroupDocs.Comparison en el directorio temporal del sistema. |
|
|  | [clearFontRegistry()](#clearFontRegistry--) | Borra la información del registro de fuentes de la memoria del montón. |
|
|  | [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Borra de forma segura la memoria del montón de las instancias thread-local del hilo actual. |
|
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Libera la memoria del montón de las instancias PDF estáticas (estáticas y threadLocal) y elimina todos los archivos temporales.
Este método no afecta la configuración de fuentes.


### clear() {#clear--}
```
public static void clear()
```


Libera la memoria del montón de las instancias PDF estáticas (estáticas y threadLocal) y elimina todos los archivos temporales.


### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Libera la memoria del montón de las instancias PDF estáticas.


### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Elimina los archivos temporales creados por GroupDocs.Comparison en el directorio temporal del sistema.


### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Borra la información del registro de fuentes de la memoria del montón.


### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Borra de forma segura la memoria del montón de las instancias thread-local del hilo actual.


