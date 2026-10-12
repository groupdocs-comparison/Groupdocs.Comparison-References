---
title: "ComparisonLogger"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Implementa métodos de registro y una forma de configurar un registrador integrado o establecer un registrador definido por el usuario."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

Implementa métodos de registro y una forma de configurar un registrador integrado o establecer un registrador definido por el usuario.


La clase permite configurar un logger integrado o personalizado y escribir mensajes de registro.


Ejemplo de uso:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## Métodos

| Método | Descripción |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Escribe un mensaje de traza al logger preconfigurado. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Escribe un mensaje de traza, stacktrace y mensaje de una excepción al logger preconfigurado. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Comprueba si el registro de traza está habilitado en el logger preconfigurado. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Escribe un mensaje de depuración al logger preconfigurado. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Escribe un mensaje de depuración, stacktrace y mensaje de una excepción al logger preconfigurado. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Comprueba si el registro de depuración está habilitado en el logger preconfigurado. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Escribe un mensaje de advertencia al logger preconfigurado. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Escribe un mensaje de advertencia, stacktrace y mensaje de una excepción al logger preconfigurado. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Comprueba si el registro de advertencia está habilitado en el logger preconfigurado. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Escribe un mensaje de error al logger preconfigurado. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Escribe un mensaje de error, stacktrace y mensaje de una excepción al logger preconfigurado. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Comprueba si el registro de error está habilitado en el logger preconfigurado. |
|
|  | [getLogger()](#getLogger--) | Obtiene el logger preconfigurado que se utilizará para escribir todo tipo de registros. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Establece el logger que se utilizará para escribir todo tipo de registros. |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Escribe un mensaje de traza al logger preconfigurado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | message | java.lang.String | El mensaje, si es nulo, el comportamiento depende del logger |
|
|  | arguments | java.lang.Object[] | Los argumentos que se incrustarán en el mensaje, si es nulo, el comportamiento depende del logger |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Escribe un mensaje de traza, stacktrace y mensaje de una excepción al logger preconfigurado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | El objeto throwable que se usará para obtener el stacktrace, si es nulo, el comportamiento depende del logger |
|
|  | message | java.lang.String | El mensaje, si es nulo, el comportamiento depende del logger |
|
|  | arguments | java.lang.Object[] | Los argumentos que se incrustarán en el mensaje, si es nulo, el comportamiento depende del logger |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Comprueba si el registro de traza está habilitado en el logger preconfigurado.


**Returns:**
boolean - true si está habilitado en el logger preconfigurado, de lo contrario false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Escribe un mensaje de depuración al logger preconfigurado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | message | java.lang.String | El mensaje, si es nulo, el comportamiento depende del logger |
|
|  | arguments | java.lang.Object[] | Los argumentos que se incrustarán en el mensaje, si es nulo, el comportamiento depende del logger |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Escribe un mensaje de depuración, stacktrace y mensaje de una excepción al logger preconfigurado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | El objeto throwable que se usará para obtener el stacktrace, si es nulo, el comportamiento depende del logger |
|
|  | message | java.lang.String | El mensaje, si es nulo, el comportamiento depende del logger |
|
|  | arguments | java.lang.Object[] | Los argumentos que se incrustarán en el mensaje, si es nulo, el comportamiento depende del logger |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Comprueba si el registro de depuración está habilitado en el logger preconfigurado.


**Returns:**
boolean - true si está habilitado en el logger preconfigurado, de lo contrario false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Escribe un mensaje de advertencia al logger preconfigurado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | message | java.lang.String | El mensaje, si es nulo, el comportamiento depende del logger |
|
|  | arguments | java.lang.Object[] | Los argumentos que se incrustarán en el mensaje, si es nulo, el comportamiento depende del logger |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Escribe un mensaje de advertencia, stacktrace y mensaje de una excepción al logger preconfigurado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | El objeto throwable que se usará para obtener el stacktrace, si es nulo, el comportamiento depende del logger |
|
|  | message | java.lang.String | El mensaje, si es nulo, el comportamiento depende del logger |
|
|  | arguments | java.lang.Object[] | Los argumentos que se incrustarán en el mensaje, si es nulo, el comportamiento depende del logger |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Comprueba si el registro de advertencia está habilitado en el logger preconfigurado.


**Returns:**
boolean - true si está habilitado en el logger preconfigurado, de lo contrario false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Escribe un mensaje de error al logger preconfigurado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | message | java.lang.String | El mensaje, si es nulo, el comportamiento depende del logger |
|
|  | arguments | java.lang.Object[] | Los argumentos que se incrustarán en el mensaje, si es nulo, el comportamiento depende del logger |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Escribe un mensaje de error, stacktrace y mensaje de una excepción al logger preconfigurado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | El objeto throwable que se usará para obtener el stacktrace, si es nulo, el comportamiento depende del logger |
|
|  | message | java.lang.String | El mensaje, si es nulo, el comportamiento depende del logger |
|
|  | arguments | java.lang.Object[] | Los argumentos que se incrustarán en el mensaje, si es nulo, el comportamiento depende del logger |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Comprueba si el registro de error está habilitado en el logger preconfigurado.


**Returns:**
boolean - true si está habilitado en el logger preconfigurado, de lo contrario false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Obtiene el logger preconfigurado que se utilizará para escribir todo tipo de registros.


**Returns:**
com.groupdocs.foundation.logging.ILogger - el logger

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Establece el logger que se utilizará para escribir todo tipo de registros.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | El logger |
|

