---
title: "Comparador"
second_title: "Referencia de API de GroupDocs.Comparison para .NET"
description: "Representa la clase principal que controla el proceso de comparación de documentos."
type: docs
weight: 100
url: /es/net/groupdocs.comparison/comparer/
---
## Comparer class

Representa la clase principal que controla el proceso de comparación de documentos.

```csharp
public sealed class Comparer : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Inicializa una nueva instancia de la clase [`Comparer`](../comparer) con la secuencia del documento fuente. |
| [Comparer](comparer#constructor_4)(string) | Inicializa una nueva instancia de la clase [`Comparer`](../comparer) con la ruta del archivo fuente. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Inicializa una nueva instancia de la clase [`Comparer`](../comparer) con la secuencia del documento fuente y [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Inicializa una nueva instancia de [`Comparer`](../comparer) con la secuencia del documento fuente y [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | Inicializa una nueva instancia de [`Comparer`](../comparer) con la ruta de la carpeta fuente y [`CompareOptions`](../../groupdocs.comparison.options/compareoptions). |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Inicializa una nueva instancia de la clase [`Comparer`](../comparer) con la ruta del archivo fuente y [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | Inicializa una nueva instancia de [`Comparer`](../comparer) con la ruta del archivo fuente y [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Inicializa una nueva instancia de la clase [`Comparer`](../comparer) con el flujo del documento, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) y [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | Inicializa una nueva instancia de la clase [`Comparer`](../comparer) con la ruta del archivo fuente, [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) y [`ComparerSettings`](../comparersettings). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | Documento resultante. |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Archivo fuente que se está comparando. |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | Carpeta fuente que se está comparando. |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | Carpeta de destino que se está comparando. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Lista de archivos de destino para comparar con el archivo fuente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Agrega un flujo de documento a la comparación. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Agrega un archivo a la comparación. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Agrega un flujo de documento a la comparación con las opciones de carga especificadas. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | Agrega una carpeta a la comparación. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | Agrega un archivo a la comparación con las opciones de carga especificadas. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Acepta o rechaza cambios y los aplica al documento resultante. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Acepta o rechaza cambios y los aplica al documento resultante. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Acepta o rechaza cambios y los aplica al documento resultante. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Acepta o rechaza cambios y los aplica al documento resultante. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Compara documentos sin guardar el resultado con opciones predeterminadas |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Compara documentos sin guardar el resultado. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Compara documentos y guarda el resultado en un flujo de archivo |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Compara documentos y guarda el resultado en la ruta del archivo |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Compara documentos sin guardar el resultado. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Compara documentos y guarda el resultado en un flujo de archivo |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Compara documentos y guarda el resultado en un flujo de archivo |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Compara documentos y guarda el resultado en la ruta del archivo |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Compara documentos y guarda el resultado en la ruta del archivo |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Compara documentos y guarda el resultado en un flujo. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Compara documentos y guarda el resultado en la ruta del archivo |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | Compara directorios y guarda el resultado en la ruta del archivo |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Libera recursos. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Obtiene la lista de cambios entre el archivo(s) fuente y destino. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | Obtiene la lista de cambios entre el archivo(s) fuente y destino. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | Obtiene la lista de cambios entre el archivo(s) fuente y destino. |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | Obtiene el flujo del documento resultante, devuelve null si el flujo no existe |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Obtener cadena de resultado después de la comparación (solo para comparación de texto). |

### Ver también

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Comparison.dll -->
