# Unhandled Exceptions in Asynchronous Dart Code

This repository demonstrates a common error in Dart when dealing with asynchronous operations and network requests: the lack of proper exception handling.

The `bug.dart` file showcases code that fetches data from an API. It includes a `try-catch` block but doesn't comprehensively handle potential exceptions, such as network errors or JSON decoding failures.

The `bugSolution.dart` file provides a corrected version that handles exceptions more robustly, ensuring better error reporting and program stability.  It offers more specific error handling based on the type of exception.

This example is crucial for understanding how to create more resilient and reliable Dart applications.