---
title: "ApplyRevisionChanges"
second_title: "Referencia de API de GroupDocs.Comparison para .NET"
description: "Procesa los cambios en las revisiones y los aplica al mismo archivo del que se tomaron las revisiones."
type: docs
weight: 20
url: /es/net/groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges/
---
## ApplyRevisionChanges(ApplyRevisionOptions) {#applyrevisionchanges}

Procesa los cambios en las revisiones y los aplica al mismo archivo del que se tomaron las revisiones.

```csharp
public void ApplyRevisionChanges(ApplyRevisionOptions changes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cambios | ApplyRevisionOptions | Lista de revisiones modificadas |

### Ver también

* class [ApplyRevisionOptions](../../applyrevisionoptions)
* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## ApplyRevisionChanges(string, ApplyRevisionOptions) {#applyrevisionchanges_2}

Procesa los cambios en las revisiones, y el resultado se escribe en el archivo especificado por ruta.

```csharp
public void ApplyRevisionChanges(string filePath, ApplyRevisionOptions changes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | Ruta del archivo de resultado |
| cambios | ApplyRevisionOptions | Lista de revisiones modificadas |

### Ver también

* class [ApplyRevisionOptions](../../applyrevisionoptions)
* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

---

## ApplyRevisionChanges(Stream, ApplyRevisionOptions) {#applyrevisionchanges_1}

Procesa los cambios en las revisiones y el resultado se escribe en el flujo del documento.

```csharp
public void ApplyRevisionChanges(Stream document, ApplyRevisionOptions changes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | Stream | Documento resultante |
| cambios | ApplyRevisionOptions | Lista de revisiones modificadas |

### Ver también

* class [ApplyRevisionOptions](../../applyrevisionoptions)
* class [RevisionHandler](../../revisionhandler)
* namespace [GroupDocs.Comparison.Words.Revision](../../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Comparison.dll -->
