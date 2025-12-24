---
title: apply_revision_changes method
second_title: GroupDocs.Comparison for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.comparison.words.revision/revisionhandler/apply_revision_changes/
is_root: false
weight: 20
---

## apply_revision_changes {#groupdocs.comparison.words.revision.ApplyRevisionOptions}

Processes changes in revisions and applies them to the same file from which the revisions were taken.



```python
def apply_revision_changes(self, changes):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| changes | groupdocs.comparison.words.revision.ApplyRevisionOptions | List of changed revisions |


## apply_revision_changes {#System.String-groupdocs.comparison.words.revision.ApplyRevisionOptions}

Processes changes in revisions, and the result is written to the specified file by path.



```python
def apply_revision_changes(self, file_path, changes):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | Result file path |
| changes | groupdocs.comparison.words.revision.ApplyRevisionOptions | List of changed revisions |


## apply_revision_changes {#io.RawIOBase-groupdocs.comparison.words.revision.ApplyRevisionOptions}

Processes changes in revisions and the result is written to the document stream.



```python
def apply_revision_changes(self, document, changes):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | Result document |
| changes | groupdocs.comparison.words.revision.ApplyRevisionOptions | List of changed revisions |



### See Also
* module [`groupdocs.comparison.words.revision`](../../)
* class [`RevisionHandler`](/comparison/python-net/groupdocs.comparison.words.revision/revisionhandler)
