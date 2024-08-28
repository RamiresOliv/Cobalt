# let

`Let` function set's a key to a value.

The `let's` saves they values until the code stops to be compiled, this means, if a function is called in another file which makes a variable, that variable will be able to be called by any other script while the compiler is live.

## usages:

```clj
(let variable (str Hello world.)) ; string
(let variable no_spaces_is_string) ; string
(let variable true) ; boolean
(let variable (get otherVariable)) ; calls another variable setted
(let variable 123) ; number
(let variable [value1 value2 value3]) ; list

(print {variable}) ; result: list, because is the last set with the variable name.
```

## In code examples:

```clj
; Storing user inputs:
(let name (prompt (str What is your name?)))
(print (str Hello {name}, How are you?))
; -------------------------------------------------------------------------------------------
; Random number generator:
(let number (math-random 1 10))
(if (>= {number} 5)
    (print (str Good job.))
else
    (print (str Sorry, you lost.))
)
(print (str Is: {number}))

; Changing values
(let test 5)
(let test (* {test} 2))
(print {test}) ; result: "10"
```
