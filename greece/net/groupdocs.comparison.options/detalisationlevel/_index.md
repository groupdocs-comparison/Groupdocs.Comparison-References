---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison για .NET Αναφορά API"
description: "Καθορίζει το επίπεδο λεπτομερειών σύγκρισης."
type: docs
weight: 230
url: /el/net/groupdocs.comparison.options/detalisationlevel/
---
## DetalisationLevel enumeration

Καθορίζει το επίπεδο λεπτομερειών σύγκρισης.

```csharp
public enum DetalisationLevel
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Low | `0` | Χαμηλό επίπεδο. Παρέχει τη βέλτιστη ταχύτητα σύγκρισης θυσιάζοντας την ποιότητα σύγκρισης. Η σύγκριση εκτελείται ανά λέξη. |
| Middle | `1` | Μεσαίο επίπεδο. Ένα λογικό συμβιβασμό μεταξύ ταχύτητας και ποιότητας σύγκρισης. Η σύγκριση εκτελείται ανά χαρακτήρα, αλλά αγνοώντας τη διάκριση πεζών-κεφαλαίων και τον αριθμό κενών. |
| High | `2` | Υψηλό επίπεδο. Η καλύτερη ποιότητα σύγκρισης, αλλά η χαμηλότερη ταχύτητα. Η σύγκριση εκτελείται ανά χαρακτήρα λαμβάνοντας υπόψη τη διάκριση πεζών-κεφαλαίων και τον αριθμό κενών. |

### Δείτε επίσης

* namespace [GroupDocs.Comparison.Options](../../groupdocs.comparison.options)
* assembly [GroupDocs.Comparison](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑ: δημιουργήθηκε από xmldocmd για GroupDocs.Comparison.dll -->
