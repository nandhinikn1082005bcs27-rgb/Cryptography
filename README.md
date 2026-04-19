# Cryptography
A collection of essential cryptographic ciphers
# 🛡️ JS-Crypto: Cryptography & Number Theory

A JavaScript implementation of essential cryptographic algorithms, ranging from classical ciphers to modern standards and key exchange protocols.

## 📁 Repository Structure

### 📜 Classical Ciphers (JS)
*   **Vigenère Cipher:** Polyalphabetic substitution using a keyword and custom `char-code` arithmetic.
*   **Affine Cipher:** Implementation using modular inverse and linear functions ($ax + b \pmod{26}$).
*   **Playfair Cipher:** 5x5 matrix-based encryption for digraphs using two-dimensional arrays.

### 🔢 Number Theory Tools
Essential helper functions for asymmetric crypto:
*   **Extended Euclidean Algorithm:** For finding modular multiplicative inverses.
*   **Modular Exponentiation:** Efficiently calculating $(base^{exp}) \pmod{mod}$.
*   **Primality Testing:** Implementation of the Miller-Rabin test.

### 🔒 Symmetric & Hashing Standards
*   **AES (Advanced Encryption Standard):** Block cipher using substitution boxes (S-boxes) and bitwise rotations.
*   **DES (Data Encryption Standard):** Implementation of the Feistel network and bit-permutation tables.
*   **CMAC:** Cipher-based Message Authentication Code for data integrity.
*   **MD5:** 128-bit hash function implementation following RFC 1321.

### 🔑 Asymmetric & Key Exchange
*   **RSA:** Asymmetric encryption utilizing `BigInt` for large prime calculations.
*   **Diffie-Hellman:** Secure shared-secret establishment using discrete logarithms.

---

## 🚀 Installation & Usage

1.  **Clone the repo:**
    ```bash
    git clone https://github.com
    ```
2.  **Run with Node.js:**
    ```bash
    node vigenere/vigenere.js
    ```
    *Note: Most scripts use native `BigInt` and require Node.js v10.4.0+.*

## 📚 Core Resources
*   [CryptoJS Documentation](https://github.com/brix/crypto-js) - Reference for industry-standard JS implementations.
*   [MDN Web Crypto API](https://mozilla.org) - Native browser encryption.
*   [Vigenère in JS Guide](https://javascript.algorithmexamples.com/web/Ciphers/vigenereCipher.html) - Step-by-step logic for classical ciphers.
