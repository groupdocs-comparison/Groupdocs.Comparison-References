---
title: "SensitivityOfComparisonForTables"
second_title: "Referencia de API de GroupDocs.Comparison para .NET"
description: "Obtiene o establece la sensibilidad de la comparación para tablas."
type: docs
weight: 220
url: /es/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables/
---
## CompareOptions.SensitivityOfComparisonForTables property

Obtiene o establece la sensibilidad de la comparación para tablas.

```csharp
public int? SensitivityOfComparisonForTables { get; set; }
```

### Property Value

Si el valor es nulo, se utiliza SensitivityOfComparison en su lugar. El porcentaje de elementos eliminados e insertados de dos objetos comparados en relación con todos los elementos de dichos objetos. Si este porcentaje se supera, el objeto no se compara sino que se considera completamente insertado y eliminado. Valor mínimo - 0% => La comparación no se realiza para ninguna longitud de la subsecuencia común de dos objetos comparados. Valor predeterminado - 75% => La comparación ocurre si el porcentaje de elementos eliminados e insertados de dos objetos comparados respecto a todos los elementos de dichos objetos no supera el 75%. Valor máximo - 100% => La comparación ocurre para cualquier longitud de la subsecuencia común de dos objetos comparados.

### Ver también

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Comparison.dll -->
