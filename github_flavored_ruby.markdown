# GitHub Flavored Ruby

* Tom Preston-Werner [@mojombo](http://twitter.com/mojombo) **GitHub**

* Breast cancer shirts

## Relentless Modularization

* How do I decide what to modularize?
  * Everything should be modularized
* Make believe open source libraries

## Readme Driven Development

* Write your README first
* README.mkd -> SPEC.mkd

## RakeGem

* Rake-based gem builder
  * and deployer, docter, tester, and manifester
* No dependencies
* Hand-rolled gemspec and simple rake tasks
* Infinite customization
* [github.com/mojombo/rakegem](http://github.com/mojombo/rakegem)

## TomDoc

* TomDoc is more than a specification; it's a lifestyle
* RDoc 3.10 will support TomDoc syntax

## Semantic Versioning

* Dependency hell
  * Version lock
  * Version promiscuity
* Declare a public API (TomDoc)
* Major changes
  * Backwards incompatible
* Minor version
  * Backwards compatible
  * New functionality
  * Internal changes
  * May contain bug fixes
* Patch version
  * Backwards compatible
  * Bug fixes only
* The spermy operator in Bundler (`~>`)
  * Use the lowest number that is compatible
* [semver.org](http://semver.org)

