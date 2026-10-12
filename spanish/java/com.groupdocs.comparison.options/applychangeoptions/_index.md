---
title: "ApplyChangeOptions"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Permite actualizar la lista de cambios antes de aplicarlos al documento resultante."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

Permite actualizar la lista de cambios antes de aplicarlos al documento resultante.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | Inicializa una nueva instancia de la clase ApplyChangeOptions. |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Inicializa una nueva instancia de la clase ApplyChangeOptions con una lista de cambios. |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | Inicializa una nueva instancia de la clase ApplyChangeOptions con una matriz de cambios. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getChanges()](#getChanges--) | Obtiene una matriz de cambios que deben aplicarse al documento resultante. |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | Establece una matriz de cambios que deben aplicarse al documento resultante. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Establece una lista de cambios que deben aplicarse al documento resultante. |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | Obtiene una bandera que determina si el estado original debe guardarse. |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | Establece una bandera que determina si el estado original debe guardarse. |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


Inicializa una nueva instancia de la clase ApplyChangeOptions.


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


Inicializa una nueva instancia de la clase ApplyChangeOptions con una lista de cambios.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | cambios | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | La lista de cambios a aplicar |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


Inicializa una nueva instancia de la clase ApplyChangeOptions con una matriz de cambios.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | La lista de cambios a aplicar |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Obtiene una matriz de cambios que deben aplicarse al documento resultante.


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - la matriz de cambios a aplicar

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


Establece una matriz de cambios que deben aplicarse al documento resultante.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | La matriz de cambios a aplicar |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Establece una lista de cambios que deben aplicarse al documento resultante.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | La lista de cambios a aplicar |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


Obtiene una bandera que determina si el estado original debe guardarse. Valor predeterminado: false.


**Returns:**
boolean - verdadero si el estado original debe guardarse, de lo contrario falso

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


Establece una bandera que determina si el estado original debe guardarse.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | saveOriginalState | boolean | Verdadero si el estado original debe guardarse, de lo contrario falso |
|

