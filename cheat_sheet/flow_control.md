## C
```C
// if-else
if (a > b) {
  ...
} else {
  ...
}
// for
for (int i = 0; i < 10; i++) {
    if (a > 5) break;
    if (a <= 5) continue;
}
// while
while (a > 1) {
  ...
}
do {
  ...
} while (a > 1);
// switch
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
// if-else
a := 1
if a > 10 {
  fmt.Println("Greate Than 10")
} else if a > 5 {
  fmt.Println("Greate Than 5")
} else {
  fmt.Println("Greate Than 1")
}

if a := 1; a > 10 {
  fmt.Println("Greate Than 10")
}

// switch
switch color {
  case "red":
    fmt.Println("stop")
  case "yellow":
    fmt.Println("caution")
  case "green", "blue":
    fmt.Println("go")
  default:
}

a := 1
switch {
  case a > 10:
    fmt.Println("Greate Than 10")
  default:
    fmt.Println("Bad")
}

// for
i := 0
for i < 10 {
  fmt.Println(i)
  if i == 3 {
    continue
  } else if i == 8 {
    break
  }
  i++
}
s:= []int{1, 2, 3}
for i, v := range s {
  fmt.Println(i, v)
}
for _, v := range s {
  fmt.Println(v)
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
# if
if x < 0:
elif x == 0:
    print "Zero"
else:
    print "more"

# for
words = ['cat', 'dog', 'bird']
for w in words:
    print w, len(w)

for i in range(10):
    print i

# break, continue
for n in range(2, 10):
    for x in range(2, n):
        if n%x == 0:
            break
        else:
            continue
    else:               # for ... else, x > n
        print n, 'is a prime number'

# while
while b < 10:
    print b

# pass
while True:
    pass

# there is no switch statment in Python!
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
