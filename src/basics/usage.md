## Things to remember when using Cobalt

Here some examples of Cobalt usage:

```clj
; functions/forms usage:
;   (function [...])

; do it like this:
(for 10 index
    (print {index})
)

; don't do it like this:
(for 10 index
    (print "number: ")(print {index}) ; you must at least separate every function by spaces: "(print "number: ") (print {index})"
)

(if (== 1 1)
    (print "1 is equal as 1.")
)

; every function will ask for different argument types and etc..
```

when you decide to use markdown to highlight Cobalt code, you can mark as clojure language to do it, e.g.

````clj

```clj
; functions/forms usage:
;   (function [...])

; do it like this:
(for 10 index
    (print {index})
)

; don't do it like this:
(for 10 index
    (print "number: ")(print {index}) ; you must at least separate every function by spaces: "(print "number: ") (print {index})"
)

(if (== 1 1)
    (print "1 is equal as 1.")
)

; every function will ask for different argument types and etc..
```

````
