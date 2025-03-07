<!-- [![crates.io](https://img.shields.io/crates/v/embedded-hal.svg)](https://crates.io/crates/embedded-hal)
[![Documentation](https://docs.rs/embedded-hal/badge.svg)](https://docs.rs/embedded-hal)
![Minimum Supported Rust Version](https://img.shields.io/badge/rustc-1.60+-blue.svg) -->

# TLA2528 [![Cloud-CI](https://github.com/Radiator-Labs/tla2528-rs/actions/workflows/cloud-ci.yml/badge.svg)](https://github.com/Radiator-Labs/tla2528-rs_fw/actions/workflows/cloud-ci.yml)

Embedded Rust driver for the TI TLA2528 ADC, an I2C-connected Analog to Digital Converter.

## Attribution

Work creating this driver to support the TLA2528 was performed as part of commercial
development by [Kelvin](https://kel.vin/) (formerly Radiator Labs), a green energy company
dedicated to decarbonizing the world's legacy buildings.

## Minimum Supported Rust Version (MSRV)

This crate is guaranteed to compile on stable Rust 1.81 and up. It *might*
compile with older versions but that may change in any new patch release.
Changes in Clippy support are the main factor driving the version dependency.

See [here](../docs/msrv.md) for details on how the MSRV may be upgraded.

## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  <http://www.apache.org/licenses/LICENSE-2.0>)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
