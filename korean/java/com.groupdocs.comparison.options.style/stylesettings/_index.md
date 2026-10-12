---
title: "StyleSettings"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "이 클래스는 텍스트 서식을 위한 스타일 설정을 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.comparison.options.style/stylesettings/
---
**Inheritance:**
java.lang.Object
```
public class StyleSettings
```

이 클래스는 텍스트 서식을 위한 스타일 설정을 나타냅니다.


이 클래스를 사용하여 글꼴 색상, 강조 색상, 스타일 속성(굵게, 밑줄, 기울임, 취소선)을 사용자 지정합니다,
문자열 구분자, 원본 크기 및 텍스트의 단어 구분자.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    StyleSettings styleSettings = new StyleSettings();
    styleSettings.setFontColor(Color.GREEN);
    styleSettings.setBold(true);
    styleSettings.setUnderline(true);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setInsertedItemStyle(styleSettings);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [StyleSettings()](#StyleSettings--) | StyleSettings 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFontColor()](#getFontColor--) | 글꼴 색상을 가져옵니다. |
|
|  | [setFontColor(Color value)](#setFontColor-java.awt.Color-) | 글꼴 색상을 설정합니다. |
|
|  | [getShapeColor()](#getShapeColor--) | 도형 색상을 가져옵니다. |
|
|  | [setShapeColor(Color value)](#setShapeColor-java.awt.Color-) | 도형 색상을 설정합니다. |
|
|  | [getHighlightColor()](#getHighlightColor--) | 하이라이트 색상을 가져옵니다. |
|
|  | [setHighlightColor(Color value)](#setHighlightColor-java.awt.Color-) | 하이라이트 색상을 설정합니다. |
|
|  | [isBold()](#isBold--) | 텍스트가 굵게 표시될지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setBold(boolean value)](#setBold-boolean-) | 텍스트를 굵게 표시할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [isUnderline()](#isUnderline--) | 텍스트에 밑줄이 적용될지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setUnderline(boolean value)](#setUnderline-boolean-) | 텍스트에 밑줄을 적용할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [isItalic()](#isItalic--) | 텍스트가 이탤릭체인지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setItalic(boolean value)](#setItalic-boolean-) | 텍스트를 이탤릭체로 할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [isStrikethrough()](#isStrikethrough--) | 텍스트에 취소선이 적용될지 여부를 나타내는 플래그를 가져옵니다. |
|
|  | [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | 텍스트에 취소선을 적용할지 여부를 나타내는 플래그를 설정합니다. |
|
|  | [getStartStringSeparator()](#getStartStringSeparator--) | 시작 문자열 구분자를 가져옵니다. |
|
|  | [setStartStringSeparator(String value)](#setStartStringSeparator-java.lang.String-) | 시작 문자열 구분자를 설정합니다. |
|
|  | [getEndStringSeparator()](#getEndStringSeparator--) | 끝 문자열 구분자를 가져옵니다. |
|
|  | [setEndStringSeparator(String value)](#setEndStringSeparator-java.lang.String-) | 끝 문자열 구분자를 설정합니다. |
|
|  | [getOriginalSize()](#getOriginalSize--) | 비교 문서의 원본 크기를 가져옵니다. |
|
|  | [setOriginalSize(Size value)](#setOriginalSize-com.groupdocs.comparison.options.style.Size-) | 비교 문서의 원본 크기를 설정합니다. |
|
|  | [getWordsSeparators()](#getWordsSeparators--) | 단어 구분 문자들을 가져옵니다. |
|
|  | [setWordsSeparators(char[] value)](#setWordsSeparators-char---) | 단어 구분 문자들을 설정합니다. |
|
### StyleSettings() {#StyleSettings--}
```
public StyleSettings()
```


StyleSettings 클래스의 새 인스턴스를 초기화합니다.


### getFontColor() {#getFontColor--}
```
public final Color getFontColor()
```


글꼴 색상을 가져옵니다.


**Returns:**
java.awt.Color - 글꼴 색상.

### setFontColor(Color value) {#setFontColor-java.awt.Color-}
```
public final void setFontColor(Color value)
```


글꼴 색상을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.awt.Color | 새로운 글꼴 색상. |
|

### getShapeColor() {#getShapeColor--}
```
public final Color getShapeColor()
```


도형 색상을 가져옵니다.


**Returns:**
java.awt.Color - 도형 색상.

### setShapeColor(Color value) {#setShapeColor-java.awt.Color-}
```
public final void setShapeColor(Color value)
```


도형 색상을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.awt.Color | 새로운 도형 색상. |
|

### getHighlightColor() {#getHighlightColor--}
```
public final Color getHighlightColor()
```


하이라이트 색상을 가져옵니다.


**Returns:**
java.awt.Color - 강조 색상.

### setHighlightColor(Color value) {#setHighlightColor-java.awt.Color-}
```
public final void setHighlightColor(Color value)
```


하이라이트 색상을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.awt.Color | 새로운 강조 색상. |
|

### isBold() {#isBold--}
```
public final boolean isBold()
```


텍스트가 굵게 표시될지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 텍스트가 굵게 표시될 경우 true, 그렇지 않으면 false.

### setBold(boolean value) {#setBold-boolean-}
```
public final void setBold(boolean value)
```


텍스트를 굵게 표시할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 텍스트를 굵게 해야 하면 true, 그렇지 않으면 false. |
|

### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


텍스트에 밑줄이 적용될지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 텍스트가 밑줄이 그어질 경우 true, 그렇지 않으면 false.

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public final void setUnderline(boolean value)
```


텍스트에 밑줄을 적용할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 텍스트에 밑줄을 적용해야 하면 true, 그렇지 않으면 false. |
|

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


텍스트가 이탤릭체인지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 텍스트가 이탤릭체일 경우 true, 그렇지 않으면 false.

### setItalic(boolean value) {#setItalic-boolean-}
```
public final void setItalic(boolean value)
```


텍스트를 이탤릭체로 할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 텍스트를 이탤릭체로 해야 하면 true, 그렇지 않으면 false. |
|

### isStrikethrough() {#isStrikethrough--}
```
public final boolean isStrikethrough()
```


텍스트에 취소선이 적용될지 여부를 나타내는 플래그를 가져옵니다.


**Returns:**
boolean - 텍스트에 취소선이 적용될 경우 true, 그렇지 않으면 false.

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public final void setStrikethrough(boolean value)
```


텍스트에 취소선을 적용할지 여부를 나타내는 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 텍스트에 취소선을 적용해야 하면 true, 그렇지 않으면 false. |
|

### getStartStringSeparator() {#getStartStringSeparator--}
```
public final String getStartStringSeparator()
```


시작 문자열 구분자를 가져옵니다.


**Returns:**
java.lang.String - 시작 문자열 구분자.

### setStartStringSeparator(String value) {#setStartStringSeparator-java.lang.String-}
```
public final void setStartStringSeparator(String value)
```


시작 문자열 구분자를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 새로운 시작 문자열 구분자. |
|

### getEndStringSeparator() {#getEndStringSeparator--}
```
public final String getEndStringSeparator()
```


끝 문자열 구분자를 가져옵니다.


**Returns:**
java.lang.String - 끝 문자열 구분자.

### setEndStringSeparator(String value) {#setEndStringSeparator-java.lang.String-}
```
public final void setEndStringSeparator(String value)
```


끝 문자열 구분자를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 새로운 끝 문자열 구분자. |
|

### getOriginalSize() {#getOriginalSize--}
```
public final Size getOriginalSize()
```


비교 문서의 원본 크기를 가져옵니다.


**Returns:**
[Size](../../com.groupdocs.comparison.options.style/size) - the original size of comparing documents.

### setOriginalSize(Size value) {#setOriginalSize-com.groupdocs.comparison.options.style.Size-}
```
public final void setOriginalSize(Size value)
```


비교 문서의 원본 크기를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.comparison.options.style/size) | 비교 문서의 새로운 원본 크기. |
|

### getWordsSeparators() {#getWordsSeparators--}
```
public final char[] getWordsSeparators()
```


단어 구분 문자들을 가져옵니다.


**Returns:**
char[] - 단어 구분자.

### setWordsSeparators(char[] value) {#setWordsSeparators-char---}
```
public final void setWordsSeparators(char[] value)
```


단어 구분 문자들을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | char[] | 새로운 단어 구분자. |
|

