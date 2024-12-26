# Dart Index Out of Bounds Exception

This repository demonstrates a common error in Dart: the `IndexOutOfRangeException`.  The `bug.dart` file contains code that tries to access an element of a list using an index that is greater than or equal to the length of the list.  The `bugSolution.dart` file shows how to prevent this error using proper index validation.

This exception occurs frequently when working with lists or arrays. It's crucial to ensure that array indices are always within the valid range (0 to length - 1).