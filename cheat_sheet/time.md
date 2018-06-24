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
import "time"

now := time.Now()
then := time.Date(2018, 1, 1, 0, 0, 0, 0, time.UTC)
then.Year()
then.Month()
then.Day()
then.Hour()
then.Minute()
then.Second()
then.Nanosecond()
then.Location()
then.Weekday()

then.Before(now)
then.After(now)
then.Equal(now)
diff = now.Sub(then)
then.Add(-diff)

now := time.Now()
secs := now.Unix()
nanos := now.UnixNano()

time.Unix(secs, 0)
time.Unix(0, nanos)

// formatting
t := time.Now()
t.Format(time.RFC3339)  // 2018-06-23T13:30:00-09:00

// parsing
t, e := time.Parse(time.RFC3339, "2018-06-23T13:30:00-09:00")

// timer
import "time"

timer := time.NewTimer(2 * time.Second)
<-timer.C

timer2 := time.NewTimer(time.Second)
go func() {
    <-time2.C
}()
stop2 := timer2.Stop()
if stop2 {
    fmt.Println("Timer 2 stopped")
}

// 
import "time"
ticker := time.NewTicker(500 * time.Millisecond)
go func() {
    for t := range ticker.C {
        fmt.Println("Tick at", t)
    }
}()

time.Sleep(1000 * time.Millisecond)
ticker.Stop()
fmt.Println("Ticker stopped")

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
import datetime

today = datetime.date.today()
now = datetime.datetime.now()
now.year
now.month
now.day
now.hour
now.minute
now.second
now.microsecond

# calculate
today = datetime.date.today()
day_after_tomorrow = datetime.timedelta(days=2)

# formatting
today = datetime.date.today()
print '{0:%Y/%d/%d}'.format(today)

now = datetime.datetime.now()
print now.strftime('%Y/%m/%d %H:%M:%S')

# parsing
str = '2018-06-24 16:00:00'
now = datetime.datetime.strptime(str, '%Y-%m-%d %H:%M:%S')

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
