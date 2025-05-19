# Name
Daniel Bonkowsky

# Check Your Understanding
1. I would run my automated tests through Github actions. This way, all the
testing is completely automated. When I make a pull request, the tests are
automatically run, letting me know whether I need to fix anything before
merging. By keeping these tests in Github, it also makes sure that everyone is
running the same test suite, so any new tests are implemented universally.

2. I would not use an end-to-end test to check if a function is returning the 
correct output. End-to-end tests are meant to check if the application as a
whole works, and individual functions should be tested with unit tests.

3. Navigation mode analyzes the page right after it loads to give an overall
performance metric. Snapshot mode analyzes the page in whatever state it's
currently in, which is best used to identify accessibility issues.

4. You could switch from using JPEG/PNG images to instead use WebP or AVIF which 
provide better compression, meaning faster downloads/less data consumption. The 
`<html>` element doesn't have a `lang` attribute, which could cause errors if a 
user is using a screen reader set to a default language different than English. 
There's also no meta description, which may hurt the page's search engine
ranking and make the search results less clear for users.