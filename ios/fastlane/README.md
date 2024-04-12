## fastlane documentation

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios updateCertificates

```sh
[bundle exec] fastlane ios updateCertificates
```

Update certificates

### ios certificates

```sh
[bundle exec] fastlane ios certificates
```

Get certificates

### ios testIpa

```sh
[bundle exec] fastlane ios testIpa
```

Build a new release ipa for testing.

### ios releaseTestflight

```sh
[bundle exec] fastlane ios releaseTestflight
```

Submit a new Build to Apple TestFlight

---

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
