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
// type
var a int           // int int8 int16 int32 int64
var a uint          // uint uint8 uint16 uint32 uint64 uintptr
var a float32       // float32 float64
var a complex64     // complex64 complex128
var a byte          // as int8
var a rune          // as int32, unicode
var a string        // default: ""
var a bool          // default: false

// defination
var a int
var a int, b int
var a, b int
var (
    a int
    b int
)

// initialize
var a, b int = 1, 2
var a, b = 1, 2
a, b := 1, 2    // in function

// const
const Pi = 3.14
const (
    A = 1
    B           // value: 1
    C = 2
)
// enum
const (
    a = iota    // 0
    b           // 1
    c           // 2
)

// pointer
a := 1
var p *int = &a
p = nil         // null pointer

// literal
1
070
0x10
1.0
true
false
"foo"
`bar`   // raw string
nil

// scope
var Pi int      // export package
var pi int      // not export

// get type
import "reflect"
fmt.Println(reflect.Typeof("a"))    // string

// type cast
x := uint8(10)
var x interface{} = 1
y := x.(float64)
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
a = 1
b = 0.0
s = 'abc'
a, b = 0, 1
a = None
a = True            # True, False
b = a and False     # or, and, not

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
