---
title: "ChangeInfo"
second_title: "GroupDocs.Comparison per .NET Riferimento API"
description: "Rappresenta informazioni sulla modifica."
type: docs
weight: 460
url: /it/net/groupdocs.comparison.result/changeinfo/
---
## ChangeInfo class

Rappresenta informazioni sulla modifica.

```csharp
public class ChangeInfo
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ChangeInfo](changeinfo)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Authors](../../groupdocs.comparison.result/changeinfo/authors) { get; set; } | Elenco degli autori. |
| [Box](../../groupdocs.comparison.result/changeinfo/box) { get; set; } | Coordinate dell'elemento modificato. |
| [Column](../../groupdocs.comparison.result/changeinfo/column) { get; set; } | Indice della colonna basato su zero della cella modificata. Popolato per il comparatore di celle (XLSX, CSV, ODS, ecc.), altrimenti nullo. |
| [ColumnHeader](../../groupdocs.comparison.result/changeinfo/columnheader) { get; set; } | Testo dell'intestazione di colonna preso dalla prima riga del foglio di lavoro per la colonna corrispondente. Popolato per il comparatore di celle quando la prima riga contiene valori di intestazione, altrimenti nullo. |
| [ComparisonAction](../../groupdocs.comparison.result/changeinfo/comparisonaction) { get; set; } | Azione (accetta o rifiuta). Questo campo indica al confronto cosa fare con questa modifica. |
| [ComponentType](../../groupdocs.comparison.result/changeinfo/componenttype) { get; set; } | Tipo di componente modificato. |
| [Id](../../groupdocs.comparison.result/changeinfo/id) { get; set; } | ID della modifica. |
| [PageInfo](../../groupdocs.comparison.result/changeinfo/pageinfo) { get; set; } | Pagina in cui è posizionata la modifica corrente. |
| [Row](../../groupdocs.comparison.result/changeinfo/row) { get; set; } | Indice della riga basato su zero della cella modificata. Popolato per il comparatore di celle (XLSX, CSV, ODS, ecc.), altrimenti nullo. |
| [SourceText](../../groupdocs.comparison.result/changeinfo/sourcetext) { get; set; } | Testo modificato del documento sorgente. |
| [StyleChanges](../../groupdocs.comparison.result/changeinfo/stylechanges) { get; set; } | Array di modifiche di stile. |
| [TargetText](../../groupdocs.comparison.result/changeinfo/targettext) { get; set; } | Testo modificato del documento di destinazione. |
| [Text](../../groupdocs.comparison.result/changeinfo/text) { get; set; } | Valore testuale della modifica. |
| [Type](../../groupdocs.comparison.result/changeinfo/type) { get; } | Tipo di modifica. |

### Vedi anche

* namespace [GroupDocs.Comparison.Result](../../groupdocs.comparison.result)
* assembly [GroupDocs.Comparison](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Comparison.dll -->
