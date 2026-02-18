# 🔐 Cryptography Toolkit

A simple Python-based cryptography toolkit that combines classical and modern encryption algorithms in one CLI application.

This project was originally developed for a Computer Security course and is now shared for documentation and reference purposes.

---

## ✨ Features

### 🔹 Classical Ciphers

* Caesar Cipher
* Vigenère Cipher
* Playfair Cipher

### 🔹 Cryptographic Components

* P-Box (Permutation)
* S-Box (Substitution + Inverse)
* AES ShiftRows demonstration

### 🔹 Modern Cryptography

* DES (ECB / CBC)
* AES (128 / 192 / 256-bit)
* RSA (Key generation, encryption & decryption)

---

## 🛠 Built With

* Python 3
* PyCryptodome
* hashlib
* base64

---

## 🚀 How to Run

Install dependency:

```bash
pip install pycryptodome
```

Run the program:

```bash
python main.py
```

---

## 📌 Notes

* DES and ECB mode are included for learning purposes.
* AES and RSA are implemented using PyCryptodome.
* The project is CLI-based with a unified main menu.
