# Dart Reduce Method and Empty List Handling

This example demonstrates a common error when using the `reduce` method in Dart with an empty list. The `reduce` method requires at least one element to function correctly; otherwise, it throws an error.

The `bug.dart` file shows the error, and `bugSolution.dart` provides a solution that gracefully handles empty lists.

## Solution
Check for the empty list condition before using `reduce`.  This avoids the runtime error and allows for cleaner, safer code.