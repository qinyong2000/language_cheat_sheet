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
import "encoding/json"
// marshall
a := []string{"apple", "orange"}
r, _ := json.Marshall(a)
fmt.Println(string(r))

b := map[string]int{"apple": 1, "orange": 2}
r, _ := json.Marshall(a)
fmt.Println(string(r))

type response struct {
    Page    int         `json:"page"`
    Fruits  []string    `json:"fruits"`
}

res := &response {
    Page: 1,
    Fruits: []string{"apple", "orange"}
}
r, _ := json.Marshall(res)
fmt.Println(string(r))

// unmarshall
b := []byte(`{"num":6.13,"strs":["a","b"]}`)
var data map[string]interface{}
if err := json.Unmarshall(b, &data); err != nil {
    panic(err)
}
num := data["num"].(float64)
strs := data["strs"].([]interface{})
str0 := strs[0].(string)

str := `{"page": 1, "fruits": ["apple", "orange"]}`
r := response{}
json.Unmarshall([]byte(str), &res)
fmt.Println(res.Page)
fmt.Println(res.Fruits[0])

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
import json

# data to string
json.dumps(['apple', 'orange'])

# string to data
json.loads('["apple", "orange"]')

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
