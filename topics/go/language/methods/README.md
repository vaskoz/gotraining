## Methods

Methods are functions that are declared with a receiver which binds the method to a type. Methods and can be used to operate on values or pointers of that type.

## Notes

* Methods are functions that declare a receiver variable.
* Receivers bind a method to a type and can use value or pointer semantics.
* Methods are valid when it is practical or reasonable for a piece of data to expose a capability.

## Links

https://golang.org/doc/effective_go.html#methods  
http://www.goinggo.net/2014/05/methods-interfaces-and-embedded-types.html

## Code Review

[Declare and receiver behavior](example1/example1.go) ([Go Playground](https://play.golang.org/p/nxAwTRWk4N))  
[Value and Pointer semantics](example5/example5.go) ([Go Playground](https://play.golang.org/p/vyWTRDs9bi))  
[Named typed methods](example2/example2.go) ([Go Playground](https://play.golang.org/p/9WeR1rShIa))  
[Function/Method variables](example3/example3.go) ([Go Playground](https://play.golang.org/p/Ewhk87BiWA))  
[Function Types](example4/example4.go) ([Go Playground](https://play.golang.org/p/EZQPrC9qsx))

## Exercises

### Exercise 1

Declare a struct that represents a baseball player. Include name, atBats and hits. Declare a method that calculates a players batting average. The formula is Hits / AtBats. Declare a slice of this type and initialize the slice with several players. Iterate over the slice displaying the players name and batting average.

[Template](exercises/template1/template1.go) ([Go Playground](https://play.golang.org/p/IG5uqVRTrc)) | 
[Answer](exercises/exercise1/exercise1.go) ([Go Playground](https://play.golang.org/p/adVfRrzmw2))
___
All material is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/LICENSE-2.0).
