1. I would run my automated tests through Github actions. This way, all the
testing is completely automated. When I make a pull request, the tests are
automatically run, letting me know whether I need to fix anything before
merging. By keeping these tests in Github, it also makes sure that everyone is
running the same test suite, so any new tests are implemented universally.

2. I would not use an end-to-end test to check if a function is returning the 
correct output. End-to-end tests are meant to check if the application as a
whole works, and individual functions should be tested with unit tests.