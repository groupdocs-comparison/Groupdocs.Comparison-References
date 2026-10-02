---
title: "Licencia"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "La clase License proporciona métodos para establecer y aplicar licencias para GroupDocs.Comparison."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

La clase License proporciona métodos para establecer y aplicar licencias para GroupDocs.Comparison.


Permite habilitar o deshabilitar funciones específicas de la biblioteca según la licencia aplicada.

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


Ejemplo de uso:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
| [License()](#License--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | Obtiene un valor que indica si la licencia se estableció o no. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Establece una licencia para Comparison usando un flujo de entrada. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Establece una licencia para Comparison usando la ruta del archivo de licencia. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Establece una licencia para Comparison usando la ruta del archivo de licencia. |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


Obtiene un valor que indica si la licencia se estableció o no.


**Returns:**
booleano - true si la licencia se estableció correctamente, de lo contrario false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Establece una licencia para Comparison usando un flujo de entrada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | El flujo de licencia, null restablece la licencia |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Establece una licencia para Comparison usando la ruta del archivo de licencia.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | La ruta del archivo de licencia |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Establece una licencia para Comparison usando la ruta del archivo de licencia.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | licensePath | java.lang.String | La ruta del archivo de licencia |
|

