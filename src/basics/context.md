# context of the language

Working with primitive datas in Cobalt.

In this page we will cover all the primitives datas. (about strings, below we have a full guide of how use they.)

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

## Strings, understanding more in depth

Using string function:

```clj
; understanding why/how/where use (str)

; strings can be formed and identified by three ways,
Hello.                  ; without any '"', this means a string.
"Hello."                ; single word string, this also means a string.
(str "Hello world!")    ; phrases into string, str function usage.

; Here some exemples and outputs:

(print Hello)        ; output: Hello
(print "Hello")        ; output: Hello
(print Hello "World!") ; output: Hello ; yes. "World!" being also a string it became a second argument, you will understand better this in logic page.
(print "Hello World!") ; output Hello World! ; correct usage of quotes.
(print (str Hello World!)) ; output: Hello World!
(print (str "Hello World!")) ; output: Hello World!

; Others str functions also works with the same logic of str and any of the mentioned types of strings.

(print (str-len Hello)) ; output 5
(print (str-len a)) ; output 1
(print (str-upper Hello World!)) ; output HELLO
(print (str-lower "Hello World!")) ; output hello world!
(print (str-lower (str Hello World!))) ; output hello world!
(print (str-upper (str "Hello World!"))) ; output HELLO WORLD!

; Conclusion is:
; Sometimes you use (str), sometimes you use "quotes", sometimes you use nothing. You lead the way.
```
