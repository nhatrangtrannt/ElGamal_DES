# Implementation of a hybrid cryptographic scheme using El Gamal and DES

Hybrid Encryption combines the efficiency of symmetric encryption with the convenience of asymmetric encryption. 

## Source files

```c++
.
├── InfInt              # Arbitrary-Precision Integer Arithmetic Library
├── hybrid              # Containing algorithm files (DES and ElGamal)
│   ├── DES.h           # Data Encryption System (DES)
│   ├── ElGamal.h       # El Gamal
│   └── main.cpp        # Run the program
└── README.md           # Document t

```
## Description 

El Gamal and DES are the two algorithms in this implementation project. Here is the process:
- El Gamal: 
  - Generate public key and private key with a choice of bit size
  - Generate a one-time session key
  - Encrypt and Decrypt the session key
- DES
  - Generate a list of subkeys using the one-time session key as a master key
  - Encrypt and Decrypt the message 
