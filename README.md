# Java Sealed Class Example
This repo groups examples of my other Java apps that implent _sealed class_, a [new feature introduced in Java 17](https://openjdk.java.net/jeps/409).

A _sealed class_ enables creating closed inheritance. In summary, it means that the superclass has a limited set of known subclasses. Venkat Subramaniam gives a [good introduction on sealed classes](https://www.youtube.com/watch?v=Xkh5sa3vjTE) if you are interested in knowing more about it.

## Examples

- A [factory method branch](https://github.com/gabrielcostasilva/dp-factory-method/tree/sealed-class-example) shows the use of `sealed` and `final` combination.

- A [chain of responsibility branch](https://github.com/gabrielcostasilva/dp-chain-responsibility/tree/sealed-class-example) exemplifies the use of the `non-sealed` keyword. 

