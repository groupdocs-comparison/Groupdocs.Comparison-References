---
title: "LoadOptions"
second_title: "Referencia de API de GroupDocs.Comparison para .NET"
description: "Permite especificar opciones adicionales al cargar un documento."
type: docs
weight: 300
url: /es/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

Permite especificar opciones adicionales al cargar un documento.

```csharp
public class LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LoadOptions](loadoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | Establezca manualmente el tipo de archivo para la comparación para sobrescribir la detección automática del tipo de archivo. |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | Lista de directorios de fuentes para cargar. |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | Indica que las cadenas pasadas son texto de comparación, no rutas de archivo (solo para Comparación de Texto). |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | Contraseña del documento. |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | Desactiva la carga de todos los recursos externos (p. ej., imágenes referenciadas por una URL remota) excepto [`WhitelistedResources`](./whitelistedresources). |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | La lista de fragmentos de URL correspondientes a recursos externos que deben cargarse cuando [`SkipExternalResources`](./skipexternalresources) está configurado en `true`. |

### Ver también

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Comparison.dll -->
