# Unhandled Exception in Asynchronous Dart Code

This repository demonstrates a common error in asynchronous Dart code: failing to properly handle exceptions thrown in asynchronous operations. The `bug.dart` file shows the problematic code, while `bugSolution.dart` provides a corrected version.

**Problem:** The original code doesn't handle exceptions thrown by the asynchronous `fetchData` function in the `main` function. This can lead to unexpected program termination.

**Solution:**  The corrected version handles exceptions using a `try-catch` block in the `main` function, providing a more robust and user-friendly experience.