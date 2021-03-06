# RustCrypto: Block Modes

[![crate][crate-image]][crate-link]
[![Docs][docs-image]][docs-link]
![Apache2/MIT licensed][license-image]
![Rust Version][rustc-image]
[![Build Status][build-image]][build-link]

Generic implementation of [block cipher modes of operation][1], including
CBC and ECB modes.

Note that this crate implements only modes which require padding. For CTR,
CFB and OFB modes (i.e. modes which transform block ciphers into stream
ciphers) see crates in the [RustCrypto/stream-ciphers][2] repository.

<img src="https://raw.githubusercontent.com/RustCrypto/meta/master/img/block-ciphers/cbc.png" width="480px">

[Documentation][docs-link]

## Minimum Supported Rust Version

Rust **1.41** or higher.

Minimum supported Rust version can be changed in the future, but it will be
done with a minor version bump.

## SemVer Policy

- All on-by-default features of this library are covered by SemVer
- MSRV is considered exempt from SemVer as noted above

## License

Licensed under either of:

 * [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
 * [MIT license](http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

[//]: # (badges)

[crate-image]: https://img.shields.io/crates/v/block-modes.svg
[crate-link]: https://crates.io/crates/block-modes
[docs-image]: https://docs.rs/block-modes/badge.svg
[docs-link]: https://docs.rs/block-modes/
[license-image]: https://img.shields.io/badge/license-Apache2.0/MIT-blue.svg
[rustc-image]: https://img.shields.io/badge/rustc-1.41+-blue.svg
[build-image]: https://github.com/RustCrypto/block-ciphers/workflows/block-modes/badge.svg?branch=master&event=push
[build-link]: https://github.com/RustCrypto/block-ciphers/actions?query=workflow%3Ablock-modes

[//]: # (general links)

[1]: https://en.wikipedia.org/wiki/Block_cipher_mode_of_operation
[2]: https://github.com/RustCrypto/stream-ciphers
