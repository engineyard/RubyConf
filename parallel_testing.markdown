# Parallel Testing World

## Why Parallel Testing

* In most cases, tests can run faster
* Faster test -> Fast development cycle
  * In TDD, BDD development
* At Ruby, committers have to run `make test-all` before committing
* Slow test time also known as 'Break time'

## Benefits

* You can fix failures faster
* Faster test, faster development, faster deployment

## Multi-(thread|process)

* Ruby's Thread can't run multiple threads at once
* Multi-Process?

## test/unit parallelization

### How it works

* Master: process that is started first. Sends instruction to workers
* Worker: process started by Master process. This process runs tests
* Master starts workers and hands test files to them to process. Rinse and repeat
  * Uses IO.popen
* Windows is not supported by patch
* Some tests are not parallel, ie: network tests using same port

### Performance

* @mrkn measured and create performance graphs
* Without parallelization: 121.49 seconds
* With parallelization: 43.41 seconds
* 2.79x faster!

### How to Use

* Separate TestCase-s to multiple file
* Ruby 1.9.3 RC1 uses parallelization
* @sora_h
