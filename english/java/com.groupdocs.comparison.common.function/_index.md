---
title: com.groupdocs.comparison.common.function
second_title: GroupDocs.Comparison for Java API Reference
description: Provides functional interfaces that allow accessing pages data during the document comparison process.
type: docs
weight: 15
url: /java/com.groupdocs.comparison.common.function/
---

Provides functional interfaces that allow accessing pages data during the document comparison process.

The functional interfaces in this package are used to access data of pages when performing document comparison using GroupDocs.Comparison.

The main functional interfaces in this package are:

 *  [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - Allows handling creating output stream used by Comparison to save pages data.
 *  [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - Allows handling releasing output stream used by Comparison to save pages data.

These functional interfaces can be used to define custom logic and behavior when working with document pages. They provide flexibility to customize how and where to save pages are processed.

For more details on working with revisions and tracked changes in Word documents using GroupDocs.Comparison for Java, please refer to the [GroupDocs.Comparison Documentation][].


[GroupDocs.Comparison Documentation]: https://docs.groupdocs.com/comparison/java/


## Interfaces

| Interface | Description |
| --- | --- |
| [CreatePageStreamFunction](../com.groupdocs.comparison.common.function/createpagestreamfunction) | Functional interface that is used to create output stream used by Comparison to save preview image. |
| [ReleasePageStreamFunction](../com.groupdocs.comparison.common.function/releasepagestreamfunction) | Functional interface that is used to close output stream that was used by Comparison to save preview image. |
