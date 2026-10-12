---
title: "DiagramMasterSetting"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Representa la configuración para la comparación maestra de diagramas."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

Representa la configuración para la comparación maestra de diagramas.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final DiagramMasterSetting diagramMasterSetting = new DiagramMasterSetting();
    diagramMasterSetting.setMasterPath(masterFilePath);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDiagramMasterSetting(diagramMasterSetting);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | Inicializa una nueva instancia de la clase DiagramMasterSetting. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | Obtiene una bandera que indica si se usará la ruta maestra de origen. |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | Obtiene una bandera que indica si se debe usar la ruta maestra de origen. |
|
|  | [getMasterPath()](#getMasterPath--) | Obtiene una ruta maestra que se utilizará para renderizar documentos. |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | Establece una ruta maestra que debe usarse para renderizar documentos. |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


Inicializa una nueva instancia de la clase DiagramMasterSetting.


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


Obtiene una bandera que indica si se usará la ruta maestra de origen.


**Returns:**
boolean - verdadero si se mostrará la ruta maestra de origen, de lo contrario falso

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


Obtiene una bandera que indica si se debe usar la ruta maestra de origen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | verdadero si se debe mostrar la ruta maestra de origen, de lo contrario falso |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


Obtiene una ruta maestra que se utilizará para renderizar documentos. MasterPath es necesario para crear un documento resultante a partir de un conjunto de formas predeterminadas.


**Returns:**
java.lang.String - ruta del documento maestro si está establecida, de lo contrario ruta maestra predeterminada

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


Establece una ruta maestra que debe usarse para renderizar documentos. MasterPath es necesario para crear un documento resultante a partir de un conjunto de formas predeterminadas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | Ruta del documento maestro si está establecida, de lo contrario ruta maestra predeterminada |
|

