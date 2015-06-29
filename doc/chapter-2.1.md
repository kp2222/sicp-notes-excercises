# Chapter 2.1

## Summary
Complex data usually contains multiple parts which usually has to dealt within in the program as single conceptual entity. Data abstraction helps us to get an abstract view of the data without needing to worry about the how the data is actually constructed.

## Example - Representing rational numbers

Rational numbers can be represented as pair of numerator and a denominator. Just with the help of one constructor and two selector functions we can pretty much completely abstract away the fact that the rational numbers are constructed using pairs. Later in the chapter we talk about an alternative implementation using nested functions and closures this change only affects the helper function as the rest of the program only uses those to work with ration number. 