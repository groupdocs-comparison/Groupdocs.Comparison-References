---
title: "ChangeInfo"
second_title: "Referencia de API de GroupDocs.Comparison para .NET"
description: "Representa información sobre el cambio."
type: docs
weight: 460
url: /es/net/groupdocs.comparison.result/changeinfo/
---
## ChangeInfo class

Representa información sobre el cambio.

```csharp
public class ChangeInfo
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ChangeInfo](changeinfo)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Authors](../../groupdocs.comparison.result/changeinfo/authors) { get; set; } | Lista de autores. |
| [Box](../../groupdocs.comparison.result/changeinfo/box) { get; set; } | Coordenadas del elemento modificado. |
| [Column](../../groupdocs.comparison.result/changeinfo/column) { get; set; } | Índice de columna basado en cero de la celda modificada. Se rellena para el comparador de celdas (XLSX, CSV, ODS, etc.), null en caso contrario. |
| [ColumnHeader](../../groupdocs.comparison.result/changeinfo/columnheader) { get; set; } | Texto del encabezado de columna tomado de la primera fila de la hoja de cálculo para la columna correspondiente. Se rellena para el comparador de celdas cuando la primera fila contiene valores de encabezado, null en caso contrario. |
| [ComparisonAction](../../groupdocs.comparison.result/changeinfo/comparisonaction) { get; set; } | Acción (aceptar o rechazar). Este campo indica a la comparación qué hacer con este cambio. |
| [ComponentType](../../groupdocs.comparison.result/changeinfo/componenttype) { get; set; } | Tipo de componente modificado. |
| [Id](../../groupdocs.comparison.result/changeinfo/id) { get; set; } | Id del cambio. |
| [PageInfo](../../groupdocs.comparison.result/changeinfo/pageinfo) { get; set; } | Página donde se coloca el cambio actual. |
| [Row](../../groupdocs.comparison.result/changeinfo/row) { get; set; } | Índice de fila basado en cero de la celda modificada. Se rellena para el comparador de celdas (XLSX, CSV, ODS, etc.), null en caso contrario. |
| [SourceText](../../groupdocs.comparison.result/changeinfo/sourcetext) { get; set; } | Texto modificado del documento fuente. |
| [StyleChanges](../../groupdocs.comparison.result/changeinfo/stylechanges) { get; set; } | Matriz de cambios de estilo. |
| [TargetText](../../groupdocs.comparison.result/changeinfo/targettext) { get; set; } | Texto modificado del documento destino. |
| [Text](../../groupdocs.comparison.result/changeinfo/text) { get; set; } | Valor de texto del cambio. |
| [Type](../../groupdocs.comparison.result/changeinfo/type) { get; } | Tipo de cambio. |

### Ver también

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Comparison.dll -->
