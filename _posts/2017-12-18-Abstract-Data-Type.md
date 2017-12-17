---
layout: post
title: Understanding Abstract Data Types(ADT)
---


Abstract Data Type[(ADT)](https://en.wikipedia.org/wiki/Abstract_data_type) refers to the basic mathematical concept that defines the data type. So, what is data type?
[Wikipedia](https://en.wikipedia.org/wiki/Data_type) defination for data type is, "A data type or simply type is a classification of data which tells the compiler or interpreter how the programmer intends to use the data." Two things appears while defining data type, collection of values and a set of operations on those values. Actual hardware or software implementation of the data types are completely dependent to the platform where it is implemented.(Different programming languages have their own data types and their operations)

So, while defining ADT, we don't really care about the space or time efficiency. Similar to the data types. In facts, data types are practical things whereas ADT are just the theoretical concepts used in the design and analysis of the algorithms, data structures like Stack, Queue, Graph, linked lists etc.

Data types are specialized whereas ADTs are generalized and theoretical. The main purpose for ADT is to encapsulate the implementation details(may be hardware or software) so that programmer only need to know about the available instructions and method to use them.

Lets consider the data type Integer. It contains all the counting numbers(positive numbers like 1, 2, 3, 4...), their additive inverses(negative numbers like -1, -2, -3,...) as well as zero. The operations among the integer may be addition, subtraction, multiplication etc. So we can call integer as an ADT.

Similarly, there can be a [rational numbers](https://en.wikipedia.org/wiki/Rational_number)(numbers that can be expressed as quotient of two integers). So, there may be certain operations among rational numbers like in integers. The values and their operations in integers are different that that of rational numbers. This can also be considered as an ADT.
