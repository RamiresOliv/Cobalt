# string calls

This method is a way to get a value from a set but in a "static" way. This means, the compiler will change the value when called one time, not updating, this is why the usage of the [get](./get) is much more stable. Otherwise, isn't required to use the get for a static value which doesn't changes constantly.

## usage:

```clj
; Static meaning:
(let continuation World!))
(str Hello {continuation}) ; results in: "Hello World!"

; Other static exemple:
(let number (prompt (str Tell me a number:))))
(print (* {number} 2)); results in: "Hello World!"

; X invalid constant changes usage:
(let number 0)
(for 100
    (let number (+ number 1))
    (print {number})
)
; result: 1 x100

; V valid constant changes usage:
(let number 0)
(for 100
    (let number (+ (get number) 1))
    (print (get number))
)
; result: 1 to 100.
```
