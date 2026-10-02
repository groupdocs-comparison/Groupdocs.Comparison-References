---
title: "set_license metode"
second_title: "Referensi API GroupDocs.Comparison untuk Python via .NET"
description: 
type: docs
url: /id/python-net/groupdocs.comparison/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Terapkan lisensi ke proses saat ini.

```python
def set_license(self, license_source):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| license_source |  | Baik jalur string ke file ``.lic`` atau objek yang dapat dibaca mirip file yang menghasilkan byte lisensi. Input mirip file ditulis ke file sementara sebelum diteruskan ke bridge. |

| Menaikkan | Deskripsi |
| :- | :- |
| `TypeError` | Jika ``license_source`` bukan jalur string maupun objek yang dapat dibaca mirip file. |

### Lihat Juga
* class [`License`](/comparison/python-net/groupdocs.comparison/license/)
