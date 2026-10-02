---
title: "set_license μέθοδος"
second_title: "GroupDocs.Comparison για Python μέσω .NET αναφορές API"
description: 
type: docs
url: /el/python-net/groupdocs.comparison/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Εφαρμόστε μια άδεια στη τρέχουσα διεργασία.

```python
def set_license(self, license_source):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| license_source |  | Είτε μια διαδρομή συμβολοσειράς προς ένα αρχείο ``.lic`` είτε ένα αναγνώσιμο αντικείμενο τύπου αρχείου που παρέχει τα bytes της άδειας. Τα εισερχόμενα τύπου αρχείου γράφονται σε ένα προσωρινό αρχείο πριν περάσουν στη γέφυρα. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `TypeError` | Αν το ``license_source`` δεν είναι ούτε διαδρομή συμβολοσειράς ούτε αναγνώσιμο αντικείμενο τύπου αρχείου. |

### Δείτε επίσης
* class [`License`](/comparison/python-net/groupdocs.comparison/license/)
