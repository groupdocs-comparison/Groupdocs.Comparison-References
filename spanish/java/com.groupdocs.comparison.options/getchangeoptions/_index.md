---
title: "GetChangeOptions"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Permite configurar filtros para obtener tipos de cambios específicos del resultado de la comparación."
type: docs
weight: 13
url: /es/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

Permite configurar filtros para obtener tipos de cambios específicos del resultado de la comparación.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | Inicializa una nueva instancia de la clase GetChangeOptions. |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | Inicializa una nueva instancia de la clase GetChangeOptions para el tipo de filtro especificado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFilter()](#getFilter--) | Obtiene el filtro para recuperar tipos de cambio específicos del resultado de la comparación. |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | Establece el filtro para recuperar tipos de cambio específicos del resultado de la comparación. |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


Inicializa una nueva instancia de la clase GetChangeOptions.


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


Inicializa una nueva instancia de la clase GetChangeOptions para el tipo de filtro especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


Obtiene el filtro para recuperar tipos de cambio específicos del resultado de la comparación.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


Establece el filtro para recuperar tipos de cambio específicos del resultado de la comparación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | El filtro que especifica los tipos de cambios a recuperar. |
|

