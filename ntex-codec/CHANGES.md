# Changes

## [0.1.2] - 2020-04-17

* Do not swallow unprocessed data on read errors

## [0.1.1] - 2020-04-07

* Optimize io operations

* Fix framed close method

## [0.1.0] - 2020-03-31

* Fork crate to ntex namespace

* Use `.advance()` intead of `.split_to()`

* Add Unpin constraint and remove unneeded unsafe

## [0.2.0] - 2019-12-10

* Use specific futures dependencies

## [0.2.0-alpha.4]

* Fix buffer remaining capacity calcualtion

## [0.2.0-alpha.3]

* Use tokio 0.2

* Fix low/high watermark for write/read buffers

## [0.2.0-alpha.2]

* Migrated to `std::future`

## [0.1.2] - 2019-03-27

* Added `Framed::map_io()` method.

## [0.1.1] - 2019-03-06

* Added `FramedParts::with_read_buffer()` method.

## [0.1.0] - 2018-12-09

* Move codec to separate crate
