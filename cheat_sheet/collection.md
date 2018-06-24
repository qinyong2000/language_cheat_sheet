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

// define
var m map[string]int
// init
m := map[string]int {
    "a": 1,
    "b": 2,     // need comma!
}
// create
m := make(map[string]int)
// get
v = m["a"]    // 1
v = m["c"]    // 0 if not exists
v, ok := m["c"] // ok == true if exists
len(m)          // 2

// replace
m["a"] = 2 
// remove
delete(m, "a")  // delete a entry

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
# list
list = []       # empty list
list = [1, 2, 3, 4]
list[0]
list[-1]        # last item
list[1:]        # slice [2, 3]
list[-2:]       # slice [3, 4]
list[:]         # slice [1, 2, 3, 4]
list[2:4] = [0, 0] # [1, 0, 0, 4]
list[2:4] = []  # [1, 4]
list[:] = []    # []

list + [5, 6]   # [1, 2, 3, 4, 5, 6]

list = [i*2 for i in range(10) if i > 0]

# tuple
t = ()      # empty tuple
t = (1, 2, "a")
t = 1, 2
a, b = t    # a = 1, b = 2

# set
s = set()   # empty set
s = set(['a', 'b', 'c', 'a'])   # a, b, c
s = set('abcda')                #a, b, c, d
a = set('abracadabra')
b = set('alacazam')
a - b           # set(['r', 'd', 'b'])
a | b           # set(['a', 'c', 'r', 'd', 'b', 'm', 'z', 'l'])
a & b           # set(['a', 'c'])
a ^ b           # set(['r', 'd', 'b', 'm', 'z', 'l'])

a = {x for x in 'abracadabra' if x not in 'abc'}

# dictionary
tel = {}          # empty dict
tel = {'jack': 4098, 'sape': 4139}

dict([('sape', 4139), ('guido', 4127), ('jack', 4098)])
dict(sape=4139, guido=4127, jack=4098)
dict(zip(['one', 'two', 'three'], [1, 2, 3]))
a = {x: x**2 for x in (2, 4, 6)}

# method
a = [66.25, 333, 333, 1, 1234.5]
a.count(333)            # 2
a.insert(2, -1)         # [66.25, 333, -1, 333, 1, 1234.5]
a.index(333)            # 1
a.remove(333)           # [66.25, -1, 333, 1, 1234.5]
a.reverse()             # [1234.5, 1, 333, -1, 66.25]
a.sort()                # [-1, 1, 66.25, 333, 1234.5]
a.pop()                 # 1234.5
len(a)                  # 5

# loop
for i, v in enumerate(['tic', 'tac', 'toe']):
    print i, v

questions = ['name', 'quest', 'favorite color']
answers = ['lancelot', 'the holy grail', 'blue']
for q, a in zip(questions, answers):
    print 'What is your {0}?  It is {1}.'.format(q, a)

knights = {'gallahad': 'the pure', 'robin': 'the brave'}
for k, v in knights.items():
    print k, v

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
