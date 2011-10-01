# High Performance Ruby: Evented vs. Threaded

Dr. Nic Williams [@drnic](http://twitter.com/drnic) **Engine Yard**

## Evented

* Moves I/O around
* Evented performance determined by I/O loop

## Threads

* For doing work

## Concurrency

* process concurrency
* threaded concurrency
  * 1 req = 1 thread = 2 kb
* evented concurrency
* You need threads and evented
* [github.com/evanphx/puma](http://github.com/evanphx/puma)
