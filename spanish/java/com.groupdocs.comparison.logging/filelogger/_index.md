---
title: "FileLogger"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Registrador que escribe los registros en un archivo."
type: docs
weight: 11
url: /es/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Registrador que escribe los registros en un archivo.


Debe usarse junto con [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger).


Ejemplo de uso:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | Inicializa una nueva instancia de la clase FileLogger con la ruta del archivo. |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Inicializa una nueva instancia de la clase FileLogger con la ruta del archivo y la configuración de niveles de registro. |
|
## Campos

| Campo | Descripción |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Escribe un mensaje de traza en el archivo. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Escribe un mensaje de traza en el archivo. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Comprueba si el registro de traza está habilitado. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Escribe un mensaje de depuración en el archivo. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Escribe un mensaje de depuración en el archivo. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Comprueba si el registro de depuración está habilitado. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Escribe un mensaje de advertencia en el archivo. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Escribe un mensaje de advertencia en el archivo. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Comprueba si el registro de advertencia está habilitado. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Escribe un mensaje de error en el archivo. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Escribe un mensaje de error en el archivo. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Comprueba si el registro de error está habilitado. |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


Inicializa una nueva instancia de la clase FileLogger con la ruta del archivo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al archivo que se utilizará para escribir registros |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Inicializa una nueva instancia de la clase FileLogger con la ruta del archivo y la configuración de niveles de registro.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al archivo que se utilizará para escribir registros |
|
|  | isTraceEnabled | boolean | Verdadero para habilitar el registro de trazas, falso en caso contrario |
|
|  | isDebugEnabled | boolean | Verdadero para habilitar el registro de depuración, falso en caso contrario |
|
|  | isWarningEnabled | boolean | Verdadero para habilitar el registro de advertencias, falso en caso contrario |
|
|  | isErrorEnabled | boolean | Verdadero para habilitar el registro de errores, falso en caso contrario |
|

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


Escribe un mensaje de traza en el archivo.


Los mensajes de registro de trazas proporcionan la información más detallada sobre el flujo de la aplicación.
El mensaje puede contener uno o varios {} que serán reemplazados por los argumentos correspondientes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | message | java.lang.String | El mensaje. |
|
|  | arguments | java.lang.Object[] | Los argumentos, reemplazan {} en el mensaje según el orden de paso; null se escribirá como 'null' |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Escribe un mensaje de traza en el archivo.


Los mensajes de registro de trazas proporcionan la información más detallada sobre el flujo de la aplicación.
El mensaje puede contener uno o varios {} que serán reemplazados por los argumentos correspondientes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | El objeto throwable que se utilizará para obtener la traza de pila |
|
|  | message | java.lang.String | El mensaje. |
|
|  | arguments | java.lang.Object[] | Los argumentos, reemplazan {} en el mensaje según el orden de paso; null se escribirá como 'null' |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Comprueba si el registro de traza está habilitado.


**Returns:**
boolean - verdadero si está habilitado, de lo contrario falso

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Escribe un mensaje de depuración en el archivo.


Los mensajes de registro de depuración proporcionan información sobre diferentes procesos en el flujo de la aplicación.
El mensaje puede contener uno o varios {} que serán reemplazados por los argumentos correspondientes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | message | java.lang.String | El mensaje. |
|
|  | arguments | java.lang.Object[] | Los argumentos, reemplazan {} en el mensaje según el orden de paso; null se escribirá como 'null' |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Escribe un mensaje de depuración en el archivo.


Los mensajes de registro de depuración proporcionan información sobre diferentes procesos en el flujo de la aplicación.
El mensaje puede contener uno o varios {} que serán reemplazados por los argumentos correspondientes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | El objeto throwable que se utilizará para obtener la traza de pila |
|
|  | message | java.lang.String | El mensaje. |
|
|  | arguments | java.lang.Object[] | Los argumentos, reemplazan {} en el mensaje según el orden de paso; null se escribirá como 'null' |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Comprueba si el registro de depuración está habilitado.


**Returns:**
boolean - verdadero si está habilitado, de lo contrario falso

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Escribe un mensaje de advertencia en el archivo.


Los mensajes de registro de advertencia proporcionan información sobre eventos inesperados y recuperables en el flujo de la aplicación.
El mensaje puede contener uno o varios {} que serán reemplazados por los argumentos correspondientes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | message | java.lang.String | El mensaje. |
|
|  | arguments | java.lang.Object[] | Los argumentos, reemplazan {} en el mensaje según el orden de paso; null se escribirá como 'null' |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Escribe un mensaje de advertencia en el archivo.


Los mensajes de registro de advertencia proporcionan información sobre eventos inesperados y recuperables en el flujo de la aplicación.
El mensaje puede contener uno o varios {} que serán reemplazados por los argumentos correspondientes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | El objeto throwable que se utilizará para obtener la traza de pila |
|
|  | message | java.lang.String | El mensaje. |
|
|  | arguments | java.lang.Object[] | Los argumentos, reemplazan {} en el mensaje según el orden de paso; null se escribirá como 'null' |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Comprueba si el registro de advertencia está habilitado.


**Returns:**
boolean - verdadero si está habilitado, de lo contrario falso

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Escribe un mensaje de error en el archivo.


Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.
El mensaje puede contener uno o varios {} que serán reemplazados por los argumentos correspondientes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | message | java.lang.String | El mensaje. |
|
|  | arguments | java.lang.Object[] | Los argumentos, reemplazan {} en el mensaje según el orden de paso; null se escribirá como 'null' |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Escribe un mensaje de error en el archivo.


Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.
El mensaje puede contener uno o varios {} que serán reemplazados por los argumentos correspondientes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | El objeto throwable que se utilizará para obtener la traza de pila |
|
|  | message | java.lang.String | El mensaje. |
|
|  | arguments | java.lang.Object[] | Los argumentos, reemplazan {} en el mensaje según el orden de paso; null se escribirá como 'null' |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Comprueba si el registro de error está habilitado.


**Returns:**
boolean - verdadero si está habilitado, de lo contrario falso

