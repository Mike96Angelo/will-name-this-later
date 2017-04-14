# Scopes
Scopes are contained in blocks

```
<name> <expression> {
    // this is a block
}
```
example:
```
// if
if x == 1 {
    // do something
} else {
    // do something
}

// while
while <expression> {
    // do something
}

// do while
do {
    // do something
} while <expression>

// each
each <enum> as <key> <value> {

}

// for ; ;
for <init>; <condition>; <iterator> {
    // do something
}

// for range
for <range> {
    // do something
}

// function
func <name> : <return-Type> (
    <arg-name>: <Type> [= <default>],
    <arg-name>: <Type> [= <default>]
    ...
) {
    // do something
}

// class
class <name> {

}

// file
// each file has its own scope
