---
tags: Educative
---

# Become a Spring Boot Developer

## Module 1: Core Java Concepts

### Variable and User Input

User input example code:
```java=
import java.util.Scanner;

class take_input {
    public static void main(String[] args) {
        Scanner scanner_one = new Scanner(System.in);
        System.out.println("Enter your name: ");
        String name = scanner_one.nextLine();
        System.out.println("Your name is: " + name);
    }
}
```

### Simple Math Logic

#### Operator associativity
Operator associativity determines whether, in an expression, if there are multiple operators like (1 + 2 - 5), how will they be evaluated if they are of the same precedence. 

Operators |	Description |	Associativity
|--|--|--|
|+ , -	 | Unary Plus and minus	|Right to left|
|! , ~	|Logical NOT and bitwise NOT	|Right to left
|=	|Direct assignment	|Right to left
|+= , -=	|Assignment by sum and difference	|Right to left
|*= , /= , %=|	Assignment by product, quotient, and remainder	|Right to left
|   <<= , >>=	|Assignment by bitwise left shift and right shift	|Right to left
|  &= , ^= , =	|Assignment by bitwise AND, XOR, and OR	|Right to left
|  ++ , --	|Suffix/postfix increment and decrement	|Right to left
| * , / , %	vMultiplication, division, and remainder	|Left to Right
|+ , -	|Addition and subtraction	|Left to Right
|<< , >>	|Bitwise left shift and right shift	|Left to Right
|< , <=	|For relational operators	|Left to Right
|> , >=	|For relational operators	|Left to Right
|== , !=	|For relational	|Left to Right
|&	|Bitwise AND|	Left to Right
|^	|Bitwise XOR (exclusive or)	|Left to Right
|&&	|Logical AND	Left to Right
|  |	Logical OR	|Left to Right
| |	Bitwise OR (inclusive or)	|Left to Right

### Exponentiation
```java=
System.out.println("2 raised to the power 3 is " + Math.pow(2, 3));
System.out.println("Exponent squared is " + Math.exp(2));
System.out.println("The square root of 16 is " + Math.sqrt(16));
System.out.println("The cube root of 27 is " + Math.cbrt(27));

// 2 raised to the power 3 is 8.0
// Exponent squared is 7.38905609893065
// The square root of 16 is 4.0
// The cube root of 27 is 3.0
```

