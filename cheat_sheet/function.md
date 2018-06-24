## C
```C
double add(double x, double y) {
    return x + y;
}

void print() {
    ...
}
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
// function
func print() {
    fmt.Println("Hello World")
}

func print(msg string) {
    fmt.Println(msg)
}

func getMessage(name string) string {
    return "hello " + name
}

// name return value
func getMessage(name string)(msg string) {
    msg = "hello " + name
    return
}

// return 2 values
func getMessage(name string)(string, string) {
    return name, "hello " + name
}

// closure
f := func(a int, b int) (int, int) {
    return b, a
}
fmt.Println(f(1, 2))

func(msg string) {
    fmt.Println(msg)
}("hello")


func foo(opts ...interface{}) {
    for _, opt := range opts {
        fmt.Println(opt)
    }
}

// higher order function
func sum(f func(int) int, n, m int) int {
    a := 0
    for ; n <= m; n++ {
        a += f(n)
    }
    return a
}
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
def foo(n):
    print n

foo(1)

def add(x, y):
    return x + y

def add(x, y): return x + y

add(1, 1)
add(x=1, y=1)

def ask(prompt, retries=4):

ask(prompt="please")

def write(*args, **keywords):
    for arg in args:
        print arg
    for kw in keywords.keys():
        print kw, ":", kwywords[kw]

write("1", "2", a="1", b="2")

# lambda
def make_increment(n):
    return lambda x,: x + n

f = make_increment(4)
f(0)
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
