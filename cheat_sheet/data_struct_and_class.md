## C
```C
/* type define */
typedef int t_int;
type_int i;
typedef int * t_int_ptr;
t_int_ptr p = &i;

/* structure */
typedef struct {
    char name[20];
    char sex;
    int age;
} t_person;
t_person person = {"tom", 'M', 20};
person.age = 30;
t_person person1 = person;
t_person *p = &person;
char *name = p->name;

union person {      // size is 30 bytes
    char first[20];
    char second[30];    
};

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
// define struct
type user struct {
    name string
    score int
}
// struct tag
type user struct {
    name string `elem:"Name"`
    score int   `elem:"Score"`
}
reflect.TypeOf(user).Field(0).Tag.Get("elem")   // Name
// struct method
func (u user)show() {
    fmt.Println("name: %s, score: %d\n", u.name, u.score)
}
func (u *user)hit() {
    u.score++
}

// init
u := user{name: "hello", score: 1}
u.hit()
u.show()

var u *user = new(user)
u.name = "hello"
u.score = 1

// interface
type User interface {
    show()
    hit()
}
var u User
u = &user{name: "hello", score: 1}   // struct user have mrthod show() and hit()
u.hit()
u.show()

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
# define
class Dog:
    kind = 'canine'
    
    def __init__(self, name):
        self.name = name
        self.tricks = []
    
    def add_trick(self, trick):
        self.tricks.append(trick)

# use
d = Dog('Buddy')
d.kind
d.name
d.add_trick('roll over')

# extend
class DerivedClassName(Base1, Base2, Base3):


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
