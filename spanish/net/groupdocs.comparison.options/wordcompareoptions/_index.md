---
title: "WordCompareOptions"
second_title: "Referencia de API de GroupDocs.Comparison para .NET"
description: "Opciones de comparación específicas de documentos Word. Hereda opciones comunes de CompareOptions./compareoptions."
type: docs
weight: 440
url: /es/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Opciones de comparación específicas de documentos Word. Hereda opciones comunes de [`CompareOptions`](../compareoptions).

```csharp
public class WordCompareOptions : CompareOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | Inicializa una nueva instancia de la clase [`WordCompareOptions`](../wordcompareoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Indica si se deben calcular coordenadas para los componentes modificados. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Especifica el cálculo de coordenadas para el modo de componentes modificados. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Describe el estilo para los componentes modificados. |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | Obtiene o establece si los marcadores en los documentos origen y destino se comparan y las diferencias se incluyen en el resultado. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | Obtiene o establece si las propiedades de documento incorporadas y personalizadas se comparan y las diferencias se incluyen en el resultado (p. ej., en la página de resumen de propiedades). |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | Obtiene o establece si las propiedades variables del documento (p. ej., campos DOCVARIABLE) se comparan y las diferencias se incluyen en el resultado. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Describe el estilo para los componentes eliminados. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Obtiene o establece el nivel de detalle de la comparación. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Indica si se deben detectar cambios de estilo o no. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Obtiene o establece el valor de ruta para el maestro o usa la comparación sin ruta del maestro. Esta opción solo es para Diagram. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Control para activar la comparación de carpetas. |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | Obtiene o establece cómo se muestran los resultados de la comparación: como revisiones de Word en modo de Seguimiento de cambios (Revisions) o como cambios resaltados renderizados directamente en el documento (Highlight). |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Indica si se debe agregar información extendida de comparación de archivos a la página de resumen o no. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Obtiene o establece el formato del archivo de comparación de carpetas resultante. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Indica si se debe agregar una página de resumen con estadísticas de cambios detectados al documento resultante o no. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Control para activar la comparación del contenido de encabezado/pie de página. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Obtiene o establece la configuración para ignorar cambios basados en la similitud. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Describe el estilo para los componentes insertados. |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | Obtiene o establece si se dejan líneas vacías en lugar del contenido insertado o eliminado para preservar el diseño y el recuento de líneas; se usa con [`ShowInsertedContent`](../compareoptions/showinsertedcontent) y [`ShowDeletedContent`](../compareoptions/showdeletedcontent). |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Indica si se deben usar marcos para formas en Word Processing y para rectángulos en documentos de Image. |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | Obtiene o establece si los saltos de párrafo (línea) que difieren entre documentos se marcan visualmente en el resultado. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Obtiene o establece un valor que indica si se deben marcar los hijos del elemento eliminado o insertado como eliminados o insertados. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Obtiene o establece los tamaños originales de los documentos comparados. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Obtiene o establece el tamaño de papel del documento resultante. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Obtiene o establece la opción de guardado de contraseña. |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | Obtiene o establece el nombre del autor usado para revisiones cuando !:WordTrackChanges está habilitado. Si se establece, este nombre se aplica al marcado de revisión en el documento resultante. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Obtiene o establece la sensibilidad de la comparación. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Obtiene o establece la sensibilidad de la comparación para tablas. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Indica si se deben mostrar los componentes eliminados en el documento resultante o no. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Indica si se deben mostrar los componentes insertados en el documento resultante o no. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Controles para habilitar la visualización solo de los elementos modificados. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Indica si se debe dejar en el documento resultante solo una página con estadísticas de los cambios detectados en el documento resultante o no. |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | Obtiene o establece si el documento resultante mantiene visible el marcado de revisión. Si es false, todas las revisiones se aceptan y el resultado aparece como texto final. Esta configuración solo tiene sentido cuando [`DisplayMode`](./displaymode) está configurado en Highlight. El valor predeterminado es true. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Ruta a la plantilla maestra del usuario para Diagramas. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Obtiene o establece una matriz de delimitadores para dividir el texto en palabras. |

### Ver también

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Comparison.dll -->
