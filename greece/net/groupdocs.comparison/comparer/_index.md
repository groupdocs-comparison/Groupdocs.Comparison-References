---
title: Comparer
second_title: GroupDocs.Σύγκριση για Αναφορά API .NET
description: Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία σύγκρισης εγγράφων.
type: docs
weight: 100
url: /el/net/groupdocs.comparison/comparer/
---
## Comparer class

Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία σύγκρισης εγγράφων.

```csharp
public class Comparer : IDisposable
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Comparer](comparer#constructor)(Stream) | Αρχικοποιεί νέα παρουσία του[`Comparer`](../comparer) τάξη με ροή εγγράφου πηγής. |
| [Comparer](comparer#constructor_4)(string) | Αρχικοποιεί νέα παρουσία του[`Comparer`](../comparer) κλάση με διαδρομή αρχείου προέλευσης. |
| [Comparer](comparer#constructor_1)(Stream, ComparerSettings) | Αρχικοποιεί νέα παρουσία του[`Comparer`](../comparer)τάξη με ροή εγγράφου πηγής και[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_2)(Stream, LoadOptions) | Αρχικοποιεί νέα παρουσία του[`Comparer`](../comparer) με ροή εγγράφου πηγής και[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_5)(string, ComparerSettings) | Αρχικοποιεί νέα παρουσία του[`Comparer`](../comparer) κλάση με διαδρομή αρχείου προέλευσης και[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_6)(string, LoadOptions) | Αρχικοποιεί νέα παρουσία του[`Comparer`](../comparer) με διαδρομή αρχείου προέλευσης και[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) . |
| [Comparer](comparer#constructor_3)(Stream, LoadOptions, ComparerSettings) | Αρχικοποιεί νέα παρουσία του[`Comparer`](../comparer) τάξη με ροή εγγράφων,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) και[`ComparerSettings`](../comparersettings) . |
| [Comparer](comparer#constructor_7)(string, LoadOptions, ComparerSettings) | Αρχικοποιεί νέα παρουσία του[`Comparer`](../comparer) τάξη με διαδρομή αρχείου προέλευσης,[`LoadOptions`](../../groupdocs.comparison.options/loadoptions) και[`ComparerSettings`](../comparersettings) . |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Source](../../groupdocs.comparison/comparer/source) { get; } | Αρχείο πηγής που συγκρίνεται. |
| [Targets](../../groupdocs.comparison/comparer/targets) { get; } | Λίστα στοχευόμενων αρχείων προς σύγκριση με το αρχείο προέλευσης. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Add](../../groupdocs.comparison/comparer/add#add)(Stream) | Προσθέτει τη ροή εγγράφων στη σύγκριση. |
| [Add](../../groupdocs.comparison/comparer/add#add_2)(string) | Προσθέτει αρχείο σε σύγκριση. |
| [Add](../../groupdocs.comparison/comparer/add#add_1)(Stream, LoadOptions) | Προσθέτει ροή εγγράφων για σύγκριση με τις καθορισμένες επιλογές φόρτωσης. |
| [Add](../../groupdocs.comparison/comparer/add#add_3)(string, LoadOptions) | Προσθέτει αρχείο για σύγκριση με τις καθορισμένες επιλογές φόρτωσης. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges)(Stream, ApplyChangeOptions) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο έγγραφο που προκύπτει. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_2)(string, ApplyChangeOptions) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο έγγραφο που προκύπτει. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_1)(Stream, SaveOptions, ApplyChangeOptions) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο έγγραφο που προκύπτει. |
| [ApplyChanges](../../groupdocs.comparison/comparer/applychanges#applychanges_3)(string, SaveOptions, ApplyChangeOptions) | Αποδέχεται ή απορρίπτει αλλαγές και τις εφαρμόζει στο έγγραφο που προκύπτει. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare)() | Συγκρίνει έγγραφα χωρίς αποθήκευση του αποτελέσματος με τις προεπιλεγμένες επιλογές |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_1)(CompareOptions) | Συγκρίνει έγγραφα χωρίς αποθήκευση του αποτελέσματος. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_3)(Stream) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα στο αρχείο stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_7)(string) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα στο αρχείο path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_2)(SaveOptions, CompareOptions) | Συγκρίνει έγγραφα χωρίς αποθήκευση του αποτελέσματος. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_4)(Stream, CompareOptions) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα στο αρχείο stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_5)(Stream, SaveOptions) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα στο αρχείο stream |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_8)(string, CompareOptions) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα στο αρχείο path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_9)(string, SaveOptions) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα στο αρχείο path |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_6)(Stream, SaveOptions, CompareOptions) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα σε ροή. |
| [Compare](../../groupdocs.comparison/comparer/compare#compare_10)(string, SaveOptions, CompareOptions) | Συγκρίνει έγγραφα και αποθηκεύει το αποτέλεσμα στο αρχείο path |
| [Dispose](../../groupdocs.comparison/comparer/dispose)() | Απελευθερώνει πόρους. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges)() | Λαμβάνει λίστα αλλαγών μεταξύ των αρχείων προέλευσης και προορισμού. |
| [GetChanges](../../groupdocs.comparison/comparer/getchanges#getchanges_1)(GetChangeOptions) | Λαμβάνει λίστα αλλαγών μεταξύ των αρχείων προέλευσης και προορισμού. |
| [GetResultString](../../groupdocs.comparison/comparer/getresultstring)() | Λήψη συμβολοσειράς αποτελεσμάτων μετά από σύγκριση (μόνο για σύγκριση κειμένου). |

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Comparison](../../groupdocs.comparison)
* συνέλευση [GroupDocs.Comparison](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Comparison.dll -->
