---
title: Comparer
second_title: GroupDocs.Comparison para la referencia de la API de .NET
description: Representa la clase principal que controla el proceso de comparación de documentos.
type: docs
weight: 100
url: /es/net/groupdocs.comparison/comparer/
---
## Comparer class

Representa la clase principal que controla el proceso de comparación de documentos.

```csharp
public class Comparer : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Inicializa una nueva instancia de[`Comparer`](../comparer) clase con documento de origen stream. |
| [Comparer](comparer#constructor_4)(string) | Inicializa una nueva instancia de[`Comparer`](../comparer) clase con la ruta del archivo fuente. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Inicializa una nueva instancia de[`Comparer`](../comparer)clase con secuencia de documento de origen y[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Inicializa una nueva instancia de[`Comparer`](../comparer) con flujo de documentos de origen y[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Inicializa una nueva instancia de[`Comparer`](../comparer) clase con la ruta del archivo fuente y[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_6)(string, LoadOptions) | Inicializa una nueva instancia de[`Comparer`](../comparer) con la ruta del archivo fuente y[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Inicializa una nueva instancia de[`Comparer`](../comparer) clase con flujo de documentos,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) y[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_7)(string, LoadOptions, ComparerSettings) | Inicializa una nueva instancia de[`Comparer`](../comparer) clase con la ruta del archivo fuente,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) y[`ComparerSettings`](../comparersettings) . |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Archivo fuente que se está comparando. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Lista de archivos de destino para comparar con el archivo de origen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Agrega flujo de documentos a la comparación. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Agrega archivo a la comparación. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Agrega flujo de documentos a la comparación con las opciones de carga especificadas. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, LoadOptions) | Agrega el archivo a la comparación con las opciones de carga especificadas. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Acepta o rechaza los cambios y los aplica al documento resultante. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Acepta o rechaza los cambios y los aplica al documento resultante. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Acepta o rechaza los cambios y los aplica al documento resultante. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Acepta o rechaza los cambios y los aplica al documento resultante. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Compara documentos sin guardar el resultado con opciones predeterminadas |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Compara documentos sin guardar resultado. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Compara documentos y guarda el resultado en el archivo stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Compara documentos y guarda el resultado en la ruta del archivo |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Compara documentos sin guardar resultado. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Compara documentos y guarda el resultado en el archivo stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Compara documentos y guarda el resultado en el archivo stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Compara documentos y guarda el resultado en la ruta del archivo |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Compara documentos y guarda el resultado en la ruta del archivo |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Compara documentos y guarda el resultado en una secuencia. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Compara documentos y guarda el resultado en la ruta del archivo |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Libera recursos. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Obtiene una lista de cambios entre los archivos de origen y de destino. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(GetChangeOptions) | Obtiene una lista de cambios entre los archivos de origen y de destino. |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Obtener cadena de resultado después de la comparación (solo para comparación de texto). |

### Ver también

* espacio de nombres [GroupDocs.Comparison](../../groupdocs.comparison)
* asamblea [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
