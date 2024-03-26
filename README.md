# Goon Squad Encrypting

Built in python.

This program allows for encrypting and decrypting using:

* Caeser Cipher
* Enhanced Caeser Cipher (Custom)
* Columnar Transposition Cipher
* Enhanced Columnar Transposition Cipher (Custom)
* A block chaining option with any of these ciphers that allows for a higher level of security that uses a block chaining concept while encrypting



The block chaining option splits the plain text into blocks of 256 bits and uses SHA256 to generate signatures for each block
where each block is XORed with the the signature of the previous block before being encrypted.
