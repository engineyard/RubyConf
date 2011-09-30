# Just Say No To :nodoc: and Document Your Code!

* Loren Segal [@lsegal](http://twitter.com/lsegal) [gnuu.org](http://gnuu.org)
  [yardoc.org](http://yardoc.org)

## Bad Documentation

* Documentation has "documentation smells"
  * Complicated return values
* :nodoc: isn't all bad; it's just heavily *abused*
  * You should decide what you want to hide when you generate output
    * You don't want to forcibly hide things
  * Ambiguity sucks

## Good Documentation

* Describe the behavior
  * Avoid first-person nouns
  * First sentence should summarize the method/class
  * Leave out implementation details unless they affect usage
* Examples! (@example)
* Mention any usage caveats (through @note)
* References (classes, methods, URLs, @see)
* List acceptable parameter return types

## Types

* Ruby is a strongly-typed language so TYPES MATTER!
* Parameter names don't tell full story
* A "type" is not *only* a class
  * Duck-types are types

## Tools

What are they good for?

* Tools can remove duplication
  * YARD RSpec plugin, YARD Cucumber plugin
* Tools can audit code

## Next Level API Design

* Document Driven Development
  * Readme Driven Development (subset of DDD)
  * DDD is about planning ahead
  * DDD is NOT "write all docs first"
  * DDD is "write, validate"
  * Important thing is that it's part of the development cycle
* Listen to what the documentation is telling you
  * We need a new abstraction

**Document Now.**

