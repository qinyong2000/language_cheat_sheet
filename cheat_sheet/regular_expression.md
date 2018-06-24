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
import "regexp"
// match
r := regexp.MustCompile(`abc`)
r.MatchString("hello")      // false
r.MatchString("hello abc")  // true
// replace
s := "123456"
r := regexp.MustCompile(`1(.)3(.)5(.)`)
r.ReplaceAllString(s, "1($1)3($2)5($3)") // 1(2)3(4)5(6)
// split
s := "1, 2, 3"
r := regexp.MustCompile(`\s*,\s*`)
r.Split(str, -1)
// find
r := regexp.MustCompile(`^a`)
r.FindAllStringSubmatch("abc")   // a

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
import re
# match
regex = r'ab+'
text = "abbabbabaaabb"
pattern = re.compile(regx)
match = pattern.match(text)
match = re.match(regex, text)

# replace
s = "aaabbbccc"
s.replace("b", "B")         # aaaBBBccc
s.replace("b", "B", 1)      # aaaBbbccc
re.sub(r'[a-z]+', "0", "abc123")  # 0123

# find
text = "dog fox"
index = text.find("fox")
if index != -1:
    print "found at", index

match = re.search(r'[a-z]+', "012abc")
if match:
    print match.group()
    print match.start()
    print match.end()
    print match.span()

re.findall(r'[a-z]+', "012abc") # ['abc']

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
