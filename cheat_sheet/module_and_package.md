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
package foo

var C int         // export
func Print() {    // export
    
}

import "foo"
foo.C
foo.Print()

import f "foo"    // alias
f.C
f.Print()

import . "foo"     
C 
Print()
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
# module module.py
def foo(n):
    print n

# use module
import module
module.foo(1)

from module import foo
foo(1)

from module import *
foo(1)

from module import foo as fooA
fooA(1)

# run module code
if __name__ == "__main__":
    foo(1)

#package
sound/                          Top-level package
      __init__.py               Initialize the sound package
      formats/                  Subpackage for file format conversions
              __init__.py
              aiffwrite.py
              auwrite.py
              ...
      effects/                  Subpackage for sound effects
              __init__.py
              echo.py
              surround.py
              ...

import sound.effects.echo
from sound.effects import echo
from sound.effects import *
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
