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
// logging
import (
    "log"
    "os"
)
// global logger
log.SetFlags(log.Ldate | log.Ltime | log.Lshortfile)
log.SetPrefix("**** ")
log.Println("Hello logging")
// logger
logger := log.New(os.Stderr, "**** ", log.LstdFlags|log.Llongfile)
logger.Fatalf("Hey!! %s", "logging")

// dir
import "os"

err := os.MkDir("tmp", 0777)    // create dir
err := os.Remove("./tmp")       // delete dir
err := os.RemoveAll("./tmp")    
err := os.Rename("file1", "file2")  // rename
p, err := os.Getwd()            // current dir
os.Chdir("/etc")                // change dir
info, _ := os.Stat("/etc")
info.IsDir()                    // is a dir?

// get file list
files, _ := ioutil.ReadDir("./")    
for _, f := range files {
    fmt.Println(f.Name())
}

files, _ := filepath.Glob("/etc/*")

// get dir
filepath.Dir("/usr/bin/ruby")   // /usr/bin

// read file
fp, err := os.Open("file.txt")
if err != nil {
    panic(err)
}
data := make([]byte, 10)
count, err := fp.Read(data)
if err != nil {
    panic(err)
}
fmt.Println("Read %d bytes: %s\n", count, data)

// write file
file, err := os.Create("file.txt")
if err != nil {
    panic(err)
}
defer file.Close()
file.Write([]byte("test"))

// read file
data, err := ioutil.ReadFile("file.txt")
if err != nil {
    panic(err)
}
fmt.Println(string(data))

// write file
b := []byte{1, 2, 3}
ioutil.WriteFile("file.txt", b)

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
# logging
import logging
logging.debug('Debugging information')
logging.info('Informational message')
logging.warning('Warning:config file %s not found', 'server.conf')
logging.error('Error occurred')
logging.critical('Critical error -- shutting down')

# dir
import os

os.path.exists('test.txt')
os.path.isfile('./test')
os.path.isdir('./test')

os.mkdir('./test')

os.remove('test1.txt')
os.rmdir('./test')
os.rename('test.txt', 'test1.txt')

os.path.split('path/to/test.txt')       # ('path/to', 'test.txt')
os.path.join('path/to', 'test.txt')     # path/to/test.txt
os.path.basename('path/to/test.txt')    # test.txt

for f in glob.glob('*.log'):
    os.remove(f)

import shutil

shutil.copyfile("test1.txt", "test2.txt")
shutil.copy("test1.txt", "test2.txt")
shutil.copy2("test1.txt", "test2.txt")  # copy with file meta
shutil.copytree("./test1", "./test2")
shutil.rmtree("./test")
shutil.move("./test1", "..")

# file read
f = open('test.txt', 'r')
for line in f:
    print line
f.close()

with open('test.txt', 'r') as f:
    for line in f:
        print line
# file write
f = open('test.txt', 'w')
f.write('xxx')
f.close()

f = open('test.txt', 'a')

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
