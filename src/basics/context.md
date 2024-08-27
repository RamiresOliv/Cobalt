Simple contexts to make the language:

```clj
; Base stuff of a language, right?

; Booleans
true = true
false = false

; String operators
nothing = "" ; (callable by {nothing} or (nothing))
space = " " ; (callable by {space} or (space))
inf = math.inf ; (callable by {inf} or (inf))

; types:
"abc" ; string
123 or "123" ; number
"a123" ; string
true or false ; boolean
nil ; nil value.
[a b c d e] ; list
```
