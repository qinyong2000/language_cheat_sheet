
# History
## C
- 1972, [Dennis Ritchie](https://en.wikipedia.org/wiki/Dennis_Ritchie)
## Objective-C
- 1984, [Brad Cox](https://en.wikipedia.org/wiki/Brad_Cox)
## C++
- 1985, [Bjarne Stroustrup](https://en.wikipedia.org/wiki/Bjarne_Stroustrup)
## Perl
- 1987, [Larry Wall](https://en.wikipedia.org/wiki/Larry_Wall)
## Bash
- 1989, [Brian Fox](https://en.wikipedia.org/wiki/Brian_Fox_(computer_programmer))
## Python
- 1990, [Guido Van Rossum](https://en.wikipedia.org/wiki/Guido_Van_Rossum)
## Java
- 1995, [James Gosling](https://en.wikipedia.org/wiki/James_Gosling) at Sun Microsystems
## PHP
- 1995, [Rasmus Lerdorf](https://en.wikipedia.org/wiki/Rasmus_Lerdorf)
## Ruby
- 1995, [Yukihiro Matsumoto](https://en.wikipedia.org/wiki/Yukihiro_Matsumoto)
## JavaScript
- 1995, [Brendan Eich](https://en.wikipedia.org/wiki/Brendan_Eich) at Netscape
## C#
- 2000, [Anders Hejlsberg](https://en.wikipedia.org/wiki/Anders_Hejlsberg)
## Scala
- 2003, [Martin Odersky](https://en.wikipedia.org/wiki/Martin_Odersky)
## Go
- 2009, [Google](https://en.wikipedia.org/wiki/Google)

# Hello World

## C
main.c
```C
#include <stdio.h>
/* Hello, World! */
int main(void) {
    printf("hello, world\n");
}
```

## Objective-C
main.m
```Objective-C
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[]) {
    @autoreleasepool {
        NSLog(@"Hello, World!");
    }
    return 0;
}
```

## C++
hello.cpp
```C++
#include <iostream>
// Hello, World!
int main() {
    std::cout << "Hello, world!\n";
    return 0;
}
```
## Java
HelloWorld.java
```Java
package main;
// Hello, World!
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
## C#
HelloWorld.cs
```C#
using System;
// Hello, World!
public class HelloWorld {
    static void Main(string[] args) {
        Console.WriteLine("Hello, world!");
    }
}
```
## Scala
HelloWorld.scala
```Scala
package main
// Hello, World!
object HelloWorld {
  def main(args: Array[String]): Unit = {
    println("Hello, World!")
  }
}
``` 
## Go
hello.go
```golang
package main

import "fmt"
// Hello, World!
func main() {
    fmt.Println("Hello, World!")
}
```

## Perl
hello.pl
```Perl
# Hello, World!
print "Hello, World!\n";
```
## Bash
hello.sh
```Bash
#!/bin/bash
# Hello, World!
var="Hello, World!"
echo "$var" 
```
## Python
hello.py
```Python
#!/usr/bin/env python

# Hello, World!
def main():
    print("Hello, World!")
 
if __name__ == '__main__':
    main()
```
## PHP
hello.php
```PHP
<?php
// Hello, World!
echo "Hello, World!";
?>
```
## Ruby
hello.rb
```Ruby
# Hello, World!
puts 'Hello, World!'
```
## JavaScript
hello.js
```JavaScript
// Hello, World!
console.log("Hello, World!");
```

# Preprocess
## C
```C
#define TRUE    1

#ifdef TRUE
  ...
#else
  ...
#endif

#include <stdio.h>
#include "example.h"
```
# Variable and Type
## C
```C
/* define */
int a, b = 1;  /* char, short, int, long, long long, float, double */
char c = 'a', letter = 66;
float f = 0.1;
unsigned int h = 0x10;
int *p = &h; /* address of h */
*p = 2;      /* h = 2 */
/* opreator */
a += b; a++; ++a; a = b**2;
z = a & b; y = ~x; z = x ^ y; z >>= 1;
a = b > 0 ? 1 : 2;
```

# Array and String
## C
```C
/* deifne */
int numbers[10];
numbers[0] = 10;
int point[] = {0, 0, 1, 0};
int len = sizeof(point) / sizeof(int); /* 4 */
int two_dim[2][3] = {{5, 2, 1}, {6, 7, 8}};
char string[] = "abcdef";
char *str = "abcdef";
char string[] = {'1', '2', 0};  // must zero terminated

/* opreate */
#include <string.h>
int len = strlen(str);
strcpy(target, source);
strncpy(target, source, n);
strcat(target, source);
strncat(target, source, n);
int cmp = strcmp(str1, str2); /* return 0 if equals */
char *p = strchr(str, 'a');   /* NULL if not found */
char *p = strstr(str, "ab");  /* NULL if not found */  

#include <stdio.h>
printf("%s\n", str);
scanf("%s", str);
```

# Collection
## C
```C
/* List */
/* Map */
/* Set */
/* Tree */
```
# Flow Control
## C
```C
if (a > b) {
  ...
}
for (int i = 0; i < 10; i++) {
    if (a > 5) break;
    if (a <= 5) continue;
}
while (a > 1) {
  ...
}
do {
  ...
} while (a > 1);

switch(i) {
    case 1:
    case 2:
       break;
    case 3:
       break;
    default:
       break;
}


```
# Function
## C
```C
double power(double x, int n) {
    ...
    return x;
}

void print() {
    ...
}
```
# Data Structure and Class
## C
```C
/* type define */
typedef int t_int;
type_int i;
typedef int * t_int_ptr;
t_int_ptr p = &i;

/* structure */
typedef struct {
    char name[20];
    char sex;
    int age;
} t_person;
t_person person = {"tom", 'M', 20};
person.age = 30;
t_person person1 = person;
t_person *p = &person;
char *name = p->name;

union person {      // size is 30 bytes
    char first[20];
    char second[30];    
};
```
# Module and Package
# Regular Expression
# Simple I/O
# Advance