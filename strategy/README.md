# Strategy Pattern

## Synopsis
We have some behaviour that varies and want to abstract it from the client class.
The strategy pattern lets you encapsulate a family of algorithms into their own set of classes.
It also lets you change behaviour at runtime as long as the object you're composing with implements the correct behaviour interface.

**Design Principle**:
* *Favour composition over inheritance*

Compose behaviours into the client class (has-a relationship). Client implementations can choose which behaviour implementation they require.

## Files in example
* behaviour { interface }
    * the behaviour we want to abstract
* behaviour implementation 1 & 2 { concrete class }
    * the concrete implementations of the behaviour
* client { abstract class }
    * the client superclass composed of behaviour
* client implementation 1 & 2 { concrete class }
    * the concrete implementations of the client superclass

