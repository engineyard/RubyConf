# Your Tests are Lying to You

* Chris Parsons [@chrismdp](http://twitter.com/chrismdp)

## When tests lie

* [Integration Tests Scam](http://infoq.com/presentations/integration-tests-scam)
* "Well designed code is easy to test" -- Corey Haines
* Not everything has to be an ActiveRecord object
* [Mocks Aren't Stubs](martinfowler.com/articles/mocksArentStubs.html)


## Pros and Cons

1. Isolation
2. Flexibility
3. Setup
  1. Mockists have to change setup each time
4. Design
  1. Classisists don't get the design feedback
5. Speed
  1. Mockists are significantly faster

## Integration Tests

* When you have more isolation, you're giving up integration tests

## Acceptance Tests

* The customer still needs to know if the software does what they've requested

## The Key Questions

1. Am I being lied to?
2. Is my test code telling me something?
  1. Break up classes and behavior
  2. Find one code file where you hate the tests and see if the problem is
     the design
3. Which gang do I belong to? Do I understand the pros and cons?
