
# Introduction to Cryptography (APT3090) - Course Overview

**Professor:** Dr. Stanley Githinji

## Course Overview
This course introduces the core techniques of cryptography around which security and trust can be constructed and highlights the implications of using such techniques. It also examines the entire key management lifecycle, exploring the differing requirements and methodologies for managing cryptographic keys of various types. The course concludes by applying these techniques in various applications and standards, including VPNs and secure email.

## Lab Reports

### LAB1 REPORT
This report discusses the implementation of a C++ program that generates two random prime numbers within a user-specified range. The program prompts the user to input the range, identifies all prime numbers within that range, and selects two primes randomly. These primes can be used for various applications, such as cryptographic key generation.

### LAB2 REPORT
This report details the implementation of an RSA key generation algorithm in C++. RSA (Rivest–Shamir–Adleman) is a widely used public-key cryptosystem that allows secure data transmission. This implementation generates two random prime numbers within a specified range and computes the public and private keys necessary for encryption and decryption.

### LAB3 REPORT
This report further explores the RSA public-key encryption algorithm, which enables secure communication. It involves generating a pair of keys: a public key used for encryption and a private key used for decryption. The security of RSA relies on the computational difficulty of factoring large prime numbers.

## Final Project

### Credit Card Vault Project
The Credit Card Vault Project aims to develop a secure system for merchants to store and manage customers' credit card information.

**Phase 1:**
- Identify and categorize sensitive, confidential, and public information.
- Define user access levels.
- Design a database schema in 3NF to ensure data integrity and minimize redundancy.

**Phase 2:**
- Implement the database schema, using AES_ENCRYPT and AES_DECRYPT for data security, and SHA-2 for password hashing.
- Create views to cater to different user access levels and ensure secure data retrieval.
- Host the application with an SSL certificate for secure communication.
- Provide comprehensive documentation detailing the source code, key functions, and database structure.

This project emphasizes data protection, efficient storage, and secure access control.

## RSA Over TCP Project

### Implementation of RSA Over TCP
In this project, we developed an RSA algorithm with a 1024-bit key size using Python due to its accessibility and user-friendly libraries. The 1024-bit key length was chosen to specify the key's security level. We created public and private keys using random numbers and used these keys to demonstrate the encryption and decryption process between Alice and Bob. Distinct programs for Alice and Bob were designed to enable secure and encrypted messaging via the TCP protocol.

---

**Author:** Ayimbisa Abigail
