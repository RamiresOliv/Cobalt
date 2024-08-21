# Bigger or equal

This operator is used to compare two values, very usefull in if's.
**Only numbers!**

## Usage:

```clj
(>= "abc" "abc") ; null
(>= 1 1) ; true
(>= 1 2) ; false
(>= 1 0) ; true
(>= "1" 0) ; true
(>= (str-len "Hello World!") 12) ; true (Is 12.)
(>= (str-len "Hello World!") 14) ; false (Is 12.)
```

## In code examples:

```clj
(print (>= 1 1)) ; yay!!
```
