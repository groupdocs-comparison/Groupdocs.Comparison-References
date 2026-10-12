---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison för .NET API-referens"
description: "Anger detaljnivån för jämförelsen."
type: docs
weight: 230
url: /sv/net/groupdocs.comparison.options/detalisationlevel/
---
## DetalisationLevel enumeration

Anger detaljnivån för jämförelsen.

```csharp
public enum DetalisationLevel
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Low | `0` | Lågnivå. Ger den bästa hastighetsjämförelsen på bekostnad av jämförelsens kvalitet. Jämförelsen utförs per ord. |
| Middle | `1` | Mellannivå. En rimlig kompromiss mellan jämförelsens hastighet och kvalitet. Jämförelsen utförs per tecken, men ignorerar teckenkänslighet och mellanslag räknas. |
| High | `2` | Hög nivå. Den bästa jämförelseskvaliteten, men den lägsta hastigheten. Jämförelsen utförs per tecken med hänsyn till teckenkänslighet och mellanslag räknas. |

### Se även

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: genererad av xmldocmd för GroupDocs.Comparison.dll -->
