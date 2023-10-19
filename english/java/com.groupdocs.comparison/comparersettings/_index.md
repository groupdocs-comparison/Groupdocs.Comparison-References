---
title: ComparerSettings
second_title: GroupDocs.Comparison for Java API Reference
description: Defines settings for customizing the behavior of the  class.
type: docs
weight: 11
url: /java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

Defines settings for customizing the behavior of the [Comparer](../../com.groupdocs.comparison/comparer) class.

Example usage:

```

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ComparerSettings()](#ComparerSettings--) | Instantiates new instance of ComparerSettings class. |
| [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | Instantiates new instance of ComparerSettings class. |
## Methods

| Method | Description |
| --- | --- |
| [getLogger()](#getLogger--) | Gets the logger implementation used for logging. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Sets the logger implementation for logging. |
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


Instantiates new instance of ComparerSettings class.

### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


Instantiates new instance of ComparerSettings class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | logger to be used |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Gets the logger implementation used for logging.

**Returns:**
com.groupdocs.foundation.logging.ILogger - the logger
### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Sets the logger implementation for logging.

Use com.groupdocs.comparison.logging.NullLogger\#NULL\_LOGGER.NULL\_LOGGER to disable logging.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.groupdocs.foundation.logging.ILogger | the logger implementation to set |

