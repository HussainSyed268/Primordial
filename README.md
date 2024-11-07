# Primordial: An Enhanced RSA Encryption Project

**Primordial** is a cryptographic project that enhances the standard RSA encryption algorithm, leveraging multi-prime RSA to improve security against factorization attacks. This project uses a full-stack architecture with a React.js frontend and a Python Flask backend. The backend performs key cryptographic operations, including prime number generation, XOR cipher encryption, multi-prime RSA encryption, and an additional obfuscation layer using a Knight’s Tour Scrambler.

## Features

- **Multi-Prime RSA Encryption**: Enhanced security with multiple prime numbers.
- **360-degree XOR Cipher**: Provides an additional layer of encryption.
- **Knight's Tour Scrambler**: Scrambles encrypted data to increase obfuscation.
- **Prime Number Generation**: Secure prime generation using Microsoft's CryptGenRandom API.
- **Factorization Resistance**: Designed to resist modern factorization attacks like Pollard's Rho Algorithm.

## Tech Stack

### Frontend
- React.js
- Tailwind CSS for UI
- Axios for API communication

### Backend
- Python Flask
- RSA, Cryptography Libraries
- Microsoft CryptGenRandom API (for prime number generation)

