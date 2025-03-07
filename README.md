# WASIX Information

As of version `0.7.1` , version of ring upstream has been updated to `0.17.0`. So now it can be basically pinned to `0.17.5` which supports WASI. So this fork is now not needed anymore.

# SCT.rs

SCT.rs is a certificate transparency SCT verifier in rust.
It uses [_ring_](https://github.com/briansmith/ring) for cryptography.

[![Build Status](https://github.com/rustls/sct.rs/workflows/sct.rs/badge.svg)](https://github.com/rustls/sct.rs/actions)
[![Coverage Status (codecov.io)](https://codecov.io/gh/rustls/sct.rs/branch/main/graph/badge.svg)](https://codecov.io/gh/rustls/sct.rs/)
[![Documentation](https://docs.rs/sct/badge.svg)](https://docs.rs/sct)
[![crates.io](https://img.shields.io/crates/v/sct.svg)](https://crates.io/crates/sct)

# Status

Ready for use:

- All intended features are implemented.
- Tests achieve 100% line coverage and all reachable branches.

# License

SCT.rs is distributed under the following three licenses:

- Apache License version 2.0.
- MIT license.
- ISC license.

These are included as LICENSE-APACHE, LICENSE-MIT and LICENSE-ISC
respectively. You may use this software under the terms of any
of these licenses, at your option.
