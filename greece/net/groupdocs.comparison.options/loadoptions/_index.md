---
title: "LoadOptions"
second_title: "GroupDocs.Comparison για .NET Αναφορά API"
description: "Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά τη φόρτωση ενός εγγράφου."
type: docs
weight: 300
url: /el/net/groupdocs.comparison.options/loadoptions/
---
## LoadOptions class

Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά τη φόρτωση ενός εγγράφου.

```csharp
public class LoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [LoadOptions](loadoptions)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [FileType](../../groupdocs.comparison.options/loadoptions/filetype) { get; set; } | Ορίστε χειροκίνητα τον τύπο αρχείου για σύγκριση ώστε να παρακάμψετε την αυτόματη ανίχνευση τύπου αρχείου. |
| [FontDirectories](../../groupdocs.comparison.options/loadoptions/fontdirectories) { get; set; } | Λίστα καταλόγων γραμματοσειρών προς φόρτωση. |
| [LoadText](../../groupdocs.comparison.options/loadoptions/loadtext) { get; set; } | Δείχνει ότι οι δοθείσες συμβολοσειρές είναι κείμενο σύγκρισης, όχι διαδρομές αρχείων (μόνο για σύγκριση κειμένου). |
| [Password](../../groupdocs.comparison.options/loadoptions/password) { get; set; } | Κωδικός πρόσβασης του εγγράφου. |
| [SkipExternalResources](../../groupdocs.comparison.options/loadoptions/skipexternalresources) { get; set; } | Απενεργοποιεί τη φόρτωση όλων των εξωτερικών πόρων (π.χ. εικόνες που αναφέρονται από απομακρυσμένο URL) εκτός από το [`WhitelistedResources`](./whitelistedresources). |
| [WhitelistedResources](../../groupdocs.comparison.options/loadoptions/whitelistedresources) { get; set; } | Η λίστα των τμημάτων URL που αντιστοιχούν σε εξωτερικούς πόρους που πρέπει να φορτωθούν όταν το [`SkipExternalResources`](./skipexternalresources) ορίζεται σε `true`. |

### Δείτε επίσης

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑ: δημιουργήθηκε από xmldocmd για GroupDocs.Comparison.dll -->
