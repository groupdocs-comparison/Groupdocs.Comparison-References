---
title: "set_license méthode"
second_title: "GroupDocs.Comparison pour Python via .NET Références d'API"
description: 
type: docs
url: /fr/python-net/groupdocs.comparison/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Appliquer une licence au processus actuel.

```python
def set_license(self, license_source):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| license_source |  | Un chemin de chaîne vers un fichier ``.lic`` ou un objet de type fichier lisible qui fournit les octets de licence. Les entrées de type fichier sont écrites dans un fichier temporaire avant d'être transmises au pont. |

| Exceptions | Description |
| :- | :- |
| `TypeError` | Si ``license_source`` n'est ni un chemin de chaîne ni un objet de type fichier lisible. |

### Voir aussi
* class [`License`](/comparison/python-net/groupdocs.comparison/license/)
