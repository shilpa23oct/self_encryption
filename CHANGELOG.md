# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [0.23.0](https://github.com/maidsafe/self_encryption/compare/v0.22.0...v0.23.0) (2021-04-13)


### ⚠ BREAKING CHANGES

* **test/lib.rs:** Last commit changed the argument types of the SE API

### Bug Fixes

* **tests/lib.rs:** Make different data size for 32 and 64 bit binaries ([c6e5ca1](https://github.com/maidsafe/self_encryption/commit/c6e5ca121f577b824539cb7cc8e6e84f1ea5e7ed))


* **test/lib.rs:** Add more crossplatform tests ([136be7f](https://github.com/maidsafe/self_encryption/commit/136be7fd58b7a23c4522244938492c44c7b27b25))

## [0.22.0](https://github.com/maidsafe/self_encryption/compare/v0.21.0...v0.22.0) (2021-04-05)


### ⚠ BREAKING CHANGES

* **self_encryptor.rs:** Remove truncate api from self encryptor

### Features

* **self_encryptor.rs:** Remove truncate api from self encryptor ([77b2f57](https://github.com/maidsafe/self_encryption/commit/77b2f57331624396cf21c484f477c5101d4ea207))
* **self_encryptor.rs:** Store chunks on write ([bed44c4](https://github.com/maidsafe/self_encryption/commit/bed44c446bfb364e48c9a17a70d6fb5399723685))


### Bug Fixes

* **Cargo.toml:** Remove rustc-serialize dependency ([a9baf6b](https://github.com/maidsafe/self_encryption/commit/a9baf6bb9bab44ce67530610dc6f9a5eacd27831))
* **self_encryptor.rs:** Fix edge case of writing ([f212e88](https://github.com/maidsafe/self_encryption/commit/f212e8828cdfd3c519a811bf4c6a9af5e3ccd037))
* **self_encryptor.rs:** Fix edge cases in truncate logic ([de3ea50](https://github.com/maidsafe/self_encryption/commit/de3ea50d5f8131c557c0bfe4ec3cd92c11989b5a))
* **self_encryptor.rs:** Requested Changes from the review ([993b524](https://github.com/maidsafe/self_encryption/commit/993b524e0d8c01d537ef9960e5e711b612653e7d))

## [0.21.0](https://github.com/maidsafe/self_encryption/compare/v0.20.2...v0.21.0) (2021-03-11)


### ⚠ BREAKING CHANGES

* **tokio:** new Tokio runtime version is not backward compatible with tokio versions < 1.

* **tokio:** upgrading to v1.3.0 ([640593b](https://github.com/maidsafe/self_encryption/commit/640593b1fbbe3d8f67c2ae730584ddbf6060703c))

### [0.20.2](https://github.com/maidsafe/self_encryption/compare/v0.20.1...v0.20.2) (2021-03-03)

### [0.20.1](https://github.com/maidsafe/self_encryption/compare/v0.20.0...v0.20.1) (2021-02-25)

## [0.20.0](https://github.com/maidsafe/self_encryption/compare/v0.19.11...v0.20.0) (2021-02-22)


### ⚠ BREAKING CHANGES

* **self_encryptor.rs:** Previous commit (c6aafe6) introduced a breaking change due to introduction of new delete trait.

### Features

* delete for Self-Encryptor ([7480376](https://github.com/maidsafe/self_encryption/commit/74803764955e3fc46771012ab81f2fee3ea59668))
* **storage:** delete trait for SEStorage ([056c4b7](https://github.com/maidsafe/self_encryption/commit/056c4b7d4cd63dc3d32a7de46338099de817915a))


* **self_encryptor.rs:** Use Err inplace of panic! and expect ([a4cae07](https://github.com/maidsafe/self_encryption/commit/a4cae07a1ff530c987513e5bba937c31e5c64d55))

### [0.19.11](https://github.com/maidsafe/self_encryption/compare/v0.19.10...v0.19.11) (2021-02-15)

### [0.19.10](https://github.com/maidsafe/self_encryption/compare/v0.19.9...v0.19.10) (2021-02-10)

### [0.19.9](https://github.com/maidsafe/self_encryption/compare/v0.19.8...v0.19.9) (2021-02-10)

### [0.19.8](https://github.com/maidsafe/self_encryption/compare/v0.19.7...v0.19.8) (2021-02-03)

### [0.19.7](https://github.com/maidsafe/self_encryption/compare/v0.19.6...v0.19.7) (2021-01-20)

### [0.19.6](https://github.com/maidsafe/self_encryption/compare/v0.19.5...v0.19.6) (2021-01-18)

### [0.19.5](https://github.com/maidsafe/self_encryption/compare/v0.19.4...v0.19.5) (2020-11-23)

### [0.19.4](https://github.com/maidsafe/self_encryption/compare/v0.19.3...v0.19.4) (2020-11-23)

### [0.19.3](https://github.com/maidsafe/self_encryption/compare/v0.19.2...v0.19.3) (2020-10-20)

### [0.19.2](https://github.com/maidsafe/self_encryption/compare/v0.19.1...v0.19.2) (2020-10-09)

### [0.19.1](https://github.com/maidsafe/self_encryption/compare/v0.19.0...v0.19.1) (2020-09-21)


### Features

* **get:** self mut for get api ([1dfeca3](https://github.com/maidsafe/self_encryption/commit/1dfeca3715604612aea982fa9c795413e4b443f5))

### [0.19.0](https://github.com/maidsafe/self_encryption/compare/v0.18.0...v0.19.0) (2020-07-30)

* Update rand and rand_chacha dep

### [0.18.0](https://github.com/maidsafe/self_encryption/compare/v0.17.0...v0.18.0) (2020-06-26)

* Update bincode dep
* Update deps > v1 in general to use implicit ^

### [0.17.0](https://github.com/maidsafe/self_encryption/compare/v0.16.0...v0.17.0) (2020-05-28)

* Update to use modern rust futures
* Use async/await throughout
* Use Arc/Mutex to enable multi-threading


### [0.16.0](https://github.com/maidsafe/self_encryption/compare/v0.15.0...v0.16.0) (2019-12-02)

* Replace the use of `rust_sodium` with `aes` for encryption.

### [0.15.0](https://github.com/maidsafe/self_encryption/compare/0.14.0...v0.15.0) (2019-08-29)

* Update rand to 0.6.0
* Remove the legacy maidsafe_utilities dependency
* Update memmap to 0.7.0 and remove the unsafe code
* Add `generate_address` function to the `Storage` trait to support data types with different address deriving algorithms
* Use rust stable / edition 2018

### [0.14.0]

* Update tiny_keccak to 1.4.0

### [0.13.0]
* Upgrade unwrap version to 1.2.0
* Use rust 1.28.0 stable / 2018-07-07 nightly
* rustfmt 0.99.2 and clippy-0.0.212
* Update license to mention GPL3 only
* Replace the brotli2 library with a pure Rust version

### [0.12.0]
* Use rust 1.22.1 stable / 2017-11-23 nightly
* rustfmt 0.9.0 and clippy-0.0.174

### [0.11.2]
* Update rust_sodium to 0.6.0

### [0.11.1]
* Update futures to latest version and fix deprecated function calls

### [0.11.0]
* Use rust 1.19 stable / 2017-07-20 nightly
* rustfmt 0.9.0 and clippy-0.0.144
* Replace -Zno-trans with cargo check
* Make appveyor script using fixed version of stable

### [0.10.0]
* Self-encrypt is now asyc using futures

### [0.9.0]
* Use sha3_256 from tiny_keccak instead of rust_sodium
* Travis uses cargo_install script from QA
* Dependencies updated

### [0.8.0]
* Update maidsafe_utilities 0.11.0
* rustfmt 0.8.1
* switch to serde instead of rustc-serialize
* cleanup CI scripts

### [0.7.1]
* Update maidsafe_utilities to v0.10.0 which removes deprecated API's.

### [0.7.0]
* Use new rust_sodium crate instead of sodiumoxide.

### [0.6.0]
* Expose a new SequentialEncryptor which publishes its data immediately if possible.

### [0.5.1]
* Fix sodiumoxide to v0.0.10 as the new released v0.0.12 does not support rustc-serializable types anymore and breaks builds

### [0.5.0]
* Use SHA256 instead of SHA512.

### [0.4.0]
* Remove asynchronous code.
* Replace Deflate compression with Brotli.
* Use `Result`s instead of panic.

### [0.3.1]
* Fix truncate, flagging first two chunks for encryption, and add new test.
* Updates contributor agreement.
* Fixed failing test exceeding serialisation limits.
* Disable clippy use_debug check.
* Updated dependencies.

### [0.3.0]
* Updated dependencies.

### [0.2.6]
* Various bug fixes and tidy up.
* Setup clippy usage.
* Include nightly builds on travis.

### [0.2.5]
* Swap forked memory_map for original memmap crate.

### [0.2.4]
* Remove wildcards from dependencies.

### [0.2.3]
* Update in line with sodiumoxide 0.0.9 changes.

### [0.2.2]
* Increase file sizes to 1Gb using memory map (previously omitted).
* Compression pre encrypt and post encrypt in encrypt and decrypt methods
* Task passing to allow cores to be lit up when handling chunks

### [0.2.1]
* Fixed lint warnings caused by latest Rust nightly

### [0.0.0 - 0.2.0]
* Initial structure
* Test set-up
* Travis integration
* Docs creation
* Docs hosting (github.io)
* Windows CI set-up (ci.AppVeyor.com)
* Read/Write file in memory based buffer
* API version 0.0.8
* Implement disk based interface as example
* Full unit tests in lib.rs
* Integrations tests in tests module
* Benchmark tests for varying file sizes from 1 byte to 10 M/b
* API stable version 0.1.0
* Coverage analysis (coveralls ?)
