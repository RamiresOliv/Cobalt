# Cobalt - language

A simple programming language, with a complex syntax made fully with Luau.

## Features:

- Free HTTP handling, _(post & get)_
- Math
- functions
- a friendly interface
- manual in-game
- open terminal
- Database _(comming soon)_
- Autorun _(comming soon)_
- much more!

---

### Roblox Experience:

https://www.roblox.com/games/97398140739060/Cobalt

You only need Roblox installed in your computer. After that, you can "run" cobalt :D
Only by entering in the experience and giving a like, helps me a lot!
This code is open-source but is protected by a [MIT license](./LICENSE).

```clojure
(var get (http-get "http://api.open-notify.org/iss-now.json"))
(var cords (listget {get} 3)) ; change this number to 1 at 3 if you are getting errors, the iss-now.json is sucks...
(print (format "current ISS, latitude: {1} and longitude: {2}" (listget {cords} 1) (listget {cords} 2)))
```
