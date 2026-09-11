# Nautilus build cache

Versioned native development artifacts used to shorten clean NautilusTrader builds.

## AWS-LC bundle

The current Windows x64 bundle contains:

- `aws-lc-sys` 0.42.0 bindings
- AWS-LC 5.1.0 static `crypto.lib`
- Headers and provenance metadata
- AWS-LC, aws-lc-sys, and Fiat-Crypto license notices

NautilusTrader pins the release URL and SHA-256 checksum in its Justfile. These artifacts are development build accelerators, not production or FIPS distributions.

Artifacts are immutable. Any input, target, ABI, or toolchain change requires a new versioned release.
