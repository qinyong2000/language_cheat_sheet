## C
```C
/* defination */
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

## Objective-C
```Objective-C
TODO
```

## C++
```C++
TODO
```
## Java
```Java
TODO
```
## C#
```C#
TODO
```
## Scala
```Scala
TODO
``` 
## Go
```golang
// define
var p [2]int
var p []int = []int{1, 2, 3, 4}

// slice
a[lo: hi]   // lo <= index < hi
a[2:]       // index 1 to tail
a[:2]       // index 0 to 1
a[:]        // all

s := a[0:2] // elements of a index 0 to 1

// function
len(p)      // lengh of array
cap(p)      // capacity of array
a = append(a, 5)            // extend capacity
s := make([]int, 5)         // len=5 capacity=5
s := make([]int, 5, 100])   // len=5 capacity=100

// string function
// concat
a := "Hello"
b := a + " World"
// heredoc
s := `
Hello
World!
`
// substring
s := "Hello World!"
s[0:5]      // Hello

import "strings"
strings.Contains("abcdef", "bc")    // true
strings.HasPrefix("abcdef", "abc")  // true
strings.Index("abcdef", "bc")       // 1

strings.ToUpper("abcd")             // ABCD
strings.ToLower("Abcd")             // abcd

strings.TrimLeft("!abcd!", "!")     // abcd!
strings.TrimRight("!abcd!", "!")    // !abcd
strings.Trim("!abcd!", "!")         // abcd

strings.Replace("abcdab", "ab", "Ab", 1) // Abcdab
strings.Replace("abcdab", "ab", "Ab", -1) // AbcdAb

strings.Split("ab,cd,ef", ",")  // []string{"ab", "cd", "ef"}
string.SplitN("ab,cd,ef", ",", 2)   // []string{"ab", "cd,ef"}

s := []string{"ab", "cd", "ef"}
strings.Join(s, ",")   // "ab,cd,ef"

// multibyte string
s := "日本語"
len(s)          // 9
len([]rune(s))  // 3

```

## Perl
```Perl
TODO
```
## Bash
```Bash
TODO
```
## Python
```Python
TODO
```
## PHP
```PHP
TODO
```
## Ruby
```Ruby
TODO
```
## JavaScript
```JavaScript
TODO
```
