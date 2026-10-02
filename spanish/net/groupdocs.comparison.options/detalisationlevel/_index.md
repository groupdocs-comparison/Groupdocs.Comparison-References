---
title: "DetalisationLevel"
second_title: "Referencia de API de GroupDocs.Comparison para .NET"
description: "Especifica el nivel de detalle de la comparación."
type: docs
weight: 230
url: /es/net/groupdocs.comparison.options/detalisationlevel/
---
## DetalisationLevel enumeration

Especifica el nivel de detalle de la comparación.

```csharp
public enum DetalisationLevel
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Low | `0` | Nivel bajo. Proporciona la comparación más rápida sacrificando la calidad de la comparación. La comparación se realiza por palabra. |
| Middle | `1` | Nivel medio. Un compromiso razonable entre la velocidad y la calidad de la comparación. La comparación se realiza por carácter, pero ignorando mayúsculas y minúsculas y el recuento de espacios. |
| High | `2` | Nivel alto. La mejor calidad de comparación, pero la velocidad más baja. La comparación se realiza por carácter considerando mayúsculas y minúsculas y el recuento de espacios. |

### Ver también

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Comparison.dll -->
