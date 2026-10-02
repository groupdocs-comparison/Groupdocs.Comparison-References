---
title: "WordCompareOptions"
second_title: "GroupDocs.Comparison για .NET Αναφορά API"
description: "Ειδικές επιλογές σύγκρισης εγγράφου Word. Κληρονομεί τις κοινές επιλογές από CompareOptions./compareoptions."
type: docs
weight: 440
url: /el/net/groupdocs.comparison.options/wordcompareoptions/
---
## WordCompareOptions class

Ειδικές επιλογές σύγκρισης εγγράφου Word. Κληρονομεί τις κοινές επιλογές από [`CompareOptions`](../compareoptions).

```csharp
public class WordCompareOptions : CompareOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [WordCompareOptions](wordcompareoptions)() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`WordCompareOptions`](../wordcompareoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CalculateCoordinates](../../groupdocs.comparison.options/compareoptions/calculatecoordinates) { get; set; } | Δείχνει αν θα υπολογιστούν οι συντεταγμένες για τα αλλαγμένα στοιχεία. |
| [CalculateCoordinatesMode](../../groupdocs.comparison.options/compareoptions/calculatecoordinatesmode) { get; set; } | Καθορίζει τον υπολογισμό συντεταγμένων για τη λειτουργία αλλαγμένων στοιχείων. |
| [ChangedItemStyle](../../groupdocs.comparison.options/compareoptions/changeditemstyle) { get; set; } | Περιγράφει το στυλ για τα αλλαγμένα στοιχεία. |
| [CompareBookmarks](../../groupdocs.comparison.options/wordcompareoptions/comparebookmarks) { get; set; } | Λαμβάνει ή ορίζει αν οι σελιδοδείκτες στα πηγαία και στοχευμένα έγγραφα συγκρίνονται και οι διαφορές περιλαμβάνονται στο αποτέλεσμα. |
| [CompareDocumentProperty](../../groupdocs.comparison.options/wordcompareoptions/comparedocumentproperty) { get; set; } | Λαμβάνει ή ορίζει αν οι ενσωματωμένες και προσαρμοσμένες ιδιότητες εγγράφου συγκρίνονται και οι διαφορές περιλαμβάνονται στο αποτέλεσμα (π.χ. στη σελίδα σύνοψης ιδιοτήτων). |
| [CompareVariableProperty](../../groupdocs.comparison.options/wordcompareoptions/comparevariableproperty) { get; set; } | Λαμβάνει ή ορίζει αν οι μεταβλητές ιδιότητες του εγγράφου (π.χ. πεδία DOCVARIABLE) συγκρίνονται και οι διαφορές περιλαμβάνονται στο αποτέλεσμα. |
| [DeletedItemStyle](../../groupdocs.comparison.options/compareoptions/deleteditemstyle) { get; set; } | Περιγράφει το στυλ για τα διαγραμμένα στοιχεία. |
| [DetalisationLevel](../../groupdocs.comparison.options/compareoptions/detalisationlevel) { get; set; } | Λαμβάνει ή ορίζει το επίπεδο λεπτομέρειας σύγκρισης. |
| [DetectStyleChanges](../../groupdocs.comparison.options/compareoptions/detectstylechanges) { get; set; } | Καθορίζει αν θα εντοπιστούν αλλαγές στυλ ή όχι. |
| [DiagramMasterSetting](../../groupdocs.comparison.options/compareoptions/diagrammastersetting) { get; set; } | Λαμβάνει ή ορίζει την τιμή διαδρομής για το κύριο αρχείο ή χρησιμοποιεί σύγκριση χωρίς διαδρομή του κύριου. Αυτή η επιλογή ισχύει μόνο για Διάγραμμα. |
| [DirectoryCompare](../../groupdocs.comparison.options/compareoptions/directorycompare) { get; set; } | Έλεγχος για ενεργοποίηση της σύγκρισης φακέλων. |
| [DisplayMode](../../groupdocs.comparison.options/wordcompareoptions/displaymode) { get; set; } | Λαμβάνει ή ορίζει πώς εμφανίζονται τα αποτελέσματα σύγκρισης: ως αναθεωρήσεις Word σε λειτουργία Παρακολούθηση Αλλαγών (Revisions) ή ως επισημασμένες αλλαγές που ενσωματώνονται απευθείας στο έγγραφο (Highlight). |
| [ExtendedSummaryPage](../../groupdocs.comparison.options/compareoptions/extendedsummarypage) { get; set; } | Καθορίζει αν θα προστεθούν εκτεταμένες πληροφορίες σύγκρισης αρχείων στη σελίδα περίληψης ή όχι. |
| [FolderComparisonExtension](../../groupdocs.comparison.options/compareoptions/foldercomparisonextension) { get; set; } | Λαμβάνει ή ορίζει τη μορφή του τελικού αρχείου σύγκρισης φακέλων. |
| [GenerateSummaryPage](../../groupdocs.comparison.options/compareoptions/generatesummarypage) { get; set; } | Καθορίζει αν θα προστεθεί σελίδα περίληψης με στατιστικά των εντοπισμένων αλλαγών στο τελικό έγγραφο ή όχι. |
| [HeaderFootersComparison](../../groupdocs.comparison.options/compareoptions/headerfooterscomparison) { get; set; } | Έλεγχος για ενεργοποίηση της σύγκρισης περιεχομένου κεφαλίδας/υποσέλιδου. |
| [IgnoreChangeSettings](../../groupdocs.comparison.options/compareoptions/ignorechangesettings) { get; set; } | Λαμβάνει ή ορίζει ρυθμίσεις για παράβλεψη αλλαγών βάσει ομοιότητας. |
| [InsertedItemStyle](../../groupdocs.comparison.options/compareoptions/inserteditemstyle) { get; set; } | Περιγράφει το στυλ για τα εισαχθέντα στοιχεία. |
| [LeaveGaps](../../groupdocs.comparison.options/wordcompareoptions/leavegaps) { get; set; } | Λαμβάνει ή ορίζει αν θα διατηρηθούν κενές γραμμές στη θέση του εισαχθέντος ή διαγραμμένου περιεχομένου για διατήρηση της διάταξης και του αριθμού γραμμών· χρησιμοποιείται με [`ShowInsertedContent`](../compareoptions/showinsertedcontent) και [`ShowDeletedContent`](../compareoptions/showdeletedcontent). |
| [MarkChangedContent](../../groupdocs.comparison.options/compareoptions/markchangedcontent) { get; set; } | Καθορίζει αν θα χρησιμοποιηθούν πλαίσια για σχήματα στην επεξεργασία κειμένου και για ορθογώνια στα έγγραφα εικόνας. |
| [MarkLineBreaks](../../groupdocs.comparison.options/wordcompareoptions/marklinebreaks) { get; set; } | Λαμβάνει ή ορίζει αν οι αλλαγές παραγράφων (γραμμών) που διαφέρουν μεταξύ των εγγράφων θα σημειώνονται οπτικά στο αποτέλεσμα. |
| [MarkNestedContent](../../groupdocs.comparison.options/compareoptions/marknestedcontent) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν θα σημειωθούν τα θυγατρικά στοιχεία του διαγραμμένου ή εισαχθέντος στοιχείου ως διαγραμμένα ή εισαχθέντα. |
| [OriginalSize](../../groupdocs.comparison.options/compareoptions/originalsize) { get; set; } | Λαμβάνει ή ορίζει τα αρχικά μεγέθη των συγκρινόμενων εγγράφων. |
| [PaperSize](../../groupdocs.comparison.options/compareoptions/papersize) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος χαρτιού του εγγράφου αποτελέσματος. |
| [PasswordSaveOption](../../groupdocs.comparison.options/compareoptions/passwordsaveoption) { get; set; } | Λαμβάνει ή ορίζει την επιλογή αποθήκευσης κωδικού πρόσβασης. |
| [RevisionAuthorName](../../groupdocs.comparison.options/wordcompareoptions/revisionauthorname) { get; set; } | Λαμβάνει ή ορίζει το όνομα συγγραφέα που χρησιμοποιείται για τις αναθεωρήσεις όταν είναι ενεργοποιημένο το !:WordTrackChanges. Εάν οριστεί, αυτό το όνομα εφαρμόζεται στην επισήμανση αναθεώρησης στο έγγραφο αποτελέσματος. |
| [SensitivityOfComparison](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparison) { get; set; } | Λαμβάνει ή ορίζει την ευαισθησία της σύγκρισης. |
| [SensitivityOfComparisonForTables](../../groupdocs.comparison.options/compareoptions/sensitivityofcomparisonfortables) { get; set; } | Λαμβάνει ή ορίζει την ευαισθησία της σύγκρισης για πίνακες. |
| [ShowDeletedContent](../../groupdocs.comparison.options/compareoptions/showdeletedcontent) { get; set; } | Καθορίζει αν θα εμφανιστούν τα διαγραμμένα στοιχεία στο τελικό έγγραφο ή όχι. |
| [ShowInsertedContent](../../groupdocs.comparison.options/compareoptions/showinsertedcontent) { get; set; } | Καθορίζει αν θα εμφανιστούν τα εισαχθέντα στοιχεία στο τελικό έγγραφο ή όχι. |
| [ShowOnlyChanged](../../groupdocs.comparison.options/compareoptions/showonlychanged) { get; set; } | Έλεγχοι για ενεργοποίηση της εμφάνισης μόνο των αλλαγμένων στοιχείων. |
| [ShowOnlySummaryPage](../../groupdocs.comparison.options/compareoptions/showonlysummarypage) { get; set; } | Καθορίζει αν θα παραμείνει στο τελικό έγγραφο μόνο μια σελίδα με στατιστικά των εντοπισμένων αλλαγών ή όχι. |
| [ShowRevisions](../../groupdocs.comparison.options/wordcompareoptions/showrevisions) { get; set; } | Λαμβάνει ή ορίζει αν το έγγραφο αποτελέσματος διατηρεί ορατή τη σήμανση αναθεώρησης. Εάν είναι ψευδές, όλες οι αναθεωρήσεις γίνονται αποδεκτές και το αποτέλεσμα εμφανίζεται ως τελικό κείμενο. Αυτή η ρύθμιση έχει νόημα μόνο όταν το [`DisplayMode`](./displaymode) ορίζεται σε Highlight. Η προεπιλεγμένη τιμή είναι true. |
| [UserMasterPath](../../groupdocs.comparison.options/compareoptions/usermasterpath) { get; set; } | Διαδρομή προς το πρότυπο master του χρήστη για Διαγράμματα. |
| [WordsSeparatorChars](../../groupdocs.comparison.options/compareoptions/wordsseparatorchars) { set; } | Λαμβάνει ή ορίζει έναν πίνακα διαχωριστών για το διαχωρισμό του κειμένου σε λέξεις. |

### Δείτε επίσης

* class [CompareOptions](../compareoptions)
* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑ: δημιουργήθηκε από xmldocmd για GroupDocs.Comparison.dll -->
