# RSAusingPython
This repository contains a Python implementation of the RSA encryption and decryption algorithm, which is a widely-used method for secure data transmission. The project demonstrates key generation, encryption, and decryption steps in RSA, providing a simple yet effective example of asymmetric cryptography

## Features
- **Key Generation**: Generate public and private RSA keys.
- **Encryption**: Encrypt plaintext messages using the public key.
- **Decryption**: Decrypt the ciphertext back to plaintext using the private key.
- **Modular and Secure**: Implements basic security measures using large prime numbers.

## Prerequisites
- Python 3.x
- Basic understanding of cryptography (optional)

## How It Works
1. **Key Generation**: 
   - Two large prime numbers are selected.
   - Public and private keys are derived from these primes using mathematical principles of modular arithmetic.
   
2. **Encryption**: 
   - The plaintext is converted to a number and encrypted using the public key.
   
3. **Decryption**: 
   - The ciphertext is decrypted using the private key to obtain the original plaintext message.
