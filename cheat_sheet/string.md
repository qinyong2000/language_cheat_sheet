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

// convert
import "strconv"
i, _ := strconv.ParseInt("10000", 2, 0)

s := fmt.Sprintf("%d", 100)

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
'eggs'
"yes"
'doesn\'t'
"doesn't"

3 * 'un' + 'ium'    # 'unununium'
'Py' 'thon'         # 'Python'
'Py' + 'thon'       # 'Python'

# here doc
print """\
Usage: thingy [OPTIONS]
    -h                        Display this usage message
    -H hostname               Hostname to connect to
"""
word = 'Python'
word[0]             # 'P'
word[-1]            # 'n'
word[0:2]           # 'Py'
word[:2]
word[4:]
word[-2:]

len(word)           # length of string

 "The sum of 1 + 2 is {0}".format(1+2)

 # convert
 str(3.14)
int('100')
int('101', 2)   # 5
int('0b101', 0) # 5
int('0o70', 0)  # 56
int('0xFF', 0)  # 255

float('3.14')



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
