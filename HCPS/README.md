# HashCommunicationProtocolStandard (HCPS): A Transactional Based Hash-Digest Communication Protocol Using Asynchronous Block Lattices, Mutable Patricia Merkle Tries, Distributed Hash Tables, And Namespaces.

**Author:** `silene | 0x20CB`
**Date Published:** Aug 13, 2025
**LICENSE:** APACHE-2.0



## Abstract

The internet has brought about it a large amount of content that has been shared and widely available, making the cost-barrier for media, education, finances, and other important information easier to handle. This in turn has has many benefits, such as helping lower-income populations, making data more widely available, and creating communities online. However, there are some inherent problems in both Web 2.0 and Web 3.0 that have been faced with criticism.

This whitepaper presents a new standard, known as `HashCommunicationProtocolStandard`, which is a novel transactional-based hash-digest communication protocol that uses new methodologies to create a censorship-resistant, more decentralized, secure interent, with ease of access and usability. It is modular by design and relies on a technological stack that can easily be implemented. It can be used for various purposes, such as, secure transactions, mutable changes, and decentralized access to content. It opposes well-known ideas and is instead its own concept. It is intended to be used to secure web transactions through a block lattice with no transaction fees, instead, using minimalproofofwork. It defines different namespaces and allows for new concepts to be presented to the general public.

## 1. Introduction


## 2. Hash-Communication-Protocol-Standard (HCPS) Cryptography

## 2.1 Hash Digests

The **chosen hash digests** are the following:

### BLAKE2s (28-32 bytes)

BLAKE2s is employed so that IoT can easily use this system as this hash function is efficient on low level devices. It is chosen at 28 bytes (224 bits) to 32 bytes (256bits) as it provides a hash digest that is both efficient and secure.

### BLAKE3

BLAKE3 is used for its efficiency of hashing content blazingly fast and remaining at 256 bits (32 bytes). It is used in general for files, for content, and for other-related objects.

### SHA384

SHA384 is used due to its well-known security and operations that it uses. It is a secure hash function, with 48 bytes (384 bits) in the digest. It is used for security.

## 2.2 Signatures

The **chosen signature schemes** are used:

### ShulginSigning

A hybrid between ED25519/ED448 with hedged signatures and SPHINCS+ (SHAKE256). It is a long-term, secure, post-quantum digital signature.

### ED25519

ED25519 (with hedged signatures) is used for signing in many applications but lacks post-quantum security.
