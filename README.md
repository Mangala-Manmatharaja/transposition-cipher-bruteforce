# 🔐 Transposition Cipher with Brute For

This Python project implements a **Transposition Cipher** encryption/decryption system enhanced with:
- a custom hash for message validation,
- brute-force key cracking using permutations.

It simulates a secure message system where encryption, decryption, hashing, and brute-force recovery are all demonstrated.

---

## 🚀 Features

- ✅ Transposition cipher encryption and decryption
- ✅ Random key generation using permutations
- ✅ Hash validation to detect tampered messages
- ✅ Brute-force key recovery using hash matching
- ✅ Clean console output with all steps logged

---

## 📂 Files

- `Proj1.py`: Main Python file (all logic in one script)
- `README.md`: Project documentation

---

## 🔧 How It Works

1. **Preprocessing**:
   - Input string is converted to lowercase and filtered to only include characters from `a` to `z`.

2. **Padding**:
   - Ensures the length of the message plus hash fits into a matrix of fixed width.

3. **Hashing**:
   - A custom 8-character hash is generated for the plaintext to validate integrity.

4. **Encryption**:
   - Transposition cipher using a randomly generated key.

5. **Decryption**:
   - Reverses the matrix-based transposition using the key.

6. **Brute-Force Attack**:
   - Tests all permutations of key vectors up to length 9 to find the correct key using hash validation.

---

## 🧠 Concepts Used
      Transposition cipher
      Matrix manipulation
      Hashing and integrity validation
      Permutations and brute-force
      Random key generation

---

## 📌 Requirements
     >>>  Python 3.x
     >>>  NumPy (for random permutation): Install via pip install numpy
---

## 🤝 Author
     Mangala-Manmatharaja

