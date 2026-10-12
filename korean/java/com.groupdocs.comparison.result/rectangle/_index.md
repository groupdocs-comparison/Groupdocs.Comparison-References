---
title: "Rectangle"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "Rectangle 클래스는 문서의 변경된 영역을 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

Rectangle 클래스는 문서의 변경된 영역을 나타냅니다.


사용 예시:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final Rectangle box = change.getBox();
         // Print the changed area on page
         System.out.println("Changed area on a page: "
                 + box.getX() + ", " + box.getY() + ", " + box.getWidth() + ", " + box.getHeight());
     }
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Rectangle 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | 지정된 사각형의 복사본인 새 Rectangle 객체를 생성합니다. |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | 지정된 x, y, 너비 및 높이를 사용하여 Rectangle 클래스의 새 인스턴스를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getHeight()](#getHeight--) | 사각형의 높이를 가져옵니다. |
|
|  | [setHeight(double value)](#setHeight-double-) | 사각형의 높이를 설정합니다. |
|
|  | [getWidth()](#getWidth--) | 사각형의 너비를 가져옵니다. |
|
|  | [setWidth(double value)](#setWidth-double-) | 사각형의 너비를 설정합니다. |
|
|  | [getX()](#getX--) | 사각형 왼쪽 위 모서리의 x 좌표를 가져옵니다. |
|
|  | [setX(double value)](#setX-double-) | 사각형 왼쪽 위 모서리의 x 좌표를 설정합니다. |
|
|  | [getY()](#getY--) | 사각형 왼쪽 위 모서리의 y 좌표를 가져옵니다. |
|
|  | [setY(double value)](#setY-double-) | 사각형 왼쪽 위 모서리의 y 좌표를 설정합니다. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


Rectangle 클래스의 새 인스턴스를 초기화합니다.


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


지정된 사각형의 복사본인 새 Rectangle 객체를 생성합니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | 복사할 사각형 |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


지정된 x, y, 너비 및 높이를 사용하여 Rectangle 클래스의 새 인스턴스를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | x | double | 사각형의 왼쪽 위 모서리의 x좌표 |
|
|  | y | double | 사각형의 왼쪽 위 모서리의 y좌표 |
|
|  | width | double | 사각형의 너비 |
|
|  | height | double | 사각형의 높이 |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


사각형의 높이를 가져옵니다.


**Returns:**
double - 사각형의 높이

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


사각형의 높이를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | double | 사각형의 높이 |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


사각형의 너비를 가져옵니다.


**Returns:**
double - 사각형의 너비

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


사각형의 너비를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | double | 사각형의 너비 |
|

### getX() {#getX--}
```
public double getX()
```


사각형 왼쪽 위 모서리의 x 좌표를 가져옵니다.


**Returns:**
double - 사각형의 왼쪽 위 모서리의 x좌표

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


사각형 왼쪽 위 모서리의 x 좌표를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | double | 사각형의 왼쪽 위 모서리의 x좌표 |
|

### getY() {#getY--}
```
public double getY()
```


사각형 왼쪽 위 모서리의 y 좌표를 가져옵니다.


**Returns:**
double - 사각형의 왼쪽 위 모서리의 y좌표

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


사각형 왼쪽 위 모서리의 y 좌표를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | double | 사각형의 왼쪽 위 모서리의 y좌표 |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
