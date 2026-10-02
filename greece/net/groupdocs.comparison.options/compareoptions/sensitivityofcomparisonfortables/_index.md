---
title: "SensitivityOfComparisonForTables"
second_title: "GroupDocs.Comparison για .NET Αναφορά API"
description: "Λαμβάνει ή ορίζει την ευαισθησία της σύγκρισης για πίνακες."
type: docs
weight: 220
url: /el/net/groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables/
---
## CompareOptions.SensitivityOfComparisonForTables property

Λαμβάνει ή ορίζει την ευαισθησία της σύγκρισης για πίνακες.

```csharp
public int? SensitivityOfComparisonForTables { get; set; }
```

### Property Value

Εάν η τιμή είναι null, χρησιμοποιείται το SensitivityOfComparison. Το ποσοστό των διαγραμμένων και εισαχθέντων στοιχείων δύο συγκρινόμενων αντικειμένων σε σχέση με όλα τα στοιχεία αυτών των αντικειμένων. Εάν αυτό το ποσοστό υπερβεί, τα αντικείμενα δεν συγκρίνονται αλλά θεωρούνται πλήρως εισαχθέντα και διαγραμμένα. Ελάχιστη τιμή - 0% => Η σύγκριση δεν πραγματοποιείται για οποιοδήποτε μήκος της κοινής υποακολουθίας δύο συγκρινόμενων αντικειμένων. Προεπιλεγμένη τιμή - 75% => Η σύγκριση πραγματοποιείται εάν το ποσοστό των διαγραμμένων και εισαχθέντων στοιχείων δύο συγκρινόμενων αντικειμένων σε σχέση με όλα τα στοιχεία αυτών των αντικειμένων δεν υπερβαίνει το 75. Μέγιστη τιμή - 100% => Η σύγκριση πραγματοποιείται για οποιοδήποτε μήκος της κοινής υποακολουθίας δύο συγκρινόμενων αντικειμένων.

### Δείτε επίσης

* class [CompareOptions](../../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑ: δημιουργήθηκε από xmldocmd για GroupDocs.Comparison.dll -->
