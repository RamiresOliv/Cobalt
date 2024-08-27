# Only smaller

This operator is used to compare two values, very usefull in if's.
**Only numbers!**

## Usage:

```clj
(< "abc" "abc") ; nil
(< 2 1) ; false
(< 1 2) ; true
(< 1 0) ; false
(< 0 0) ; false
(< "1" 0) ; false
(< (str-len "Hello World!") 12) ; false (Is 12.)
(< (str-len "Hello World!") 13) ; true (Is 12.)
```

## In code examples:

```clj
(print (< 1 0)) ; yay!!
```
