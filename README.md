swiftcheatsheet
===============

A quick cheat sheet and reference guide for Apple's Swift language. This guide intends to cover all the key features of Swift, including Strings, Arrays, Dictionaries and Flow Control.

Swift is a new programming language for developing iOS and OS X apps that was introduced by Apple in June 2014.

##Variables
```js
var myExplicitInt: Int = 1 // explicit type
var x = 1, y = 2, z = 3 // declare multiple integers
myExplicitInt = 2 // set to another integer value
```

##Constants
```js
let myInt = 1
myInt = 2 // compile-time error!
```

##Strings
```js
var myString = "a"
let myImmutableString = "c"
myString += "b" // ab
myString = myString + myImmutableString // abc
myImmutableString += "d" // compile-time error!

let count = 7
let message = "There are \(count) days in a week"
```
