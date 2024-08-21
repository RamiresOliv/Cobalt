Rubber looks like a challenge to understand, but it's not. Believe me.

`(print (str Hello World!))`

_Later, back here and explain to yourself what the above code does._

#

## Understanding Rubber logic:

So that the compiler understands the code and executes each thing in its proper place, we separate the commands in parentheses, so the compiler knows what to execute first and what is a command and string.

Ex: `(<COMMAND> <ARG1> <ARG2> ...)`
_Arguments are always separated by spaces, i.e._ using: `(print Hello World!)` it's not right!
Because "Hello" counts as a single argument, and "World!" counts as a single argument too! So, in this cases we use `(str ...)` which makes our lifes better, every argument inside the command will be translated to a single argument. So now, using: `(print (str Hello World!))` it's right!!
Because the function `(str ...)` joins all the arguments in only one.

With this basic logic, we can do a lot of stuff, but rememmber, some others functions or commands has they own arguments or expected values, to check they you can visit the [references](../references/) section, where we will be talking about every command in Rubber.
