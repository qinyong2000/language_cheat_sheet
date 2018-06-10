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
ioutil.WriteFile("file.txt", b, )
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
