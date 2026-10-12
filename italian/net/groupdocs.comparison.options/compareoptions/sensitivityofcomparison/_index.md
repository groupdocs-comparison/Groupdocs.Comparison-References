---
title: "SensitivityOfComparison"
second_title: "GroupDocs.Comparison per .NET Riferimento API"
description: "Ottiene o imposta una sensibilità del confronto."
type: docs
weight: 210
url: /it/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparison/
---
## CompareOptions.SensitivityOfComparison property

Ottiene o imposta una sensibilità del confronto.

```csharp
public int SensitivityOfComparison { get; set; }
```

### Property Value

La percentuale di elementi eliminati e inseriti di due oggetti confrontati in relazione a tutti gli elementi di questi oggetti. se questa percentuale viene superata, l'oggetto non viene confrontato ma è considerato completamente inserito ed eliminato. Valore minimo - 0% => Il confronto non avviene per alcuna lunghezza della sottosequenza comune di due oggetti confrontati. Valore predefinito - 75% => Il confronto avviene se la percentuale di elementi eliminati e inseriti di due oggetti confrontati rispetto a tutti gli elementi di questi oggetti non supera il 75. Valore massimo - 100% => Il confronto avviene per qualsiasi lunghezza della sottosequenza comune di due oggetti confrontati.

### Vedi anche

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Comparison.dll -->
