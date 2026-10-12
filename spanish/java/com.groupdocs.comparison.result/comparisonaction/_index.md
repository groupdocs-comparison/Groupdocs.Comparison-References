---
title: "ComparisonAction"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "El enum ComparisonAction representa las acciones que pueden aplicarse a un cambio durante el proceso de comparación de documentos."
type: docs
weight: 15
url: /es/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

El enum ComparisonAction representa las acciones que pueden aplicarse a un cambio durante el proceso de comparación de documentos.


Cada constante en este enum representa una acción específica y proporciona una descripción legible para humanos y un valor numérico.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         if (changeInfo.getId() % 2 == 0) {
             changeInfo.setComparisonAction(ComparisonAction.REJECT);
         }
     }
     comparer.applyChanges(resultFile, changes);
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
|  | [NONE](#NONE) | Representa ninguna acción. |
|
|  | [ACCEPT](#ACCEPT) | Representa una acción de aceptación. |
|
|  | [REJECT](#REJECT) | Representa una acción de rechazo. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analiza la representación en cadena de ComparisonAction para obtener la constante del enum. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Crea una nueva constante del enum ComparisonAction usando el valor numérico proporcionado. |
|
|  | [toString()](#toString--) | Representación en cadena de ComparisonAction. |
|
|  | [toInt()](#toInt--) | Representación numérica de ComparisonAction. |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


Representa ninguna acción. El cambio no tendrá ningún efecto.


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


Representa una acción de aceptación. El cambio será visible en el archivo resultante.


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


Representa una acción de rechazo. El cambio será invisible en el archivo resultante.


### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


Analiza la representación en cadena de ComparisonAction para obtener la constante del enum.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La representación en cadena de ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


Crea una nueva constante del enum ComparisonAction usando el valor numérico proporcionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | intValue | int | La representación numérica de ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Representación en cadena de ComparisonAction.


**Returns:**
java.lang.String - valor en cadena de la constante del enum

### toInt() {#toInt--}
```
public int toInt()
```


Representación numérica de ComparisonAction.


**Returns:**
int - valor numérico de la constante del enum

