# Reversing Elden Ring

A living document on the inner workings of Elden Ring.

## The basics

Some surface-level information to get started.

### Regulation

The regulation file in Elden Ring is encrypted with AES-256-CBC, identical to Dark Souls 3.

The decryption key is `99 bf fc 36 6a 6b c8 c6 f5 82 7d 09 36 02 d6 76 c4 28 92 a0 1c 20 7f b0 24 d3 af 4e 49 3f ef 99`.

The resulting plaintext is a DCX file containing a BND4.
