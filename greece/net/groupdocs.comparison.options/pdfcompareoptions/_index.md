---
title: "PdfCompareOptions"
second_title: "GroupDocs.Comparison για .NET Αναφορά API"
description: "Συγκεκριμένες επιλογές σύγκρισης εγγράφου PDF. Κληρονομεί τις κοινές επιλογές από το CompareOptions./compareoptions."
type: docs
weight: 360
url: /el/net/groupdocs.comparison.options/pdfcompareoptions/
---
## PdfCompareOptions class

Συγκεκριμένες επιλογές σύγκρισης εγγράφου PDF. Κληρονομεί τις κοινές επιλογές από [`CompareOptions`](../compareoptions).

```csharp
public class PdfCompareOptions : CompareOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfCompareOptions](pdfcompareoptions)() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PdfCompareOptions`](../pdfcompareoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AnnotationAuthorName](../../groupdocs.comparison.options/pdfcompareoptions/annotationauthorname) { get; set; } | Λαμβάνει ή ορίζει το όνομα του συγγραφέα που χρησιμοποιείται για τις σημειώσεις όταν το [`DisplayMode`](./displaymode) είναι ορισμένο σε Interleaved. |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Δείχνει αν θα υπολογιστούν οι συντεταγμένες για τα αλλαγμένα στοιχεία. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Καθορίζει τον υπολογισμό συντεταγμένων για τη λειτουργία αλλαγμένων στοιχείων. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Περιγράφει το στυλ για τα αλλαγμένα στοιχεία. |
| [CompareImagesPdf](../../groupdocs.comparison.options/pdfcompareoptions/compareimagespdf) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα συγκριθούν εικόνες σε έγγραφα PDF. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Περιγράφει το στυλ για τα διαγραμμένα στοιχεία. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Λαμβάνει ή ορίζει το επίπεδο λεπτομέρειας σύγκρισης. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Καθορίζει αν θα εντοπιστούν αλλαγές στυλ ή όχι. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Λαμβάνει ή ορίζει την τιμή διαδρομής για το κύριο αρχείο ή χρησιμοποιεί σύγκριση χωρίς διαδρομή του κύριου. Αυτή η επιλογή ισχύει μόνο για Διάγραμμα. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Έλεγχος για ενεργοποίηση της σύγκρισης φακέλων. |
| [DisplayMode](../../groupdocs.comparison.options/pdfcompareoptions/displaymode) { get; set; } | Λαμβάνει ή ορίζει πώς θα διαμορφωθεί το έγγραφο αποτελέσματος σύγκρισης. Η προεπιλεγμένη τιμή είναι Inline. |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Καθορίζει αν θα προστεθούν εκτεταμένες πληροφορίες σύγκρισης αρχείων στη σελίδα περίληψης ή όχι. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Λαμβάνει ή ορίζει τη μορφή του τελικού αρχείου σύγκρισης φακέλων. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Καθορίζει αν θα προστεθεί σελίδα περίληψης με στατιστικά των εντοπισμένων αλλαγών στο τελικό έγγραφο ή όχι. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Έλεγχος για ενεργοποίηση της σύγκρισης περιεχομένου κεφαλίδας/υποσέλιδου. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Λαμβάνει ή ορίζει ρυθμίσεις για παράβλεψη αλλαγών βάσει ομοιότητας. |
| [ImagesInheritanceMode](../../groupdocs.comparison.options/pdfcompareoptions/imagesinheritancemode) { get; set; } | Καθορίζει την πηγή κληρονομίας εικόνων όταν η σύγκριση εικόνων είναι απενεργοποιημένη. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Περιγράφει το στυλ για τα εισαχθέντα στοιχεία. |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Καθορίζει αν θα χρησιμοποιηθούν πλαίσια για σχήματα στην επεξεργασία κειμένου και για ορθογώνια στα έγγραφα εικόνας. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν θα σημειωθούν τα θυγατρικά στοιχεία του διαγραμμένου ή εισαχθέντος στοιχείου ως διαγραμμένα ή εισαχθέντα. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Λαμβάνει ή ορίζει τα αρχικά μεγέθη των συγκρινόμενων εγγράφων. |
| [PagesSetup](../../groupdocs.comparison.options/pdfcompareoptions/pagessetup) { get; set; } | Λαμβάνει ή ορίζει το εύρος σελίδων για σύγκριση. Όταν είναι null, συγκρίνονται όλες οι σελίδες. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος χαρτιού του εγγράφου αποτελέσματος. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Λαμβάνει ή ορίζει την επιλογή αποθήκευσης κωδικού πρόσβασης. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Λαμβάνει ή ορίζει την ευαισθησία της σύγκρισης. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Λαμβάνει ή ορίζει την ευαισθησία της σύγκρισης για πίνακες. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Καθορίζει αν θα εμφανιστούν τα διαγραμμένα στοιχεία στο τελικό έγγραφο ή όχι. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Καθορίζει αν θα εμφανιστούν τα εισαχθέντα στοιχεία στο τελικό έγγραφο ή όχι. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Έλεγχοι για ενεργοποίηση της εμφάνισης μόνο των αλλαγμένων στοιχείων. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Καθορίζει αν θα παραμείνει στο τελικό έγγραφο μόνο μια σελίδα με στατιστικά των εντοπισμένων αλλαγών ή όχι. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Διαδρομή προς το πρότυπο master του χρήστη για Διαγράμματα. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Λαμβάνει ή ορίζει έναν πίνακα διαχωριστών για το διαχωρισμό του κειμένου σε λέξεις. |

### Δείτε επίσης

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑ: δημιουργήθηκε από xmldocmd για GroupDocs.Comparison.dll -->
