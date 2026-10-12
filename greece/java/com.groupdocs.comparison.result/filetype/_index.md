---
title: "FileType"
second_title: "GroupDocs.Comparison for Java Αναφορά API"
description: "Η απαρίθμηση FileType αντιπροσωπεύει τον τύπο ενός αρχείου που χρησιμοποιείται στη διαδικασία σύγκρισης εγγράφων."
type: docs
weight: 16
url: /el/java/com.groupdocs.comparison.result/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>
```

Η απαρίθμηση FileType αντιπροσωπεύει τον τύπο ενός αρχείου που χρησιμοποιείται στη διαδικασία σύγκρισης εγγράφων.


Ορίζει διαφορετικούς τύπους αρχείων όπως έγγραφα Word, αρχεία PDF και άλλα.
Παρέχει μεθόδους για την απόκτηση λίστας όλων των τύπων αρχείων που υποστηρίζονται από το GroupDocs.Comparison, ανίχνευση τύπου αρχείου με βάση την επέκταση κ.λπ.
Χρησιμοποιήστε αυτό το enum για να καθορίσετε τον τύπο αρχείου όταν εργάζεστε με τη βιβλιοθήκη GroupDocs.Comparison.

* Learn more about file formats supported by GroupDocs.Comparison: [Full list of supported document formats](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* Learn more about getting supported file types in Java: [How to get supported file formats in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+supported+file+formats)


Παράδειγμα χρήσης:

````

  // Set the file type to Word document
  final FileType fileType = FileType.DOCX;
  // Perform comparison using the specified file type
  final LoadOptions loadOptions = new LoadOptions(fileType);
  try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
      comparer.add(targetFile);

      comparer.compare(resultFile, compareOptions);
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Άγνωστος τύπος |
|
|  | [AS](#AS) | μορφή γλώσσας προγραμματισμού ActionScript |
|
|  | [AS3](#AS3) | μορφή γλώσσας προγραμματισμού ActionScript |
|
|  | [ASM](#ASM) | μορφή γλώσσας προγραμματισμού Assembler |
|
|  | [BAT](#BAT) | Αρχείο σεναρίου σε DOS, OS/2 και Microsoft Windows |
|
|  | [CMD](#CMD) | Αρχείο σεναρίου σε DOS, OS/2 και Microsoft Windows |
|
|  | [C](#C) | μορφή γλώσσας προγραμματισμού C-Based |
|
|  | [H](#H) | Τα αρχεία κεφαλίδας C-Based περιέχουν ορισμούς συναρτήσεων και μεταβλητών |
|
|  | [PDF](#PDF) | μορφή Adobe Portable Document |
|
|  | [DOC](#DOC) | Έγγραφο Microsoft Word 97-2003 |
|
|  | [DOCM](#DOCM) | Έγγραφο Microsoft Word Macro-Enabled |
|
|  | [DOCX](#DOCX) | Έγγραφο Microsoft Word |
|
|  | [DOT](#DOT) | Πρότυπο Microsoft Word 97-2003 |
|
|  | [DOTM](#DOTM) | Πρότυπο Microsoft Word Macro-Enabled |
|
|  | [DOTX](#DOTX) | Πρότυπο Microsoft Word |
|
|  | [XLS](#XLS) | Φύλλο εργασίας Microsoft Excel 97-2003 |
|
|  | [XLT](#XLT) | Πρότυπο Microsoft Excel |
|
|  | [XLSX](#XLSX) | Φύλλο εργασίας Microsoft Excel |
|
|  | [XLTM](#XLTM) | Πρότυπο Microsoft Excel macro-enabled |
|
|  | [XLSB](#XLSB) | Δυαδικό φύλλο εργασίας Microsoft Excel |
|
|  | [XLSM](#XLSM) | Φύλλο εργασίας Microsoft Excel με ενεργοποιημένα μακροεντολές |
|
|  | [POT](#POT) | Πρότυπο Microsoft PowerPoint |
|
|  | [POTX](#POTX) | Πρότυπο Microsoft PowerPoint |
|
|  | [POTM](#POTM) | Πρότυπο Microsoft PowerPoint με υποστήριξη μακροεντολών |
|
|  | [PPS](#PPS) | Παρουσίαση διαφανειών Microsoft PowerPoint 97-2003 |
|
|  | [PPSX](#PPSX) | Παρουσίαση διαφανειών Microsoft PowerPoint |
|
|  | [PPTX](#PPTX) | Παρουσίαση Microsoft PowerPoint |
|
|  | [PPT](#PPT) | Παρουσίαση Microsoft PowerPoint 97-2003 |
|
|  | [PPTM](#PPTM) | Παρουσίαση Microsoft PowerPoint με ενεργοποιημένες μακροεντολές |
|
|  | [PPSM](#PPSM) | Παρουσίαση διαφανειών Microsoft PowerPoint με ενεργοποιημένες μακροεντολές |
|
|  | [VSDX](#VSDX) | Σχέδιο Microsoft Visio |
|
|  | [VSD](#VSD) | Σχέδιο Microsoft Visio 2003-2010 |
|
|  | [VSS](#VSS) | Στυλό Microsoft Visio 2003-2010 |
|
|  | [VST](#VST) | Πρότυπο Microsoft Visio 2003-2010 |
|
|  | [VDX](#VDX) | Σχέδιο XML Microsoft Visio 2003-2010 |
|
|  | [ONE](#ONE) | Έγγραφο Microsoft OneNote |
|
|  | [ODT](#ODT) | Κείμενο OpenDocument |
|
|  | [ODP](#ODP) | Παρουσίαση OpenDocument |
|
|  | [OTP](#OTP) | Πρότυπο παρουσίασης OpenDocument |
|
|  | [ODS](#ODS) | Φύλλο εργασίας OpenDocument |
|
|  | [OTT](#OTT) | Πρότυπο κειμένου OpenDocument |
|
|  | [RTF](#RTF) | Έγγραφο εμπλουτισμένου κειμένου |
|
|  | [TXT](#TXT) | Έγγραφο απλού κειμένου |
|
|  | [CSV](#CSV) | Αρχείο τιμών διαχωρισμένων με κόμμα |
|
|  | [HTML](#HTML) | Γλώσσα Σήμανσης Υπερκειμένου |
|
|  | [MHTML](#MHTML) | Mime HTML |
|
|  | [MOBI](#MOBI) | μορφή e-book Mobipocket |
|
|  | [DCM](#DCM) | Ψηφιακή Απεικόνιση και Επικοινωνία στην Ιατρική |
|
|  | [DJVU](#DJVU) | μορφή Deja Vu |
|
|  | [DWG](#DWG) | μορφές δεδομένων σχεδίασης Autodesk |
|
|  | [DXF](#DXF) | AutoCAD ανταλλαγή σχεδίων |
|
|  | [BMP](#BMP) | Bitmap εικόνα |
|
|  | [GIF](#GIF) | μορφή ανταλλαγής γραφικών |
|
|  | [JPEG](#JPEG) | Κοινή Φωτογραφική Ομάδα Ειδικών |
|
|  | [JPG](#JPG) | Κοινή Φωτογραφική Ομάδα Ειδικών |
|
|  | [PNG](#PNG) | Φορητά Δικτυακά Γραφικά |
|
|  | [SVG](#SVG) | Γραφικά Διανυσματικής Κλίμακας |
|
|  | [EML](#EML) | Μήνυμα ηλεκτρονικού ταχυδρομείου |
|
|  | [EMLX](#EMLX) | Αρχείο ηλεκτρονικού ταχυδρομείου Apple Mail |
|
|  | [MSG](#MSG) | Μήνυμα ηλεκτρονικού ταχυδρομείου Microsoft Outlook |
|
|  | [CAD](#CAD) | μορφή αρχείου CAD |
|
|  | [CPP](#CPP) | μορφή γλώσσας προγραμματισμού C-Based |
|
|  | [CC](#CC) | μορφή γλώσσας προγραμματισμού C-Based |
|
|  | [CXX](#CXX) | μορφή γλώσσας προγραμματισμού C-Based |
|
|  | [HXX](#HXX) | Αρχεία κεφαλίδας που γράφονται στη γλώσσα προγραμματισμού C++ |
|
|  | [HH](#HH) | Πληροφορίες κεφαλίδας που αναφέρονται από αρχείο πηγαίου κώδικα C++ |
|
|  | [HPP](#HPP) | Αρχεία κεφαλίδας που γράφονται στη γλώσσα προγραμματισμού C++ |
|
|  | [CMAKE](#CMAKE) | Εργαλείο για τη διαχείριση της διαδικασίας κατασκευής λογισμικού |
|
|  | [CS](#CS) | μορφή γλώσσας προγραμματισμού CSharp |
|
|  | [CSX](#CSX) | μορφή αρχείου σεναρίου CSharp |
|
|  | [CAKE](#CAKE) | μορφή συστήματος αυτοματοποίησης κατασκευής διαπλατφόρμας CSharp |
|
|  | [DIFF](#DIFF) | μορφή εργαλείου σύγκρισης δεδομένων |
|
|  | [PATCH](#PATCH) | μορφή λίστας διαφορών |
|
|  | [REJ](#REJ) | μορφή απορριφθέντων αρχείων |
|
|  | [GROOVY](#GROOVY) | Αρχείο πηγαίου κώδικα γραμμένο σε μορφή Groovy |
|
|  | [GVY](#GVY) | Αρχείο πηγαίου κώδικα γραμμένο σε μορφή Groovy |
|
|  | [GRADLE](#GRADLE) | Μορφή συστήματος αυτοματοποίησης κατασκευής |
|
|  | [HAML](#HAML) | Γλώσσα σήμανσης για απλοποιημένη δημιουργία HTML |
|
|  | [JS](#JS) | Μορφή γλώσσας προγραμματισμού JavaScript |
|
|  | [ES6](#ES6) | Μορφή τυποποιημένης γλώσσας σεναρίου JavaScript |
|
|  | [MJS](#MJS) | Επέκταση για αρχεία μονάδων EcmaScript (ES) |
|
|  | [PAC](#PAC) | Αρχείο αυτόματης ρύθμισης διαμεσολαβητή (Proxy Auto-Configuration) για μορφή συνάρτησης JavaScript |
|
|  | [JSON](#JSON) | Ελαφριά μορφή για αποθήκευση και μεταφορά δεδομένων |
|
|  | [BOWERRC](#BOWERRC) | Αρχείο ρυθμίσεων για έλεγχο πακέτων στην πλευρά του διακομιστή |
|
|  | [JSHINTRC](#JSHINTRC) | Εργαλείο ποιότητας κώδικα JavaScript |
|
|  | [JSCSRC](#JSCSRC) | Μορφή αρχείου ρυθμίσεων JavaScript |
|
|  | [WEBMANIFEST](#WEBMANIFEST) | Το αρχείο Manifest περιλαμβάνει πληροφορίες για την εφαρμογή |
|
|  | [JSMAP](#JSMAP) | Αρχείο JSON που περιέχει πληροφορίες για το πώς να μεταφράσετε τον κώδικα πίσω στον πηγαίο κώδικα |
|
|  | [HAR](#HAR) | Η μορφή HTTP Archive |
|
|  | [JAVA](#JAVA) | Μορφή γλώσσας προγραμματισμού Java |
|
|  | [LESS](#LESS) | Μορφή γλώσσας φύλλου στυλ δυναμικού προεπεξεργαστή |
|
|  | [LOG](#LOG) | Η καταγραφή διατηρεί ένα μητρώο γεγονότων, διεργασιών, μηνυμάτων και επικοινωνίας |
|
|  | [MAKE](#MAKE) | Το Makefile είναι ένα αρχείο που περιέχει ένα σύνολο οδηγιών που χρησιμοποιούνται από το εργαλείο αυτοματοποίησης κατασκευής make για τη δημιουργία ενός στόχου |
|
|  | [MK](#MK) | Το Makefile είναι ένα αρχείο που περιέχει ένα σύνολο οδηγιών που χρησιμοποιούνται από το εργαλείο αυτοματοποίησης κατασκευής make για τη δημιουργία ενός στόχου |
|
|  | [MD](#MD) | Μορφή γλώσσας Markdown |
|
|  | [MKD](#MKD) | Μορφή γλώσσας Markdown |
|
|  | [MDWN](#MDWN) | Μορφή γλώσσας Markdown |
|
|  | [MDOWN](#MDOWN) | Μορφή γλώσσας Markdown |
|
|  | [MARKDOWN](#MARKDOWN) | Μορφή γλώσσας Markdown |
|
|  | [MARKDN](#MARKDN) | Μορφή γλώσσας Markdown |
|
|  | [MDTXT](#MDTXT) | Μορφή γλώσσας Markdown |
|
|  | [MDTEXT](#MDTEXT) | Μορφή γλώσσας Markdown |
|
|  | [ML](#ML) | Μορφή γλώσσας προγραμματισμού Caml |
|
|  | [MLI](#MLI) | Μορφή γλώσσας προγραμματισμού Caml |
|
|  | [OBJC](#OBJC) | Μορφή γλώσσας προγραμματισμού Objective-C |
|
|  | [OBJCP](#OBJCP) | Μορφή γλώσσας προγραμματισμού Objective-C++ |
|
|  | [PHP](#PHP) | Μορφή γλώσσας προγραμματισμού PHP |
|
|  | [PHP4](#PHP4) | Μορφή γλώσσας προγραμματισμού PHP |
|
|  | [PHP5](#PHP5) | Μορφή γλώσσας προγραμματισμού PHP |
|
|  | [PHTML](#PHTML) | Τυπική επέκταση αρχείου για προγράμματα PHP 2 |
|
|  | [CTP](#CTP) | Μορφή προτύπου CakePHP |
|
|  | [PL](#PL) | Μορφή γλώσσας προγραμματισμού Perl |
|
|  | [PM](#PM) | Μορφή μονάδας Perl |
|
|  | [POD](#POD) | Μορφή ελαφριάς γλώσσας σήμανσης Perl |
|
|  | [T](#T) | Μορφή αρχείου δοκιμής Perl |
|
|  | [PSGI](#PSGI) | Διεπαφή μεταξύ διακομιστών ιστού και εφαρμογών ιστού και πλαισίων γραμμένων στη γλώσσα προγραμματισμού Perl |
|
|  | [P6](#P6) | Μορφή γλώσσας προγραμματισμού Perl |
|
|  | [PL6](#PL6) | Μορφή γλώσσας προγραμματισμού Perl |
|
|  | [PM6](#PM6) | Μορφή μονάδας Perl |
|
|  | [NQP](#NQP) | Μεσαία γλώσσα που χρησιμοποιείται για την κατασκευή του μεταγλωττιστή Rakuto Perl 6 |
|
|  | [PROP](#PROP) | Μορφή αρχείου ιδιοτήτων |
|
|  | [CFG](#CFG) | Αρχείο διαμόρφωσης που χρησιμοποιείται για την αποθήκευση ρυθμίσεων |
|
|  | [CONF](#CONF) | Αρχείο διαμόρφωσης που χρησιμοποιείται σε συστήματα βασισμένα σε Unix και Linux |
|
|  | [DIR](#DIR) | Ο φάκελος είναι μια θέση για την αποθήκευση αρχείων στον υπολογιστή |
|
|  | [PY](#PY) | Μορφή γλώσσας προγραμματισμού Python |
|
|  | [RPY](#RPY) | Μηχανή αρχείων βασισμένη σε Python για τη δημιουργία και εκτέλεση παιχνιδιών |
|
|  | [PYW](#PYW) | Αρχεία που χρησιμοποιούνται στα Windows για να υποδεικνύουν ότι πρέπει να εκτελεστεί ένα script |
|
|  | [CPY](#CPY) | Μορφή script ελεγκτή Python |
|
|  | [GYP](#GYP) | Μορφή εργαλείου αυτοματοποίησης κατασκευής |
|
|  | [GYPI](#GYPI) | Μορφή εργαλείου αυτοματοποίησης κατασκευής |
|
|  | [PYI](#PYI) | Μορφή αρχείου διεπαφής Python |
|
|  | [IPY](#IPY) | Μορφή script IPython |
|
|  | [RST](#RST) | Ελαφριά γλώσσα σήμανσης |
|
|  | [RB](#RB) | Μορφή γλώσσας προγραμματισμού Ruby |
|
|  | [ERB](#ERB) | Μορφή γλώσσας προγραμματισμού Ruby |
|
|  | [RJS](#RJS) | Μορφή γλώσσας προγραμματισμού Ruby |
|
|  | [GEMSPEC](#GEMSPEC) | Αρχείο προγραμματιστή που καθορίζει τα χαρακτηριστικά ενός RubyGems |
|
|  | [RAKE](#RAKE) | Εργαλείο αυτοματοποίησης κατασκευής Ruby |
|
|  | [RU](#RU) | Μορφή αρχείου διαμόρφωσης Rack |
|
|  | [PODSPEC](#PODSPEC) | Μορφή ρυθμίσεων κατασκευής Ruby |
|
|  | [RBI](#RBI) | Μορφή αρχείου διεπαφής Ruby |
|
|  | [SASS](#SASS) | Μορφή γλώσσας φύλλων στυλ |
|
|  | [SCSS](#SCSS) | Μορφή γλώσσας φύλλων στυλ |
|
|  | [SCALA](#SCALA) | μορφή γλώσσας προγραμματισμού Scala |
|
|  | [SBT](#SBT) | μορφή εργαλείου κατασκευής SBT για Scala |
|
|  | [SC](#SC) | μορφή φύλλου εργασίας Scala |
|
|  | [SH](#SH) | μορφή σεναρίου προγραμματισμένου για bash |
|
|  | [BASH](#BASH) | Τύπος ερμηνευτή που επεξεργάζεται εντολές κελύφους |
|
|  | [BASHRC](#BASHRC) | Αρχείο που καθορίζει τη συμπεριφορά των διαδραστικών κελύφων |
|
|  | [EBUILD](#EBUILD) | Εξειδικευμένο σενάριο bash που αυτοματοποιεί διαδικασίες μεταγλώττισης και εγκατάστασης για πακέτα λογισμικού |
|
|  | [SQL](#SQL) | μορφή Structured Query Language |
|
|  | [DSQL](#DSQL) | μορφή Dynamic Structured Query Language |
|
|  | [VIM](#VIM) | μορφή αρχείου πηγαίου κώδικα Vim |
|
|  | [YAML](#YAML) | μορφή γλώσσας σειριοποίησης δεδομένων αναγνώσιμη από άνθρωπο |
|
|  | [YML](#YML) | μορφή γλώσσας σειριοποίησης δεδομένων αναγνώσιμη από άνθρωπο |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromFileNameOrExtension(String value)](#fromFileNameOrExtension-java.lang.String-) | Επιστρέφει FileType βάσει ονόματος αρχείου ή επέκτασης |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Λαμβάνει λίστα των υποστηριζόμενων τύπων αρχείων |
|
|  | [areEquals(FileType left, FileType right)](#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Ελέγχει την ισότητα των παρεχόμενων τύπων αρχείων |
|
|  | [areNotEquals(FileType left, FileType right)](#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-) | Ελέγχει αν οι παρεχόμενοι τύποι αρχείων δεν είναι ίσοι |
|
|  | [getFileFormat()](#getFileFormat--) | Λαμβάνει περιγραφή κειμένου του τύπου αρχείου |
|
|  | [getExtension()](#getExtension--) | Λαμβάνει την επέκταση του τύπου αρχείου |
|
|  | [toString()](#toString--) | Λαμβάνει την αναπαράσταση συμβολοσειράς του [FileType](../../com.groupdocs.comparison.result/filetype), για παράδειγμα |
'μορφή γλώσσας προγραμματισμού PHP (.php)'

|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Άγνωστος τύπος


### AS {#AS}
```
public static final FileType AS
```


μορφή γλώσσας προγραμματισμού ActionScript


### AS3 {#AS3}
```
public static final FileType AS3
```


μορφή γλώσσας προγραμματισμού ActionScript


### ASM {#ASM}
```
public static final FileType ASM
```


μορφή γλώσσας προγραμματισμού Assembler


### BAT {#BAT}
```
public static final FileType BAT
```


Αρχείο σεναρίου σε DOS, OS/2 και Microsoft Windows


### CMD {#CMD}
```
public static final FileType CMD
```


Αρχείο σεναρίου σε DOS, OS/2 και Microsoft Windows


### C {#C}
```
public static final FileType C
```


μορφή γλώσσας προγραμματισμού C-Based


### H {#H}
```
public static final FileType H
```


Τα αρχεία κεφαλίδας C-Based περιέχουν ορισμούς συναρτήσεων και μεταβλητών


### PDF {#PDF}
```
public static final FileType PDF
```


μορφή Adobe Portable Document


### DOC {#DOC}
```
public static final FileType DOC
```


Έγγραφο Microsoft Word 97-2003


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Έγγραφο Microsoft Word Macro-Enabled


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Έγγραφο Microsoft Word


### DOT {#DOT}
```
public static final FileType DOT
```


Πρότυπο Microsoft Word 97-2003


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Πρότυπο Microsoft Word Macro-Enabled


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Πρότυπο Microsoft Word


### XLS {#XLS}
```
public static final FileType XLS
```


Φύλλο εργασίας Microsoft Excel 97-2003


### XLT {#XLT}
```
public static final FileType XLT
```


Πρότυπο Microsoft Excel


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Φύλλο εργασίας Microsoft Excel


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Πρότυπο Microsoft Excel macro-enabled


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Δυαδικό φύλλο εργασίας Microsoft Excel


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Φύλλο εργασίας Microsoft Excel με ενεργοποιημένα μακροεντολές


### POT {#POT}
```
public static final FileType POT
```


Πρότυπο Microsoft PowerPoint


### POTX {#POTX}
```
public static final FileType POTX
```


Πρότυπο Microsoft PowerPoint


### POTM {#POTM}
```
public static final FileType POTM
```


Πρότυπο Microsoft PowerPoint με υποστήριξη μακροεντολών


### PPS {#PPS}
```
public static final FileType PPS
```


Παρουσίαση διαφανειών Microsoft PowerPoint 97-2003


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Παρουσίαση διαφανειών Microsoft PowerPoint


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Παρουσίαση Microsoft PowerPoint


### PPT {#PPT}
```
public static final FileType PPT
```


Παρουσίαση Microsoft PowerPoint 97-2003


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Παρουσίαση Microsoft PowerPoint με ενεργοποιημένες μακροεντολές


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Παρουσίαση διαφανειών Microsoft PowerPoint με ενεργοποιημένες μακροεντολές


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Σχέδιο Microsoft Visio


### VSD {#VSD}
```
public static final FileType VSD
```


Σχέδιο Microsoft Visio 2003-2010


### VSS {#VSS}
```
public static final FileType VSS
```


Στυλό Microsoft Visio 2003-2010


### VST {#VST}
```
public static final FileType VST
```


Πρότυπο Microsoft Visio 2003-2010


### VDX {#VDX}
```
public static final FileType VDX
```


Σχέδιο XML Microsoft Visio 2003-2010


### ONE {#ONE}
```
public static final FileType ONE
```


Έγγραφο Microsoft OneNote


### ODT {#ODT}
```
public static final FileType ODT
```


Κείμενο OpenDocument


### ODP {#ODP}
```
public static final FileType ODP
```


Παρουσίαση OpenDocument


### OTP {#OTP}
```
public static final FileType OTP
```


Πρότυπο παρουσίασης OpenDocument


### ODS {#ODS}
```
public static final FileType ODS
```


Φύλλο εργασίας OpenDocument


### OTT {#OTT}
```
public static final FileType OTT
```


Πρότυπο κειμένου OpenDocument


### RTF {#RTF}
```
public static final FileType RTF
```


Έγγραφο εμπλουτισμένου κειμένου


### TXT {#TXT}
```
public static final FileType TXT
```


Έγγραφο απλού κειμένου


### CSV {#CSV}
```
public static final FileType CSV
```


Αρχείο τιμών διαχωρισμένων με κόμμα


### HTML {#HTML}
```
public static final FileType HTML
```


Γλώσσα Σήμανσης Υπερκειμένου


### MHTML {#MHTML}
```
public static final FileType MHTML
```


Mime HTML


### MOBI {#MOBI}
```
public static final FileType MOBI
```


μορφή e-book Mobipocket


### DCM {#DCM}
```
public static final FileType DCM
```


Ψηφιακή Απεικόνιση και Επικοινωνία στην Ιατρική


### DJVU {#DJVU}
```
public static final FileType DJVU
```


μορφή Deja Vu


### DWG {#DWG}
```
public static final FileType DWG
```


μορφές δεδομένων σχεδίασης Autodesk


### DXF {#DXF}
```
public static final FileType DXF
```


AutoCAD ανταλλαγή σχεδίων


### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap εικόνα


### GIF {#GIF}
```
public static final FileType GIF
```


μορφή ανταλλαγής γραφικών


### JPEG {#JPEG}
```
public static final FileType JPEG
```


Κοινή Φωτογραφική Ομάδα Ειδικών


### JPG {#JPG}
```
public static final FileType JPG
```


Κοινή Φωτογραφική Ομάδα Ειδικών


### PNG {#PNG}
```
public static final FileType PNG
```


Φορητά Δικτυακά Γραφικά


### SVG {#SVG}
```
public static final FileType SVG
```


Γραφικά Διανυσματικής Κλίμακας


### EML {#EML}
```
public static final FileType EML
```


Μήνυμα ηλεκτρονικού ταχυδρομείου


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Αρχείο ηλεκτρονικού ταχυδρομείου Apple Mail


### MSG {#MSG}
```
public static final FileType MSG
```


Μήνυμα ηλεκτρονικού ταχυδρομείου Microsoft Outlook


### CAD {#CAD}
```
public static final FileType CAD
```


μορφή αρχείου CAD


### CPP {#CPP}
```
public static final FileType CPP
```


μορφή γλώσσας προγραμματισμού C-Based


### CC {#CC}
```
public static final FileType CC
```


μορφή γλώσσας προγραμματισμού C-Based


### CXX {#CXX}
```
public static final FileType CXX
```


μορφή γλώσσας προγραμματισμού C-Based


### HXX {#HXX}
```
public static final FileType HXX
```


Αρχεία κεφαλίδας που γράφονται στη γλώσσα προγραμματισμού C++


### HH {#HH}
```
public static final FileType HH
```


Πληροφορίες κεφαλίδας που αναφέρονται από αρχείο πηγαίου κώδικα C++


### HPP {#HPP}
```
public static final FileType HPP
```


Αρχεία κεφαλίδας που γράφονται στη γλώσσα προγραμματισμού C++


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Εργαλείο για τη διαχείριση της διαδικασίας κατασκευής λογισμικού


### CS {#CS}
```
public static final FileType CS
```


μορφή γλώσσας προγραμματισμού CSharp


### CSX {#CSX}
```
public static final FileType CSX
```


μορφή αρχείου σεναρίου CSharp


### CAKE {#CAKE}
```
public static final FileType CAKE
```


μορφή συστήματος αυτοματοποίησης κατασκευής διαπλατφόρμας CSharp


### DIFF {#DIFF}
```
public static final FileType DIFF
```


μορφή εργαλείου σύγκρισης δεδομένων


### PATCH {#PATCH}
```
public static final FileType PATCH
```


μορφή λίστας διαφορών


### REJ {#REJ}
```
public static final FileType REJ
```


μορφή απορριφθέντων αρχείων


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Αρχείο πηγαίου κώδικα γραμμένο σε μορφή Groovy


### GVY {#GVY}
```
public static final FileType GVY
```


Αρχείο πηγαίου κώδικα γραμμένο σε μορφή Groovy


### GRADLE {#GRADLE}
```
public static final FileType GRADLE
```


Μορφή συστήματος αυτοματοποίησης κατασκευής


### HAML {#HAML}
```
public static final FileType HAML
```


Γλώσσα σήμανσης για απλοποιημένη δημιουργία HTML


### JS {#JS}
```
public static final FileType JS
```


Μορφή γλώσσας προγραμματισμού JavaScript


### ES6 {#ES6}
```
public static final FileType ES6
```


Μορφή τυποποιημένης γλώσσας σεναρίου JavaScript


### MJS {#MJS}
```
public static final FileType MJS
```


Επέκταση για αρχεία μονάδων EcmaScript (ES)


### PAC {#PAC}
```
public static final FileType PAC
```


Αρχείο αυτόματης ρύθμισης διαμεσολαβητή (Proxy Auto-Configuration) για μορφή συνάρτησης JavaScript


### JSON {#JSON}
```
public static final FileType JSON
```


Ελαφριά μορφή για αποθήκευση και μεταφορά δεδομένων


### BOWERRC {#BOWERRC}
```
public static final FileType BOWERRC
```


Αρχείο ρυθμίσεων για έλεγχο πακέτων στην πλευρά του διακομιστή


### JSHINTRC {#JSHINTRC}
```
public static final FileType JSHINTRC
```


Εργαλείο ποιότητας κώδικα JavaScript


### JSCSRC {#JSCSRC}
```
public static final FileType JSCSRC
```


Μορφή αρχείου ρυθμίσεων JavaScript


### WEBMANIFEST {#WEBMANIFEST}
```
public static final FileType WEBMANIFEST
```


Το αρχείο Manifest περιλαμβάνει πληροφορίες για την εφαρμογή


### JSMAP {#JSMAP}
```
public static final FileType JSMAP
```


Αρχείο JSON που περιέχει πληροφορίες για το πώς να μεταφράσετε τον κώδικα πίσω στον πηγαίο κώδικα


### HAR {#HAR}
```
public static final FileType HAR
```


Η μορφή HTTP Archive


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Μορφή γλώσσας προγραμματισμού Java


### LESS {#LESS}
```
public static final FileType LESS
```


Μορφή γλώσσας φύλλου στυλ δυναμικού προεπεξεργαστή


### LOG {#LOG}
```
public static final FileType LOG
```


Η καταγραφή διατηρεί ένα μητρώο γεγονότων, διεργασιών, μηνυμάτων και επικοινωνίας


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Το Makefile είναι ένα αρχείο που περιέχει ένα σύνολο οδηγιών που χρησιμοποιούνται από το εργαλείο αυτοματοποίησης κατασκευής make για τη δημιουργία ενός στόχου


### MK {#MK}
```
public static final FileType MK
```


Το Makefile είναι ένα αρχείο που περιέχει ένα σύνολο οδηγιών που χρησιμοποιούνται από το εργαλείο αυτοματοποίησης κατασκευής make για τη δημιουργία ενός στόχου


### MD {#MD}
```
public static final FileType MD
```


Μορφή γλώσσας Markdown


### MKD {#MKD}
```
public static final FileType MKD
```


Μορφή γλώσσας Markdown


### MDWN {#MDWN}
```
public static final FileType MDWN
```


Μορφή γλώσσας Markdown


### MDOWN {#MDOWN}
```
public static final FileType MDOWN
```


Μορφή γλώσσας Markdown


### MARKDOWN {#MARKDOWN}
```
public static final FileType MARKDOWN
```


Μορφή γλώσσας Markdown


### MARKDN {#MARKDN}
```
public static final FileType MARKDN
```


Μορφή γλώσσας Markdown


### MDTXT {#MDTXT}
```
public static final FileType MDTXT
```


Μορφή γλώσσας Markdown


### MDTEXT {#MDTEXT}
```
public static final FileType MDTEXT
```


Μορφή γλώσσας Markdown


### ML {#ML}
```
public static final FileType ML
```


Μορφή γλώσσας προγραμματισμού Caml


### MLI {#MLI}
```
public static final FileType MLI
```


Μορφή γλώσσας προγραμματισμού Caml


### OBJC {#OBJC}
```
public static final FileType OBJC
```


Μορφή γλώσσας προγραμματισμού Objective-C


### OBJCP {#OBJCP}
```
public static final FileType OBJCP
```


Μορφή γλώσσας προγραμματισμού Objective-C++


### PHP {#PHP}
```
public static final FileType PHP
```


Μορφή γλώσσας προγραμματισμού PHP


### PHP4 {#PHP4}
```
public static final FileType PHP4
```


Μορφή γλώσσας προγραμματισμού PHP


### PHP5 {#PHP5}
```
public static final FileType PHP5
```


Μορφή γλώσσας προγραμματισμού PHP


### PHTML {#PHTML}
```
public static final FileType PHTML
```


Τυπική επέκταση αρχείου για προγράμματα PHP 2


### CTP {#CTP}
```
public static final FileType CTP
```


Μορφή προτύπου CakePHP


### PL {#PL}
```
public static final FileType PL
```


Μορφή γλώσσας προγραμματισμού Perl


### PM {#PM}
```
public static final FileType PM
```


Μορφή μονάδας Perl


### POD {#POD}
```
public static final FileType POD
```


Μορφή ελαφριάς γλώσσας σήμανσης Perl


### T {#T}
```
public static final FileType T
```


Μορφή αρχείου δοκιμής Perl


### PSGI {#PSGI}
```
public static final FileType PSGI
```


Διεπαφή μεταξύ διακομιστών ιστού και εφαρμογών ιστού και πλαισίων γραμμένων στη γλώσσα προγραμματισμού Perl


### P6 {#P6}
```
public static final FileType P6
```


Μορφή γλώσσας προγραμματισμού Perl


### PL6 {#PL6}
```
public static final FileType PL6
```


Μορφή γλώσσας προγραμματισμού Perl


### PM6 {#PM6}
```
public static final FileType PM6
```


Μορφή μονάδας Perl


### NQP {#NQP}
```
public static final FileType NQP
```


Μεσαία γλώσσα που χρησιμοποιείται για την κατασκευή του μεταγλωττιστή Rakuto Perl 6


### PROP {#PROP}
```
public static final FileType PROP
```


Μορφή αρχείου ιδιοτήτων


### CFG {#CFG}
```
public static final FileType CFG
```


Αρχείο διαμόρφωσης που χρησιμοποιείται για την αποθήκευση ρυθμίσεων


### CONF {#CONF}
```
public static final FileType CONF
```


Αρχείο διαμόρφωσης που χρησιμοποιείται σε συστήματα βασισμένα σε Unix και Linux


### DIR {#DIR}
```
public static final FileType DIR
```


Ο φάκελος είναι μια θέση για την αποθήκευση αρχείων στον υπολογιστή


### PY {#PY}
```
public static final FileType PY
```


Μορφή γλώσσας προγραμματισμού Python


### RPY {#RPY}
```
public static final FileType RPY
```


Μηχανή αρχείων βασισμένη σε Python για τη δημιουργία και εκτέλεση παιχνιδιών


### PYW {#PYW}
```
public static final FileType PYW
```


Αρχεία που χρησιμοποιούνται στα Windows για να υποδεικνύουν ότι πρέπει να εκτελεστεί ένα script


### CPY {#CPY}
```
public static final FileType CPY
```


Μορφή script ελεγκτή Python


### GYP {#GYP}
```
public static final FileType GYP
```


Μορφή εργαλείου αυτοματοποίησης κατασκευής


### GYPI {#GYPI}
```
public static final FileType GYPI
```


Μορφή εργαλείου αυτοματοποίησης κατασκευής


### PYI {#PYI}
```
public static final FileType PYI
```


Μορφή αρχείου διεπαφής Python


### IPY {#IPY}
```
public static final FileType IPY
```


Μορφή script IPython


### RST {#RST}
```
public static final FileType RST
```


Ελαφριά γλώσσα σήμανσης


### RB {#RB}
```
public static final FileType RB
```


Μορφή γλώσσας προγραμματισμού Ruby


### ERB {#ERB}
```
public static final FileType ERB
```


Μορφή γλώσσας προγραμματισμού Ruby


### RJS {#RJS}
```
public static final FileType RJS
```


Μορφή γλώσσας προγραμματισμού Ruby


### GEMSPEC {#GEMSPEC}
```
public static final FileType GEMSPEC
```


Αρχείο προγραμματιστή που καθορίζει τα χαρακτηριστικά ενός RubyGems


### RAKE {#RAKE}
```
public static final FileType RAKE
```


Εργαλείο αυτοματοποίησης κατασκευής Ruby


### RU {#RU}
```
public static final FileType RU
```


Μορφή αρχείου διαμόρφωσης Rack


### PODSPEC {#PODSPEC}
```
public static final FileType PODSPEC
```


Μορφή ρυθμίσεων κατασκευής Ruby


### RBI {#RBI}
```
public static final FileType RBI
```


Μορφή αρχείου διεπαφής Ruby


### SASS {#SASS}
```
public static final FileType SASS
```


Μορφή γλώσσας φύλλων στυλ


### SCSS {#SCSS}
```
public static final FileType SCSS
```


Μορφή γλώσσας φύλλων στυλ


### SCALA {#SCALA}
```
public static final FileType SCALA
```


μορφή γλώσσας προγραμματισμού Scala


### SBT {#SBT}
```
public static final FileType SBT
```


μορφή εργαλείου κατασκευής SBT για Scala


### SC {#SC}
```
public static final FileType SC
```


μορφή φύλλου εργασίας Scala


### SH {#SH}
```
public static final FileType SH
```


μορφή σεναρίου προγραμματισμένου για bash


### BASH {#BASH}
```
public static final FileType BASH
```


Τύπος ερμηνευτή που επεξεργάζεται εντολές κελύφους


### BASHRC {#BASHRC}
```
public static final FileType BASHRC
```


Αρχείο που καθορίζει τη συμπεριφορά των διαδραστικών κελύφων


### EBUILD {#EBUILD}
```
public static final FileType EBUILD
```


Εξειδικευμένο σενάριο bash που αυτοματοποιεί διαδικασίες μεταγλώττισης και εγκατάστασης για πακέτα λογισμικού


### SQL {#SQL}
```
public static final FileType SQL
```


μορφή Structured Query Language


### DSQL {#DSQL}
```
public static final FileType DSQL
```


μορφή Dynamic Structured Query Language


### VIM {#VIM}
```
public static final FileType VIM
```


μορφή αρχείου πηγαίου κώδικα Vim


### YAML {#YAML}
```
public static final FileType YAML
```


μορφή γλώσσας σειριοποίησης δεδομένων αναγνώσιμη από άνθρωπο


### YML {#YML}
```
public static final FileType YML
```


μορφή γλώσσας σειριοποίησης δεδομένων αναγνώσιμη από άνθρωπο


### values() {#values--}
```
public static FileType[] values()
```




**Returns:**
com.groupdocs.comparison.result.FileType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static FileType valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype)
### fromFileNameOrExtension(String value) {#fromFileNameOrExtension-java.lang.String-}
```
public static FileType fromFileNameOrExtension(String value)
```


Επιστρέφει FileType βάσει ονόματος αρχείου ή επέκτασης


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | java.lang.String | Όνομα αρχείου ή επέκταση, όχι null |
|

**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the file type

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Λαμβάνει λίστα των υποστηριζόμενων τύπων αρχείων


**Returns:**
java.util.List<com.groupdocs.comparison.result.FileType> - λίστα των FileType

### areEquals(FileType left, FileType right) {#areEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areEquals(FileType left, FileType right)
```


