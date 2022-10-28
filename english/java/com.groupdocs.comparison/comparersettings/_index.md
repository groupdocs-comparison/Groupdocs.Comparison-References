---
title: ComparerSettings
second_title: GroupDocs.Comparison for Java API Reference
description: Defines settings for customizing  behaviour.
type: docs
weight: 11
url: /java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

Defines settings for customizing [Comparer](../../com.groupdocs.comparison/comparer) behaviour.
## Constructors

| Constructor | Description |
| --- | --- |
| [ComparerSettings()](#ComparerSettings--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getLogger()](#getLogger--) | Logger implementation |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Logger implementation, use com.groupdocs.foundation.logging.NullLogger\#NULL\_LOGGER.NULL\_LOGGER to disable logging |
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Logger implementation

**Returns:**
com.groupdocs.foundation.logging.ILogger - the logger
### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Logger implementation, use com.groupdocs.foundation.logging.NullLogger\#NULL\_LOGGER.NULL\_LOGGER to disable logging

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.groupdocs.foundation.logging.ILogger | the value |

