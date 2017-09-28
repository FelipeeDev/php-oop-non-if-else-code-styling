# PHP OOP Non if-else code styling

### TABLE OF CONTENT
- [Introduction](#introduction)
- [Principles](#principles)
    - [Principle 1: No conditions in OOP](#principle-1-no-conditions-in-oop)
    - [Principle 2: At least PHP 7.0](#principle-2-at-least-php-70)
    - [Principle 3: There are tree kinds of return](#principles-3-there-are-there-kinds-of-return)
    - [Principle 4: Parameters should have type declarations](#principles-4-parameters-should-have-type-declarations)
- [Level 0: stop using 'elseif' and 'switch' statements](#level-0-stop-using-elseif-and-switch-statments)
- [Level 1: stop using 'else' word](#level-1-stop-using-else-word)
- [Level 2: stop using 'if' word](#laravel-2-stop-using-if-word)
- [Level 3: stop using if shorthand](#level-3-stop-using-if-shorthand)
- [Level 4: Do not use any type of conditions!](#level-4-do-not-use-any-type-of-conditions)

## Introduction

This document contains examples of how to became a real PHP OOP ninja and stops to using conditional statements in your code. First read about principles. Then - when you are ready - proceed the secret techniques of unconditionally programming.

## Principles

There are few principles that you have to note before you begin your adventure with new kind of PHP code writing. So let's begin!

### Principle 1: No conditions in OOP

*There should NOT be any conditions in clear Object-Oriented Programing.*

The first and the most important principle. Each object should contains methods that are responsible for acting and not for making decisions. So we can say in the other words: The method does not depend on what it receives - it always tries to do what it is responsible for - regardless of the input parameter.

So we can say that object-oriented programming is uncompromising and:

1. It's clear!
2. It's testable!!
3. It's has readable code and programming interface!!!

### Principle 2: At least PHP 7.0

[PHP 7.0](http://php.net/manual/en/migration70.new-features.php) have most of, and [PHP 7.1](http://php.net/manual/en/migration71.new-features.php) have all solutions needed (to forget about the `if` statements and other conditional statements) such as:
- type hints and scalar type declaration
- return type declaration (and nullable types)
- null coalescing operator
- Throwable interface
- multi catch exception handling 
 
### Principle 3: There are tree kinds of return

We can distinguish three kinds of return values:
- "The type of desire" - this is the type that is declared as a return type of the method. In some circumstances it can became a void type of `null`.
- Void values - which mostly represents command bus methods.
- Exception - all the variety of the exceptions and errors (everything that implements `Throwable` interface)

### Principle 4: Parameters should have type declarations

All the method's parameter should have type declaration. And that's all for now. You will see later why type hints are so important.

## Level 0: stop using 'elseif' and 'switch' statements

## Level 1: stop using 'else' word

## Level 2: stop using 'if' word

## Level 3: stop using if shorthand

## Level 4: Do not use any type of conditions!