Ελέγχει την ισότητα των παρεχόμενων τύπων αρχείων


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Αριστερό αντικείμενο [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Δεξιό αντικείμενο [FileType](../../com.groupdocs.comparison.result/filetype). |
|

**Returns:**
boolean - true εάν είναι ίσο, αλλιώς false

### areNotEquals(FileType left, FileType right) {#areNotEquals-com.groupdocs.comparison.result.FileType-com.groupdocs.comparison.result.FileType-}
```
public static boolean areNotEquals(FileType left, FileType right)
```


Ελέγχει αν οι παρεχόμενοι τύποι αρχείων δεν είναι ίσοι


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | left | [FileType](../../com.groupdocs.comparison.result/filetype) | Αριστερό αντικείμενο [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | right | [FileType](../../com.groupdocs.comparison.result/filetype) | Δεξιό αντικείμενο [FileType](../../com.groupdocs.comparison.result/filetype). |
|

**Returns:**
boolean - true εάν δεν είναι ίσο, αλλιώς false

### getFileFormat() {#getFileFormat--}
```
public String getFileFormat()
```


Λαμβάνει περιγραφή κειμένου του τύπου αρχείου


**Returns:**
java.lang.String - περιγραφή τύπου αρχείου

### getExtension() {#getExtension--}
```
public String getExtension()
```


Λαμβάνει την επέκταση του τύπου αρχείου


**Returns:**
java.lang.String - επέκταση του τύπου αρχείου

### toString() {#toString--}
```
public String toString()
```


Λαμβάνει την αναπαράσταση συμβολοσειράς του [FileType](../../com.groupdocs.comparison.result/filetype), για παράδειγμα
'μορφή γλώσσας προγραμματισμού PHP (.php)'



**Returns:**
java.lang.String - αναπαράσταση συμβολοσειράς

