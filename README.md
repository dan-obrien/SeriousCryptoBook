# SeriousCryptoBook
Notes from Serious Cryptography

**Informational security** - security in theory

- Does not quantify security as options are either secure or insecure
- Not useful in practice
- The one time pad is informationally secure

**Computational security** - security in practice

- Views a cipher as secure if it cannot be broken with a *reasonable* amount of time, and with reasonable resources

Cipher E
Plaintext P
Ciphertext C
128-bit key K

C = E(P, K)

If a plaintext, ciphertext pair is known (P, C), but not the key K, this could be broken by tryng all 2^128 possible keys K.

It is therefore not informationally secure; however, it is computationall secure due to the amount of time it would require to perform this brute force attack.

Computational security is sometimes expressed as (t, ε)

Where:
t - limit on the number of operations that an attacker will carry out
ε - (epsilon) limit on the probability of success of an attack

