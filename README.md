# sandbox-gdb

## prerequisites

```
$ codesign --entitlements gdb.xml -fs gdbc $(which gdb)
$ sudo pkill taskgated
```

## 1

### refs

* http://www.zombie-hunting-club.com/entry/2017/10/22/185656?amp=1

## 2

### refs

* http://www.zombie-hunting-club.com/entry/2017/10/11/220937
* https://stackoverflow.com/questions/10115540/gdb-split-view-with-code

### commands etc

* `list`
* `-tui`
* `c+x` -> `c+a`
* `c+x` -> `2`
