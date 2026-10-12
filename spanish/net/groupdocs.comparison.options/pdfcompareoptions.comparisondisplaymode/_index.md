---
title: "PdfCompareOptions.ComparisonDisplayMode"
second_title: "Referencia de API de GroupDocs.Comparison para .NET"
description: "Controla cómo se dispone el documento resultante de la comparación PDF."
type: docs
weight: 370
url: /es/net/groupdocs.comparison.options/pdfcompareoptions.comparisondisplaymode/
---
## PdfCompareOptions.ComparisonDisplayMode enumeration

Controla cómo se dispone el documento resultante de la comparación PDF.

```csharp
public enum ComparisonDisplayMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Inline | `0` | Modo predeterminado. Produce un único documento PDF fusionado donde el contenido eliminado se resalta en un color y el contenido insertado en otro. Tanto el contenido de origen como el de destino coexisten en las mismas páginas, lo que puede causar superposición cuando los documentos difieren significativamente. |
| SideBySide | `1` | Cada página de resultados muestra una página de origen y su página de destino correspondiente una al lado de la otra. Las eliminaciones aparecen a la izquierda (lado de origen) y las inserciones a la derecha (lado de destino). El contenido de los dos documentos nunca se superpone, lo que hace que este modo sea adecuado cuando los documentos difieren mucho. |
| Interleaved | `2` | Produce un documento con páginas alternas: las páginas impares provienen del documento de origen (mostrando eliminaciones) y las páginas pares provienen del documento de destino (mostrando inserciones). Abra el resultado en un visor PDF con la vista "Two Page View" habilitada para ver cada par origen/destino lado a lado en pantalla. Al igual que SideBySide, este modo evita la superposición de contenido y es más adecuado para documentos con diferencias pronunciadas. |

### Ver también

* class [PdfCompareOptions](../pdfcompareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Comparison.dll -->
