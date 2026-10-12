---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison για .NET Αναφορά API"
description: "Αναπαριστά την κύρια κλάση που ελέγχει τη διαχείριση των αναθεωρήσεων."
type: docs
weight: 540
url: /el/net/groupdocs.comparison.words.revision/revisionhandler/
---
## RevisionHandler class

Αναπαριστά την κύρια κλάση που ελέγχει τη διαχείριση των αναθεωρήσεων.

```csharp
public sealed class RevisionHandler : IDisposable
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [RevisionHandler](revisionhandler#constructor)(Stream) | Αρχικοποιεί νέα παρουσία της κλάσης [`RevisionHandler`](../revisionhandler) με ροή αρχείου που περιέχει αναθεωρήσεις. |
| [RevisionHandler](revisionhandler#constructor_2)(string) | Αρχικοποιεί νέα παρουσία της κλάσης [`RevisionHandler`](../revisionhandler) με τη διαδρομή προς το αρχείο που περιέχει αναθεωρήσεις. |
| [RevisionHandler](revisionhandler#constructor_1)(Stream, bool) | Αρχικοποιεί νέα παρουσία της κλάσης [`RevisionHandler`](../revisionhandler) με ροή αρχείου που περιέχει αναθεωρήσεις και ρητό έλεγχο ιδιοκτησίας ροής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges)(ApplyRevisionOptions) | Επεξεργάζεται τις αλλαγές στις αναθεωρήσεις και τις εφαρμόζει στο ίδιο αρχείο από το οποίο λήφθηκαν οι αναθεωρήσεις. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_1)(Stream, ApplyRevisionOptions) | Επεξεργάζεται τις αλλαγές στις αναθεωρήσεις και το αποτέλεσμα γράφεται στη ροή του εγγράφου. |
| [ApplyRevisionChanges](../../groupdocs.comparison.words.revision/revisionhandler/applyrevisionchanges#applyrevisionchanges_2)(string, ApplyRevisionOptions) | Επεξεργάζεται τις αλλαγές στις αναθεωρήσεις, και το αποτέλεσμα γράφεται στο καθορισμένο αρχείο με τη διαδρομή. |
| [Dispose](../../groupdocs.comparison.words.revision/revisionhandler/dispose)() | Απελευθερώνει πόρους. |
| [GetRevisions](../../groupdocs.comparison.words.revision/revisionhandler/getrevisions)() | Λαμβάνει τη λίστα όλων των αναθεωρήσεων. |

### Δείτε επίσης

* namespace [GroupDocs.Comparison.Words.Revision](../../groupdocs.comparison.words.revision)
* assembly [GroupDocs.Comparison](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑ: δημιουργήθηκε από xmldocmd για GroupDocs.Comparison.dll -->
