---
title: "Basic Type 선언"
categories:
  - JAVA
tags:
  - java
---

```java
public calss PrimaryType{
  public static void main(String[] args){
    byte b =127;
    short s = 32767;
    int i = 2000000000;
    long l = 9999999999L;
    float f =0.45f;
    double d = 0.325;
    boolean b = true;
    char c = 'A';
    
    System.out.println(b + s + i + l + f + d + b + c);
    
  }
} 
```



1. *자바의 기본 타입*

   자바에서 기본 타입은 데이터, 값 그 자체.

2. 기본 타입의 선언

   ```데이터타입 변수이름 = 값 ;``` 의 형태로 선언.

   예시 ) 

   ```int date =  0615;```

   

3. 기본 타입의 종류

   |    구분     |  종류   | 범위                                                         |
   | :---------: | :-----: | :----------------------------------------------------------- |
   |    정수     |  byte   | -128 ~ 127                                                   |
   |    정수     |  short  | -32,768 ~ 32,767                                             |
   |    정수     |   int   | -2,147,483,648 ~ 2,147,483,647<br>(최대200억 으로 외우면 편함.) |
   |    정수     |  long   | -9,223,372,036,854,775,808 ~ 9,223,372,036,854,775,807<br>(long 타입은 값 뒤에 L을 붙여야 하는데, 대 소문자 둘 다 사용 가능하지만 보통 대문자를 사용.) |
   |    실수     |  float  | 1.소수점이 없는 경우 최대 39자리 수로 표시된다.<br>2.소수점만 있는 경우 최소 크기는 소수점 아래 45자리 수 까지 표기 가능하다.<br>(float 타입은 값 뒤에 f나 F 둘 다 사용 가능.) |
   |    실수     | double  | 1.소수점이 없는 경우 최대 309자리 수로 표시.<br>2. 소수점만 있는 경우 최소 크기는 소수점 아래 325 자리 수로 표시. |
   | 참/<br>거짓 | boolean | 참이면 true, 거짓이면 false 값이 표시된다.                   |
   |    문자     |  char   | 0 ~ 65,571 에 해당하는 문자를 표시한다<br>(해당 문자의 아스키 코드 값) |

   

   

   
