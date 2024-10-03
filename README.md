# flutter-mocks
Sometimes, unit tests might depend on classes that fetch data from live web services or databases. This is inconvenient for a few reasons:

- Calling live services or databases slows down test execution.
- A passing test might start failing if a web service or database returns unexpected results. This is known as a "flaky test."
- It is difficult to test all possible success and failure scenarios by using a live web service or database.
  
Therefore, rather than relying on a live web service or database, you can "mock" these dependencies. Mocks allow emulating a live web service or database and return specific results depending on the situation.

Generally speaking, you can mock dependencies by creating an alternative implementation of a class. Write these alternative implementations by hand or make use of the Mockito package as a shortcut.

https://docs.flutter.dev/cookbook/testing/unit/mocking
