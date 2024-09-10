## Cobalt Logic

Cobalt looks like a challenge to understand, but it's not. Believe me.

```clj
(print (str Hello World!)) ; output: Hello World!
```

_Later, back here and explain to yourself what the above code does._

#

## Understanding Cobalt logic:

So that the compiler understands the code and executes each thing in its proper place, we separate the commands in parentheses, so the compiler knows what to execute first and what is a function, what is string, numbers, etc...

e.g: `(<FUNCTION/FORM> <ARG1> <ARG2> ...)`
_Arguments are always separated by spaces, i.e._ using: `(print Hello World!)` it's not right!
Because "Hello" counts as a single argument, and "World!" counts as a single argument too, we talk more about strings and how use they in the [basics/context](context) page.

With this basic logic, we can do a lot of stuff, but remember, some others functions or commands has they own arguments or expected values, to check they you can visit the [references](../references/) section, where we will be talking about every command in Cobalt.
