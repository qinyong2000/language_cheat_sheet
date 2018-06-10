## C
```C
```

## Objective-C
```Objective-C
```

## C++
```C++
```
## Java
```Java
```
## C#
```C#
```
## Scala
```Scala
``` 
## Go
```golang
// return error
func div(a, b float64)(float64, error) {
    if b == 0.0 {
        return 0.0, errors.New("divided by zero")
    }
    return a / b, nil
}
if r, err := div(1.0, 0.0); err != nil {
    fmt.Println("err", err)
}

// custom error
type MyError struct {
    code int
    msg string
}
// implement Error interface
func (err *MyError) Error() string {
    return fmt.Sprintf("err %s [code=%d]", err.msg, err.code)
}

func foo() error {
    return MyError{code:100, msg:"error"}
}

// panic handle
if err := foo(); err != nil {
    fmt.Println(err)
}

func foo()(err error) {
    defer func() {  // catch panic
        if r := recover(); r != nil {
            err = fmt.Errorf("Recovered from: %v", r)
        } 
    }()
    f()
    err = nil
    return
}

func f() {
    panic("Panic")  // throw panic
}
```

## Perl
```Perl
```
## Bash
```Bash
```
## Python
```Python
```
## PHP
```PHP
```
## Ruby
```Ruby
```
## JavaScript
```JavaScript
```
