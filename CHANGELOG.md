# Changelog

All notable changes to this project will be documented in this file, organized by crate.
Each change must be linked to a pull request or commit.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### CI

#### Added

- CI: add support for macos-latest with Rust 1.84
  ([#3131](https://github.com/o1-labs/proof-systems/pull/3131))

### [arrabbiata](./arrabbiata)

#### Changed
- (No changes in current release)

### [folding](./folding)

#### Changed
- (No changes in current release)

### [groupmap](./groupmap)

#### Changed
- Make field of BWParameters public
  ([#3326](https://github.com/o1-labs/proof-systems/pull/3326))

### [ivc](./ivc)

#### Changed
- (No changes in current release)

### [kimchi](./kimchi)

#### Changed
- (No changes in current release)

### [kimchi-msm](./msm)

#### Changed
- (No changes in current release)

### [kimchi-stubs](./kimchi-stubs)

#### Changed

- Remove warnings `+adx/+bmi2 is not a recognised feature for this target,
  issue [#3322](https://github.com/o1-labs/proof-systems/issues/3322)
([#3248](https://github.com/o1-labs/proof-systems/pull/3248))
- Move lagrange_basis module from kimchi-stubs in poly-commitment
  ([#3329](https://github.com/o1-labs/proof-systems/pull/3329))

### [mina-curves](./curves)

#### Changed
- (No changes in current release)

### [mina-hasher](./hasher)

#### Changed
- (No changes in current release)

### [mina-poseidon](./poseidon)

#### Changed
- (No changes in current release)

### [mina-signer](./signer)

#### Added

- Implement a method to return a dummy signature
  ([#3327](https://github.com/o1-labs/proof-systems/pull/3327))
- Implement `derive_nonce_compatible` function, a nonce derivation algorithm
  compatible with the TypeScript and OCaml implementation
  ([#3302](https://github.com/o1-labs/proof-systems/pull/3302/))
- Add `packed` parameter to `Signer::sign` method to control nonce derivation method
  - `packed: true` uses OCaml/TypeScript compatible nonce derivation
  - `packed: false` uses standard Rust nonce derivation (will be deprecated)
  ([#3302](https://github.com/o1-labs/proof-systems/pull/3302/))

#### Changed
- Make CompressedPubKey orderable
  ([#3328](https://github.com/o1-labs/proof-systems/pull/3328))
- Make the structure `Message` from `schnorr.rs` public
  ([#3302](https://github.com/o1-labs/proof-systems/pull/3302/))
- Make the fields of the structure `Schnorr` from `schnorr.rs` public
  ([#3302](https://github.com/o1-labs/proof-systems/pull/3302/))

### [mvpoly](./mvpoly)

#### Changed
- (No changes in current release)

### [o1-utils](./utils)

#### Changed
- (No changes in current release)

### [o1vm](./o1vm)

#### Changed
- (No changes in current release)

### [plonk_wasm](./plonk-wasm)

#### Changed
- (No changes in current release)

### [poly-commitment](./poly-commitment)

#### Changed

- Move lagrange_basis module from kimchi-stubs in poly-commitment
  ([#3329](https://github.com/o1-labs/proof-systems/pull/3329))

### [turshi](./turshi)

#### Changed
- (No changes in current release)

## Previous Changes

For changes prior to this changelog introduction, please refer to the git commit history
and individual component changelogs in their respective directories.
