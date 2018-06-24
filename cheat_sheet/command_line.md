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
import "os"

args := os.Args
arg0 := args[0]     // program name
arg1 := args[1]     // first paramater

os.Exit(0)          // return status code 

import "flag"

intOpt := flag.Int("i", 0, "i option")
boolOpt := flag.Bool("b", false, "b option")
strOpt := flag.String("s", "default", "s option")
flag.Parse()
fmt.Println(*intOpt)
fmt.Println(*boolOpt)
fmt.Println(*strOpt)
fmt.Println(flag.Args())
// cli -h
// cli -i 123 -b true -s abc a1 a2 a3
// 123
// true
// abc
// [a1, a2, a3]

err := exec.Command("ls").Run()
out, err := exec.Command("ls", "-la").Output()
err:= exec.Command("ls", "-la").Start()

cmd := exec.Command("sleep", "5s")
cmd.Start()
cmd.Wait()

// environment
os.Setenv("FOO", "1")
os.Getenv("FOO")
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
# argument
import getopt, sys
def main():
    try:
        opts, args = getopt.getopt(sys.argv[1:], "ho:v", ["help", "output="])
    except getopt.GetoptError as err:
        print str(err)
        usage()
        sys.exit(2)
    output = None
    verbose = false
    for o, a in opts:
        if o == "-v":
            verbose = True
        elif o in ("-h", "--help"):
            usage()
            sys.exit()
        elif o in ("-o", "--output"):
            output = a
        else:
            assert False, "unhandle option"
if __name__ == "__main__":
    main()

import argparse

parser = argparse.ArgumentParser()
parser.add_argument('-o', '--output')
parser.add_argument('-v', dest='verbose', action='store_true')
args = parser.parse_args()

import optparse

parser = optparse.OptionParser()
parser.add_option("-f", "--file", dest="filename",
                  help="write report to FILE", metavar="FILE")
parser.add_option("-q", "--quiet",
                  action="store_false", dest="verbose", default=True,
                  help="don't print status messages to stdout")

(options, args) = parser.parse_args()

# command
import commands

commands.getstatusoutput('ls')
commands.getoutput('ls')

# environment
import os

for k, v in os.environ.items():
    print("{key}: {value}".format(key=k, value=v))

os.environ['FOO'] = 'FOO'
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
