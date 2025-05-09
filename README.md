# bubble-sort-assignment


Bubble Sort for Python Lists and Linked Lists

 Project Overview
This project implements a Bubble Sort algorithm that operates seamlessly on both built-in Python lists and a custom LinkedList class. It features comprehensive unit tests and GitHub Actions for continuous integration and testing.

 Why use __iter__?
The __iter__ method is implemented in the LinkedList class to enable iteration using for loops and to easily convert the linked list to a standard Python list with list(). This greatly simplifies sorting and test validations.

 Error vs. Failure in Unit Testing

Error: An issue that prevents a test from executing, such as a syntax mistake or calling a non-existent method.
Example: AttributeError when a method is not defined.

Failure: The test runs, but the actual output doesn't match the expected result.
Example: Bubble sort returns [3, 2, 1] instead of [1, 2, 3].

Use of AI
AI tools were used to support development, especially in designing test cases, handling edge conditions, and refining the iteration logic in the custom LinkedList.

 Unit Test Coverage

Supports standard Python lists

Supports custom linked lists

Correctly handles edge cases:

Empty lists

Single-element lists

Lists with negative values
