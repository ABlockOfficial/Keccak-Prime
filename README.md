# Keccak Prime

The hashing algorithm that keeps your PoW blockchain green.

To make use of CPU acceleration for AES, provide the following compilation flags:

```
RUSTFLAGS="-Ctarget-cpu=sandybridge -Ctarget-feature=+aes,+sse2,+sse4.1,+ssse3"
```
