---
title: "Συγκριτής"
second_title: "GroupDocs.Comparison για .NET Αναφορά API"
description: "Αναπαριστά την κύρια κλάση που ελέγχει τη διαδικασία σύγκρισης εγγράφων."
type: docs
weight: 100
url: /el/net/groupdocs.comparison/comparer/
---
## Comparer class

Αναπαριστά την κύρια κλάση που ελέγχει τη διαδικασία σύγκρισης εγγράφων.

```csharp
public sealed class Comparer : IDisposable
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Αρχικοποιεί νέο παράδειγμα της κλάσης [`Comparer`](../comparer) με ροή πηγαίου εγγράφου. |
| [Comparer](comparer#constructor_4)(string) | Αρχικοποιεί νέο παράδειγμα της κλάσης [`Comparer`](../comparer) με διαδρομή πηγαίου αρχείου. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Αρχικοποιεί νέο παράδειγμα της κλάσης [`Comparer`](../comparer) με ροή πηγαίου εγγράφου και [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Αρχικοποιεί νέο παράδειγμα του [`Comparer`](../comparer) με ροή πηγαίου εγγράφου και [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_6)(string, CompareOptions) | Αρχικοποιεί νέο παράδειγμα του [`Comparer`](../comparer) με διαδρομή πηγαίου φακέλου και [`CompareOptions`](../../groupdocs.comparison.options/compareoptions). |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Αρχικοποιεί νέο παράδειγμα της κλάσης [`Comparer`](../comparer) με διαδρομή πηγαίου αρχείου και [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_7)(string, LoadOptions) | Αρχικοποιεί νέα παρουσία του [`Comparer`](../comparer) με τη διαδρομή του αρχείου προέλευσης και το [`LoadOptions`](../../groupdocs.comparison.options/loadoptions). |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Αρχικοποιεί νέα παρουσία της κλάσης [`Comparer`](../comparer) με ροή εγγράφου, το [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) και το [`ComparerSettings`](../comparersettings). |
| [Comparer](comparer#constructor_8)(string, LoadOptions, ComparerSettings) | Αρχικοποιεί νέα παρουσία της κλάσης [`Comparer`](../comparer) με τη διαδρομή του αρχείου προέλευσης, το [`LoadOptions`](../../groupdocs.comparison.options/loadoptions) και το [`ComparerSettings`](../comparersettings). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Result](../../groupdocs.comparison/comparer/result) { get; } | Έγγραφο αποτελέσματος. |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Αρχείο προέλευσης που συγκρίνεται. |
| [SourceFolder](../../groupdocs.comparison/comparer/sourcefolder) { get; } | Φάκελος προέλευσης που συγκρίνεται. |
| [TargetFolder](../../groupdocs.comparison/comparer/targetfolder) { get; set; } | Φάκελος προορισμού που συγκρίνεται. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Λίστα αρχείων προορισμού για σύγκριση με το αρχείο προέλευσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Προσθέτει ροή εγγράφου στη σύγκριση. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Προσθέτει αρχείο στη σύγκριση. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Προσθέτει ροή εγγράφου στη σύγκριση με καθορισμένες επιλογές φόρτωσης. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, CompareOptions) | Προσθέτει φάκελο στη σύγκριση. |
| [Add](../../groupdocs.comparison/comparer/add#add_4)(string, LoadOptions) | Προσθέτει αρχείο στη σύγκριση με καθορισμένες επιλογές φόρτωσης. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο τελικό έγγραφο. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Συγκρίνει έγγραφα χωρίς αποθήκευση του αποτελέσματος με τις προεπιλεγμένες επιλογές |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Συγκρίνει έγγραφα χωρίς αποθήκευση του αποτελέσματος. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα σε ροή αρχείου |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα σε διαδρομή αρχείου |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Συγκρίνει έγγραφα χωρίς αποθήκευση του αποτελέσματος. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα σε ροή αρχείου |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα σε ροή αρχείου |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα σε διαδρομή αρχείου |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα σε διαδρομή αρχείου |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα σε ροή. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα σε διαδρομή αρχείου |
| [CompareDirectory](../../groupdocs.comparison/comparer/comparedirectory)(string, CompareOptions) | Συγκρίνει κατάλογο και αποθηκεύει το αποτέλεσμα σε διαδρομή αρχείου |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Απελευθερώνει πόρους. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Λαμβάνει λίστα αλλαγών μεταξύ αρχείου(ων) προέλευσης και προορισμού. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(ChangeType) | Λαμβάνει λίστα αλλαγών μεταξύ αρχείου(ων) προέλευσης και προορισμού. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_2)(GetChangeOptions) | Λαμβάνει λίστα αλλαγών μεταξύ αρχείου(ων) προέλευσης και προορισμού. |
| [GetResultDocumentStream](../../groupdocs.comparison/comparer/getresultdocumentstream)() | Λαμβάνει τη ροή του εγγράφου αποτελέσματος, επιστρέφει null εάν η ροή δεν υπάρχει |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Λάβετε τη συμβολοσειρά αποτελέσματος μετά τη σύγκριση (μόνο για σύγκριση κειμένου). |

### Δείτε επίσης

* namespace [GroupDocs.Comparison](../../groupdocs.comparison)
* assembly [GroupDocs.Comparison](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑ: δημιουργήθηκε από xmldocmd για GroupDocs.Comparison.dll -->
