## C
```C
TODO
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
// goroutine
go foo(a, b)

// channel
var ch chan int
ch = make(chan int)
ch = make(chan int, 100) // buffer length 100

ch <- 1                 // write 1 to channel
v:= <- ch               // read from channel, read blocking
v, ok := <- ch          // ok == true if read success
for v := range ch {     // read util close
}
close(ch)

// select
select {
    case v <- ch1:
        fmt.Println(v)
    case v <- ch2:
        fmt.Println(v)
    default:
        fmt.Println("nothing")    
}

// gorouting + channel
func foo(ch chan int) {
    for _, v := range []int{1, 2, 3} {
        fmt.Println(v)
        ch <- v
    }
    close(v)
}

ch := make(chan int)
go foo(ch)
for i := range ch {
    fmt.Println(i*10)
}

// result
1
10
2
20
3
30
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
