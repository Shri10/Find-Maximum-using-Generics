# Find Maximum Using Generics

This project is about finding the maximum of three variables using Generics in C#. 

## Branches:

1. **UC1:** This branch contains the code to find the maximum of three Integers. The code is tested using 3 test cases with the maximum number at the 1st, 2nd, and 3rd position. We use Integer Object and compareTo method to test the maximum number.

2. **UC2:** This branch extends the functionality to find the maximum of three Floats. The same testing approach is followed as in UC1.

3. **UC3:** This branch deals with finding the maximum of three Strings. For example, given the strings "Apple", "Peach", "Banana", it should return "Peach" as the maximum.

4. **Refactor1:** This branch refactors all the three functionalities into one generic method which can find the maximum of any data type that extends the Comparable interface. The generic method is then tested to ensure it functions correctly with Integer, Float, and String.

5. **Refactor2:** This branch further refactors the code to create a generic class which can take in three variables of a generic type. A parameterized constructor is written, and the `testMaximum` method is internally called, passing the three instance variables. The generic class is then tested to ensure it works as expected.

6. **UC4:** This branch extends the maximum method to take more than three parameters. It uses options and sorting to find the maximum.

7. **UC5:** This branch extends the maximum method to also print the maximum value to stdout using a generic method. A `printMax` generic method is written, which is internally called from `testMaximum`.

This project will help you understand the concept of Generics and its application in real-world programming. The use of Generics makes the code more type-safe, and reusable as the same code can be used with different data types.