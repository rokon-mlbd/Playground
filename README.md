# Playground
This is generally where I do test and try codes for better understanding of what it means and how to hearness the Swift compiler potentials.

## Associated Types
One of the most twisted topics in Swift is definitely `associatedtype` . I am currently trying to literally break down this concept to a layman understanding and by so doing I could also understand it myself. 

### Definition of Associated Types
`associatedtype` is a protocol generic placeholder for an unknown `Concrete Type`  that requires concretization on adoption at the consumer side.  

### Problems solved by Associated Types
 - `associatedtype`  was introduced to solve the problem of rich and multi type abstraction which are not available in object-oriented subtyping.
- Designed to address the known naive `generic protocol` especially where complexity scales badly with more generic type introduction.

### Advantages of Associated Types
- `associatedtype`  come into play when subtyping alone cannot capture the rich type relationship between types. 
- They help specify the precise and exact type of an object with a protocol subtyping.
- They provide the relationship that you cannot fit into an object related type hierarchy.

- [Please see complete `associatedtype` article on medium](https://medium.com/@bobgodwinx/swift-associated-type-design-patterns-6c56c5b0a73a). <br />
- [Full example code is also available on Playground](https://github.com/bobgodwinx/Playground/blob/master/Associated%20Types.playground/Contents.swift)


